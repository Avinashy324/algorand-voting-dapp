# Algorand Voting DApp

A decentralized voting application built on the **Algorand blockchain** using Python and the Algorand SDK. This project enables transparent, tamper-proof, and trustless voting on-chain.

---

## Project Overview

This dApp allows users to create polls and cast votes that are recorded directly on the Algorand blockchain. By leveraging Algorand smart contracts (written in PyTeal/AVM), every vote is immutable, verifiable, and fully transparent — ensuring fair elections without a central authority.

---

## Tech Stack

| Layer | Technology |
|------------|-----------------------------------|
| Blockchain | Algorand (TestNet / MainNet) |
| Smart Contract | PyTeal / TEAL (AVM) |
| Backend | Python 3.10+ |
| SDK | py-algorand-sdk |
| Frontend | React.js (planned) |
| Wallet | Pera Wallet / AlgoSigner |

---

## Project Structure

```
algorand-voting-dapp/
├── contracts/ # PyTeal smart contracts
│ ├── voting_contract.py
│ └── compile.py
├── scripts/ # Deployment & interaction scripts
│ ├── deploy.py
│ ├── create_poll.py
│ └── cast_vote.py
├── client/ # Frontend (React)
│ └── src/
├── tests/ # Unit tests
│ └── test_voting.py
├── requirements.txt
└── README.md
```

---

## Planned Features

- [x] Repository setup and project structure
- [ ] Smart contract for poll creation
- [ ] Smart contract for vote casting
- [ ] One-vote-per-wallet enforcement
- [ ] Real-time vote tally on-chain
- [ ] Frontend integration with Pera Wallet
- [ ] Deployment to Algorand TestNet
- [ ] Full audit trail and result verification

---

## Getting Started

### Prerequisites

- Python 3.10+
- [py-algorand-sdk](https://github.com/algorand/py-algorand-sdk)
- [PyTeal](https://github.com/algorand/pyteal)
- Algorand node or access to [AlgoNode](https://algonode.io/)

### Installation

```bash
git clone https://github.com/Avinashy324/algorand-voting-dapp.git
cd algorand-voting-dapp
pip install -r requirements.txt
```

---

## Author

**Avinashy324** — Algorand Course Project

---

## License

This project is open-source and available under the [MIT License](LICENSE).

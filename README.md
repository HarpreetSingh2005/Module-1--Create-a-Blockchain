# Blockchain A-Z Project

This is my first blockchain project from the **Blockchain A-Z course**.
It’s a minimal blockchain built in Python with a simple **Proof of Work** and exposed as a **Flask API**.


---


## Features

- Create a blockchain

- Mine new blocks

- Validate the chain

- Flask-based REST API


---


⚡ Installation & Usage
```bash
git clone https://github.com/yourusername/Blockchain-AZ-Project.git
cd Blockchain-AZ-Project

# Install dependencies
pip install -r requirements.txt

# Run app
python app.py
```
---

## API Endpoints

- /mine_block → Mine a new block

- /get_blockchain → Get the blockchain

- /is_valid → Check validity

---

## Example: Mine a Block

**Request**

GET http://127.0.0.1:5000/mine_block


**Response**

{
  "message": "Congratulations! you just mined a block",
  "index": 2,
  "timestamp": "2025-08-31 12:34:56",
  "proof": 533,
  "previous hash": "003abc..."
}

---

## Tech Stack

- Python 3.x

- Flask

- SHA-256 Hashing

Consensus: Proof of Work

---

## 🙌 Acknowledgment

Inspired by the **Blockchain A-Z course**

---

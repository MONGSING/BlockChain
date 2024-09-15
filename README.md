
# Blockchain Implementation Using Python

This project is a Python implementation of a simple blockchain with core functionalities like Proof of Work (POW), mining, and block validation.

## Features

- Block Creation: Generates blocks with index, timestamp, data, proof, and previous hash.
- Mining: Implements Proof of Work by finding a valid hash starting with four leading zeros.
- Blockchain Validation: Verifies the integrity of the blockchain.
- Tamper Detection: Detects modifications to the blockchain.


## Requirements

- Python 3.x
- FastAPI
- Uvicorn
## How to Run
1.Clone the repository:
```bash
  git clone https://github.com/MONGSING/BlockChain
```
2.Install dependencies:
```bash
  pip install fastapi uvicorn
```
3.Run the blockchain:
```bash
  python Main.py
```
    
## Blockchain Structure
Each block contains the following:

- Index: Position in the chain.
- Timestamp: Time of block creation.
- Data: Information stored in the block.
- Proof: Proof of Work for the block.
- Previous Hash: Hash of the previous block.
## License
This project is licensed under the MIT License.

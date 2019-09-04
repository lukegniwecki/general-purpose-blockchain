# General Purpose Blockchain
General Purpose Blockchain I have created in Python as part of a Blockchain course. 

## Required
Python 3.6

Flask: install in terminal 
```pip install Flask==0.12.2```

Quickstart guide: 
```https://flask.palletsprojects.com/en/1.0.x/quickstart/```

## Libraries
- datetime - needed time stamping of blocks
- hashlib - used to hash the blocks
- json - used to encode the blocks before they are hashed
- Flask - Flask class from the flask library for creating a web application 
- jsonify - used to return messages in postman when requesting the state of the blockchain or asking to return the key info of the block that has been mined in the json format

## Requests 
Requests used to query the blockchain once the application is running in on Flask:

**Get Chain** 
- Queries the current state of blockchain: http://127.0.0.1:5000/get_chain

**Mine Block**:
- Mines a new block: http://127.0.0.1:5000/mine_block

**Is Chain Valid**: 
- Checks if Blockchain is valid i.e. if all previous hashes match with all blocks: http://127.0.0.1:5000/is_chain_valid 

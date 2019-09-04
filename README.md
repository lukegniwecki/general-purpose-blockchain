# General Purpose Blockchain
General Purpose Blockchain I have created in Python as part of a Blockchain course. 

# Required
Python

Flask: install in terminal 
```pip install Flask==0.12.2```

Quickstart guide: 
```https://flask.palletsprojects.com/en/1.0.x/quickstart/```

# Libraries
- datetime - needed time stamping of blocks
- hashlib - used to hash the blocks
- json - used to encode the blocks before they are hashed
- Flask - Flask class from the flask library for creating a web application 
- jsonify - used to return messages in postman when requesting the state of the blockchain or asking to return the key info of the block that has been mined in the json format

# Requests to query the blockchain once the application is running in on Flask
- http://127.0.0.1:5000/get_chain
- http://127.0.0.1:5000/mine_block
- http://127.0.0.1:5000/is_chain_valid 

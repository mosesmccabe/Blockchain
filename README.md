# Blockchain
```
Part 1: Create a blockchain 
Part 2: Decentralize it to create a Cryptocurrency. 
```

## Part 1 - Create a Blockchain
Blockchain is a list of blocks that are lined together using Hash Cryphography (SHA245).
Each block contains a cryptographic hash of the previous block, a timestamp, and data

![block diagram](https://user-images.githubusercontent.com/25771787/161406970-5c1af906-e4f6-47a5-b8db-074769ef961f.png)


## How to run the program
1. Either fork or download the app
2. Install all package: 
   - install [Flask](https://flask.palletsprojects.com/en/2.0.x/#)
     - Flask is a web framework used to build web application
   - download [Postman](https://www.postman.com)
      - Postman is an HTTP cline which provide a user freindly interface for making request
3. Open and run the application in any python IDE 

## How to interact with the app using Postman
1. While the app is running in your IDE. 
2. Open Postman and perform one of the following actions
   - To get the full blockchan 
      - select **GET** enter the URL ***http://127.0.0.1:5001/get_chain*** click **Send**  <img width="854" alt="fullBlockchain" src="https://user-images.githubusercontent.com/25771787/161406879-6a5d2205-9403-428b-9e38-00d784a4b51f.png">
   - To Mine a block
      - select **GET** enter the URL ***http://127.0.0.1:5001/mine_block*** click **Send** <img width="852" alt="mineBlock" src="https://user-images.githubusercontent.com/25771787/161406912-db762cc6-9ff4-49c8-9369-e22d4eb46b9a.png">
   - To check if the Blockchain is valid
      - select **GET** enter the URL ***http://127.0.0.1:5001/is_valid*** click **Send**  <img width="857" alt="isValid" src="https://user-images.githubusercontent.com/25771787/161406916-c34ac0f3-8ed1-4844-b3a1-77ea19eb2881.png">






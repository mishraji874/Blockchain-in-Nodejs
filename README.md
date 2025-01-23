# Blockchain using Nodejs

This project provides a foundational implementation of a blockchain using Node.js. It serves as a practical exploration of core blockchain principles, including:

* **Block Creation:** Demonstrates the process of creating new blocks with unique hashes and linking them to previous blocks to form a chain.
* **Data Storage:** Explores methods for securely storing and retrieving data on the blockchain.
* **Consensus Mechanisms:** Implements basic consensus algorithms (e.g., Proof-of-Work simulation) to ensure data integrity and prevent tampering. 

<!-- TABLE OF CONTENTS -->

## Steps done
  <ol>
    <li>
     <a>Creating a basic P2P network</a>
    </li>
    <li>
     <a>Sending and receiving blocks</a>
    </li>
    <li>
     <a>Registering miners and creating new blocks</a>
    </li>
    <li>
     <a>Setting up a name-value database, LevelDB</a>
    </li>
    <li>
     <a>Creating a private-public wallet</a>
    </li>
    <li>
     <a>Creating an API</a>
    </li>
    <li>
     <a>Creating a command-line interface</a>
    </li>
  </ol>


## Getting Started

1. Clone the repository:
   ```sh
   git clone https://github.com/mishraji874/Blockchain-using-Nodejs.git
   ```

2. Go the folder using the given below command:
   ```sh
   cd Blockchain-using-Nodejs
   ```

3. Install the respective dependencies:
    ```sh
    npm install
    ```

4. After installing the dependencies, run the main `p2p.js` file to see the working blockchain on the terminal:
    ```sh
    node p2p.js
    ```
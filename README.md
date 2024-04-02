## D_Share_Dapps: Decentralized File Storage System on Blockchain

### Introduction
D_Share_Dapps is a decentralized file storage system built on a blockchain network. It allows users to store files across multiple nodes on the blockchain, ensuring data integrity, security, and decentralization.

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/D_Share_Dapps.git
   ```

2. **Install Dependencies for Hardhat:**
   ```bash
   # Navigate to the root directory
   cd D_Share_Dapps
   # Install hardhat dependencies
   npm install
   ```

3. **Compile Smart Contract:**
   ```bash
   # Compile Smart Contract
   npx hardhat compile
   ```

4. **Deploy Smart Contract:**
   ```bash
   # Deploy Smart Contract
   npx hardhat run --network localhost scripts/deploy.js
   ```

5. **Install Dependencies for the React Frontend:**
   ```bash
   # Navigate to the React client directory
   cd client 
   # Install React dependencies
   npm install
   ```

6. **Run the React Application:**
   ```bash
   # Start React Application
   npm start
   ```

### Configuration

1. **Set up Environment Variables:**
   - Obtain API keys for Pinata to interact with IPFS.
   - Update the React component (`FileUpload.js`) with your Pinata API keys.

### Note

1. **Install Metamask:**
   - Ensure Metamask is installed and configured in your browser for Ethereum interactions.

2. **Update Contract Address:**
   - After smart contract deployment, make sure to update the contract address in `App.js` within the React application.

3. **Upload Image before "Get Data":**
   - Click "Get Data" only after uploading an image on Pinata. Otherwise, it will throw an error stating "You don't have access".

4. **Accessing Other User Images:**
   - Use the "Get Data" button to access other users' images. Input the user's address in the designated box, but remember, you can only access their images if they've granted you access through the smart contract. Otherwise, it will throw an error saying "You don't have access".

### Contributors
- Your Name (@yourusername)
- Additional contributors

### License
This project is licensed under the [MIT License](LICENSE).
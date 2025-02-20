# SmartContracts
Smart Contracts for protocol testing and Deployments

---

### **Step 1: Prepare Your Image and Metadata**
Before you deploy an NFT, you need an **image and metadata** file.

1. **Upload Your Image to IPFS**  
   - Use [Pinata](https://www.pinata.cloud/) or [NFT.Storage](https://nft.storage/) to upload your image.
   - After uploading, copy the **CID (Content Identifier)**.
   - Example image URL:  
     ```
     https://ipfs.io/ipfs/QmYourImageCID
     ```

2. **Create Metadata (JSON format)**  
   - Watch Video

3. **Upload Metadata JSON to IPFS**  
   - Upload the `metadata` in iptions.
   - Get the **CID** and use the metadata URL:
     ```
     https://ipfs.io/ipfs/QmYourMetadataCID
     ```

---

### **Step 2: Write the NFT Smart Contract**
Now, let's write an **ERC-721** contract using **Remix IDE**.

1. **Open Remix IDE**  
   - Go to [Remix](https://remix.ethereum.org/).

2. **Create a New File**  
   - In the **File Explorer**, create a new file, e.g., `MyNFT.sol`.

3. **Copy and paste the MyNFT.sol code**
   
---

### **Step 3: Compile the Contract**
1. **Go to the "Solidity Compiler" Tab** (on the left menu in Remix).
2. **Select Compiler Version**: Choose `0.8.19` (or the latest 0.8.x).
3. **Click "Compile MyNFT.sol"**.

---

### **Step 4: Deploy the Contract**
1. **Go to the "Deploy & Run Transactions" Tab**.
2. **Select "Injected Provider - MetaMask"** as the environment.
3. **Select the "MyNFT" Contract** from the dropdown.
4. **Click "Deploy"**.
5. **Approve the Transaction** in MetaMask.

---

### **Step 5: Mint an NFT**
Once deployed:
1. Copy the **Metadata URL** from IPFS (from Step 1).
2. In Remix, under **Deployed Contracts**, find `mintNFT`.
3. Enter:
   - **recipient address** (your wallet)
   - **tokenURI** (IPFS metadata URL: `https://ipfs.io/ipfs/QmYourMetadataCID`).
4. Click **transact** and confirm in MetaMask.

---

### **Step 6: View Your NFT on OpenSea**
- Go to **OpenSea Testnet**:  https://testnets.opensea.io/
- Enter your contract address and find your NFT.

---

### **You’re Done! 🚀**
Now, you have successfully **created and deployed an NFT with an image**! 🎉 Let me know if you need further guidance! 🚀

**Follow** : https://x.com/cryptoconsol

**Join** : https://t.me/cryptoconsol

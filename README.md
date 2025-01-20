# DIV
A blockchain-powered solution to enforce age compliance and prevent underage gambling while preserving privacy.


Here’s a **GitHub README file** for the DIVGuard MVP project:

---

# DIVGuard: Decentralized Age Verification for Gaming  

DIVGuard is a **Minimal Viable Product (MVP)** designed to prevent underage gambling by leveraging **Aadhaar-based age verification** and **blockchain credentials**. This project ensures compliance with Indian regulations while prioritizing user privacy and security.  

---

## Features  
- **Aadhaar Sandbox Integration**: Mock age verification using UIDAI’s test APIs.  
- **Blockchain Credentials**: Issue "Age ≥18" as an NFT on Polygon Mumbai Testnet.  
- **Mobile Wallet**: Store and share credentials via a React Native app.  
- **Demo Gambling App**: Age-gated access to a sample poker game.  

---

## Tech Stack  
- **Frontend**: React.js (Web), React Native (Mobile).  
- **Backend**: Node.js + Express (mock Aadhaar API).  
- **Blockchain**: Polygon Mumbai Testnet, Solidity.  
- **Design**: Figma (UI components and style guide).  

---

## Getting Started  

### Prerequisites  
- Node.js (v16+).  
- MetaMask (Polygon Mumbai Testnet configured).  
- Expo CLI (for mobile app).  

### Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/divguard.git  
   cd divguard  
   ```  
2. Install dependencies:  
   ```bash  
   npm install  
   ```  
3. Deploy the smart contract:  
   - Open `AgeCredential.sol` in Remix IDE.  
   - Compile and deploy to Polygon Mumbai Testnet.  
   - Update the contract address in `src/config.js`.  

### Running the Project  
1. Start the mock Aadhaar API:  
   ```bash  
   cd backend  
   npm start  
   ```  
2. Run the mobile wallet:  
   ```bash  
   cd mobile-wallet  
   expo start  
   ```  
3. Launch the gambling demo:  
   ```bash  
   cd gambling-demo  
   npm start  
   ```  

---

## Usage  
1. Open the mobile wallet app.  
2. Scan a mock Aadhaar QR code or enter a test ID.  
3. If age ≥18, an NFT credential is issued.  
4. Open the gambling demo and connect your wallet.  
5. Access is granted if the NFT is verified.  

---

## Contributing  
Contributions are welcome! Open an issue or submit a PR.  

---

## License  
This project is licensed under the MIT License.  

---

## Acknowledgments  
- UIDAI for the Aadhaar sandbox.  
- Polygon for the Mumbai Testnet.  
- Figma for UI design tools.  

---


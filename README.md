
## Frontend code of Edubuk eSeal dApp integrated with Lisk Mainnet Blockchain

Edubuk eSeal makes credentials verification and background checks secure, efficient, cost-effective, and fraud-free using AI & Blockchain Technology. Since launch, Edubuk has recorded 20,000+ certificates on the blockchain, has secured partnerships with 15 universities and third party background verification companies.  Globally recognized with 40+ awards on merit, including Best Edtech Startup in G20 Conference, and media recognition from CNBC, CNN, Forbes, Economic Times and Grants from major Blockchains, Edubuk has build on Solana chain now as we prepare to Launch as a part of Singapore based Tenity's accelerator program. We are setting new standards in the credentials & background verification industry, globally.

Whitepaper, Pitchdeck and One-Pager: https://drive.google.com/drive/folders/1fA-XGaz3OWDLDFFHLfqSbEGPv3xvEAAq?usp=sharing

## Check out demo video : https://www.youtube.com/watch?v=PPuRPsPV3LM

## Lisk Mainnet Contract Address: 0xECC026aED6830Cc44dCC1146D053af7B4F8a5CE7

**There are 4 stakeholders :**

1.) Issuer: University or Employer who issues the academic certificate or Work-Experience certificate.

2.) Holder: Student or Employee with whom this certificate resides.

3.) Verifier: Other Universities or Other Employers who directly wish to check the authenticity of the credential of the student on the blockchain. 

4.) Requestor: Third party background verification companies: These companies request the candidate to share their digitally verified certificate stored on the blockchain with them for verification purposes.

## Screenshots
![image](https://github.com/user-attachments/assets/f3b70192-16f5-4b38-a38d-5365a8e74268)
![image](https://github.com/user-attachments/assets/2a51fa29-7924-4a01-b6ae-d68b730827e8)
![image](https://github.com/user-attachments/assets/0c46189b-2b3b-4872-80a6-481c434de67f)
![image](https://github.com/user-attachments/assets/d7edcf2a-ed3b-4948-9cba-3b8ddffc4783)
![image](https://github.com/user-attachments/assets/2863c48d-6fad-47f6-bc39-bb6bac60c02e)
![image](https://github.com/user-attachments/assets/87ab773c-c308-401f-a469-bef53191b22c)
![image](https://github.com/user-attachments/assets/2ce30787-7023-465c-b8eb-966ca1671904)
![image](https://github.com/user-attachments/assets/92d2dc2b-b0b7-402d-b671-5623fbf082d3)
![image](https://github.com/user-attachments/assets/a8f3ce8c-b711-45e3-8ae5-06ea1fb89f2e)
![image](https://github.com/user-attachments/assets/991e942a-7afc-46d5-ae3c-725a4f98719d)



**This project includes a decentralized application (dApp) for recording and verifying certificates on the Lisk Sepolia blockchain. The dApp has two main components:**

**1. e-Sealing**

The e-Sealing Tab allows users to register certificates on the blockchain by signing the transaction using a Web3 wallet. When registering a certificate:
Metadata Fields: Users provide three metadata fields:
Certificate Issued To: The beneficiary of the certificate.
Certificate Issued By: The issuing authority.
Certificate Type: Description of the certificate.
Upload Certificate: Users upload a digital copy of the certificate from their local computer.
Register File Hash: Clicking "Register File Hash" generates a cryptographic hash of the file and creates a transaction on the blockchain. This process records six fields:
Beneficiary
Certifying Authority
Certificate Details
Unique file hash (cryptographic)
Timestamp (when the certificate was recorded in UTC)
Witness (certifying authority's wallet address)

**2. Verification**
The Verification Tab allows users to upload a digital certificate and click "Verify Certificate." The dApp retrieves the six fields from the blockchain to verify the information. If all fields match, it displays a "Certificate Verified" message. If the certificate has been tampered with or was not registered on the chain, it shows "Error! Certificate Not Verified."

**Use Cases**
This dApp has various applications requiring immutable and verifiable records of certification, such as:
- **Educational Credentials**
- **Professional Licenses**
- **Authenticity Certificates for Digital or Physical Assets**

## Tech Stack
  - Frontend: React,Tailwind,CSS.
  - Backend: Nodejs, ExpressJs, MongoDB.
  - Smart Contract: Solidity.
  - IDE: Remix-Ethereum.
  - Blockchain Network: Lisk Mainnet.
  - Libraries: etherjs,papaparse,axios,nanoid etc.
  - Decentralized cloud storage:IPFS

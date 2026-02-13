Github repo: https://github.com/jasingizwe/YourVoice  

Video demo: https://drive.google.com/file/d/13HPbLlWLA_pssVNqkhrhPyADek0FoSJe/view?usp=sharing 

1. Introduction 

YourVoice is a decentralized blockchain-based case management system designed to support survivors of Gender-Based Violence (GBV). The platform enables survivors to securely register, create multiple case files, store evidence off-chain, and selectively grant access to responsible organizations.
The system leverages smart contracts deployed on an Ethereum-compatible blockchain to ensure immutability, transparency, and decentralized trust. Unlike traditional centralized systems, YourVoice removes reliance on a single authority and instead uses blockchain consensus and cryptographic validation to guarantee security and accountability.

2. Smart contract

The YourVoice smart contract acts as the core backend logic of the decentralized application (dApp). It manages:
Survivor registration


Case creation and tracking


Evidence referencing through IPFS


Organization approval and role management


Access permissions


Case status updates


Event logging for auditability


Each survivor is uniquely identified through their blockchain wallet address, which functions as a decentralized identity. Survivors may create multiple case files, and each case is permanently recorded on the blockchain.

3. System Architecture

YourVoice follows a hybrid on-chain/off-chain architecture:

On-Chain (Blockchain Layer)

Case metadata


IPFS evidence hash


Case status


Access permissions


Organization approvals


Event logs


Off-Chain (Distributed Storage Layer)

Evidence files (documents, images, or reports) are stored using:
InterPlanetary File System
Only the cryptographic content hash of the file is stored on-chain. This ensures:
Reduced gas costs


Protection of sensitive data


Integrity verification


Tamper detection


If a file is modified, its hash changes, making any manipulation immediately detectable.

4. Data Visualization
To enhance transparency, usability, and analytical insight, YourVoice incorporates blockchain data visualization as part of the frontend dashboard. These visualizations allow both survivors and authorized organizations to clearly understand blockchain activity without needing technical blockchain knowledge.
The UI layer will present visual representations of smart contract interactions and consensus validation, making the decentralized system easier to interpret and monitor.


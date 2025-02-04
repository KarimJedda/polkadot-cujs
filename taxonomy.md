**product**
   - A field to specify whether the CUJ applies to the **Hub**, the **Cloud**, or **both**. 
   - Example Values: `hub`, `cloud`, `both`
   
**persona**
   - A field to group personas into generalized categories and understand which product their goals primarily map to:
     - `developer` (e.g., Smart Contract Developer, Web3 Dev)
     - `business` (e.g., Business Decision Maker, Enterprise)
     - `user` (e.g., DOT Wallet Holder, Governance Participant)
   - This makes it easier to tailor the experiences and avoid mixing overly technical and non-technical perspectives.

**level**
   - Identifies the onboarding complexity or experience level required for the CUJ. This can be used to address both new users and sophisticated/advanced participants.
   - Example Values: 
     - `beginner`
     - `intermediate`
     - `advanced`


### How to Classify Hub vs Cloud?
To decide whether a CUJ belongs to the **Hub**, **Cloud**, or both, think about the key goals and personas:

#### Polkadot Hub
The **Hub** generally involves infrastructure and community-oriented use cases:
- **Governance**: Voting, council participation, referenda.
- **Staking**: Participating in securing the network.
- **Identity Services**: Assigning on-chain identities for Sybil resistance and user reputation.
- **Assets**: Managing DOT and native assets.
- **Smart Contracts**: Deploying simple dApps compatible with the Hub.
- **Coretime Trading**: Interacting with or leveraging coretime mechanics.

Goals that focus on improving the **network-level functionality** or the **user experience** of DOT users will likely be tied to the **Hub**.

#### Polkadot Cloud
The **Cloud** is geared toward high-throughput businesses, advanced scalability, and interoperability:
- **Rollups / Parachains**: Focus on high-scale computation for gaming, stablecoins, and payments.
- **EVM Compatibility**: Developers using Solidity or other EVM-based tools.
- **Cross-Blockchain Communication**: BridgeHub, Snowbridge, cross-chain transactions.
- **Decentralized Storage and Computation**: JAM services, Lambda architecture, off-chain tools.
- **Enterprise Scalability**: Heavy computations for businesses.

Goals that emphasize **decentralized scalability** or the needs of businesses—especially those with performance and throughput concerns—should align with the **Cloud**.

#### Both Hub and Cloud
Some journeys may touch on **both Hub and Cloud** if they:
- Require interoperability between Hub-provided services (e.g., staking, governance) and Cloud features like computational scaling (e.g., rollups).
- Leverage cross-chain messaging, governance systems, or DOT for onboarding users.

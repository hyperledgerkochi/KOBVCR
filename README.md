# KOBVCR
Title    |   KOB Verifiable Credential Registry
---------|-------------------------------------
Version  |   TBD

### Abstract
*A verifiable credential can represent all of the same information that a physical credential represents.A project under KochiOrgBook which can be considered as a database where all VCs of various registered associations are going to reside.It provides a mechanism to express these sorts of credentials on the Web in a way that is cryptographically secure, privacy respecting, and machine-verifiable.*

### Dependent Projects


### Motivation
- *This project is made in the objective of convenience of verifiable credential through Web with all the benefits of a physical credential. Verifiable credentials are a way to establish trust. Verifiable indicates the credential is rendered tamper-evident and in a manner whereby the issuer can be cryptographically verified. So standardization of digital claims makes it more reliable. KOBVCR focuses on*
    - *verifying the integrity of information.*
    - *cryptographic techniues for preserving the certainty of verifiable credentials.*
    - *establish a registry for storing credentials.*

### Status of the Project
*Incubation*

### Solution
- *There are four roles supported by verifiable credentials: 
- *Issuer*
- *Verifier*
- *Holder*
- *Verifiable Data Registry*
*The **issuer**, or the authority on some information about a subject (e.g a person), issues a credential containing this information in the form of claims to a holder. The **holder** is responsible for storing and managing that credential. When a **verifier**, sometimes referred to as a relying party, needs to validate some information, they can request from the holder some data to meet their verification requirements. Depending on the capabilities of the underlying technology, the holder is free to present the claims contained in their verifiable credentials using any number of techniques to preserve their privacy.A **Verifiable Data Registry** commonly a decentralized ledger which serves as a system for mediating the creation and verification of issuer identifiers, keys and other relevant data like verifiable credential schemas and revocation registries.*


![image of vcr](https://github.com/Noureen124/KOBVCR/blob/master/vcr%20pic.png)


*Here, verifiable credentials of registered entity is going to reside with a set of API calls for performing various tasks.*

### Contributors
*Noureen Rahman MK(https://github.com/Noureen124)*

### Testing the projects
*TBD*

### References
- *https://www.w3.org/TR/vc-data-model*
- *https://github.com/hyperledger/aries-rfcs*
- *https://medium.com/mattr-global/a-solution-for-privacy-preserving-verifiable-credentials-f1650aa16093*

### Solution
There are four roles supported by verifiable credentials:
*Issuer, Verifier, Holder, Verifiable Data Registry.*

- The **issuer**, or the authority on some information about a subject (e.g a person), issues a credential containing this information in the form of claims to a holder. 
- The **holder** is responsible for storing and managing that credential. 
- A **verifier**, sometimes referred to as a relying party, needs to validate some information, they can request from the holder some data to meet their verification requirements. Depending on the capabilities of the underlying technology, the holder is free to present the claims contained in their verifiable credentials using any number of techniques to preserve their privacy.
- A **Verifiable Data Registry** commonly a decentralized ledger which serves as a system for mediating the creation and verification of issuer identifiers, keys and other relevant data like verifiable credential schemas and revocation registries.




**<p style="text-align: center;">
![vcr pic](images/vcr pic.png)
</p>**




Here, verifiable credentials of registered entity is going to reside with a set of API calls for performing various tasks. It receives API calls from KOBAW and KOBConnect (Mobile app) while searching some credentials in VCR.

- VCR is public data but private in nature.
- VCR is created for each association and also for the KochiOrgBook level. 
    - An association VCR contains the information about the proofs each association can issue;
    - KOB level VCR contains information about the individual citizen.
- Orgbook level VCR is a distributed VCR, all nodes of our public identity utility is distributed , whereas VCR for association is purely held and managed by the association itself.



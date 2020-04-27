# **GoTrace**
## **GoTrace is an open-source, privacy-first infrastructure toolset to equip pandemic response applications for global adoption.**

### **Problem Sphere & Motivation**

The rapid and unpredictable spread of the COVID-19 pandemic is posing an unprecedented challenge to our global health systems, economies and social fabric. Comprehensive testing, education and awareness of potential illness exposure are a cornerstone of effective and preventative pandemic responses.

Contact tracing is a data management and monitoring tool, which enables the identification of individuals that have been infected and/or those who have been exposed to individuals with the illness to take preventative measures and self-isolate.

Countries with strong democratic values require voluntary tracing schemes for socio-political acceptance, but risk to data privacy and civil rights present a hurdle to adoption. For contact tracing systems are to offer an effective pathway to prevention they must be widely adopted.

### **The Role of Privacy-First Solutions**

While 82% respondents of a 60-person survey we conducted during the hackathon agree that contract tracing apps could act as an effective lever of pandemic response, only 63% were likely to use them if available. When asked if they were likely to use a contact tracing applications that effectively safeguard data privacy and user anonymity, respondents were 20% more likely to use them.

Effective solutions will require solutions that enable unprecedented global self-reporting schemes, privacy and anonymity coordination. To close the close the 20% adoption gap privacy-first infrastructure tools are required.

Social contact tracing systems can only offer an effective pathway to prevention if they are widely adopted. According to a recent Oxford Study, it may require 56% participation of a population to allow for efficient pandemic response and spread mitigation. In terms of the EU population, this would require voluntary participation by 249.2 million individuals to achieve the Oxford Study benchmark.

Our user research indicates that developing an open-source, privacy-first developer tool can offer a pathway to close the 20% adoption gap. This would represent 89.2 million individuals whose adoption offers a pathway to more effective crisis response tools and saving lives, without sacrificing data-privacy and user anonymity. Moreover, improving contact tracing tools can accelerate and improve large-scale socio-economic mobility management.

### **Non Functional Requirements**

**Privacy**
- User-level (Confidentiality): Pseudoanonymous DID generation
- Field-Specific (Data): Limited data-sharing, non-revealing localized device data
- Transaction-Level (Data Traffic Tracing): Publishing transactions of the network

**Identification**
- Device-specific (Bound): Derive from hardware UUIDs
- User-specific (Transferable): Limited contact info collection and no federated ID connectivity

**Data Storage**
- Local Storage
- Encrypted Data
- Avoid Central Database Honeypots

**Procotol Connectivity**
- Adoption & Access: Breadth of integration and usage
- Pluggability: Microservices for storage

**Performance**
- UX: Event streaming & TX Orchestration
- Read / Write Load: Processing Stages / Optimization

![Image](https://user-images.githubusercontent.com/60437465/80346227-50ae6380-8862-11ea-8a28-dc2e2e94299a.png)


### **High-Level Architecture**

Our solution allows developers to leverage open-source blockchain and distributed storage components to extend their social tracing applications with enhanced privacy and security features. Please see the solution architecture overview and solution framework below. 

![Image](https://user-images.githubusercontent.com/60437465/80346122-2492e280-8862-11ea-8964-043f8aeda7e7.png)

GoTrace includes modular components for wallet generation and distributed storage infrastructur. Key features of the component architecture include secure, distributed storage enabled data-sharing, anonymous DID generation, in-app notifications, and support for proof and incentive functionalities (ERC721/20 Ethereum Token Standards).

![Image](https://user-images.githubusercontent.com/60437465/80346133-2a88c380-8862-11ea-8781-393c94743ebb.png)

### **Solution Overlay - Coalition Network**

To examplify integration points and functional improvements we mapped out a solution integration with the existing Coalition Network, build on the Whisper Protocol and leveraging low battery bluetooth and local device storage for detection services.  While this is a use case specific example GoTrace integrations can also be applied to other applications that call for self-reporting reporting, user anonymity preservation and incentive layers.

![Image](https://user-images.githubusercontent.com/60437465/80346239-53a95400-8862-11ea-8bdd-2841415d6cd3.png)

**Feature Extensions**
Metamask Wallet Integration:
- Wrap application inside metamask wallet as a dapp deployment. 
- Enable in-app wallet notifications to mitigate need for other identifiers (phone number, email etc)
- Enable user-centric identification scheme
- Enable certification and incentive issuance and claim functions (ERC721/ERC20)

Data Anchoring & Proofs:
- Allow data anchoring to public Ethereum network
- Leverage messaging via Whisper Protocol

Attestations & Certificates:
- Add additional user flow for connectivity to existing healthcare APIs
- Certificate issuance enabled via DID verified claims

Distributed Storage:
- DID Resolve, Pairs + Timestamp
- ERC721 unique issuance or certification representing interactions / privacy grouping


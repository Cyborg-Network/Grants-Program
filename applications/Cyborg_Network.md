# Cyborg Network - Decentralized Computing paradigms for web 3.0

- **Team Name:** Cyborg Network
- **Payment Address:** Polkadot/Kusama (USDT) payment address. Format: (e.g. 0x8920... (DAI))
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 2

## Project Overview :page_facing_up:

### Overview

Cyborg Network is aimed at pioneering a novel approach to decentralized cloud computing within the Polkadot Ecosystem by establishing a marketplace that harnesses crowdsourced infrastructure. As a premier venture of this nature in the Polkadot landscape, our network effortlessly allows providers to integrate their machines, rewarding them for their invaluable participation.

We actively oversee the provider machines, leveraging them as servers to cater to diverse customer demands, ensuring their specifications are met seamlessly.

Our primary focus rests on delivering bespoke service packages, each meticulously crafted for different deployment scenarios. Our objective is to offer users a service experience reminiscent of the Web 2.0 era. While our foundation is anchored in decentralized cloud solutions, our long-term vision is set on transitioning towards a decentralized edge, especially as we delve into the flourishing AI and IoT age.

We are embarking on an ambitious mission to establish ourselves as a Polkadot and Kusama parachain. Our decision is anchored in several key reasons:

First, we're enticed by their advanced interoperable features, such as shared security and XCM. These functionalities pave the way for seamless integrations with other projects within the ecosystem.

Second, the unparalleled ecosystem and technical support provided by Polkadot and Kusama have been instrumental in our development, and we've had the privilege of closely collaborating with them over the years.

Lastly, the substrate framework stands out as the premier tool for crafting blockchains from the ground up in today's landscape. Our commitment to excellence aligns with the capabilities it offers.

### Project Details

#### Architecture:

The core of our computing solution relies on both off-chain components and substrate pallets that work harmoniously with each other.


![IoT Devices (1920 × 1250 px)](https://github.com/Cyborg-Network/Grants-Program/assets/93442895/84f62d3a-d53a-4531-af86-498acaf6cbba)


Our system invites users to download and run our Cyborg Smart Client (CSC) binary as a root, allowing them to become a provider within our network seamlessly. Upon activation, the CSC immediately establishes a WebSocket connection with CyberHub—our sophisticated backend server and event handler. CyberHub not only serves as an oracle for our substrate blockchain but also links to a dedicated database containing all crucial business data. While these components start off centralized, we're strategically planning to transition them to decentralized structures after ensuring our business model operates flawlessly in such an environment.

We've embedded all operational logic within our pallets. Through the Cyborg Connect platform Dapp, which is integrated with our blockchain, customers have direct access to enact actions on the hosted machine. Both providers and customers can utilize our platform to view detailed analytics and metrics pertaining to their instances.

##1: Connection Flow for the Provider
![8](https://github.com/Cyborg-Network/Grants-Program/assets/93442895/8295b8fe-5ebd-4e7a-b3dd-291e93aa5ac9)

##2: Customer End
![9](https://github.com/Cyborg-Network/Grants-Program/assets/93442895/cb1c204f-e8e0-4ca2-81c5-23bc0c08d938)



Initially, our goal is to configure the system to support predefined static instances, notably blockchain nodes. Our vision then expands to embracing custom deployments for applications and storage. By evolving in this manner, we aspire to establish ourselves as the premier decentralized computing hub for Polkadot ecosystem projects. Leveraging this infrastructure, we intend to develop transformative products such as:

- A Decentralized Postgres Database
- Decentralized CDN
- Decentralized Personal Drive Storage

These solutions are designed to address real-world challenges while harnessing the security inherent to blockchain technology.

### Ecosystem Fit

Cyborg Network augments the Polkadot ecosystem by ushering in decentralized cloud and edge computing, crucial for the burgeoning Web3 and blockchain landscapes. By primarily catering to Web2 application providers, we're paving the way for a fresh wave of users to engage with the Polkadot ecosystem, fueling its expansion.

Though Cyborg and the Phala Network share aspirations of decentralized cloud computing within the Polkadot/Kusama environment, our technical paths are distinct. Phala leans towards off-chain computation, anchored by a fortified smart contract platform. Our perspective suggests Phala may resonate more with traditional sectors, like health tech, aiming to harness blockchain's innovation. Conversely, our insights show that off-chain computation finds favor with Web2-centric applications. Hence, rather than viewing Phala as a direct rival, we consider them as a complementary entity, even if occasional market overlaps arise.

Our ultimate ambition is to evolve into a comprehensive decentralized edge computing network, thereby unlocking novel markets, especially in real-time data management for edgeAI and edge IoT devices. 

For instance, we've been in discussions with a firm operating security cameras monitoring vehicular compliance, like adherence to seatbelt regulations and lane discipline. Their operations grapple with latency challenges attributed to the tangible distance separating cloud data centers and the cameras. Our solution addresses this by offering proximate edge instances hosted by local entities but ensuring utmost security through a protected computing environment, a feature we're actively developing.

The technological landscape sees a plethora of competitors, each carving their niche with unique technical and market strategies. Renowned names include SONM, Aleph.im, Akash, Golem, Cudos, and StackOS, among others. The vast spectrum of contenders across diverse ecosystems underscores our mission's gravity. To maintain its edge, Polkadot must foster a spectrum of cloud computing initiatives, directly rivaling centralized Web2 behemoths like AWS and Google Cloud, thereby consolidating its position against formidable adversaries.

It's worth highlighting that the Solana ecosystem, discerning the nuances between different cloud computing models, endorses both in-chain (Akash) and off-chain (Aleph.im) decentralized projects. Such a discerning approach grants Solana a competitive edge in the decentralized cloud computing domain.


## Team :busts_in_silhouette:

### Team members

- [Barath Kanna](https://www.linkedin.com/in/barath-kanna-23a23a172) - Founder & CEO
- [Kresna Sucandra](https://www.linkedin.com/in/kresna-sucandra) - Co-Founder & CTO
- [Megha Varshini](https://www.linkedin.com/in/megha-varshini-tamilarasan-b1247a212) - Co-Founder & COO

### Contact

- **Contact Name:** Kresna Sucandra
- **Contact Email:** kresnasucandra@gmail.com
- **Website:** https://cyborgnetwork.io

### Team's experience

- [Barath Kanna]((https://www.linkedin.com/in/barath-kanna-23a23a172)) - A developer with a specialization in Rust and blockchain technology. His experience is rooted in designing blockchain infrastructure solutions. Notably, he is an alumni of the Polkadot Blockchain Academy's third cohort at UC Berkeley (July - Aug 2023)

- [Kresna Sucandra](https://www.linkedin.com/in/kresna-sucandra) - With three years of work in Rust, Substrate, and INK, Kresna has a foundational background in blockchain solutions. He was the former co-founder and head of protocol development at [Invarch Network](https://invarch.network/) ( Polkadot and Kusama parachain). Beyond this, he is also a Polkadot Ambassador who manages the Polkadot Hub in Bali.

- [Megha Varshini](https://www.linkedin.com/in/megha-varshini-tamilarasan-b1247a212) - She has been involved in operations for Web3 projects and has taken initiatives in the blockchain community. One of her contributions is the establishment of [Indi Verse DAO](https://www.linkedin.com/company/indi-verse-dao), a web 3.0 community with a focus on blockchain education in India. Additionally, she is the candidate of the Polkadot Ambassador Program.

### Team Code Repos

Project GitHub repositories.

- https://github.com/Cyborg-Network - Organization
- https://github.com/Cyborg-Network/cyborg-node
- https://github.com/Cyborg-Network/cyberhub [still private]

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/beekay2706 
- https://github.com/SHA888 
- https://github.com/Megha2712
  
### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/barath-kanna-23a23a172 
- https://www.linkedin.com/in/kresna-sucandra 
- https://www.linkedin.com/in/megha-varshini-tamilarasan-b1247a212 

## Development Status :open_book:

We have completed the functional side of Cyborg Smart Client (CSC) and we have lite versions of  CyberHub and Pallet Edge Connect that are configured to work with off chain workers as a PoC and we also have a demo video demonstrating the same.

[Cyborg Network PoC 1 Demo](https://www.youtube.com/watch?v=sSNg0Q_DJyk)

Currently we are migrating the configs from off chain worker to oracle support based on advice from Sacha Lansky during a Hackadot 2023 office hours. We also took development advice from Jimmy Chu during an online mentorship event.

At PBA, Barath Kanna (CEO) was able to communicate the idea of Cyborg Network to various people from Parity and web3 foundation viz: Joshua Cheong, Radha Dasari, Shawn Tabrizi, Rae Deng, Clifton Yeo , Bharghav Bhatt etc. and sought valuable feedback that has greatly improved our approach towards our product. 

We have been interacting closely with the square one team at Parity (Nico Morgan and Joshua Cheong) as a part of our application process for the substrate Builder’s program chains track, our application to this grant is based on their recommendation.


## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/Support%20Docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

> :exclamation: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Projects that submit other people's work without proper attribution will be immediately terminated.**

### Overview

- **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 Example — Basic functionality

- **Estimated duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

> :exclamation: **The default deliverables 0a-0d below are mandatory for all milestones**, and deliverable 0e at least for the last one. 

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.) |
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Substrate module: Y | The Y Substrate module will... |
| 3. | Substrate module: Z | The Z Substrate module will... |
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 5. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |
| 6. | Smart contracts: ... | We will deliver a set of ink! smart contracts that will...


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

...


## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.

## Referral Program (optional) :moneybag: 

You can find more information about the program [here](../README.md#moneybag-referral-program).
- **Referrer:** Name of the Polkadot Ambassador or GitHub account of the Web3 Foundation grantee
- **Payment Address:** BTC, Ethereum (USDC/DAI) or Polkadot/Kusama (USDT) payment address. Please also specify the currency. (e.g. 0x8920... (DAI))

## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.

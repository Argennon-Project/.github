

## The Argennon Project

Argennon (*the classical pronunciation should be used:* /ɑrˈɡen.non/) is a next-gen cloud based blockchain and smart
contract platform. The Argennon blockchain uses
a hybrid proof of stake (HPoS) consensus protocol, which is capable of combining the benefits of
a centralized and a decentralized system. Thanks to the cloud
based design of the Argennon blockchain, transaction validation does not require costly
computational resources, and normal personal computers or smartphones, with limited hardware capabilities, can
validate transactions and actively
participate in the Argennon consensus protocol. This property makes Argennon a truly decentralized and
democratic blockchain and one of the most secure existing platforms.

The Argennon cloud is formed by a permission-less network of Publicly Verifiable Database (PV-DB) servers. A
PV-DB server in Argennon, is a conventional data server which uses its computational and
storage resources to help the Argennon network process transactions. A large portion of incentive rewards in
the Argennon platform is devoted to PV-DB servers. This incentivizes the development of conventional
networking, storage and computational hardware, which can benefit all areas of information technology.
This contrasts with the approach of some older blockchains that incentivizes the development of a totally
useless technology of hash calculation.

By using cryptographic accumulators, the integrity of data on the Argennon cloud is guaranteed, and there
is no need for trusting cloud servers. At the same time, by using a smart clustering algorithm the network usage
and the overhead of the cryptographic proofs is kept manageable.

An initial draft of the Argennon white paper can be
found [here](https://raw.githubusercontent.com/aybehrouz/AVM/main/pdf/A.pdf). In addition,
this [link](https://github.com/aybehrouz/argennon#readme) provides a brief overview of the important properties of the Argennon
platform.

Until the launch of the Argennon main-net, an ERC20 token and a governance system will be deployed on the Binance Smart
Chain or the Ethereum network in order to represent investors' share in the project and give them the opportunity to
determine the project's path. After the launch of the Argennon blockchain, this token will be convertible in 1:1 ratio
to the native currency of the Argennon blockchain.

**Please check out the Argennon community on [Discord](https://discord.gg/7u3cXNt5yN), [Telegram](https://t.me/Argennon_Chat), [Reddit](https://www.reddit.com/r/Argennon/) and [Twitter](https://twitter.com/Argennon_org)!**
### Development Roadmap

- [x] **The Argennon execution layer (AscEE):** Main functionalities of the Argennon execution layer should be implemented as described in the white paper.

- [ ] **Trustful test-net:** This is a test-net without voting and cryptographic accumulators, all nodes trust each other. There is only one delegate and one PV-DB server in this network.
  - [ ] **[Trustful Validator](https://github.com/orgs/Argennon-Project/projects/4)**
  - [ ] **[Trustful Fake PV-DB server](https://github.com/orgs/Argennon-Project/projects/5)**
  - [ ] **[Trustful Proposer](https://github.com/orgs/Argennon-Project/projects/6)**

- [ ] **ARG token v2 and ADAGs:** The Argennon DAO and the 2nd version of the ARG token will be deployed on the Binance Smart Chain. Decentralized conversion of ARG v1 token into ARG v2 should be provided by a smart contract. A website will be created for interacting with the Argennon smart contracts.
  - [ ] **[DAO & Token](https://github.com/orgs/Argennon-Project/projects/8)**
  - [ ] **[Argennon Website](https://github.com/orgs/Argennon-Project/projects/7)**

- [ ] **Trust-less client-server test-net:** This network will include voting and accumulators. It still has only one delegate and one PV-DB server, so the topology of this network is mostly client-server and the P2P network between PV-DB servers will not be implemented in this test-net.

- [ ] **The Argon compiler:** A compiler should be implemented for the main smart contract language of the Argennon platform. That implicitly would require that the specification of the Argennon Standard Representations (ASRs), including the ArgC language, are finalized.
 
- [ ] **Insecure test-net:** This network will include multiple delegates and multiple PV-DB servers. It essentially provides a complete implementation of the Argennon protocol. However, this implementation does not need to be completely secure. For example, it might be vulnerable to DOS attacks, or manage cryptographic keys insecurely.

- [ ] **Secure test-net:** This network is a pre-launch test-net and includes all features of the Argennon main-net. This network should be run for at least 3 months.

- [ ] **Main-net launch and the bridging service:** The Argennon blockchain will be deployed. A bridging service will be available for users to bridge their ARG token on the BSC to the Argennon blockchain.
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

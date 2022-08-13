## The Argennon Project

Argennon* is a next generation cloud based blockchain and smart
contract platform. The Argennon blockchain uses
a hybrid proof of stake (HPoS) consensus protocol, which is capable of combining the benefits of
a centralized and a decentralized system. In Argennon, ledger storage and transaction processing are
outsourced to the cloud and normal personal computers or smartphones, with limited hardware
capabilities, are able to validate transactions and actively
participate in the Argennon consensus protocol. This property makes Argennon a truly decentralized and
democratic blockchain and one of the most secure existing platforms.

The Argennon cloud is trustless and publicly verifiable. Computational Integrity (CI) is
achieved by using succinct argument of knowledge systems (STARK/SNARK)
and data integrity is guaranteed by cryptographic accumulators. At the same time, a smart
clustering algorithm keeps the bandwidth usage and the overhead of cryptography manageable
for validators.

The Argennon protocol strongly incentivizes the formation of a permission-less network of Publicly Verifiable
Cloud (PVC) servers. A PVC server in Argennon, is a conventional data server which uses its computational and
storage resources to help the Argennon network process transactions. This encourages the development
of conventional networking, storage and compute hardware, which can benefit all areas of information technology.
This contrasts with the approach of some older blockchains that incentivized the development of a totally
useless technology of hash calculation.

An Argennon validator is light enough to be implemented as a smart contract. By deploying an Argennon validator
on another blockchain, Argennon could use more established networks as an extra layer of security, specially
during the bootstrapping phase, when ARG is not well distributed yet.

An initial draft of the Argennon white paper can be
found [here](https://raw.githubusercontent.com/aybehrouz/AVM/main/pdf/A.pdf). In addition,
this [link](https://github.com/aybehrouz/argennon#readme) provides a brief overview of the important properties of the
Argennon platform.

Until the launch of the Argennon main-net, an ERC20 token and a governance system will be deployed on the Binance Smart
Chain or the Ethereum network in order to represent investors' share in the project and give them the opportunity to
determine the project's path. After the launch of the Argennon blockchain, this token will be convertible in 1:1 ratio
to the native currency of the Argennon blockchain.

**Please check out the Argennon community on [Discord](https://discord.gg/7u3cXNt5yN)
, [Telegram](https://t.me/Argennon_Chat), [Reddit](https://www.reddit.com/r/Argennon/)
and [Twitter](https://twitter.com/Argennon_org)!**

### Development Roadmap

- [x] **The Argennon execution layer (AscEE):** Main functionalities of the Argennon execution layer should be
  implemented as described in the white paper.

- [ ] **Trustful test-net:** This is a test-net without voting and cryptographic accumulators, all nodes trust each
  other. There is only one delegate and one PVC server in this network.
    - [ ] **[Trustful Validator](https://github.com/orgs/Argennon-Project/projects/4)**
    - [ ] **[Trustful Fake PVC server](https://github.com/orgs/Argennon-Project/projects/5)**
    - [ ] **[Trustful Proposer](https://github.com/orgs/Argennon-Project/projects/6)**

- [ ] **ARG token v2 and ADAGs:** The Argennon DAO and the 2nd version of the ARG token will be deployed on the Binance
  Smart Chain. Decentralized conversion of ARG v1 token into ARG v2 should be provided by a smart contract. A website
  will be created for interacting with the Argennon smart contracts.
    - [ ] **[DAO & Token](https://github.com/orgs/Argennon-Project/projects/8)**
    - [ ] **[Argennon Website](https://github.com/orgs/Argennon-Project/projects/7)**

- [ ] **The Argennon CI proof system:** The Computational Integrity prover and verifier will be implemented. A compiler
  with the ability to arithmetize Argennon applications should be developed.

- [ ] **The Argon compiler:** A compiler should be implemented for the main smart contract language of the Argennon
  platform. That implicitly would require that the specification of the Argennon Standard Representations (ASRs),
  including the ArgC language, are finalized.

- [ ] **Trust-less client-server test-net:** This network will include voting and accumulators. It still has only one
  delegate and one PVC server, so the topology of this network is mostly client-server and the P2P network between PVC
  servers will not be implemented.

- [ ] **Insecure test-net:** This network will include multiple delegates and multiple PVC servers. It essentially
  provides a complete implementation of the Argennon protocol. However, this implementation does not need to be
  completely secure. For example, it might be vulnerable to DOS attacks, or manage cryptographic keys insecurely.

- [ ] **Secure test-net:** This network is a pre-launch test-net and includes all features of the Argennon main-net.
  This network should be run for at least 3 months.

- [ ] **Main-net launch and the bridging service:** The Argennon blockchain will be deployed. A bridging service will be
  available for users to bridge their ARG token on the BSC to the Argennon blockchain.

_______

**The classical pronunciation should be used:* /ɑrˈɡen.non/
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

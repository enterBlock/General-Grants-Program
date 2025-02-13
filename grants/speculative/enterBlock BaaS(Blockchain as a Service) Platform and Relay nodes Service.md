# enterBlock BaaS(Blockchain as a Service) Platform and Relay nodes Service

[![img](https://github.com/w3f/General-Grants-Program/raw/56e713d579beca128a6c97abc1535ac7c312383d/src/enter_baas.jpg)](https://github.com/w3f/General-Grants-Program/blob/56e713d579beca128a6c97abc1535ac7c312383d/src/enter_baas.jpg)

## Project Description

- Abstract
  - First goal : Providing Substrate-based blockchains(BaaS solutions) for users (mainly companies) to easily use blockchains with substrate framework.
  - Second goal : Many clients sometimes want to use our BaaS system as well as services related to many other parachains in the Polkadot ecosystem. We will make application for clients easily use APIs without knowing the structure of many other parachains in the Polkadot ecosystem.

We will provide common pallets for some EIPs and documents basically so that they can be applied quickly and easily in applying blockchain and tokens to companies. We have already developed these projects through Parity, and we want to integrate them to develop them.

- Introduction
  - BaaS Solutions : BaaS, which means blockchain as a service, can provide a blockchain service suitable for the environment even if the company preparing the blockchain service does not know blockchain technology. Compared with general nodes, the purpose of BaaS nodes is to quickly build the environment that companies mainly need, and provide various other services such as blockchain-based data inquiry, transaction transmission, and data analysis. It helps developers quickly validate their concepts and models. Even without a specialized blockchain development manpower, it is possible to construct blockchain nodes with a few clicks and implement smart contracts and core technologies of the blockchain. With our BaaS services, companies that want to introduce a blockchain service can dramatically reduce the cost and time for service development. Currently, there are many service-type blockchain providers, and more companies are entering the market every year. In particular, there are some very reliable companies(Miscrosoft, Blockstream, Deloitte, Amazon and Dragonchain) that have already started offering these services to their customers. Unlike the above companies and similar like luniverse, enterBlock's enterprise-type BaaS utilizes Polkadot's interoperability, scalability, forkless future proof, and full security advantages to build blockchains based on the simple substrate framework in a matter of minutes.
  - Application : enterBlock can support any other parachains infrastructure with HTTP endpoints. If clients are interested in serving API requests to and from one of our preconfigured other parachains such as Kusama, ChainX and other Parachains, Even if they don't know the characteristics of other parachains, they can easily use their services by calling any other parachains' apis in polkadot ecosystem easily through our application.
- Brief Explanation for the enterBlock BaaS Architecture
  - The enterprise block chain BaaS provided by enterBlock can provide various types of services as shown in the figure above. For example, if a general financial company wants to build a blockchain for their service operation, it can be easily built through our enterBlock platform. If they want to put their desired business logic on the blockchain, enterBlock can easily provide their desired logic in the form of runtime API using pallets provided by substrate. Also, if you want to bring financial data from outside, you can easily meet their requirements by using offchain workers. Each blockchain in enterBlock can communicate with each other and exchange assets and data. The conclusion is that for each company, a blockchain suitable for the desired business logic is possible in enterBlock.
  - supported common pallets functions : We will make and support these common pallet, anyone who uses our BaaS can use these pallets by substrate. We will integrate the functions provided by Ethereum EIP below into our BaaS with rust language with open source.
    - token(erc-20) : https://eips.ethereum.org/EIPS/eip-20
    - token(erc-721) : https://eips.ethereum.org/EIPS/eip-721
    - token(erc-777) : https://eips.ethereum.org/EIPS/eip-777
    - token(erc-1155) : https://eips.ethereum.org/EIPS/eip-1155
  - custom pallets functions : Since custom pallets have different desired parts for each client, this part will be developed upon request of client development after the mainnet release with no opensource.
  - We may use AWS marketplace that with AMI that runs substrate node with our BaaS services, users can run nodes which is appropriate to their services. And we will support manuals and customer services to users that when issues happen from services, users can handle with issues very quickly.
- Brief Explanation for the enterBlock Application
  - Application provides client-side plugins to interact with the Kusama, ChainX and other any parachains in polkadot. Our application provides sending rpc calls to the any other parachain in polkadot connecting you to your desired parachains. With regard to providing this user experience to the clients, it is up to the development progress of each other parachains.
- Expectations
  - enterBlock's Blockchain-as-a-Service (BaaS) makes it easy for anyone from passionate startups and large enterprises to create blockchain applications. This is possible by creating a blockchain-based product and eliminating a lot of technical complexity. Most of the creation, implementation, and maintenance of an operational blockchain infrastructure no longer needs to be built from scratch. As banks and traditional financial institutions invest in blockchain with many companies in various industries, the chances of a blockchain provider as a service are very successful. BaaS services are particularly useful for startups that lack funds and talent, which are barriers to entry for blockchain innovation. In addition, it is possible to overcome some difficulties with our BaaS service. Digital transformation is currently the biggest trend in the financial sector. In the current situation where fintech companies are rapidly entering, financial sectors, including banks, will also be difficult to survive without disruptive innovation. Therefore, it is judged that traditional financial institutions, including banks, will utilize the blockchain provided by enterBlock, which can easily build and manage blockchains in financial services. On the basis of enterBlock BaaS, it is expected that the financial system can obtain an unprecedented cost reduction through blockchain. In the current centralized system, central security that stores all transaction records and personal information is very important. Financial fraudsters constantly develop all kinds of new technologies to paralyze this security system. So, financial companies are investing enormous costs in the technology to defend them. As e-commerce expands more and the Internet of Things (IoT) eras transactions between objects, costs are bound to rise. enterBlock is expected to grow as a breakthrough company in the enterprise-type BaaS market by solving the above problems for companies in preparation for such a market.
- enterBlock Projects in progress and ready to use BaaS services based on Substrate
  - GlueOS : It is a blockchain project that provides a development-friendly environment, and is a blockchain project focused on increasing developer convenience and providing the same user experience as a web and mobile environment. Therefore, general developers can easily participate in blockchain-based service development through glue.
    - https://www.glueos.com/
  - beat someone : As it is a copyright creation platform, anyone can easily trade their own creations.
    - http://mvp.beatsomeone.com/beatsomeone/index
- Team Experience
  - GlueOS under development(Parity-ether PoA base Solution) : [https://glueoscan.com](https://glueoscan.com/)

## Team members

- Team leader
  - David Park : Coin(20+) wallet, sign server development & node operation guide@Bithumb Exchange. Samsung Galaxy S S-memo Development.
- Team members
  - Mike MU : Blockchain researcher(Create a Blockchain research report 30+ 2) , DeFi Korea Co-Organizer, GrowFi Co-Founder, Korea Government Support Blockchain Education Instructor
  - Jay Lee : Coin(20+) wallet, sign server development & node operation guide @Bithumb Exchange. Mobile model leading & releasing team for USA market(AT/T, T-mobile) @LG MC.
  - Brian Noh : Deﬁ Project full-stack Developer. (https://github.com/bannplayer/Growdrop/tree/master 3). Korea Government Support Blockchain Education Instructor.
  - Adonis Seo : Exchange service Front-end & Back-end development Bithumb Cryptocurreny Deposit/Withdraw development .
  - Ian Son : Bithumb new exchange system development, Coin/Token Management/Listing system development.
  - Kidori Park : Exchange web solution developer. Korea Government Support Blockchain Education Instructor.
  - Gami Wang : Exchange Product manager

## Team Website

- https://www.linkedin.com/company/enterblock/
- [http://www.enterblock.co](http://www.enterblock.co/) (TBD)

## Team's experience

- Bithumb CryptoCurrency Researcher. Node Operation Guide, wallet, Cold Wallet Management, wallet, smartcontract,deposit/withraw, exchange Matching engine Development
- UDTSwap : Automated token exchange using multiple liquidity pool economy building on Nervos
- Growdrop : Funding the revolution of blockchain ecosystem with DeFi
- Substrate Delivery Partners

## Team Code Repos

- Growdrop :https://github.com/GrowFi-labs/Growdrop
- UDTswap :https://github.com/GrowFi-labs/UDTswap
- Growfi labs :https://github.com/GrowFi-labs

## Team LinkedIn Profiles

- David Park :[https://www.linkedin.com/in/%EA%B2%BD%EB%82%A8-%EB%B0%95-5a9805182/](https://www.linkedin.com/in/경남-박-5a9805182/)
- Jay Lee :https://www.linkedin.com/in/jay-lee-a24614aa/
- Mike MU :https://www.linkedin.com/in/mike-mu-a69160162/
- Jiamei Wang :https://www.linkedin.com/in/jiamei-wang-6b85791ab/
- Kiseok Park :https://www.linkedin.com/in/kiseok-park-722433177/
- Ian Son :[https://www.linkedin.com/in/%EC%83%81%EC%9C%A4-%EC%86%90-39095ba3/](https://www.linkedin.com/in/상윤-손-39095ba3/)
- Adonis Seo :https://www.linkedin.com/in/donghyuk-seo-0079a5131/
- Brian Noh :https://www.linkedin.com/in/sunglae-noh-533381196/

## Development Roadmap

For each milestone:

- Please be sure to include a specification of the software. The level of detail must be enough so that we are able to test that the software meets the specification.
- Please include total amount of funding requested per milestone. Funding can be in fiat (CHF, EUR or USD) or in DOTs. It can also be in a combination of fiat and DOTs. Please reach out to [grants@web3.foundation](mailto:grants@web3.foundation) (http://grants@web3.foundation/) to discuss what amount in fiat and DOTs would be appropriate for your project.
- Please note that we require documentation (e.g. tutorials) in each milestone. This ensures that the code can be widely used by the community.
- Please commit to providing a docker container for the delivery of your project.
- Please indicate the number of Full-Time Employees working on each milestone, and include the number of days along with their cost per day.

### Milestone 1 — Implement Substrate Modules — 1 month — $33,000

- Planning and Node configuration
- Plan
  - We will first organize functions for users.
  - We will proceed with web page UI design to provide functions.
  - Interface composition and document creation that enterprise developers can easily develop
- Node configuration
  - Configure substrate nodes that fits to users which want to run substrate nodes
  - Build docker for testing
- deliverable
  - primitive substrate node in docker or anything that can check if configuration is fine and node works well

### Milestone 2 — API implementation and testing— 1 month — $33,000

- make common EIP pallets (EIP20, EIP721, EIP777, EIP1155)
- common EIP pallets testing
- make runtime APIs and RPCs with common EIP pallets
- EIP20, EIP721, EIP777, EIP1155 smart contracts code using ink!
- smart contract testing
- Off-chain workers that can interact with common EIP pallets
- deliverable
  - common EIP pallets and smart contracts open sourced in github

### Milestone 3 — Operation and Testing — 1 month — $33,000

- MVP model for copyright registration and sales site for beatsomeone will be released
  - [http://mvp.beatsomeone.com/beatsomeone/index]
- Web application
- API document page
- Create management page for users
- deliverable
  - Web application that users can use BaaS service

## Future Plans

- Reference site extension and suggestion
  - Additional reference site extensions
- Proposal for Korean government project
  - Proposed to Korea's blockchain task system
  - custom common pallets that can help finantial projects

## FAQ

- What programming language would the developers code in your BaaS?
  - Rust
- What parts will be made with open source ?
  - common EIP pallets
  - for the custom pallets, since custom pallets have different desired parts for each clients, this part will be developed upon request of clients development after the mainnet release with no open source.
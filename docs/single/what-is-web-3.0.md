---
title: What is Web 3.0?
summary: Web 3.0 is what people are referring to as version 3 of the internet, the decentralized internet of the future. Version 1 of the web was the beginning. Websites were very simple with limited interactivity and the basic tools and protocols of the internet were first being developed. Later, websites started to be created with more interactive content such as web apps and social media websites, which changed the way we interact with each other around the globe forever. This marked the start of Web
authors:
  - Web3 Developer (@web3developer)
date: 2019-06-02
some_url: 
---

# What is Web 3.0?


Web 3.0 is what people are referring to as version 3 of the internet, the decentralized internet of the future. Version 1 of the web was the beginning. Websites were very simple with limited interactivity and the basic tools and protocols of the internet were first being developed. Later, websites started to be created with more interactive content such as web apps and social media websites, which changed the way we interact with each other around the globe forever. This marked the start of Web 2.0.
With this new era of social interactivity and cloud computing came some drawbacks for users. Companies are starting to collect massive amounts of personal data to the point where privacy is increasingly becoming a concern for users. Data is very valuable for companies as well as for malicious users and so securing all this data which is stored in centralized databases is becoming more and more difficult as hackers get smarter and computers get faster. For these reasons, people are saying that the internet is broken and needs to be fixed and as a result many projects have been started which plan to fix these problems by rebuilding the internet from the ground up. Many new Web 3.0 technologies, tools, and frameworks are currently being created.

#### Bitcoin
Bitcoin was really the beginning of this story and the technology that inspired many others to start working towards building Web 3.0. Bitcoin, is a completely decentralized (has no central governing authority) cryptocurrency which allows users to transfer value in the form of Bitcoin (digital currency) without requiring any third party or trusted middle man (such as a bank) to approve the transactions. It uses a peer to peer network of computers where all nodes that participate in the network are equal and the protocol ensures that participants can transact securely with each other.
Bitcoin was a ground breaking technology because it was the first to create a way for users to securely transact with each other without requiring any third party to facilitate trust between them. This is a revolutionary idea when you think about it because it has the potential to allow us to build more efficient systems on the web that will do away with many third party businesses and corporations that will one day be made obsolete.
The Bitcoin protocol uses cryptography and a data structure called a ‘blockchain’ to store groups of immutable transactions together in blocks which are linked in chains using cryptographic hashes. It turns out that this data structure has many desirable properties and for this reason blockchain based technologies have become very popular.

#### Blockchain and DLTs (Distributed Ledger Technologies)
Web 3.0 at it’s core will rely on the use of blockchain and distributed ledger technologies in order to facilitate the secure transfer of value between users and to securely store immutable data and to execute code that cannot be tampered with. The term blockchain refers to technologies which use a blockchain data structure where as distributed ledger technologies refers to technologies that create some form of distributed ledger that has similar properties to a blockchain but is not necessarily implemented in the same way.
A blockchain is basically a distributed ledger which stores cryptography signed transactions in blocks which are linked together using hashes which link each block with the previous block making the data in each block effectively immutable. Any changes to a block can be detected by verifying that the hash in each block matches the computed hash of the data in that block.

#### Ethereum — The World Computer
After Bitcoin many other cryptocurrencies and blockchain projects were created with each reimplementing much of the same logic and each running on their own separate peer to peer network. In 2013, Vitalik Buterin proposed a new project called Ethereum, aka ‘The World Computer’ which generalised the blockchain idea and created a platform which allows developers to easily create their own cryptocurrencies and blockchain based applications.
Ethereum has a Turing complete virtual machine called the EVM (Ethereum Virtual Machine) which can execute code stored in the blockchain called ‘smart contracts’. Code and data stored on the blockchain has the desirable properties of being tamper proof, censorship resistant, secure and completely decentralized with no central controlling authority. Once something is put on the blockchain is it there forever and cannot be removed. Ethereum smart contracts can be written in a number of programming languages which compile down into EVM bytecode which can be executed on the Ethereum blockchain. Solidity is currently the most popular language and has a familiar javascript like syntax which is easy for developers experienced in other languages to learn.
Ethereum was the first of its kind and is currently the most popular general purpose blockchain platform but other projects such as EOS, NEO and Tron are also trying to compete in the space. Ethereum appears to be more focused on its core principle of pure decentralization having no controlling authority while these other names sacrifice true decentralization in order to achieve higher transaction throughput.

#### Moving from Client-Server to Peer-to-Peer
The current internet is based on a client-server architecture. HTTP the client-server based protocol which is now ubiquitous across the internet basically involves having clients request data from servers which are waiting to serve requests. This architecture leads to a centralized internet where data is stored in centralized databases and servers which are owned and controlled by corporations that serve the data to users when they request it. The model is lacking in a few areas such as security, fault tolerance and censorship resistance. Companies with large amounts of data will become the target of attackers who want to gain access to that data which is very valuable. If data is stored in one place it is easier to steal then if it is stored in many places for example. Another problem is that data stored on the server is owned by the company and not the user. This leads to some problems such as privacy concerns and also possible unethical censorship, blocking or removal of a user’s data due to the political agenda of the company holding the data.
A peer to peer architected internet can solve many of these problems by making protocols and technologies that allow all computers to be equal, removing single points of failure, single points of control, centralized databases and making more efficient use of resources as computers can be functioning as both a client and server at the same time allowing resources of the internet to be utilised more efficiently. Blockchain technologies use peer to peer protocols to decentralize access to the blockchain and to allow all users to transact equally with no controlling entity deciding who is allowed to participate.

#### The Decentralized Cloud
I believe we are now nearing the end of Web 2.0 era. At this present time there are massive cloud computing companies such as AWS, Azure and Google Cloud which provide server farms for companies to hire and run applications by using compute, storage and networking services on demand for a reasonable price. While these services are very good for businesses at the moment because they are cheep and easy to use, I believe in the future all software will run on new decentralized cloud computing platforms which will move the cloud from client-server to a more peer to peer architecture, and using cryptocurrencies for the payment of resources rather than using fiat currencies. This cloud will eventually be much cheaper, more secure, more fair for users, censorship resistant and will allow users to buy or sell resources rather than just buying from big companies. A decentralized cloud would in theory be a much more efficient use of the global computing resources available because all computers connected to the internet, including mobile phones can participate as both a user and provider of resources. Here is a summary of a few interesting projects that are currently in development in this space:

#### IPFS
A peer to peer protocol for serving files which could eventually replace the client-server based HTTP protocol. Besides being peer to peer, IPFS uses a content based addressing mechanism rather than a location based one such as the URL mechanism used by HTTP. It works by taking a hash of the file data and using that as the resource locator rather than the name and location of the file. One thing to note is that IPFS is not a storage or hosting provider, it is just a protocol and therefore it relies on IPFS nodes to be serving the file data. If you had a website you wanted to host on IPFS you would need to run your own IPFS node to serve the files to the rest of the network because there is no guarantee that the rest of the network will keep serving all your files forever. Filecoin was created to solve this kind of problem allowing you to pay to have someone else host your files for you.

#### Filecoin
Is a peer to peer decentralized blockchain based file hosting service which has it own cryptocurrency which is used to buy and sell storage resources for rent in the platform. By paying to have your IPFS files stored in Filecoin you will be able to guarantee that users can access your files for as long as you pay for the storage. Filecoin will perhaps one day be a replacement for AWS S3 and Google Cloud Storage.

#### Golem
Described as the decentralized super computer, Golem is a peer to peer blockchain based decentralized computing platform. In the Golem ecosystem, you can loan out your computer’s spare resources to others who need the additional power to perform complex computations and tasks. Golem may one day replace AWS EC2 and Google Compute Engine.

#### ENS
The Ethereum Name Service (ENS) aims to replace DNS by creating a lookup service mapping human readable names to Ethereum addresses and other resources. ENS offers a secure & decentralised way to address resources both on and off the blockchain using simple, human-readable names.

#### DApps — Decentralized Applications
Finally on top of all these new technologies, blockchain protocols, and decentralized platforms, a new wave of applications will be and has already started to be developed. These Web 3.0 applications are called DApps (Decentralized Applications) and are built on top of peer to peer, decentralized and blockchain based technologies and so they benefit from the properties of the underlying technologies described above. Users will transact using cryptocurrencies and will store data and code on the blockchain and on the decentralized cloud.
Users will have full ownership of their data which will also be censorship resistant because it is permanently stored on the blockchain. Currently most DApps are developed to run on the Ethereum blockchain and are written in Solidity. They also use IPFS to serve the frontend which connects to smart contracts running on the blockchain and do away with the traditional centralized backend database and APIs. There is still much work to be done before we complete decentralizing the internet and so there has never been a better time to learn about Web 3.0 and become a DApps developer. Keep following me here at Web3 Developer if you want to learn more!



---

- **Kauri original title:** What is Web 3.0?
- **Kauri original link:** https://kauri.io/what-is-web-30/2678d5d36f5c45f981e482de289ce154/a
- **Kauri original author:** Web3 Developer (@web3developer)
- **Kauri original Publication date:** 2019-06-02
- **Kauri original tags:** ethereum, blockchain, web3, dapps
- **Kauri original hash:** Qmb2Vx4Gm3CPsLczXJ34RcfVzrNWPNCUVZFypcRLK8Xppg
- **Kauri original checkpoint:** QmYRYAA1TRyDiXS6uLXdt6qS8AnW63tqJHYpUQKrdyNz7h




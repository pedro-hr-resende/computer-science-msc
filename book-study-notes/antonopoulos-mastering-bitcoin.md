<!--
STUDENT: PEDRO HENRIQUE RESENDE RIBEIRO
DESCRIPTION: MASTERING BITCOIN - PROGRAMMING THE OPEN BLOCKCHAIN
DATE: 2024-06-22 - TIME: 05:30
-->

# MASTERING BITCOIN - PROGRAMMING THE OPEN BLOCKCHAIN

>ANTONOPOULOS, Andreas M. Mastering Bitcoin: Programming the open blockchain. "O'Reilly Media, Inc.", 2017.

<p align="justify">
"Bitcoin is a collection of concepts and technologies that form the basis os a digital money ecosystem. Units of currency called bitcoin are used to store and transmit value among participants in the bitcoin network." - pg. 1
</p>

<p align="justify">
"Bitcoin can be purchased, sold, and exchanged for other currencies at specialized currency exchanges. Bitcoin in a sense is the perfect form of money for the internet because it is fast, secure, and borderless." - pg. 1
</p>

<p align="justify">
"Users of bitcoin own keys that allow them to prove ownership of bitcoin in the bitcoin network. With these keys they can sign transactions to unlock the value and spend it by transferring it to a new owner. Keys are often stored in a digital wallet on each user's computer or smartphone." - pg. 1
</p>

<p align="justify">
"Bitcoin are created through a process called 'mining', which involves competing to find solutions to a mathematical problem while processing bitcoin transactions." - pg. 1
</p>

<p align="justify">
"Every 10 minutes, on average, a bitcoin miner is able to validate the transactions of the past 10 minutes and is rewarded with brand new bitcoin. Essentially, bitcoin mining decentralizes the currency-issuance and clearing functions of a central bank and replaces the need for any central bank." - pg. 2
</p>

<p align="justify">
"The difficulty of the processing task that miners must perform is adjusted dynamically so that, on average, someone succeeds every 10 minutes regardless of how many miners (and how much processing) are competing at any moment. The protocol also halves the rate at which new bitcoin are created every 4 years, and limits the total number of bitcoin that will be created to a fixed total just below 21 million coins. The result is that the number of bitcoin in circulation closely follows an easily predictable curve that approaches 21 million by the year 2140." - pg. 2
</p>

<p align="justify">
"Of course, conventional money is also often stored and transmitted digitally. In these cases, the counterfeiting and double-spend issues are handled by clearing all electronic transactions through central authorities that have a global view of the currency in circulation." - pg. 3
</p>

<p align="justify">
"For digital money, which cannot take advantage of esoteric inks or holographic strips, cryptography provides the basis for trusting the legitimacy of a user's claim to value. Specifically, cryptographic digital signatures enable a user to sign a digital asset or transaction proving the ownership of that asset. With the appropriate architecture, digital signatures also can be used to address the double-spend issue." - pg. 3
</p>

<p align="justify">
"Bitcoin was invented in 2008 with the publication of a paper titled 'Bitcoin: A peer-to-peer electronic cash system', written under the alias of Satoshi Nakamoto [...]." - pg. 4
</p>

<p align="justify">
"The key innovation was to use a distributed computation system (called a 'Proof-of-Work' algorithm) to conduct a global 'election' every 10 minutes, allowing the decentralized network to arrive at consensus about the state of transactions. This elegantly solves this issue of double-spend where a single currency unit can be spent twice." - pg. 4
</p>

<p align="justify">
"Bitcoin's total market value has at times exceeded $35 billion US dollars, depending on the bitcoin-to-dollar exchange rate. The largest transaction processed so far by the network was $150 million US dollars, transmitted instantly and processed without any fees." - pg. 4
</p>

<p align="justify">
"Bitcoin is a protocol that can be accessed using a client application that speaks the protocol. A 'bitcoin wallet' is the most common user interface to the bitcoin system, just like a web browser is the most common user interface for the HTTP protocol." - pg. 6
</p>

<p align="justify">
"There is also a reference implementation of the bitcoin protocol that includes a wallet, know as the 'Satoshi Client' or 'Bitcoin Core', which is derived from the original implementation written by Satoshi Nakamoto." - pg. 6
</p>

<p align="justify">
"Bitcoin wallets can be categorized as follows, according to the platform [...]" - pg. 7
</p>

- Desktop wallet
- Mobile wallet
- Web wallet
- Hardware wallet
- Paper wallet

<p align="justify">
"Another way to categorize bitcoin wallets is by their degree of autonomy and how they interact with the bitcoin network [...]" - pg. 7
</p>

- Full-node client
- Lightweight client
- Third-part API client

<p align="justify">
"Combining these categorizations, many bitcoin wallets fall into a few groups, with the three most common being desktop full client, mobile lightweight wallet, and web third-party wallet." - pg. 8
</p>

<p align="justify">
"Bitcoin addresses start with a 1 or 3. Like email addresses, they can be shared with other bitcoin users who can use them to send bitcoin directly to your wallet.There is nothing sensitive, from a security perspective, about the bitcoin address. It can be posted anywhere without risking the security of the account. Unlike email addresses, you can create new addresses as often you like, all of which will direct funds to your wallet. In fact, many modern wallets automatically create a new address for every transaction to maximize privacy. A wallet is simply a collection of addresses and the keys that unlock the funds within." - pg. 10
</p>

<p align="justify">
"In fact, in most wallets, there is no association between the bitcoin address and any externally identifiable information including the user's identity. [...]. Only once it has been associated with a transaction does it become part of the know addresses in the network." - pg. 10
</p>

<p align="justify">
"Bitcoin transactions are irreversible. [...]. For someone selling bitcoin, this difference introduces a very high risk that the buyer will reverse the electronic payment after they have received bitcoin, in effect defrauding the seller. To mitigate this risk, companies accepting traditional electronic payments in return for bitcoin usually require buyers to undergo identity verification and credit-worthiness checks, which may take several days or weeks." - pg. 10
</p>

<p align="justify">
"One of the advantages of bitcoin over other payment systems is that, when used correctly, it affords users much more privacy. Acquiring, holding, and spending bitcoin does not require you to divulge sensitive and personaly identifiable information to third parties. However, where bitcoin touches traditional systems, such as currency exchanges, national and international regulations often apply. In order to exchange bitcoin for your national currency, you will often be required to provide proof of identity and banking information. Users should be aware that once a bitcoin address is attached to an identity, all associated bitocin transactions are also easy to identify and track." - pg. 11
</p>

<p align="justify">
"Bitcoin, like most other currencies, has a floating exchange rate. That means that the value of bitcoin vis-avis any other currency fluctuates according to suplly and demand in the various markets where it is traded." - pg. 12
</p>

<p align="justify">
"Chicago Mercantile Exchange Bitcon Reference Rate: A reference rate that can be used for institutional and contractual reference, provided as part of investiment data feeds by the CME." - pg. 12
</p>

<p align="justify">
"At first, Alice's address will show the transaction from Joe as 'Unconfirmed'. This means that the transaction has been propagated to the network but has not yet been recorded in the bitcoin transaction ledger, known as the blockchain. To be confirmed, a transaction mus be included in a block and added to the blockchain, which happens every 10 minutes, on average. In traditional financial terms this is known as clearing." - pg. 14
</p>

<p align="justify">
"The bitcoin system, unlike traditional banking and payment systems, is based on decentralized trust. Instead of a central trusted authority, in bitcoin, trust is achieved as an emergent property from the interactions of different participants in the bitcoin system." - pg. 15
</p>

<p align="justify">
"A blockchain explorer is a web application that operates as a bitcoin search engine, in that it allows you to search fo addresses, transactions, and blocks and see the relationship and flows between them." - pg. 15
</p>

<p align="justify">
"Popular blockchain explorers include: [...]. Each of these has a search function that can take a bitcoin address, transaction hash, block number, or block hash retrieve corresponding information from the bitcoin network." - pg. 16
</p>

- Bitcoin Block Explorer
- BlockCypher Explorer
- Blockchain.info
- BitPay Insight

<p align="justify">
"The bitcoin network can trasact in fractional values e.g., from millibitcoin (1/1,000th of a bitcoin) down to 1/100,000,000th of a bitcoin, which is known as a satoshi." - pg. 18
</p>

<p align="justify">
"In simple terms, a transaction tells the network that the owner of some bitcoin value has authorized the transfer of that value to another owner. The new owner can now spend the bitcoin by creating another transaction that authorizes transfer to another owner, and so on, in a chain of ownership." - pg. 18
</p>

<p align="justify">
"The inputs and outputs (debits and credits) do not necessarily add up to the same amount. Instead, outputs add up to slightly less than inputs and the difference represents an implied transaction fee, which is a small payment colected by the miner who includes the transaction in the ledger." - pg. 18
</p>

<p align="justify">
"The transactions form a chain, where the inputs from the latest transaction correspond to outputs from previous transactions. Alice's key provides the signature that unlocks those previous transaction outputs, thereby proving to the bitcoin network that she owns the funds." - pg. 19
</p>

<p align="justify">
"Many bitcoin transactions will include outputs that reference both an address of the new owner and an address of the current owner, called the change address. This is because transaction inputs, like currency notes, cannot be divided." - pg. 20
</p>

<p align="justify">
"Different wallets may use different strategies when aggregating inputs to make a payment requested by the user. They might aggregate many small inputs, or use one that is equal to or larger than the desired payment. Unless the wallet can aggregate inputs in such a way to exactly match the desired payment plus transaction fees, the wallet will need to generate some change. This is very similar to how people handle cash." - pg. 20
</p>

<p align="justify">
"In summary, transactions move value from transaction inputs to transaction outputs. An input is a reference to a previous transaction's output, showing where the value is coming from. A transaction output directs a specific value to a new owner's bitcoin address and can include a change output back to the original owner. Outputs from one transaction can be used as inputs in a new transaction, thus creating a chain of ownership as the value is moved from owner to owner." - pg. 21
</p>

<p align="justify">
"Importantly, a wallet application can construct transactions even if it is completely offline. Like writing a check at home and later sending it to the bank in an envelope, the transaction does not need to be constructed an signed while connected to the bitcoin network." - pg. 22
</p>

<p align="justify">
"A bitcoin wallet application that runs as a full-node client actually contains a copy of every unspent output from every transaction in the blockchain. This allows a wallet to construct transaction inputs as well as quickly verify incoming transactions as having correct inputs. However, because a full-node client takes up a lot of disk space, most user wallets run 'lightweight' clients that track only the user's own unspent outputs." - pg. 22
</p>

<p align="justify">
"If the wallet application does not maintain a copy of unspent transaction outputs, it can query the bitcoin network to retrieve this information using a variety of APIs available by different providers or by asking a full-node using an application programming interface (API) call." - pg. 22
</p>

<p align="justify">
"A transaction output is created in the form of a script that creates an encumbrance on the value and can only be redeemed by the introduction of a solution to the script." - pg. 24
</p>

<p align="justify">
"Because the transaction contains all the information necessary to process, it does not matter how or where it is transmitted to the bitcoin network. The bitcoin network is a peer-to-peer network, with each bitcoin client participating by connecting to several other bitcoin clients. The purpose of the bitcoin network is to propagate transactions and blocks to all participants." - pg. 25
</p>

<p align="justify">
"Any system, such as a server, desktop application, or wallet, that participates in the bitcoin network by 'speaking' the bitcoin protocol is called a bitcoin node. [...]. Any bitcoin node that receives a valid transaction it has not seen before will immediately foward it to all other nodes to which it is connected, a propagation technique known as flooding. Thus, the transaction rapidly propagates out across the peer-to-peer network, reaching a large percentage of the nodes within a few seconds." - pg. 25
</p>

<p align="justify"></p>

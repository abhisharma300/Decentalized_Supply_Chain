# Decentralized Supply Chain

## Concept:

One of the biggest challenges with supply chains is the lack of transparency in product tracking which leads to increased costs, counterfeit goods, and unnecessary waste. Decentralized implementation of supply chain helps in improving transparency in supply chain & traceability of the product w.r.t it's provenance. By effectively managing supply chain, companies are able to create more efficient solutions for customers.

This implementation considers the underlying asset to be Coffee Bean and demonstrates traceability & transparency as it moves through the supply chain.

At the core of these transactions is trust + automation  (of negotiations) this can be achieved by shared ledger which allows companies to collaborate & interact effectively

## Architecture:

BlockChain Solution Layers:

**Smart Contracts** that help track product origination and verify product authenticity

-  Asset: any physical or digital entity that requires tracking
	Asset Attributes:
		a. Ownership
		b. Date/Time
		c. Location
		d. Grade
	
- Actors: who interact with this asset and trandform it from one state to another
	a. Farmer
	b. Distributor
	c. Retailer
	d. Consumer

- Role Permissions: for each actor

- Business Process:
progression of assets through various steps of business process which is recorded on chain for lookback and evidence of trail

**DAPP Client** The front-end of the application runs on the client's machine, powered by a lite-server. Using web3/metamask (using infura's endpoints), it communicates with the deployed smart contract from Ethereum Rinkeby Test Network. I



## Supply Chain Modelling for Coffee Bean : 


Coffee Bean from farmer to customers
1. Growing
2. Harvesting
3. Packing
4. Shipping
5. Roasting
Each stage involves a different supplier


## Implementation Walkthorugh ##

**Product Overview**
- SKU Is generated automatically by the system. Starts with 0 and increments as more items are added
- UPC is the unique id of the asset using which the  actors can track . Fetch Data 1 and Fetch Data 2 will return the state of the asset from blockchain

![Screenshot](Images/Product_Overview.png)



How Smart Contracts can improve supply chain
a. Transparency
b. Traceability
c. Efficiency

Use block-chain to collect data at each stage
Product is safe & coming from reliable surces. 
This transaparency allows you to have more confidence in the legitimacy of the product.
Open Shared Ledger allows business & consumer to better track information about goods & services
Traceability: information about product quality & its journey
using smart contracts you can track any of steps, program contracts for them and then get accurate information.
Smart sensors will capture how long a product was in shipment & for how long at what temperaure
Trace origin of product is valuable when product recall is needed



Efficiency: by programming smart contracts we can answer how fast a process is , how much it costs. Smart contracts can handle automation of some part of negotiations

Automate trust between company, supplier & customers




	





As you’ve learned in the course, a blockchain-based supply chain management solution can provide more accurate tracking, helping reduce fraud by transparently tracking product originatio

For this project, you will get to pick a supply chain of your choice and architect a DApp (Decentralized Application) authenticity management system backed by the Ethereum platform
To do so, you’ll scope out the needs of the various actors in the supply chain and create smart contracts that help track product origination and verify product authenticity. Then tie it all together with a simple front-end that allows users to manage the product life-cycle as the product moves through the supply chain!














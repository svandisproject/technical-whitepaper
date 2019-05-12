
# Svandis Technical Roadmap

## Q1 2018
### Data Mining Worker
* Broke ground on the worker application for distributed users to contribute their computing resources. The worker is used to actively query websites that have been tagged by the Svandis Internal team. 
* When new information is found by a worker, a socket-server confirms the findings and is able to forward them onto the content extractor.
* With outside users to contributing computational resources, more web sources online can be queried by the system.

### Svandis Frontend
* The frontend for svandis is an angular application created to act as a dashboard for the many features included within the system.
* It was created in Material Design with friendly login options. It will serve as a platform for the newsfeed, the ICO screeners, alt-coin screeners and up to date information, and blockchain connected modules that serve to keep the platform transparent.

### Research & Development
* The team researched originally the data structures that token offerings have in common to create a standardized fact reporting system for blockchain.
* News aggregation and the scraping of data sources was of particular interest in research. 

## Q2 2018

### Data Content Extraction
* Works to extract content from URLs programmed by the Svandis Internal Team. The content extracted is later scraped with machine learning to be relevant in the platform's news feed.
* The Content extractor is meant to integrate natural machine learning to improve the quality of the tags important to users in the newsfeed.

### Svandis Token Sale Smart Contracts
* Started working on the Ethereum Based Smart Contracts for Svandis.
* In this quarter, the Svandis token sale protocol was created. The token sale will be tiered and feature a Svandis ERC20 token.

### Whitepaper
* The original Svandis Whitepaper was released to give prospective ecosystem participants an overview of how Svandis is a unique model for all types of users to gain more knowledge and information within the cryptocurrency space.
 
### Token Sale Website
* The Svandis main website was designed and created to show off the most important information on the Svandis platform.
* Svandis key features from the whitepaper are presented on the website. The prospective token sale information has also been listed. Finally, the team and advisors are listed within the website.

## Q3 2018

### ICO Screeners
* Started UI and Schematics For ICO Screeners. Created the detail sets for the ICO screeners. Internally drafting the schematics for different types of Svandis data available. 
* ICO Screeners are available through the front end, they show important information such as price, industry, country, team members. 
* This information is meant to be crowdsourced in the future and improved by decentralized Svandis users acting in the benefit of the ecosystem, in return for Svandis rewards.

### Alt Coins Info and Screeners
* Such as with the ICO Screeners, there are is also up to date Alt Coin information available in the platform. This information will later be partially crowdsourced for factual information.
* Technical information such as the price, price changes and volume are available through the platform. 

### Technical Whitepaper
* This whitepaper was created in the purpose of offering an extended explanation for the goals of the Svandis platform. By concisely breaking down the different components of the full system, we are able to pinpoint why Svandis is useful.
* Svandis' technical architecture allows for the system to take on great loads of data, scrape it and present it to interested blockchain users. Those users have different ways to contribute to the ecosystem, and can furthermore influence the actual content of the Svandis offering.
* Svandis offers a news feed for opinion based information through the use of the content extractor and worker. Svandis offers a database of factual cryptocurrency information through crowdsourced data. Users are incentivized to submit factual information about token offerings and active tokens for example.

### Svandis Helpdesk
* Established the Svandis helpdesk to gain users feedback, offering technical support with the demo, and offer information on the Svandis upcoming token sale.

### Customizable Interface
* Steps were taken to make the frontend more customizable in appearance for the end user. The UI was significantly improved with new features and settings. 

### Token Sale Administration Module
* In order to help administer the token sale, the team built a typescript angular based administration module for internal use.
* To help the token sale move smoothly, the smart contract admin panel will allow the internal team to be able to execute a potential ICO from their browser in metamask.

### Beta Testing
* The front end and worker applications were qualified as minimum viable offerings for a demo. Beta users joined Svandis to start building feedback on the application.

## Q4 2018

### Frontend Newsfeed
* In this quarter the frontend had the UI for the newsfeed complete, now users can see newsfeeds from multiple sites around the world. 
* Globally distributed workers run remotely and provide processing power to scrape set web sources, the content is then extracted through the system and the end result is displayed to the user.
* Users can filter the news feed with parameters such as date, categories and sentiment.

### MVP for Ethereum User Onboarding tour
* Logged in users in the platform are now able to onboard onto the Blockchain. The MVP has been setup for both crypto beginners and expert users. Blockchain keys are setup for a user within the browser. The user is then able to save the key. 
* Expert users have the ability to manage their own decentralized identity. They can save their key, and if it is lost they are the only ones who can recover it.
* Beginner users are able to manage their own decentralized identity as well, however we introduce centralization as we give Svandis a key. This way, although the user can save their key, Svandis is able to recover their blockchain identity if they lose the key stored in their browser.
* The strategy here is to allow users to gain their decentralized identity to be able to submit signed data to the platform. This verifies users identities and provides a way for Svandis to assign reputation to a user. Unlike centralized ICO platforms, the users reputation is linked to their ability to submit factual unbiased information about projects.
* Users do not require metamask to interact, everything is done through the browser. Fees are collected from the user to cover the cost of backend processes, Svandis submits the users decentralized identity to the blockchain on their behalf using a signed message to confirm it was them. Svandis covers gas fees.
* This feature was inspired by Ethereum Improvement Protocol EIP 1078 for Universal Login.

### Svandis Smart Contract Backend
* To support the Svandis ecosystem, a set of smart contracts for a blockchain backend were drafted. This backend serves for the primary goal of having users submit signed structured data from their browser, and send it to a blockchain enabled express server. Processing this, the express backend creates a pseudo state channel low-gas and highly transparent system for creating and approving crypto currency information connected with the Ethereum Blockchain.
* The backends first function is to onboard beginner and expert users onto the blockchain. This is done through a signed message sent from the browser holding the users unique blockchain key. Therefore users can create a decentralized identity and potentially pay Svandis through fiat currency or participation in the platform to take care of gas fees. This was created on the Kovan network.
* When the user works on factual information such as the ICO or Alt Coin Screeners, the smart contract backend accepts these structured and signed data sets. The backend has been setup so that when there are active users submitting new ICOs and new changes to token information, there is a mechanism which ensures a consensus was made before submitting it to the network.
* Information is not always posted directly to the blockchain. Users sign their structured data so that after a consensus is done, they can prove that they were in favour of the consensus for the information. Afterwards as it is a pseudo state channel system, all the information can be compared afterwards and submitted onto the blockchain periodically as required.
* The smart contract backend is meant to pose no gas cost to end users and have minimum gas costs for Svandis. It is to act as a mechanism to prove which decentralized user submitted factual information and whether to accept it or not.

## Q1 - Q2 2019

### User Testing
* It is important for a beta software project to undergo rigorous user testing. The project is hosted at app.svandis.io for test users.
* A/B testing and observing how the user interacts with the software is important. During this phase we are evaluating the MVP and what changes need to be made for a go-to market strategy from a technical perspective

### Concept Validation
* With large amount of code and features created, the technical team analyzed how to best combine functionalities moving forward and re prioritize user epics Svandis wishes to accomplish before go to market.

### Svandis Widget
* The newsfeed and important cryptocurrency information will be available via a widget. In this quarter development started on the widget which will be available through the Svandis front end.
* Developers will be able to integrate the Svandis widget into their existing website with HTML code available to access the widget.


## Q3 2019

### Release version of Svandis MVP
* The MVP for Svandis built on app.svandis.io will move forward to a release version. Public users will be able to create an account with Svandis.
* The first users will be able to use Svandis as a newsfeed source for their cryptocurrency information. They will have access to a large array of up to date opinion based articles.
* Improvements for the onboarding tour onto the blockchain. Users connecting their social media accounts will acheive a higher reputation on the network.
* ICO Screeners built by the Internal Svandis Team will be available to users.
* Alt Coin Information will be available and allow users to see up to date information of price, volume, price swings.
* Users are be able to onboard into the blockchain and gain the decentralized identity, to get ready for them to submit data to the consensus mechanism. More information about blockchain transactions and consensus decisions will be available to ecosystem participants.
* Decentralized blockchain identity is based on EIP 725 and 735 protocols. These include key management options for users and signing of claims on the blockchain to enable rewards for users verifying their social media.
* The newsfeed will filter information and allow for customization of the Svandis dashboard and widget.

### Beta Version of Data Mining App
* The data mining app will be available to beta users, for testing on their own machines.
* Svandis will test scaling out the socket server and aggregating content from a large database of cryptocurrency information sources.

## Q4 2019

### Backend Consensus Activated
* The backend will have its consensus code ready so that users can submit new or changed ICO Screener or Alt Coin Screener information.
* Users will submit new data or data that has been identified by the Svandis internal team. The platform will be updated with the information that meets the consensus.
* Quantitative data such as token sale caps, number of tiers, rate per eth or usd will be the first information available for users, with qualitative string or concept based data coming later on.
* The information will be submitted to the blockchain after a certain period. Consensus will be proven as the users will submit confidential signed data structures that only they could have created to the platform.

### User Rewards Activated
* The microraiden microtransactions will be generated for users who contribute to the platform by submitting signed structured data to consensus.
* Users using the data mining app will receive token microtransaction token rewards for content successfully found and scraped from web sources.

### Release version of Data Mining App Available
* Users will be able to use the data mining app to contribute to the Svandis platform. This will increase the velocity at which new information is available on the Newsfeed from a large quantity of opinion based news sources.
* Token awards will be available to users offering their computing resources to the Svandis ecosystem.

### Mobile Responsive Web App
* The front end currently available in Angular will be ported to also be available on mobile operating systems.
* Having the Svandis app more accessible will empower cryptocurrency enthusiasts and allow them to receive the latest cryptocurrency information in the moment it happens.
* Optional notifications will allow users to set alerts when important events like catalysts occur. Such events can inform traders and allow them to make educated economic decisions in the cryptocurrency space.

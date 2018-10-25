<p align="center">
  <a href="http://svandis.io/" target="blank"><img src="/images/image1.png?raw=true" width="320" alt="Svandis" /></a>
</p>

# Svandis.io Technical Whitepaper

**October 25th, 2018**

## Abstract

**Svandis mission**
Every day, the difficulty in evaluating the reliability and relevance of facts within the cryptocurrency space multiplies. This difficulty is pronounced by the growing number of data sources reporting on the emergence and adoption of blockchain across all industries, as well as a huge amount of often conflicting and imprecise market data. This outdated or biased data becomes a problem for traders and investors. The Svandis mission is to offer a data platform with a trustable strategy to validate, analyze and visualize objective and relevant data about the crypto market rapidly to eliminate these inconsistencies.

**The Platform**
Svandis is a blockchain-based data platform providing research and visualization tools to crypto market participants. All data is aggregated in one place, gathered by the DataMining App and Research Community, a gamified validation system on the Ethereum blockchain. This valuable and trusted data is then accessible via the Svandis toolset: Newsfeed, Screeners (ICO and Altcoins), Catalyst Analysis tools, Heatmaps, Alerts, Indices, and Portfolio. By multiplying and expanding the opportunities for interoperability between the Svandis tools, true clarity and insight into data becomes possible, in the form of a modular dashboard. Additional features and products are offered by third-parties within the Svandis Marketplace to provide a broader product line for traders.

Data gathering - Decentralized and crowdsourced due diligence

Svandis approach to data gathering starts with a decentralized Research Community with users who have control of their own blockchain identity. The Research Community and DataMining App bring new possibilities in the speed of available data. Not only is the process of accumulating cryptocurrency information faster and more efficient, but it brings much-needed objectivity and reliability to the information. This hybrid solution balances scalability with the needs for off blockchain scalable decision making for the Research Community.

The Svandis Research Community is a “Research and Data Verification” mechanism with a multiple validation process to complete data integrity checks on ICOs and token sales. This can include any token,  including tokens governed by decentralized autonomous organizations or stablecoins. Furthermore, the Research Community assists newsfeed curation, catalyst validation and more in return for token rewards. The goal is to ensure the validity of several categories of information by using a standardized template to create consistency in the presentation and reliability of data. 

The DataMining App is a cross-platform data-miner for online news and article sources. It is an open-source crawling application that users can install on their computers to participate in data crowdsourcing in return for rewards. This automated process will increase the speed and accuracy of the Svandis Newsfeed and Catalyst Analysis features, which provide an objective perspective to give traders deep insight. The Svandis solution balances the need for correlating qualitative and quantitative information for traders through our rich toolset.


**Data processing**
In order to facilitate a positive feedback loop between the Research Community and the Internal Analytics team, we will be using natural language processing such as sentiment analysis to pinpoint catalysts - a revelation or event that propels the price up or down - and other events within the ecosystem. These will be integrated during the off blockchain data consensus mechanism as well as to correlate similar information being presented by members of the Research Community. Research Community members will sign the data they present at consensus in order to build a positive and actionable reputation. A solid reputation will equate to stronger influence on the community and more token rewards for research accomplished.

## DISCLAIMER
This Technical Whitepaper does not constitute an offer to sell or invitation to purchase any securities of any nature whatsoever, and the content of this presentation is not intended to constitute legal, commercial or tax advice. Some of the declarations contained in this WP constitute forward-looking statements and are subject to change without prior notice.

The Svandis Technical Whitepaper is intended for preparation, description and information purposes only, and does not constitute an offer or solicitation to buy or sell any securities or invest in any of all types of financial instruments. This document is not compiled in compliance with and is not subject to, the laws and regulations of any jurisdiction created to protect the investors. Nothing published by Svandis or one any of its subsidiaries should be taken as investment advice. Please consult an appropriate licensed professional before engaging in any financial transaction, including any investment related to the ideas or opinions expressed, in the past, present or future, by Svandis or any future entity working for the parent entity. The information document below should not be seen as exhaustive and does not imply any element of a contractual relationship. Its sole aim is to submit relevant and reasonable information to potential token holders so that they can determine whether they should undertake an in-depth analysis of the company before intending to acquire tokens.

The Svandis token, or SVN, is a cryptographic token used to access the Svandis Platform. In no circumstances should the SVN tokens be confused with security tokens. All SVN tokens purchases are non-refundable. SVN token ownership does not represent any future governance of the platform or Svandis. By purchasing the SVN token, you will be deemed to have carefully reviewed the purchase terms. In addition, you represent and warrant that you are of sufficient legal age to be bound by these terms and that you may not under any circumstances hold the company, its representatives, founders, affiliates or advisors, either now or in the future, liable for any loss or damage arising from the purchase or sale of the SVN token. The purchaser is solely and entirely responsible for all risks associated with the purchase of the SVN token, and warrants that this purchase is made to support the project development activities and not to make a speculative investment. Svandis recognizes that the purchaser will have to meet KYC (Know Your Customer) and AML (Anti-Money Laundering) requirements when buying the SVN token. Svandis expressly disclaims any liability or responsibility for any direct or indirect loss or damage of any nature whatsoever, relating directly or indirectly to: (1) the reliance on any information content presented in this document, (2) any error, omission or inaccuracy relative to the information herein or (3) any action deriving from the information herein.

This Technical Whitepaper, any portion or copy thereof shall not be brought, transmitted or distributed in any countries where the distribution or diffusion of the token sale or the initial coins offer described within the Technical Whitepaper is prohibited or restricted. You are not eligible, and you cannot buy any Svandis token if you are a citizen, resident or green card holder of the United States of America.

# Table of Contents
<!-- MarkdownTOC depth=4 autolink=true bracket=round list_bullets="-*+" -->
- [Introduction](#introduction)
- [Toolset Overview](#toolset-overview)
  * [ICO & Token Sale Screener](#ico-and-token-sale-screener)
  * [Cryptocurrency & Token Screener](#cryptocurrency-and-token-screener)
  * [News Feed](#newsfeed)
  * [Charts](#charts)
  * [Catalysts Analysis](#catalyst-analysis-tool)
  * [Heatmaps & Groups](#heatmaps-and-groups)
  * [Watchlist & Alerts](#watchlist-and-alerts)
  * [Portfolio](#portfolio)
  * [Customized Interface](#customisable-user-interface)
  * [The Svandis Ecosystem](#the-svandis-ecosystem)
  * [Svandis DataMining App](#svandis-datamining-app)
  * [Svandis Marketplace](#svandis-marketplace)
  * [Svandis Indices](#svandis-indices)
  * [API Core](#api-core)
- [Data Mining Architecture](#data-mining-architecture)
  * [Data Mining Workers](#data-mining-workers)
  * [Machine Learning & Sentiment Analysis](#machine-learning-and-sentiment-analysis)
  * [Svandis Database](#svandis-database)
- [Research Community Structure](#research-community-structure)
  * [Roles in the Research Community](#roles-in-the-research-community)
- [Ratings and Svandis Power](#rating-and-svandis-power)
  * [Rating](#rating)
  * [Svandis Power](#svandis-power)
  * [Newsfeed Rating](#newsfeed-rating)
- [Blockchain Architecture](#blockchain-architecture)
  * [ERC 725/735 Identity](#erc-725735-decentralized-identities)
- [Screeners Workflow for the Research Community](#screeners-workflow-for-the-research-community)
  * [Data Submission Phase](#data-submission-phase)
  * [Data Validation Phase](#data-validation-phase)
  * [Data Signing and Screeners on the Blockchain](#data-signing-and-screeners-on-the-blockchain)
  * [Consensus and Off-Chain Settlement](#consensus-and-off-chain-settlement)
  * [Blockchain Data Publication Phase](#blockchain-data-publication-phase)
  * [Data Modification Phase](#data-modification-phase)
  * [Token Project Participants](#token-project-participants)
  * [SVN Token Economics](#svn-token-economics)
  * [ERC20 Micro Rewards on MicroRaiden](#erc20-micro-rewards-on-microraiden)
  * [Ecosystem Evolution](#ecosystem-evolution)
- [Conclusion](#conclusion)
<!-- /MarkdownTOC -->

# Toolset Overview

The Svandis Platform is a comprehensive toolset of features designed to give traders deeper insights into the cryptocurrency market. The tools combine the transparency of the blockchain and the efficiency of machine learning to notify traders of market opportunities in the moment. These tools do not run entirely on blockchain, rather they constitute a hybrid solution of smart contracts, off chain databases, and API’s. The solution is designed to use blockchain in certain situations, where doing so decreases the need for users to trust centralized parties. The screener presented by Svandis is free from bias and uses decentralization of user identities to increase trustlessness. The data miner works to harvest a news feed of factual and up to date data sources for users, to offer a greater perspective into the blockchain space. 

The Svandis ecosystem will be an industry first — a comprehensive crypto-research and visualization platform that combines crowdsourced data and machine learning.  Researchers earn the SVN token as a reward for researching and curating high-quality information while naturally learning more about cryptocurrency.

This document seeks to describe how Svandis can take advantage of the transparency of the blockchain while remaining a scalable and low-cost service to its user base. After describing the toolset and decentralized user growth, we will discuss how the solution will evolve to shift more responsibility towards an educated autonomous Research Community and away from a centralized software organization. 

## ICO and Token Sale Screener
Screeners are trustworthy sets of data about cryptocurrencies, tokens, ICOs or token sales which have been curated by Svandis and the Research Community through validation on grids of data fields. Svandis screeners will allow users to filter crypto-assets by various parameters using customized criteria to identify the best investment and trading opportunities. Many relevant screeners already exist and are available via traditional financial platforms. We will adjust how such existing financial tools like screeners work by adding an additional layer of transparency, using crowdsourced data from a decentralized community as a source of information. 

Companies will increasingly make their data more accessible to enhance their competitive position within the crypto space. We already see new models like DAICO emerging and the Svandis Platform must be adaptive to welcome those evolution by modifying our screener model to adapt. As the number of parameters involved in the buying of particular token also increases, the Svandis screeners structured template will be adapted to reflect those continuous changes.

Svandis screeners are meant to be built up for all currently operating ICO, DAICO and other fundraising or governance methods, as well as global tokens and cryptocurrencies. To build comprehensive sets of data, we will be powered by a combination of the Research Community and the internal analytics team to curate this. Such dependency is mitigated by the token incentive structure explained later on, which involves token rewards for participation. 

The screeners API will be available for use within algorithmic trading strategies. Speed will be an advantage for users who want to use statistics for momentum-based trading strategies and statistical arbitrage. For event-driven strategies, a newsfeed will be available through a text analytics API. The screener itself consists of a structured data template filled and signed by the users who researched and/or validated it with their unique Ethereum blockchain identity.

The ICO and token sale screener will sort and filter past and future ICO’s and token sales according to various parameters. A continuous updating, completed by the Research Community will ensure accurate data. A wide range of criteria will be available and customisable, providing myriad ways to fine-tune the screener. A full description of each ICO and token sale will be available, including the latest news about it.

<details><summary>Expand examples of filters available:</summary><br>


* Algorithm
* Type
* Hard Cap
* Min Cap
* Max supply
* Sale Supply
* Price USD/ETH
* Investors
* Whitepaper
* Private sale
* Bounty
* Days left
* Staking
* Masternodes
* Burning
* Protocol or dApp
* Type of Consensus
* Sector
* Algorithm
* Type
* KYC (investment range)
* Country
* Country restriction
* Actual sale stage
* Demo availability
* Accepted currencies
* Project completion
* % Tokens to the team
* % of Tokens being sold
* Smart contract audit
* Individual cap
* Medium/Telegram/Twitter followers, Reddit subscriber


</details><br>


## Cryptocurrency and Token Screener
The screener will sort and filter cryptocurrencies and tokens according to a variety of parameters, both fundamental and technical. Brief information will be posted within each cryptocurrency and token page, along with a chart displaying technical indicators and news gathered from varying sources. A vast range of criteria will be available to fine-tune parameters, providing a multitude of configurations to discover and filter cryptocurrencies and tokens.

<details><summary>Expand examples of filters available:</summary><br>


* Market Cap 
* Exchange
* Algorithm
* Type
* Price
* Performance
* Max supply
* Volume 24h
* Age
* Circulating supply
* Sector
* Type
* Average volume 52 weeks
* ICO amount
* Return on ICO USD/ETH
* Medium/Telegram/Twitter followers, Reddit subscriber
* Svandis Indice
* Performance (price and volume)
* Moving average (Price and Price Crossover)
* Oscillators (RSI, Stochastic oscillator, Stochastic RSI, William %R)
* Trend indicators (MACD, MACD Histogram, Parabolic SAR, ADX) 
* Ichimoku Cloud (Price/Cloud, Tenkan/Kijun)
* Volatility (ATR, Bollinger bands)
* Volume (Ease of movement, OBV)
* NVT Signal, NVT Ratio


</details>


## Newsfeed
Svandis is developing a customizable newsfeed for different markets, with an initial focus on the cryptocurrency industry. In this context, our goal is to aggregate crypto-related news across a variety of sources that have been shown to significantly influence the market, including websites, Twitter, Reddit, Telegram, Medium and other blogs. We aim to provide traders and investors with this information in near real-time.

With access to the Svandis newsfeed, crypto-market participants will no longer need to follow hundreds of Twitter accounts, subscribe to newsletters, keep numerous tabs opened in their web browser, alternate between sources, etc. They will receive all the information they need in one place, and will be among the first to know when and why the market is moving. Svandis will track thousands of sites both automatically and manually, fetching and highlighting the most important items using machine learning, language processing, the human insight of the Research Community and professional analysts and journalists.

Each news source will be assigned a set of tags, including but not limited to:
* **Descriptors:** Name of the digital asset, ICO or token sale, symbol
* **Sector:** Art, Sports, Gambling, Education, Banking, Business services, Charity, Cryptocurrency, etc
* **Category:** Partnership, Project update, Token sale, New Listing, Legal,  Regulation, Event
* **Importance:** Regular News, Hot News, Breaking News
* **Sentiment:** Bullish, Bearish
* **Media type:** video, article, blog, image/infographic, forum/discussion group

Crypto-market participants seeking real-time information will be able to customize their newsfeed according to their needs. For example, if a trader is interested in a token that has just been issued after a token sale, and is not yet listed on any of the major exchanges, they will be able to configure their newsfeed in such a way that they will receive news about this particular token in regards to exchange listings, or post ICO/token sale status. As the popularity of the Svandis Platform grows, the goal is to sign exclusive contracts with companies, exchanges and other news sources in order to publish their own news releases first at a predetermined time, in a single place and without information leaks.

The newsfeed works in synchronization with our community of data miners. The Svandis internal team collects trustworthy news outlets online and program carefully chosen CSS selectors to lock onto the URLs of new articles found within the sources. It is then the design of the automated data mining workers (on the locally running Svandis Data Mining App) to use community resources to scrape new URLs to submit to Svandis in return for SVN rewards.

Newsfeed sources will initially be curated by the Svandis Internal Team to become a high quality source of information from the beginning. As our technology stack develops, we will add more features allowing for users to add their own news sources. This will require validation mechanisms to approve new content including a final check by a mediator or analyst of the Svandis internal team before being published. A huge Research Community will be faster and more efficient than an internal team, as with scaling of user participation we create an autonomous environment to compile cryptocurrency news/info.

Through supervised machine learning, we will improve the tagging mechanisms over time by harvesting common terms and trends related to the tags that pull the highest quality news stories. Natural language processing and sentiment analysis are important components of machine learning theory we will need to apply to help tag and identify trends in blockchain projects.

Research Community users utilizing the newsfeed have the option to tag the sentiment (e.g.., bearish, bullish) of articles in the feed as a means of notifying the community on the current or changing sentiment in the market or news. This feature is for users that contribute to the Research Community and benefits basic users with better insights on the community sentiment for a given project. Additionally, relevant tags will be made available as necessary, such as the flagging of an article to mark it as more "significant" in order to grasp bigger news making an impact on the community. Offering sentiment analysis and catalysts as discussed later, we can create a more robust service of alerts for our users on demand with market trends.

Website listed in the news feed may change CSS selectors, have their site hacked, or purposely publish false information over time. Articles from such news feed sources are misleading, so users should therefore have the ability to mark items as toxic. At this time users may block content from sites they deem toxic. Articles marked as toxic can help the team of analysts at Svandis refine newsfeeds in order to maintain a consistently trustworthy offering. This mechanism will work to show a news source % of toxic articles, and will give the users the options to exclude certain news sources based on this metric. Sources validated as toxic should be paused, modified, or deleted from feed based on the % of articles from a source deemed toxic. Naturally, Svandis does not want news sources with many toxic articles as users will develop the perception that the sources are not trustworthy information. Through a combination of such tags, we can curate the feed and ensure an increase in quality offered by the newsfeed over time. 

## Charts

Charts will form an integral part of the Svandis Platform. Whether a cryptocurrency is selected from the screener, index, heatmap or group, a dedicated chart page will offer actionable information on a diverse range of technical indicators and catalysts. Svandis' charts will combine different types of data to create new insights for professional traders who want to take a step back and analyze the elements that influence their investments in greater depth. As the ergonomics of the Svandis tools are a priority, particular attention will be paid to all chart-related tools to optimize the customizable user experience. The end result is a more efficient workflow for traders and investors.

Charts will be built on top of the TradingView Platform and will be accessible on the user frontend Svandis application. [Trading View](https://www.tradingview.com/HTML5-stock-forex-bitcoin-charting-library/) offers a comprehensive platform for developers to include in their applications. We are choosing to bootstrap this chart as it is an industry leader and will serve as a supplement to the other information Svandis will be presenting to the community.  

## Catalyst Analysis Tool

Svandis will offer its users the opportunity to visualize the impact of a significant event on the price of a cryptocurrency asset. The objective is to identify “price influencing” events on a familiar tradingview chart for users to identify market opportunities. This could include any eventuality, e.g., an announcement or publication, partnership announcement, new tools, analysts’ and influencers’ mention or ranking update, change in legislation, legal prosecution, critical hirings, or potential mergers and acquisitions.

Such events might not have an immediate effect on a company’s fundamentals, but short-term traders will be able to benefit from the analysis of these elements. This Svandis functionality will allow users to combine complementary data from multiple sources on a single chart, with the belief that the more flexible the UX, the better. Catalysts can be grouped and investigated to determine their impact later on in historical reviews. The Svandis Internal Team will be responsible for facilitating online Research Community users to validate the occurrence events detected by machine learning logic patterns.

In order to facilitate a positive feedback loop between the Research Community and the Internal Analytics team, we will be using natural language processing such as sentiment analysis to pinpoint catalysts - a revelation or event that propels the price up or down - and other events within the ecosystem. These will be integrated during the off blockchain data consensus mechanism as well as to correlate similar information being presented by members of the Research Community. Research Community members will sign the data they present at consensus in order to build a positive and actionable reputation. A solid reputation will equate to stronger influence on the community and more token rewards for research accomplished.

Catalyst analysis uses a combination of standard data collection, our flagged newsfeed, and changes in price to create a meaningful offering for the community. These catalysts are meant to be posted onto a historical chart to try and visualize the effect of an event and its related sentiment upon a cryptocurrency.

Svandis has the opportunity to use a combination of human-analyst input, monitoring of price action, and the flagged articles on the newsfeed to create catalysts. Newsfeed articles contain both bullish/bearish sentiment indicators that the community can use to assign the sentiment of articles, as well as an "importance" flag to pinpoint significant articles with a daily limit in place on this for scarcity. The catalyst will exemplify the effect of sentiment and significance in major stories on the resulting short-term price swing of the cryptocurrency. This will be an optional parameter to be posted on tradingview charts afterward.

The workflow for identifying a catalyst starts with our backend using machine learning to seek out articles with strong sentiment and significance. This is combined with the monitoring of price fluctuations to notify analysts of a potential catalyst. It will be up to responsive and anonymous Research Community members to decide whether to notify the community of a catalyst or not by flagging it. There will also be an option for the Research Community to push their own custom catalysts which may be based on existing news in the web feed or not, which could later also be listed on the marketplace. Within Svandis, mechanisms exist so that when there is a critical mass of online users, they may act on their own and interact solely with the platform to make decisions with their fellow users.

In many cases, there will be price fluctuations without any single identifiable cause. We can retrospectively rationalize these fluctuations. However, the specific cause is still unknown. By tagging these events we gain a better understanding of what portion of large market movements can actually be attributed to a concise occurrence.

To sum up the active workflow, the backend server will be monitoring for changes of, for example, high percentage swings over past hour or day in the token price, depending on the historical volatility of the token. If a price swing of this intensity is detected, machine learning algorithms will start the analysis. It will analyze the quantity of news stories, the bearish/bullish sentiment (we want to correlate up-swings with bullish sentiment, for example), and significance levels for the news stories. If there is a significant economic fluctuation that can be attributed to an increase in news and relevant sentiment, the system will add the most relevant tags and content to the catalyst. If the solution cannot pinpoint a specific group of tags to describe the catalyst event occurring, the catalyst will be flagged. 

## Heatmaps and Groups

Svandis is developing a visual heatmap of the market that will help traders check the crypto-market status on a daily basis or over a specified period. Heatmaps translate raw, complex financial data into visual maps by presenting live, vivid images that dynamically change; providing traders with a mechanism to quickly determine which cryptocurrencies and tokens are moving, how far they are moving and in which direction. Heatmaps are industry-proven investment tools that synthesize complex data to help individuals make educated trading decisions. The market capitalization of each token or cryptocurrency will be displayed on the heatmap, as well as the change in their price for a given period (day, week, month, quarter, year). Svandis heatmaps will reflect most of the tradeable crypto assets, which may include (but not limited to) the following categories:

* Cryptocurrencies
* Entertainment
* Energy
* Prediction Markets
* Gaming/eSports
* VR/AR
* Insurance
* Lending
* Funds/Investment Managers
* Governance
* The Internet of Things
* Data
* Ticketing
* Wallets & Money Services
* Exchanges and Cryptocurrencies Trading

In addition to the heatmaps, users will be able to group cryptocurrencies and tokens included in the Svandis screener. This grouping tool will allow crypto-assets to be visualized by sector, industry, geography and capitalization. Each group will be sortable by different filters and visualization options, e.g., tables, bar charts, spectra, grids, etc. Users can select to display group information onto a heatmap.

Heatmaps will be built on the Svandis front-end application to present another perspective to traders. They will be built using [D3 technology](https://github.com/d3/d3). This module has a plethora of use within the online community, and we can build a powerful platform for our heatmaps upon it.

Groups and filters will be available with the heatmaps, and they will be customizable for traders to analyze the data points most relevant to their research needs. Users will be able to share groups they find useful. An example of a group would be the selection of cryptocurrencies with same type of blockchain or based upon a thematic commonality, such as "ICOs with Year To Date (YTD) positive returns from the 2018 bear market."

## Watchlists and Alerts

In order to continuously monitor crypto-assets, users can access the Svandis Watchlist and Alerts tools. Watchlists will quickly and easily collate into an editable list of crypto-assets that the user wants to monitor. It will be possible to assign tags and change the display order in simple steps. The watchlist will also incorporate a configurable alert function, offering users a range of notification options for certain conditions via Telegram, SMS or email.

Watchlists will be a component of our backend Svandis services. When users register for the aforementioned notifications, the backend will monitor for catalysts or events, significant price swings in cryptocurrencies, news feed articles, or other relevant information to relay to the user in real time. This allows the Svandis community to stay on top of the latest cryptocurrency changes as they happen. Svandis will build on top of NestJS technology to create the backend microservices facilitating real-time feedback for events in the Svandis community.

## Portfolio
The Svandis ecosystem provides a proficient and reliable tool for quick portfolio visualization. The portfolio developed by Svandis will connect to several popular exchanges, allowing users to evaluate the impact of breaking news on their portfolio, as well as quickly applying heatmaps to their assets for decision making.

The portfolio for a given user will be available on their front-end Svandis application. Svandis will save portfolio information securely in our database. Users wishing to share their portfolio may be entitled to SVN rewards. Users will be able to customize their portfolio and use tools such as heatmaps, catalyst analysis and charts to see how their investments are working for them. Users can reliably add and remove items from their portfolio with a rich array of fields to allow traders to keep track of their performance. The Svandis application uses the [material design](https://material.angular.io) software package to provide a rich user experience.

## Customisable User-Interface
Every Svandis user will have a customizable interface to arrange and present data in the most suitable way for their trading needs. It will include different colour schemes and layouts for added customization.

The Svandis application is built on top of Angular and Angular Material Design. The application will act as a customizable dashboard where users will be able to customize styling as mentioned, as well as save default configuration for their charts, heatmaps, and portfolios. The customizability of the UI will allow traders to get all information they need on one dashboard without having to have multiple tabs and services open on their local machine.

## The Svandis Ecosystem

![Ecosystem](/images/image2.png?raw=true "Ecosystem")

The power of the decentralized Research Community is unparalleled in the cryptomarket and may increase the capability to detect opportunities or report organized information in a quick and efficient manner. In addition, the information created by them is more trustworthy as there are mechanisms in place that prohibit the community from gaining rewards from false information researched.

The Research Community and the Svandis Analytics Team are the essential players in the Svandis ecosystem. Their roles, and in particular the Community’s role, will enable traders using the Svandis Platform to receive all necessary crypto-data in one place before the majority of market participants. 

The Svandis Research Community is a trusted information and data verification platform. Svandis aims to create professional development opportunities for the most active community members who wish to complete data checks on ICOs and token sales. The goal is to check the validity of several categories of information published on an ICO or token sale. Using a standardized template to ensure consistency in the presentation of data, a checklist on various points will be available to verify and share with the community whether the given project is (1) legitimate and (2) technically feasible over a realistic period of time. Applying the diversity of expertise available among Svandis users will help target high potential projects, as well as share precautionary opinions on others. We believe that an incentivized community of reviewers can look at important elements, such as company & team backgrounds, ICO metrics, etc.

This dynamic system will be comprised of two phases for a given screener. The first phase is creating the initial information for all existing cryptocurrency and token projects. The second phase is curating this information, so each time more up-to-date information can be provided. Token rewards vary for the task being completed.

Svandis will deploy a series of Solidity smart contracts on the Ethereum blockchain. These contracts, “The Svandis Ecosystem" containing decentralized identity for the Research Community and trustless proofs for the consensus to build reliable Svandis data. The smart contracts involved will be discussed in [Research Community Structure](#research-community-structure).

![Ecosystem](/images/image3.png?raw=true "Ecosystem")

![Ecosystem](/images/image4.png?raw=true "Ecosystem")

![Ecosystem](/images/image5.png?raw=true "Ecosystem")

**Multi Language** is one of the fundamentals of the Ecosystem, not just the screeners but also extending to the newsfeed and dashboard. Svandis is a growing team of individuals from Canada, Russia, Iceland, Vietnam, Ukraine, and many more. In order to support a global crypto community, we plan to integrate our front-end Svandis application offering with translation services serving a scope of languages on the fly. There will be built-in automated translation so that we only need to collect real-time information and screener updates in English to increase the speed of our offering. Cryptocurrency projects attract users from all corners of the globe. Allowing new users to understand facts in their native language is one of the best ways Svandis can contribute to blockchain adoption.

## Svandis DataMining App
Svandis will offer users data-mining functionality via the cross-platform DataMining Application. The DataMining App is an open-source crawling application that users can install on their computers to participate into data crowdsourcing and get SVN rewards. Crawling is systematically visiting a number of web pages in order to harvest and index data sources. The DataMining App is an automated software that crawls websites, grabbing copies of pages to index.

Receiving tasks from the Svandis server, the DataMining App will support the newsfeed by fetching website pages and social media content (all with user permission) to enable the analysis of a vast quantity of historical and real-time data. The web sources that will be crawled are served up by our worker-api with quality control in place to prevent workers from collecting information from toxic sites. Once the encrypted data is sent to the Svandis servers, it is processed using machine learning algorithms to allow correlation analysis of variables affecting a crypto-asset’s price. This automated process will increase the speed and accuracy of the Svandis Newsfeed and Catalyst Analysis tools (to be described in subsequent articles). Svandis will not collect personal data of any kind; Svandis adheres to the highest security standards with regard to personal information, is taking all possible steps to conform with the GDPR standards. Users have the option to remove their decentralized identity from our on chain user registry.

The type of data a miner’s device will grab will depend on the strength of their internet connection and device’s computing power. For example, those with a faster internet connection and a computer of higher processing power may grab real-time data, which should be more readily available to users in the Svandis ecosystem (e.g., prices, volume, news, etc.); those with a slower internet connection and a device of lower processing power may grab historical data.

This DataMining App is bundled with our desktop application for MacOS, Windows, and Linux and will be available on other platforms as the project evolves. This project is discussed in further details in [Data Mining Architecture](#data-mining-architecture)


![DataMining](/images/image6.png?raw=true "Datamining")

![DataMining](/images/image7.png?raw=true "Datamining")

See in depth functional description [Data Mining Architecture](#data-mining-architecture)

## Svandis Marketplace

The Svandis Marketplace is a connection between Svandis, community, and partners who wish to offer their expertise via our platform.

In a digital ecosystem, big data is a natural and renewable resource. The Research Community and the DataMining App will gather massive amounts of data. The same data can be used in a variety of ways. By offering data-as-a-service through the Svandis Marketplace, our target is now to define an effective way to improve the services offered to professional traders through the development of partnerships that will create new and improved products with the collected data. These include data creators and aggregators, as well as crypto traders and investors. 

Based upon this data, companies and third parties can offer indicators, analyses, misinformation detection, etc. to their clients, or simply use it for their own utility. With the help of Big Data, the Svandis Marketplace will become a research and utility hub for crypto traders and investors.

B2B (business-to-business) B2C (business-to-customer) and C2C (customer-to-customer) services and products will be available. Among B2B solutions, Svandis will sell raw data to third parties to make it possible to create services available as add-ons or interoperable plugins for platform users. For companies that need data which are difficult to collect through automated processes, on-demand Svandis grids will be available, adapted to different sectors of activity, allowing them to distribute research and validation tasks that will be completed by the Research Community. 

Similarly, companies wishing to offer their users a newsfeed adapted to the content and challenges of their sectors will be able to use Svandis' services. As for the DataMining App, its power and flexibility will facilitate data collection and website crawling according to business needs. Other types of needs will require more formal partnerships, such as the availability of Svandis catalysts for sites such as exchanges offering charts or access to partner data feeds including outside reviews not endorsed by Svandis or its Research Community.

B2C framework represents the case where Svandis partners or institutional clients (quant firms, analytical companies, research centres, exchanges and many others) would like to have a possibility to distribute their products and services to Svandis audience. Examples of such products are indicators, raw data, sentiments, research etc.

The advantages of a B2C framework are institutional clients will benefit from having a new way to distribute their products to a new, broad and diverse audience of crypto-market traders and analysts; Svandis community and users will benefit from having more useful tools on their shelves; Svandis ecosystem itself will benefit from having a reward from distribution, or by having more data in one place.

B2C distribution is possible only after a confirmation by Svandis and works on one of three basis:
Free distribution - a client is a well-known institution with a high quality product - Svandis ecosystem will mostly benefit from having such a partner and branding promotion;
Paid distribution - Svandis ecosystem will receive a one-time reward in SVN tokens from a client for giving him an opportunity to present his product to the broad audience;
Revenue sharing - Svandis ecosystem will receive a reward in SVN tokens based on a percentage from sales of client’s paid product to Svandis audience.

C2C products, mainly free-of-charge, will help to increase the reach of Svandis' tools. Users will be able to offer their views on the market by sharing their watchlist, custom groups, alerts, newsfeed’s filters, their own custom layout, catalysts or overview of their portfolio to share their strategies. This will widen the offering of services such as subscriptions to "top picks" by expert traders, premium analytics from users who decide to show their trading history, performance and portfolio in exchange for SVN token rewards, subscriptions to third party watchlists, alerts and catalyst feeds, visual customizations, etc.

Costs within the marketplace will be resolved using SVN token as the main currency. Users will be able to utilize tokens they got awarded  in the platform directly in the marketplace. Users will also have the choice of gaining discounts on premium services by holding a large amount of SVN tokens. This mechanism allows users to benefit from holding the token instead of trading it.


## Svandis Indices

To better serve traders, Svandis will be implementing indices in the platform. These indices will be compiled by the Svandis team and will be available to users in the front end application. The indices will integrate with user portfolios and custom interface.

The Svandis indices will be developed by the Internal Research and Analysis Team. For example, a major Svandis index will be an index of 30 well-performing crypto-assets. The goal is to establish a leading performance indicator of the largest cryptocurrencies and tokens in terms of market capitalization. Other Svandis indices may include an index showing a 30-day market volatility for instance.

With Svandis, users will be able to formulate their own indices. This tool will allow the cryptocurrency market to be divided into user-defined subgroups for the tracking of price and volume changes. The Customised Index Builder will include varying parameters to help users search for and better organize cryptocurrencies. As we will offer users the ability to create indices, the top indices with X+ different cryptocurrencies may receive token rewards. This promotes users to publish their indices to benefit other Svandis users.

## API Core

The fabric of the Svandis solution is woven by the API architecture. The Svandis v1 API is based on PHP and uses [Symfony](https://symfony.com) as a framework. Symfony was chosen for its high-quality offering in web applications. This service serves up information to a user’s front-end application. It is used in the collection of data from data-mining users. The API works to also supply endpoints for ICO and token screeners, in addition to blockchain-signed message hashes that will go along with "signed data." The login mechanism to the API is with JSON Web Token (JWT), which allows for a given user to interact with the solution. 

The API is furthermore connected to the mining architecture, for supplying the sources in the Svandis news feed. The information at the core of the Svandis solution is stored on PostgreSQL and Cassandra databases, which work via the API. Svandis uses [Swagger](https://swagger.io) service for documentation of the API methods.   For testing purposes, Svandis has chosen [PHPUnit](https://phpunit.de) to add a rich set of unit tests to the API feature.

For Blockchain related functionalities, we will supply a Svandis Ecosystem Smart Contract explorer through the API. This will be a method of returning the data hashes for signed data stored on the database. It will allow for users to query for recent signatures of the decentralized Research Community who met consensus on an updated token. The smart contracts explorer will allow users to pinpoint the address of currently deployed Svandis smart contracts and the transaction hashes for the function calls that happen on these contracts, for the purpose of keeping the platform transparent. Svandis smart contracts are written in Solidity programming language. Svandis smart contracts have been thoroughly tested in the [Truffle test framework](https://truffleframework.com/docs/truffle/testing/testing-your-contracts).

Throughout the backend for example with the worker-api project, there is use of [NestJS](https://nestjs.com). This framework provides a low weight server API implementation for constructing REST services rapidly. This backend service is also used in conjunction with Svandis publishing information onto the blockchain with a typescript code base to facilitate calls to Web3.js. The framework chosen to test NestJs specifically is [JestJs](https://jestjs.io/) . 

# Data Mining Architecture
## Data Mining Workers

Bundled with the front-end Desktop Application for Linux, Windows, and MacOS, we have included our worker module. Within the application, users can find a data mining sub-application, where, after acknowledging terms and conditions, they will proceed to mine web-feed information on their machine. Svandis web feeds are curated lists of trustworthy news sources, carefully selected based on CSS Selectors on the websites from which they originate. Not all news information will be blockchain or cryptocurrency related, so our carefully selected tags and machine-learning generated tags will extract URLs only of relevant articles. In return for lending the processing power on their machine, users mining for web feeds will receive SVN rewards.

The front-end Svandis application is bundled so that it can be offered across various platforms. The front end is based on Angular and Typescript. Front end testing is based on [Karma Jasmine unit tests](https://jasmine.github.io) & [Protractor e2e](https://www.protractortest.org/) frameworks to assure a fluid user experience.

The desktop worker crawls for links, and afterward sends to the worker-api server project built on NestJS technology. Our active server socket validates them and, if the link has not been crawled, will indicate as such to the worker. It is then the task of the worker to forward the data to the backend content-extractor written in Python. This backend content-extractor will integrate natural language processing and pattern recognition to improve the quality of the tags being used by the platform to curate feeds.

Currently, the CSS selectors associated with new content on web feeds are being programmed by the internal Svandis team. We hope that in the future this can be a task for the Research Community, so that they may receive SVN token rewards for accomplishing this task in many more languages. Consensus-based mechanisms can be put in place to confirm or reject a new web feed that a community developer might propose. The web feeds eventually will be moved over to the blockchain to work similar to screeners.

## Machine Learning and Sentiment Analysis
In order to facilitate a positive feedback loop between the internal analytics team and the Research Community, we will be using machine learning to pinpoint catalysts and other events within the ecosystem. Such identified events will be harvested from big data and prioritized for internal members to execute actions in the research platform and create catalysts. Natural language processing and pattern recognition will be used during the consensus mechanism to correlate similar information being presented by Research Community members, more information on the community consensus will follow.

Machine learning is a part of data mining as we need to ensure that the tags that we are associating with respective web feeds are accurate. In addition, as we curate high-quality content from our tags, our worker will become smarter as a result of machine learning. We will be able to automate the collection of tags or terms that produce similar content results based on our current tags.

The users of the Svandis ecosystem will be able to tag sentiment on the web feed and in other deeper insights. We will be using [Stanford's Core NLP package](https://stanfordnlp.github.io/CoreNLP/) as a machine learning engine for sentiment-analysis. Using this combination of human and automated sentiment analysis, we will be able to pinpoint with greater accuracy the bullish and bearish trends in a given market. Also, using fuzzy logic and mathematical methods, we will be able to extrapolate trends in sentiment changes in order to attribute to the performance of the market. Svandis provides this alongside heatmaps, catalysts and portfolios to ensure we provide expert traders and newcomers alike with the most comprehensive cryptocurrency information in one place. 

Information that characterizes as quantitative and qualitative will be subjected to different machine learning algorithms, within the Ecosystem. In the case of qualitative info it is important to pinpoint the topic, the sentiment and the significance to correlate this with Svandis catalysts. This functionality will work on our backend servers, with internal code based in Typescript, Angular, PHP and Python to create the appropriate solution.

## Svandis Database

Svandis leverages a PostgreSQL database for the newsfeed and screener information. The database layer lies behind our backend API service. The [PostgreSQL](https://www.postgresql.org) solution is used for creating object-relational databases and storing most of the structured data for the solution, including the screeners. The decentralized Research Community will be able to validate the state of this data with off-chain signatures as discussed in the blockchain architecture. This approach will allow us to validate the state of our database externally in a public and simplified format on the Ethereum blockchain.

There is a Cassandra database used for historical data crawling information. Svandis is choosing to use a Cassandra database as it supplies a robust NoSQL solution that will be able to scale quickly and can support a high volume of requests from the data mining community. Cassandra's tech stack is decentralized so that there is no single point of failure. There will also be data hash-proofs of the state of structured data in the database for token screeners completed by the decentralized Research Community. The databases will support blockchain functionality acting as a secondary source of history for signed structured data messages, token transfers, new user creation, etc. Using a combination of database types the development team can be more agile as to choose the right database method for the situation, where PostgreSQL is used for storage of structured information whereas Cassandra is used for cases where a large volume of incoming data is involved.

# Research Community Structure

Svandis will focus on a mixed B2C and B2B business model, as our target audience includes retail cryptocurrency traders, crypto-asset investors, exchanges, crypto-hedge funds, analytics companies, and traditional retail traders planning to enter the cryptocurrency market. Our Research Community will comprise passionate cryptocurrency users dedicated to curating accurate blockchain content in return for ecosystem token rewards.

The internal Svandis Analytics Team will provide the expertise necessary to conduct analysis and approve the content that is offered to users of the service. Like users in the Research Community, the Analytics Team will submit and verify data on cryptocurrencies and tokens.

This internal team will be responsible for validating the input from the Svandis Community for more complex data sets. Their work will cover ICOs and token sales, active tokens, project updates, classification of the most important news to ensure that breaking news is promptly identified as catalysts, and more. The growing team consists of senior analysts, researchers, editors, and developers working with data-grabbing technologies.

From launch, the Svandis ecosystem will include a comprehensive database of common crypto-assets (tokens, coins, cryptocurrencies and ICOs), which aims to rival existing crypto-information sources. Users within the Svandis community will be invited into the Beta Community Research prior to a public launch.

In order to sustain the highest quality of data on all current projects, Svandis internal analytics will only be able to support the curation and building of the community. To manage such a vast amount of new and changing information we will be highly dependent on a Research Community made up of decentralized actors, incentivized with token rewards. The Research Community will be divided into levels and "Svandis Power" signifying essentially a weighted vote. The concept of voting power in the solution will be explained later on herein. This proves to ensure that the most reputable and trustworthy actors have the most weight in the system.

The cooperation of the Internal Svandis team with the Svandis Research Community is a pillar of the project, and as the project scales and grows, the philosophy is for the Research Community to require less dependence on the Svandis Internal Team. The final result is a curated registry of cryptocurrency information that the Research Community can be proud to claim as their creation.

We believe that bringing gamification concepts into the Svandis Research Community is a powerful approach to building a motivated and dedicated group of individuals striving towards common goals. By conducting efficient research on cryptocurrency and blockchain projects, users will evolve on a gamified platform that includes levels, milestones and achievements. The most proficient and productive users will have more power and privileges throughout Svandis Platform, with titles and an on-chain reputation. Furthermore, that on-chain reputation is coupled with a decentralized identity only the user can control.

Having healthy competition among the Research Community enable us to get the most out of each participant, and will be easily trackable through real-time leaderboards to identify valuable researchers.  A key ingredient of any game is the reward.  This is where our SVN token economy can provide a significant incentive to engage our audience. An essential goal of the Research Community gamification is for each participant to help fellow researchers make effective decisions regarding their own investments in the cryptocurrency industry.

The following section contains the distinct roles within the Research Community and how they work together to create a valuable ecosystem.

## Roles in the Research Community

The Research Community is made up of actors who will have an identity created for them on the blockchain to which they hold the key access. As users submit reputable actions on the platform, their level reflected on the blockchain will increase over time and give them more "power" in the Svandis process and consensus. The system is designed to ensure top contributing users can move up the ranks and learn more about cryptocurrency, while spam or manipulative  accounts will have a difficult time making an impact on the truthful nature of the solution.

The current plan for the Research Community involves various levels, achieved through research actions, as well as submission of KYC and Social Media authentication. The model for this is shown below; note this presentation is a living document and is **subject to change** as we balance the business requirements for the Svandis organization and the role of consensus in the Research Community.

| Level | Granted Privilege | "Svandis Power" |
| ------ | :------------------------: | -----------:|
| 1   | Submit grade 1 data. Submit new projects | 1 |
| 2   | Submit grade 2 data. | 1 |
| 3   | Submit grade 3 data. | 1 |
| 4   | Submit grade 4 data. | 1 |
| 5   | Submit grade 5 data. Request Modifications to existing screeners. | 1 |
| 6   | Validate grade 1 data. | 1 |
| 7   | Validate grade 2 data. | 1 |
| 8   | Validate grade 3 data. | 1 |
| 9   | Validate grade 4 data. | 1 |
| 10  | Validate grade 5 data. | 1 |
| 11  | Tag X sentiments per day. Rating on news articles. | 2 |
| 12  | Validate new project submission. | 2.2 |
| 13  |  | 2.5 |
| 14  |  | 2.8 |
| 15  | Premium Marketplace Unlocks | 3 |
| 16  |  | 3.2 |
| 17  |  | 3.5 |
| 18  |  | 3.8 
| 19  |  | 4 |
| 20+| Help eliminate problematic news in web feed. Tag up X web-feed sentiments per day. | 5 |

### Newcomers
**Requirements:** Registered Svandis user (mandatory)

**Rights:** A newcomer logging into the Research Community interface will receive simple and easy data validation requests (grade 1 type) for research. Those requests will be the same ones that are presently open for validation within the community. However, the newcomer’s results will not be recorded for the official consensus. The idea behind this is that data validated by newcomers should not count towards the consensus of data integrity. Their results are compared with the data of researcher’s data for personal statistics and, after a series of successful submissions, the user will prove himself as a trusted novice participant. This allows a sense of security and trust in the data; the platform can help prevent spam from malicious new users, egregiously wrong data, or erroneous information. The system will automatically filter out the bad actors.

The main goal for a newcomer is to submit enough accurate data to become a researcher, which at that point they unlock the possibility of receiving SVN rewards for the work accomplished. If a newcomer submits a complete KYC, he will receive a significant rating upgrade.


### Researchers
**Requirements:** Light internal KYC, Level 5 in Research Community

**Rights:** Researchers can start submitting data available in the grids. Once they reach rating level 5, they can submit any kind of data. Data validation requests start at level 6 and increases until level 10. Researchers can also suggest new project submissions and flag incorrect or false data in the ICO screener. Researchers get SVN token rewards for their successful work.

There will be a rating level from 1 to 20 where each level will unlock new actions or new fields to validate. Each data field will have a ‘’grade’’ linked to it for validation request purposes. Evolving profile as a researcher will unlock higher data grades and allow the validation of a wider area of data submission requests. The rating required for certified researcher rank (level 10) will be fairly easy to reach and let researchers submit and validate all the information about projects. The following ranks will be, on the other hand, significantly harder.


### Certified Researchers
**Requirements:** Ranking needed for a researcher to be able to submit and validate any type of data, Level 10 in Research Community.

**Rights:** Certified researchers can submit, validate or modify any data field, but still need to be validated by Research Community. At this point, reaching higher levels allows users to obtain higher Svandis Power within the platform and unlocks actions available on the Svandis Newsfeed. They will now be able to tag “sentiments” in the news articles in order to rate bullish - bearish.


### Certified Analysts
**Requirements:** Extensive experience within Svandis Platform, Level 20+ in Research Community

**Rights:** Certified analysts can analyse all the processes of the data workflow on Svandis Platform, enabling them to identify anomalies that might be occurring in the system. They are also in charge of submitting and validating data that requires rigorous methods of investigation. At this level, they have the ability to officially push project data into the ICO screener. Furthermore, they get a basic training on how the Research Community works so that they can contribute their ideas into the greater community. Certified Analysts can propose tweaks and ideas to the Svandis Internal Team through suggestion box. They may act as trainers for researchers as these individuals have shown their value and capacity to deliver in a fast and accurate manner.


### Mediators
**Requirements:** Complete KYC and video interview, Certified Analysts 

**Rights:** Mediators act as referees when a project team submits conflicting data into the grid or when data cannot reach consensus on whether it is considered good or wrong. They communicate with projects to let them know about their grid submission on Svandis Platform. They are the bridge between projects and the Strategic Development office.  Analysing internal statistics and suggesting platform improvement are tasks that will be done at this top ranking level on the Svandis Platform. Mediators are dedicated community members who will have ongoing responsibility in the platform as it evolves.


## Rating and Svandis Power
### Rating
Each researcher’s level (from 1 to 20) is directly calculated by a range of variables based off a user’s productivity and effectiveness. The process behind this will be transparent and published after the beta application version is complete. Before reaching the Certified Researcher level, a user in the Research Community must increase their rating with:

1. Accuracy of data submission, validation and modification
2. Ability to perform and reach consensus with other users in a time box
3. Streaks of successful actions
4. Activity frequency on the platform
5. Difficulty of the data submitted
6. Correctly Identify spam and malicious content in ecosystem

On the other hand, participants who fail to achieve consensus by submitting erroneous data for validation will be losing rating points. There will be a mechanism where users working on data validation can set an "online" status when they are ready to validate. As such, there will exist penalties for users who set an "online" status and do not respond to data validation requests or who regularly dismiss them. This functionality is similar to multiplayer online games where users negatively affect their reputation when they accept to be part of a game lobby and afterwards are inactive or leave mid game.

### Svandis Power
The Svandis Power is the weight of the participant throughout the Svandis Platform as a user of the Research Community. Users will strive to increase their level in order to raise their power commitment in the community hierarchy. The Svandis Power will influence the participants actions in the following features:

1. Data validation consensus (Research Community)
2. News articles rating (Newsfeed)
3. Sentiment: Bearish / Bullish / Important (Newsfeed)

The more time a user spends as a reputable actor on the platform, the more influence (higher level over time) they will achieve along with SVN token rewards. This is both to curate an excellent community of researchers as well as to gamify the users experience with the Svandis ecosystem. In the case of consensus for example, more senior users will have more weight in off-chain consensus.

### Newsfeed Rating

The Svandis Power is also relevant in the Newsfeed Rating system. As users reach level 11, they unlock the privilege of rating any articles they read (1 being mediocre and 5 excellent). This is only a mechanism to rank quality of trustworthy articles, and is not related to sentiment or problematic articles. Article rating is a way for us to provide a separate filter of significant and high quality information as curated by the community. Here is how article weighted rating will operate:


![Newsfeed](/images/image8.png?raw=true "Newsfeed")


For each User, (Svandis Power * Rating) = Total User Rating Applied to Article

Sum User Ratings / Total amount of Svandis Power = Article Rating

In this example, Article Rating would be:

{(2 * 3) + (2.5 * 2) + (3.5 * 5) + (5 * 3)}/{2 + 2.5 + 3.5 + 5}  =  3.346 Article Rating


# Blockchain Architecture
## ERC 725/735 Decentralized Identities

The methodology behind identity on the blockchain is an especially interesting topic in the Ethereum community today. There are various Ethereum Improvement Proposals that have been put forward, and groups (such as UPort, Status.im, Civic, Tenzorum, and the Ethereum organization) are seeking to provide their own innovative solutions. However what they share is decentralization of identities, key management, "claims" made by trusted parties, controlled by a smart contract. The exact manner in which these solutions are formulated differ based on the exact business specifications of the organization.

Svandis is presenting a **decentralized first** and **low gas cost** solution for the Research Community. After research into the subject and carefully weighing the benefits of other open source solution, we decided to take a similar approach to identity such as the [Origin.js project](https://github.com/OriginProtocol/origin-js). This solution is compliant with [EIP725](https://github.com/ethereum/EIPs/issues/725) and [EIP735](https://github.com/ethereum/EIPs/issues/735) .

In order to have a seamless solution, initially Svandis will deploy the identity of users on the blockchain for them. Users will have the choice of selecting a status of ‘’beginner’’ or ‘’expert’’ user, which determines whether or not they would like Svandis to hold a key to their identity contract. Both beginner and expert users will generate, without the need for Metamask, a local file in browser containing their web wallet that can only be opened with a password. Beginner users will allow Svandis to add the Svandis organization as the recovery key for this on-chain contract (which contains their decentralized "reputation" on-chain). Expert users will have their own recovery mechanism, and will acknowledge that if they lose access to all their keys they will not be able to recover their on-chain "reputation" connected to this smart contract. Users will be prompted to learn more about blockchain and eventually use Metamask or a hardware wallet to store their recovery key as beginners become experts. As the Research Community moves towards being completely on the blockchain, the recovery mechanism key for beginners may be potentially transferred to the custodianship of a decentralized autonomous organization. The goal is to inform beginners during their participation on the platform so that they can learn to take control of their own blockchain keys for purposes of utility and store of value.

For KYC and social media connected accounts, we will also add trusted "claims" on the blockchain. This will be for users that authenticate a social media provider with Svandis. It will also cover users who wish to confirm their real identity on-chain in exchange for token rewards for reducing spamming accounts onto the platform. Users may receive claims from any trusted third party source which will confirm presumptions about a given blockchain account. 

As expert users will be able to take full control of their on-chain identity, they will have the ability to confirm that they are the only users in control of their identity. This is a secondary authentication alongside their standard JWT Auth login which will enable these users to validate that they are truthfully attesting information to the Research Community, and it is not the action of the Svandis organization speaking on these specific expert user's behalf. Svandis is decentralized first. The Svandis organization will not contribute to bias expressions on the platform nor knowingly post non factual information onto the blockchain.

[See our Identity Contracts on Github](https://github.com/svandisproject/svandis-backend/tree/master/contracts/identity)

## Screeners Workflow for the Research Community

### Data Submission Phase

The Svandis Svandis Internal Team or a certified analyst push a selection of "Initial Coin Offering" projects from a screener suggestion form that can be provided by all ranks above Newcomer. Apart from a required rating, separate mechanisms to counter spam or nonexistent projects will be developed. This ICO suggestion form will need to be filled with factual information about the project, including but not limited to the name, website and type of blockchain the project is or will be built upon.

Anyone (except newcomers) can suggest new project grids to be researched. The suggestion is validated by certified researchers who have reached level 12. When reviewers have confirmed the existence of the new project, it goes into an analyst dashboard. The analyst perform final verifications and can push the grid.

The Research Community receives a notification about new projects available for submission and data validation. Users in the Research Community can mark themselves online in order to receive notifications.

Each data field has a unique SVN token reward attached to it, which will be triggered later on by successful consensus by users. The original data may be submitted by X different participants meeting consensus as well, dependent on the complexity of the data field. The design of the rewards scheme is being designed and will be transparent to the community when it is in place.

As soon as a data field is filled and submitted, it is sent to the backend for processing. Within the grid, there will be a visual effect on the data field that it is currently ‘’validating’’. During this period a consensus will be reached with other online users, which is partially dependent on the "Svandis power" of the actors in consensus.

While a field has the status "validating", the researchers will still be able to submit data. If they end up agreeing on the right answer, they may get a reward depending on the accuracy and speed of their submission (eg. only first X participants to submit correct data will receive reward).

Data being submitted may have consensus reached and move directly to the publishing phase along with a signed blockchain attestation. However, more complex information may need to be validated in a new consensus by more advanced online users. Most spam and malicious information will not pass the Data Submission Phase.

### Data Validation Phase

Once a user reaches level 6, he will be able to set his profile to "Active Validator," which will enable him to start receiving validation requests. Validation requests will be needed for more complex data, as a second step after data has been submitted and has possibly undergone consensus by other users. Being efficient with this tool will be crucial for increasing researcher rating. Many aspects of the Research Community are focused on activeness and accuracy of a user’s validation responses. Data validation serves as an extra method to ensure the highest quality of information is included on the platform.

The data submission is sent to a fixed amount of X anonymous online users with the appropriate rating level to operate on these fields. There will be a mechanism where data submission is sent to Svandis Internal Team analysts if not enough users are online for approving new data that’s been published. Critical mass for the project will improve the factor of random selection in this case, random selection of a large user base is needed to ensure that researchers are not working together to approve biased or false information. Again, the data to be validated will likely have already gone through the data submission phase.

When data gets submitted, for example, ‘’ICO project X’’ hard cap, and reviewers do not see the answer, they are alerted that someone submitted a value and they have been randomly selected to find the correct answer as a reviewer. So instead of just seeing the answer and clicking on a button, they have to find the answer and submit it as well. Depending on the complexity of the value, the system will automatically compile the results and compare with the researcher’s submission. This system will be more complex from a processing and UX perspective for qualitative data that cannot be compared (non-numerical and non-standardized string format, free-flowing wording).

There is an option for a reviewer to dismiss a request, removing the user from the processing. The request will then be sent to another user with a similar Svandis Power.

If X% consensus on reviewers data cannot be reached, it is disapproved. If X% consensus is reached but is not the same data as the researcher’s submission, it is sent to analysts. There might be cases where not enough participants responds to a validation request. For this matter, a time box should be used and the request will be sent to another user when it expires. Consensus needs to be made by anonymous users that are random from each other so that online users do not conspire to create a bias answer. The necessity of random number generation to select from anonymous online users is crucial in this case.  The whole concept of decentralized actors comes into play when the on chain state of the data is subject to be changed. All data that reaches consensus will come along with the signature of the Research Community member who researched it, so that the community knows that Svandis acted transparently and that Svandis themselves did not come to the decision. 

A user who dismisses too many requests might receive less data requests and will take longer to reach higher levels, while faster and accurate reviewers will be sent significantly more data requests to be validated (algorithm parameters). This setup will quicken the process of data validation consensus.


Please read more about [Consensus and Off Chain settlement](#consensus-and-off-chain-settlement) to learn about Svandis' solution for randomness and low weight resolution on consensus off-chain.

### Data Signing and Screeners on the Blockchain

The solution Svandis serves is lightweight and low cost. For this reason we don't intend on add all information directly onto the blockchain. As mentioned Svandis will be using a PostgreSQL database solution for storing screener information, alongside the current on chain state. The conceptual information on this database will be represented by specific structured data snippets from which we can extract a "data hash" and post the current state to the blockchain. This data hash is Keccak256 computed from the final structured data reflected in the database. The format for the structured data will be open source on GitHub with all fields and field format types included.

As users contribute to ICO or Token screeners, they will be coming to agreement with other users in the Svandis consensus mechanism. Each time a user fills out a set of new or updated fields to add to the information set for a screener they will generate a "signature" of that decision in their browser. This means that only by unlocking your in-browser Ethereum authentication can you submit "signed" data to be considered in consensus and eventually published to the blockchain dependent on off-chain results. As aforementioned this means that Svandis can confirm afterward the exact on-chain identity of the users who submitted consensus, and expert users will be able to attest that Svandis had no influence on their signed information. This signature will be published alongside the screener's data fields that were modified.

[See our Contracts Backend for publishing signed data on Github](https://github.com/svandisproject/svandis-backend/tree/master/contracts/svandisdata)


### Consensus and Off-Chain Settlement

Creating a random consensus for new validating Svandis data and executing this logic is not cost effective to compute on the Ethereum blockchain today, completely on chain. We use a combination of random selection off chain with decentralized identity on chain to create a consensus and settlement mechanism to meet the needs of the cryptocurrency space. We hope to improve the technology we build to shift more responsibility to the community later on. 

To make a decision on behalf of [beginner and expert accounts](#blockchain-architecture) working together, consensus must be achieved in a hybrid on and off chain solution.  The power and rating effect on consensus and quantity of token rewards is subject to changes in the Research Community development. This meaning as the platform is tested in a Beta phase, we will adjust the effect of users level on overall consensus as we continue development. The net effect of users Svandis power (otherwise weighted influence) will be transparent on Github. 

The mechanism of consensus will rely on Y users interacting in either the Data Submission or Validation phase. These users must be randomly selected by Svandis off-chain and this will be based **on a randomized selection using entropy from the last Ethereum block hash**.  To participate, technically the Y online users selected will first transmit a signed data hash with hidden data to Svandis. Once Y online users have submitted to the consensus, they will reveal another signed "secret" which can be used for trustless confirmation of what they researched for this data field. Through a combination of Machine learning, data analyst parameters, and UX features Svandis will make a decision on whether a consensus was reached between users on a server in a transparent fashion. Svandis provides the data signature of the users to prevent the situation where Svandis is suspected of perpetrating the consensus. Users will receive a unique Svandis signed digital passphrase each time they start consensus on a field as **Proof of Entropy**. This means in addition to signing this data which will be discussed further, decentralized users will be able to demonstrate they were part of consensus- so that Svandis can’t just pick bias consensus answers without including all the users that were chosen to make the consensus. Random number generation may come from a trusted third party server. Machine learning can correlate similar information being presented by Research Community members in situations where a distinct quantitative answer is not concluded.

Successful consensus reached by over X% of users based on the Svandis power attributed to the given users' ratings, means that there is a new hashed data state to characterize the structured data representing a screener. The metric of Svandis power allows for more experienced researchers to have a larger swing on X% consensus. Afterward, Svandis will publish to the blockchain (in low-frequency intervals and publicly providing a signed transaction, as mentioned herein) alongside publishing the exact signed message hash that the decentralized community members originally submitted. If consensus is not reached there will be no change on the blockchain, if there is an action later on by Svandis Internal analytics team this might trigger an action being recorded on-chain.

Every Token or ICO screener is represented on the blockchain as a piece of "Svandis data", and the original state of the associated data template is published when a new contract is deployed to the blockchain for a screener. Every time the information about that ICO or Token screener changes, that contract will be subject to having its current "state" changed to the most recent data hash for the associated screener.

**To deal with the cost** of publishing information to the blockchain, we will not be publishing at a common interval. We will publish the state of the current database X times per day publicly on the chain funded on low gas cost. In real time, we will publicly publish a feed on Svandis website where we will post signed transactions (that have not been submitted to the blockchain) with the current state of our information. This means that any user can submit this transaction on-chain (and trigger a gas cost) if they wanted to, meaning Svandis maintains accountability and transparency for the actions of the backend while saving cost when updating to the blockchain.

This process is necessary to provide a lightweight and transparent layer to our offering, and to integrate the blockchain functionally. Our development plan balances between user-friendliness, decentralization, and responsibility to the community to create mechanisms in the smart contracts to promote truthfulness in our offering.

Based on the state of consensus, there will be micro rewards associated with each field of a screener that a Research Community member successfully helps complete. These micro-rewards will be facilitated in a low-cost Micro Raiden solution, discussed further herein.

### Blockchain Data Publication Phase

For a certain duration of the platform alpha release, Certified Analysts will receive the result from Data Validators with a low % consensus. However, once the data is validated with X% consensus, it should be pushed into the system automatically. At this time there is a mechanism to publish the state of this information to the blockchain and assure transparency for decentralized actors. [Read more about structured data state on the blockchain](#Data-Signing-and-Screeners-on-the-Blockchain)

After analyzing the results, the analyst or the system will publish the final data set to the platform dependent on which data fields were discovered for the project. Researchers will receive rewards depending on the speed of their submission, whether they acted in the submission or validation phase for this data, and the complexity of the field combined with their level.

For simple quantitative data (might be available to the newcomers), consensus from the certified reviewers will likely result in the data being published directly on the platform without having to be analyzed by Certified Analysts.

As users continue to interact in the Svandis ecosystem, the platform will capture their achievements. A reputation module will be available to the Research Community with personal statistics: progression on a daily basis, amount of data entered, validated, etc.


### Data Modification Phase

Each project’s grid has a "flag" option available for any participant of the Research Community, for when a field is not up to date. This is to trigger data modification of projects, which frequently changes parameters such as token sale design, team members and working product milestones.

Once the researcher enters the updated data in the grid, it follows the same process as a new data validation dependent on the field complexity.

Some data fields may have to change constantly, for example: the current amount of token sold during an ICO. Those will be reserved for the analysts to update when needed.

Users will have the option to receive alerts when their favourite screener grids have been updated by a consensus-reaching body of users, so that they always have up to date information on projects, as well as updated catalysts.


### Token Project Participants

There will be a second category of users that include project participants (ex: CEO, founders). The majority of the platform users will be independent but there will be an option to register as a user from an existing project or company. Each of those participants will require an extensive KYC to prove the relationship between himself and the project. Once registered, the project participant will be able to submit their own project or contest data. Researchers are in charge of validating the data, while Mediators take care of data contestation. This type of user will be able to connect their profile directly to the team section of the project and get project-specific notifications. They will be able to as well contribute to the Research Community.

Participants directly connected to the Svandis Platform and verified can then add contact information for users to reach out with questions about the project or business opportunities.


## SVN Token Economics

**The SVN Token**

The SVN token is an ERC20-Compliant Token to be deployed on the blockchain. Our Crowdsale Contract (https://github.com/svandisproject/smart-contract) contains an example of our current token contract.

SVNs are fungible utility tokens, have a finite supply and have the following functions:

* Rewarding the members of the Research Community for data submission and validation;
* Rewarding participants who use the DataMining App;
* Establishing a token transfer model between Svandis clients (demand) and Research/DataMining users (supply);
* Providing access to the different service levels of the Svandis platform;
* Providing access to additional Svandis and third party products and services on the Svandis Marketplace.

**SVN in the Research Community**

SVN tokens provide a contingency management system. The reward for the participation of Research Community members fluctuates according to the time required to collect information and the number of members available to perform a task for a given period. This approach promotes maximum participation outside peak periods when fewer participants are available. In this way, the internal economy stimulates more constant productivity and data validation over a 24-hour period. The tools in the Svandis platform use the continuously produced data to ensure up-to-date information. 

To encourage active participation of members in the Research Community, token rewards are immediate. In this context, earning the SVN utility token is an economic reward that encourages the frequency and effectiveness of participation. Token SVNs are used in conjunction with a multi-level gamification system. Higher-level tasks may offer higher rewards; difficult-to-acquire data may be scaled several times higher for successful researchers. As a participant progresses through these levels, progressive access to new tasks will consequently unlock more opportunities for rewards in token SVN. On the other hand, low participation, inactivity, inaccuracy, and regularly erroneous work will cause participants to regress in gamification levels. 

**SVN in the DataMining App**

The DataMining app coupled with the added benefits of a specific SVN token allows Svandis to achieve economies of scale more rapidly in data scraping and processing, i.e., encouraging with SVN rewards a critical mass of participants to use the DataMining App more actively. The objective is to ensure as many automated data collection actions as possible. The rewards will depend on the duration of use of the DataMining App, the volume of data transmitted for a given period of time, and the task requirements for bandwidth usage or computing power required over time.

**SVN Token Volumetrics**

The Svandis platform offers information services that enhance market understanding. The collection and validation of this information is based on a mixed crowdsourcing strategy supported by an Internal Analytics Team. There is an internal token economy based on the value of the information for Svandis platform users versus the cost of the work required to collect and process it via the Research Community and the DataMining App. 

Utilizing the SVN, Svandis increases the likelihood of reaching economies of scale more rapidly. The more participants in the Research Community and the users of the DataMining App, the more powerful the data collection becomes. This virtuous loop improves the quality of Svandis' services while reducing production cost. The objective is greater long-term competitiveness regarding the platform's access costs for users. As the gamification dynamics improve and we become more efficient at curating new data, this will mean a better product for users at a lower cost. Gradually, Svandis will use and direct the mass of SVNs in circulation to develop new products, such as Svandis Grid on demand for third parties. These new products will generate new tasks for the Research Community, and therefore new reward opportunities. 


**SVN - Access Level**

Svandis offers several levels of access to its services and tools. Continuous holding of a fixed quantity of SVN will provide access to different plans with tiered discounts on services or enhanced toolsets for more advanced trading insights and data. The possibility of using SVNs to purchase different monthly access levels will also be offered. The packages available allow users to choose from a variety of options or pre-determined packages. Levels of access to our products will be published after the release of products.

While the possession of a large quantity of SVNs increases access to all the features and content of Svandis, this does not pose an issue in the operation of the platform, the Research Community or the Marketplace. The platform is based on a principle of microtransactions, and users may participate on the Research Community to gain more rewards to use elsewhere.  

SVN in the Svandis Marketplace
The use of the SVN as common unit for the Svandis Marketplace makes it possible to maintain a balance between the value of the information, the rewards for participants who help optimise its gathering, and the costs of the products or services offered by Svandis or third parties on the Marketplace. When the value of the users’ rewards in the Research Community or DataMining App fluctuates in proportion to participation, a dynamic balance of costs is possible.

Research Community participants will be able to use their SVNs according to their needs. For example, an experienced trader will be able to benefit from a higher level of access to the services and tools of the Svandis platform. Traders who want to develop their knowledge, can use their SVNs to buy peer-to-peer or third party content via the Svandis Marketplace, acquiring access to content curation tools, such as watchlists proposed by influencers or an add-on for the Svandis ICO screener designed by a partner company that offers a ranking system. The differing levels of the gamification system also provide access to certain Marketplace content, such as limited edition Svandis skins and visual customizations.

**Terms and Conditions**

By releasing SVN tokens, Svandis offers all crypto-market participants the opportunity to become part of a professional infrastructure that gathers data on cryptocurrency and token trading, as well as ICO and token sales. This infrastructure will include the following features: ICO and Token Sale Screener, Cryptocurrency and Token Screener, Newsfeed, Charts, Catalysts Analysis, Heatmaps and Groups, Watchlists and Alerts, Marketplace, Portfolio Management Tools, and Customised Index Builder.

SVN token holders can receive access to the aforementioned products, with the level of product and tool access depending on the quantity of tokens in each holder's possession. In addition, we will develop a simple model for buying access to the Svandis tools with SVN tokens.
Thus, the Svandis tools will be available only through the ownership of SVN tokens and, in order to gain access to the products, a SVN token holder earns access by:

Buying tokens at any time and having access to the products as a token-holder (in accordance with defined access levels, to be published in due course), or;
Purchasing access to one or more toolsets with SVN tokens.
The Svandis Community will receive rewards for expediting the process of data gathering (data miners) and submitting and verifying the information in the platform. This will ensure circulation of tokens in the Svandis ecosystem; tokens will be used as the key to access Svandis products and as the reward for bringing actual information to these products

**Expediency of Issuing SVN Tokens**

Issuing infrastructure tokens specific to Svandis will help limit the number of participants who have early access to the platform, which is currently a necessity due to the low liquidity of the cryptocurrency markets compared to traditional financial markets. Thus, a limited number of market participants (both individual traders and hedge funds) will be among the first to receive information, enabling them a greater time to react. The issuance of SVN tokens will help create a professional structure for a limited number of traders at first and then, with increasing liquidity in the cryptocurrency markets, for everyone.

**ERC721 Non-Fungible Tokens**

Non Fungible tokens (NFT) are unique collectible items on the blockchain. In addition to token rewards, we are exploring the possibility of offering NFT’s to users. This allows users to collect Svandis NFT’s on their digital blockchain identity, after reaching consensus with other users on the solution. These NFT’s are then collectible, as they are unique to the user and their research accomplishments. NFT’s being rewarded in this context is similar to “badges” users are familiar with collecting in video games. These NFT’s can be left on the users address or traded away to other addresses, and are initially created by the Svandis controlled private key. 

## ERC20 Micro Rewards on MicroRaiden

To deal with quick token transfers, we can use a custom off-chain settling solution. We are working with MicroRaiden/Raiden.network technology for SVN token rewards. At a high level, this works by opening up a payment channel between the Svandis rewards token account and the user working on the network. Micro rewards of SVN are given for each proper validation based on the parameters of the gamification. These micro-rewards are settled in real time by the actors on the off-chain solution. When users want to withdraw these rewards, basically they will close the channel using the most recent signed transaction between user and rewards token fountain. Using the Raiden network would be a great way to implement this payment channel, and must be further explored for viability.

We will implement MicroRaiden for rapid SVN token transfers, facilitating micro-rewards. The exact integration with smart contracts and backend solutions is under development and is subject to the current best practices for token transfers. State channels is another concept that Svandis is dedicated to research, as it is a necessary layer for creating a scalable solution that can solve transparency in this space as well as give users control of on chain identity.

## Ecosystem Evolution

The first phase of the Svandis Ecosystem is to curate the highest quality and most up-to-date cryptocurrency information available. The role of the Svandis Internal Team to act as a trusted organisation will be adequate as long as advancements, such as development and community building, become mature enough to allow us to move from a centralised solution toward decentralisation.

Bearing in mind the efficiency, transparency and diversity of the offer, the Svandis workforce will move from the Svandis Internal Team to the Research Community and the Svandis Marketplace to a large extent.  The target is to decentralise an ever-increasing part of the processes in order to give the best of what the blockchain space can offer.  The Svandis ecosystem is a data hub with the ultimate goal of redefining organisational, operational and ethical standards by converging the best of traditional markets and cryptos together, while avoiding the traps of the past. 

Svandis is dedicated to creating a decentralised solution that one day will be able to sustain growth and cultivation autonomously. Svandis Internal Team analysts will cease to contribute to the Research Community, and will at that time focus efforts on deeper insights demonstrated through research articles, marketplace offerings, and new development features.

# Conclusion

The Svandis team is proud to propose this technical solution for the creation of a Decentralized Research Community and platform which will enrich the cryptocurrency trading experience for beginners and seasoned crypto veterans alike.  In order to have reliable and wide accumulation of information for the decentralized ecosystem, it is essential that we build the tools which will facilitate crowd participation in the due diligence processes.

This document acts as a living technical whitepaper for the time being, and we are open to the community proposing pull requests to improve the content or even proposing new ideas or alternative opinions on the development of the Research Community.

Feedback and issues are welcome from the community. The goal of our solution is to be promote decentralization and offer a lightweight solution to increase the transparency of our offering.

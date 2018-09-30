![Svandis](/images/image1.png?raw=true "Svandis")
# Svandis.io Technical Whitepaper

**September 26, 2018**

**Abstract:** 
Svandis is developing a platform for crypto market participants, providing leading financial research, analytical and visualisation tools for anyone actively involved in the cryptocurrency space: short- and long-term traders, analysts, hedge funds, institutional investors, proprietary trading firms, venture capital funds, token sales contributors, and exchanges. 

The Svandis ecosystem is a collection of powerful tools, analytics, and indicators for professional traders in need of real-time, actionable data and analyses. Beginners will find it easy, professional traders will find it comprehensive. The Svandis ecosystem aggregates data from a wide range of sources into one place, transforming raw data into reliable and valuable information, and covering professional crypto market participants with up-to-the-minute news and updates filtered by the Svandis research community and analysts through a web-based application. 

Svandis provides users with a greater understanding of market conditions and trends, as well as a comprehensive platform for the evaluation of fundamentals behind cryptocurrency initiatives, e.g., initial coin offerings (ICOs) and token sales. Svandis aggregates data from a variety of sources; transforming data into reliable and actionable information for professional traders and beginners alike. 

The Svandis platform provides leading financial research, analytical and visualisation tools for anyone actively involved in the space: short-term and swing traders, traditional holders, analysts, hedge funds, institutional investors, proprietary trading firms, venture capital funds, token sale contributors, and exchanges.

Every feature proposed is part of a strategic vision to enhance the user’s overview of the cryptocurrency market. Svandis tools generate a customisable way to cross-check a wide range of data and gain a perspective for different values. 

<details><summary>Expand Svandis Features: </summary><br>


1. ICO and token-sale screener
2. Cryptocurrency and token screener
3. Newsfeed
4. Charts
5. Catalysts analysis
6. Heatmaps and Groups
7. Watchlists and Alerts
9. Portfolio
9. Svandis DataMining App
10. Certified reviewer
11. Data analysis
12. Marketplace
13. Svandis indices
14. Indices builder
15. Customised user interface
</details><br>

The Svandis Research Community will be involved in producing crowdsourced information of value through the DataMining app, receiving Svandis tokens (SVN) for their participation. In addition, the Svandis Team will certify reviewers and external analysts to complete data verification regarding ICO and token sale projects and teams.

Svandis is a team of market traders, crypto enthusiasts, investors, engineers, and statisticians.  In crypto trading, timing is everything. Svandis aims to incorporate best practice from financial platforms to address the needs of everyone who is involved in the new era of cryptocurrency trading.


**DISCLAIMER:** 
This Technical Whitepaper does not constitute an offer to sell or invitation to purchase any securities of any nature whatsoever, and the content of this presentation is not intended to constitute legal, commercial or tax advice. Some of the declarations contained in this WP constitute forward-looking statements and are subject to change.
 
The Svandis Whitepaper is intended for preparation, description and information purposes only, and does not constitute an offer or solicitation to buy or sell any securities or invest in any of all types of financial instruments. This document is not compiled in compliance with, and is not subject to, the laws and regulations of any jurisdiction created to protect the investors. Nothing published by Svandis or one any of its subsidiaries should be taken as investment advice. Please consult an appropriate licensed professional before engaging in any financial transaction, including any investment related to the ideas or opinions expressed, in the past, present or future, by Svandis or any future entity working for the parent entity. The information document below should not be seen as exhaustive and does not imply any element of a contractual relationship. Its sole aim is to submit relevant and reasonable information to potential token holders so that they can determine whether they should undertake an in-depth analysis of the company before intending to acquire tokens.
 
The Svandis token, or SVN, is a cryptographic token used to access the Svandis platform. In no circumstances should the SVN tokens be confused with security tokens. All SVN tokens purchases are non-refundable. SVN token ownership does not represent any future governance of the platform or Svandis. By purchasing the SVN token, you will be deemed to have carefully reviewed the purchase terms. In addition, you represent and warrant that you are of sufficient legal age to be bound by these terms and that you may not under any circumstances hold the company, its representatives, founders, affiliates or advisors, either now or in the future, liable for any loss or damage arising from the purchase or sale of the SVN token. The purchaser is solely and entirely responsible for all risks associated with the purchase of the SVN token, and warrants that this purchase is made to support the project development activities and not to make a speculative investment. Svandis recognises that the purchaser will have to meet KYC (Know Your Customer) and AML (Anti-Money Laundering) requirements when buying the SVN token. Svandis expressly disclaims any liability or responsibility for any direct or indirect loss or damage of any nature whatsoever, relating directly or indirectly to: (1) the reliance on any information content presented in this document, (2) any error, omission or inaccuracy relative to the information herein or (3) any action deriving from the information herein.

This Technical Whitepaper, any portion or copy thereof shall not be brought, transmitted or distributed in any countries where the distribution or diffusion of the token sale or the initial coins offer described within the Technical Whitepaper is prohibited or restricted. You are not eligible and you cannot buy any Svandis token if you are a citizen, resident or green card holder of the United States of America, or a resident of the People’s Republic of China, or Singapore.

# Table of Contents
<!-- MarkdownTOC depth=4 autolink=true bracket=round list_bullets="-*+" -->

- [Introduction](#introduction)
- [Feature Overview](#feature-overview)
  * [ICO & Token Sale Screener](#ico-and-token-sale-screener)
  * [Cryptocurrency & Token Screener](#cryptocurrency-and-token-screener)
  * [News Feed](#news-feed)
  * [Charts](#charts)
  * [Catalysts Analysis](#catalysts-analysis)
  * [Heatmaps & Groups](#heatmaps-and-groups)
  * [Watchlist & Alerts](#watchlist-and-alerts)
  * [Portfolio](#portfolio)
  * [Customized Interface](#customisable-user-interface)
  * [Svandis DataMining App](#svandis-datamining-app)
  * [Marketplace](#marketplace)
  * [Svandis Indices](#svandis-indices)
- [Data Mining Architecture](#data-mining-architecture)
  * [Data Mining Workers](#data-mining-workers)
  * [Machine Learning & Sentiment Analysis](#machine-learning-and-sentiment-analysis)
  * [Svandis Database](#svandis-database)
- [Research Community Blockchain Architecture](#research-community-blockchain-architecture)
  * [ERC 725/735 Identity](#erc-725-and-735-identity)
  * [Decentralization of Research Community](#decentralization-of-research-community)
  * [Data Signing & Screeners](#data-signing-and-screeners)
  * [Consensus & Off Chain Settlement](#consensus-and-off-chain-settlement)
  * [Token Economics](#token-economics)
  * [ERC20 Micro Rewards on MicroRaiden](#erc20-micro-rewards-on-microraiden)
- [Conclusion](#conclusion)

<!-- /MarkdownTOC -->

# Features

## ICO and Token Sale Screener
Svandis screeners will allow users to filter cryptoassets by numerous parameters using customised criteria to identify the best investment opportunities. Many relevant screeners already exist and are available via traditional financial platforms. It is therefore necessary to adjust existing financial tools, like screeners, to the crypto market.

Svandis screeners are meant to be built up for all currently operating ICO token sales and Cryptocurrencies. To build such a large set of data, we will be dependent on a combination of internal team research and public Research Community analysts, researchers, verifiers of data to curate this.

The screeners API will be available for use in algorithmic trading strategies. Speed will be an advantage for users who want to use statistics for momentum-based strategy and statistical arbitrage, or news for event-driven strategy through a text analytics API. 

We believe that the way ICOs and tokens sales are managed will be improved in the near future. The Svandis ecosystem will have standards in place for data verification, processing, and analytics. Companies will increasingly make their data more accessible to enhance their competitive position within the crypto space. As the number of parameters involved when buying a particular token also increases, the Svandis screeners will be adapted to reflect those continuous changes. 

The ICO and token sale screener will sort and filter past and future ICO and token sales according to various parameters. A wide range of criteria will be available and customisable, providing myriad ways to fine-tune the screener. A full description of each ICO and token sale will be available, including the latest news about it.

<details><summary>Expand examples of filters available:</summary><br> 

  * Token standard
  * Country restrictions
  * ICO token price USD
  * ICO token price ETH
  * Hard cap USD
  * Hard cap ETH
  * Min cap USD
  * Already raised
  * Whitelist (YES/NO)
  * Open pre-sale
  * Bonus 1
  * Bonus 2
  * Bonus 3
  * KYC (investment range)
  * Accepted currencies
  * Blockchain advisors
  * Industry advisors
  * Legal partners
  * Tokens to the team
  * Smart contract audit
  * Team members
  * Staff size
  * Product (alpha/demo/developed etc.)
  * Industry
  * Competitors
  * Individual Cap
  * Circulating Supply
  * Total Supply
  * Team vesting and cliff
  * Advisers vesting and cliff
  * Presale contributors vesting and cliff
  * Telegram members
  * Twitter followers
  * Country
  * Airdrops
</details><br>


## Cryptocurrency and Token Screener
The screener will sort and filter cryptocurrencies and tokens according to numerous parameters, both fundamental and technical. Brief information about the cryptocurrency or company will be posted on each cryptocurrency and token page, along with a chart showing technical indicators and news gathered from various resources. A vast range of criteria will be available to fine-tune to different parameters, providing thousands of ways to find and filter cryptocurrencies and tokens. 

<details><summary>Expand examples of filters available:</summary><br> 

  * Exchange(s)
  * Capitalisation
  * Country
  * Sector/Industry
  * 1-week high/low
  * 1-month high/low
  * 52-week high/low
  * 9-day SMA
  * 20-day SMA
  * 50-day SMA
  * 200-day SMA
  * MACD
  * RSI
  * Ichimoku Cloud
  * Volatility
  * Return from ICO
  * Performance (1, 2, 3)
  * Analyst recommendation
  * Price
  * Technical pattern
  * ICO date
  * New high/low
  * Overbought/Oversold
  * Average volume
  * Most active
  * Most volatile
  * Major news
</details>


## Newsfeed
Svandis is developing a customised newsfeed for the cryptocurrency market. Our goal is to aggregate crypto-related news across a variety of sources that has been shown to significantly influence the market, including websites, Twitter, Slack, Reddit, Telegram, Mediums, and other blogs. We aim to enable traders with this information in essentially real time. 

With access to the Svandis newsfeed, crypto-market traders will no longer need to subscribe to hundreds of Twitter accounts and newsletters, keep numerous tabs opened in their web browser, alternate between sources, etc. They will receive all the news they need in one place, and will be among the first to know when the market is moving. Svandis will track thousands of sites both automatically and manually, downloading and highlighting the most important news using machine learning, language processing and the human insight of professional analysts and journalists.

Each news source will be assigned a set of tags, including but not limited to:
Descriptors: Name of the digital asset, ICO or token sale
Data Type: Political, economical, exchange listing, etc.
Significance Level: Old (unimportant updates and additions), ordinary, important, or breaking news

Crypto-market traders will be able to customise their newsfeed to see only the most important news on the assets that are of interest to them. For example, if a trader is interested in a token that has just been issued after a token sale, and is not yet listed on any of the major exchanges, they will be able to configure their newsfeed in such a way that they will receive news about this particular token in regards to exchange listings. As the popularity of the Svandis platform grows the goal is to sign exclusive contracts with companies, exchanges and other news sources in order to publish news releases first at a predetermined time, in a single place and without information leaks.

The newsfeed works in correlation with our community of data miners. Svandis analysts collect trustworthy news outlets online and program carefully chosen css selectors to grip onto the URL's of new articles found on the sources. Then it is the job of the automated data mining workers on the locally running Svandis Data Mining App to use community resources to scrape new URL's to submit to Svandis in return for SVN rewards.
tosers to refine their feeds. Through machine learning we will improve our tagging over time by harvesting common terms and trends related to the tags pulling the highest quality news stories.

Users utilizing the newsfeed have the option to tag the sentiment (bearish/bullish) of the feed in order to let the community know about  the sentiment in the news stories or themes. There is also a flag on each article to mark it more "Important" in order to grasp bigger news making an impact on the community. Combining sentiment analysis and significance of different themes, we can create a more robust service of alerts for our users about trends in any given cryptocurrency market.

Users also have the ability to mark a newsfeed as Toxic. Articles marked as toxic can help the team of Analysts at Svandis with removing or refining news webfeeds to maintain a consistently trustworthy offering.

## Charts

Charts will form an integral part of the Svandis platform. Whether a cryptocurrency is selected from the screener, index, heatmap or  group, a dedicated chart page will offer actionable information on a diverse range of technical indicators and catalysts. Svandis' charts will combine different types of data to provide actionable information and insights to professional traders who want to take a step back and analyse the elements that influence their investments in greater depth. With the ergonomics of Svandis tools a priority, close attention will be focused on all chart-related features, to optimise the user experience and with it the efficiency of the work of investors.

Charts will be built ontop of the TradingView Platform, and will be accessable on the user frontend Svandis application. [Trading View](https://www.tradingview.com/HTML5-stock-forex-bitcoin-charting-library/) offers a comprehensive and free platform for developers to include in their applications. We are choosing to bootstrap this chart as it is an industry leader, it will act as a supplement to the other information Svandis will be presenting to the community.   

## Catalyst Analysis

Svandis will offer its users the opportunity to visualise the impact of a significant event on the price fluctuations of a cryptoasset. The objective is to identify price influencing events on a chart, e.g., an announcement or publication, partnership announcement, new product feature, analysts’ and influencers’ mention or ranking update, change in legislation, legal prosecution, critical hirings, or potential mergers and acquisitions.
These events might not have an immediate effect on a company’s fundamentals , but short-term traders will be able to benefit from the analysis of these elements on a cryptocurrency price fluctuations. This Svandis functionality will allow users to combine complementary data from multiple sources on a single chart. The data will be analysed by the Svandis Analytics Team to provide users with a better overview of the past and future impact of the various catalysts and related investment opportunities.

Catalyst analysis uses a combination of standard data collection, our flagged newsfeed, and changes in price to create a meaningful offering for the community. These catalysts are meant to be posted onto a historical chart to try and visualize the effect of an event on a cryptocurrency.

Svandis has the opportunity to use a combination of analyst human input, monitoring of price swings, and the flagged articles on the newsfeed to create catalysts. News feed articles contain both bullish/bearish sentiment indicators that the community can use to assign the sentiment of articles, they also have an "importance" flag in order to pinpoint significant articles. The catalyst will exemplify the affect of sentiment and significance in major stories on the resulting short-term price swing of the cryptocurrency. This will be an optional parameter to be viewed on trading view charts afterwards. 

The flow for a catalyst will start with our backend using machine learning to seek out articles with strong sentiment and significance. This combined with price fluctuations will notify analysts of a potential catalyst. It will be up to random and responsive research community members to act as analysts and decide whether to notify the community of a catalyst or not. There will also be an option for the research community to add their own custom catalysts which may be based on existing news in the web feed or not.

## Heatmaps and Groups

Svandis has developed a visual heatmap of the market that will help traders check the crypto-market status on a daily basis or over a specified period. Heatmaps translate raw, complex financial data into visual maps by presenting live, vivid images that dynamically change, allowing traders to quickly determine which cryptocurrencies and tokens are moving, how far they are moving and in which direction. Heatmaps are industry-proven investment tools that synthesise complex data to help individuals make more proficient trading decisions. The market capitalisation of each token or cryptocurrency will be displayed on the heatmap, as well as the change in their price for a given period (day, week, month, quarter, year). Svandis heatmaps will reflect most of the tradable crypto assets, which may include (but not limited to) the following categories:

* Cryptocurrencies
* Content
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

In addition to the heatmaps, users will be able to group cryptocurrencies and tokens included in the Svandis screener. This Svandis grouping feature will enable cryptoassets to be visualised by sector, industry, country and capitalisation. Each group will be sortable by different filters and visualisation options, e.g., tables, bar charts, spectra, grids, etc.

Heatmaps will be built on the Svandis front end application to add another perspective to traders. They will be built using [D3 technology](https://github.com/d3/d3) in javascript. This module has plenty of use in the online community and we can build a strong platform for our heatmaps upon it.

Groups and filters will be available in correlation with the heatmaps and they will be customizable for traders to analyze the datapoints most relevant to their investigation.

## Watchlists and Alerts

In order to to continuously monitor cryptoassets, users can access the Svandis Watchlist and Alerts features. The watchlists will quickly and easily gather into an editable list of cryptoassets that the user wants to monitor. It will be possible to assign tags and change the display order in simple steps. The watchlist will also incorporate a configurable alert function offering users a range of options to be notified about certain conditions via Telegram, SMS or email.

Watchlists will be a component of our backend Svandis services. When users register for aforementioned notifications, the backend will monitor for catalysts or events, significant price swings in crypto currencies, news feed articles, or other relevant information to relay to the user in real time. This allows the Svandis community to stay on top of the latest cryptocurrency changes as they happen. Svandis will build on top of Nest Js technology to create microservices facilitating real time feedback for events in the Svandis community.

## Portfolio
The Svandis ecosystem provides a proficient and reliable tool for quick portfolio visualisation. The portfolio developed by Svandis will connect to several popular exchanges, allowing users to evaluate the impact of breaking news on their portfolio, as well as quickly applying heatmaps to their assets for decision making.

The portfolio for a given user will be available on their front end Svandis application. Svandis will save portfolio information securely in our centralized database. Users wishing to share their portfolio may be entitled to SVN rewards. Users will be able to customize their portfolio and use tools such as heatmaps, catalyst analysis and charts to see how their investments are working for them. Users can reliably add and remove items from their portfolio with a rich array of fields to allow traders to keep track of performance, inside of a material design UX on the Svandis front end application.

## Customisable User-Interface
Every Svandis feature will have a customisable user-interface to arrange and present data in the most suitable way for every trader. It will include differing colour schemes and layouts for added customisation.

The Svandis application is built on top of Angular 6 and Angular Material Design. The application will act as a customizable dashboard where users will be able to customize styling as mentioned, as well as save default configuration for their charts, heatmaps, and portfolios. The customizability of the UI will allow traders to get all information they need on one dashboard without having to have multiple tabs and services open on their local machine.

## The Svandis Ecosystem

![Ecosystem](/images/image2.png?raw=true "Ecosystem")

The power of the decentralized research community is unparalleled in the cryptomarket and may increase the capability to detect opportunities or report organised information in a quick and efficient manner.
The Research Community and the Svandis Analytics Team are the central players in the Svandis ecosystem. Their roles, and in particular the Community’s role, will enable traders using the Svandis platform to receive all necessary crypto-data in one place before the majority of market participants.
Svandis Research Community - Trusted Reviewer and Data Verification
Svandis aims to create professional development opportunities for the most active community members who wish to complete data checks on ICOs and token sales. The goal is to check the validity of several categories of information published on an ICO or token sale. Using a standardised template to ensure consistency in the presentation of data, a checklist on various points will be available to verify and share with the community whether the given project is (1) legitimate and (2) technically feasible over a realistic period of time. Applying the diversity of expertise available among Svandis users will help target high potential projects, as well as share precautionary opinions on others. We believe that a community of reviewers can look at important elements, such as company and team backgrounds, and ICO metrics.

This dynamic system will comprise of two phases for a given screener. The first phase is creating the initial information for all existing and useful cryptocurrencies and tokens. The second phase is curating this information, each time more up-to-date truthful information can be provided. Token rewards vary for the task being completed.

Svandis will deploy a series of solidity smart contracts "The Svandis Ecosystem" containing decentralized identity for the research community and trustless proofs for the state of Data consensus. The smart contracts involved will be discussed in [Research Community Blockchain Architecture](#research-community-blockchain-architecture).

![Ecosystem](/images/image3.png?raw=true "Ecosystem")

![Ecosystem](/images/image4.png?raw=true "Ecosystem")

![Ecosystem](/images/image5.png?raw=true "Ecosystem")


## Svandis DataMining App
Svandis will offer users a data-mining functionality by using the cross-platform DataMining Application. The DataMining App is an open-source crawling application that users can install on their computers to participate into data crowdsourcing. Crawling is systematically visiting a number of web pages in order to create and index data. The DataMining App is an automated software that crawl websites, grabbing copies of pages to index. 
Receiving tasks from the Svandis command server, the DataMining App will grab website pages and social media content (all with user permission) to enable the analysis of a vast quantity of historical and real-time data. Once the encrypted data is sent to the Svandis servers, it is processed using machine learning algorithms to allow correlation analysis of variables affecting a cryptoasset’s price. This automated process will increase the speed and accuracy of the Svandis Newsfeed and Catalyst Analysis features (to be described in subsequent articles). Svandis will not collect personal data of any kind; Svandis adheres to the highest security standards with regard to personal information.

The type of data a miner’s device will grab will depend on the strength of their internet connection and device’s computing power. For example, those with a faster internet connection and a computer of higher processing power may grab real-time data, which should be more readily available to users in the Svandis ecosystem (e.g., prices, volume, news, etc.); those with a slower internet connection and a device of lower processing power may grab historical data.

This datamining app is bundled with our desktop application for Linux, Windows, and OSX, and will be available on other platforms as the project evolves. This project is discussed in further details [Data Mining Architecture](#data-mining-architecture)


![DataMining](/images/image6.png?raw=true "Datamining")

![DataMining](/images/image7.png?raw=true "Datamining")

See in depth functional description [Data Mining Architecture](#data-mining-architecture)

## Marketplace
The Svandis Marketplace will provide third-party access via the Svandis API. Svandis is planning to provide the access to Svandis products for corporate clients, as well as to Svandis Partners products for retail and corporate clients. This feature will help to distribute products of Svandis and company's partners.

The marketplace will be programmed into the front end Svandis application. Costs within the marketplace will be resolved using SVN token as the currency. Users will be able to utilize tokens they received as rewards in the platform directly on the marketplace.

## Svandis Indices

To better serve traders, we will be implementing Indices in the platform. These indices will be compiled both by the Svandis team and will be available to users. This software offering will be developed along side other dashboard features in the front end Svandis application, and will integrate with user portfolios and custom interface.

The Svandis indices will be developed by the Internal Research and Analysis Team. For example, a major Svandis index will be an index of 30 cryptoassets issued by the highest ranked companies. The goal is to establish a leading performance indicator of largest cryptocurrencies and tokens in terms of market capitalisation. Other Svandis indices may include a volatility index showing a projected 30-day market volatility.

With Svandis, users will be able to formulate their own indices. This feature will allow the cryptocurrency market to be divided into user-defined subgroups for the tracking of price and volume changes. The Customised Index Builder will include varying parameters.

# Data Mining Architecture
## Data Mining Workers

Bundled with our front end Desktop Application for Linux, OSX, and Windows we have included our worker module. Within the application, users can find a datamining sub application, where they can acknowledge terms and conditions and proceed to mine web feed information on their machine. Our web feeds are curated lists of trustworthy news sources, carefully chosen based on CSS Selectors on the websites they originate from. Not all news information will be blockchain or cryptocurrency related, so our carefully selected Tags and machine learning generated tags will take care of extracting URL's only of relevant articles. In return for lending the processing power on their machine, users mining for web feeds will receive SVN rewards.

The front end Svandis application is bundled with [Electron technology](https://github.com/electron) so that it can be offered across various platforms. The front end is based on Angular 6 and Javascript. 

The desktop worker crawls for links, and afterwards sends to the socket server build on NestJs technology. The socket validates them and if the link has not been crawled it will indicate to the worker. It is then the task of the worker to send to the backend content extractor written in Python programming language.

Currently the CSS selectors associated with new contents on web feeds are being programmed custom by the internal svandis team. We hope that in the future this can be a task for the research community, so that they can receive SVN token rewards for accomplishing this task in many more languages. Consensus based mechanisms can be put in place to confirm or reject a new web feed that a community developer might propose.

## Machine Learning and Sentiment Analysis
In order to facilitate a positive feedback loop between the Internal analytics team and the research community, we will be using machine learning to pinpoint catalysts and other events within the ecosystem for which the internal team will make its best contribution. Machine learning will be used during the consensus mechanism as well to correlate similar information being presented by research community members.

Machine learning is a part of data mining as we need to assure that the tags that we are associating to the Webfeeds are in fact accurate. In addition, as we curate high quality content from our tags, our worker will become smarter with Machine learning in that we will be able to automate the collection of tags or terms that produce similar content results based on our current tags.

The users of the svandis ecosystem will be able to tag sentiment. We will be using [Stanford's Core NLP package](https://stanfordnlp.github.io/CoreNLP/) in order to do our own sentiment analysis on content as well. Using a combination of human and automated sentiment analysis we will be able to pinpoint with greater accuracy bullish and bearish trends in a given market. Using fuzzy logic and mathematical methods we will be able to extrapolate trends in sentiment to the performance of the market and supply this alongside heatmaps, catalysts and portfolios to ensure we provide complex traders and newcomers alike with the most comprehensive Cryptocurrency information in one place.

## Svandis Database

Svandis will be using a traditional centralized database for the newsfeed and screener information. The database layer lies behind our backend API service. The decentralized research community will be able to validate the state of this data with off chain signatures as discussed in the blockchain architecture. This approach will allow us to validate the state of our database externally in a decentralized format.

The database being used is a Cassandra database stack. Svandis is choosing to use a Cassandra database as it supplies a robust NoSQL solution that will be able to scale quickly to the high velocity of token information and web content that we will be receiving on a second to second basis for the Svandis project. Cassandra's tech stack is decentralized so that there is no single point of failure.

# Research Community Structure

Svandis will focus on a mixed B2C and B2B business model, as our target audience includes retail cryptocurrency traders, cryptoasset investors, crypto-hedge funds, analytics companies, and traditional retail traders planning to enter the cryptocurrency market.

The internal Svandis Analytics Team will provide the expertise necessary to conduct analysis and approve the content that is offered to users of the service. Like users in the Research Community, the Analytics Team will submit and verify data on cryptocurrencies and tokens.
They will be responsible for validating the input from the Svandis Community for more complex data sets. Their work will cover ICOs, token sales, project updates, classification of the most important news to ensure that breaking news is promptly identified, and more. The growing team consists of senior analysts, researchers, editors, and developers working with data-grabbing technologies.
From launch, the Svandis ecosystem will include a comprehensive database of cryptoassets (tokens, coins, cryptocurrencies and ICOs), which aims to rival existing crypto-information sources. Users within the Svandis community will be invited into the Beta Community Research prior to a public launch.
The Svandis ecosystem will be an industry first — a comprehensive crypto-research and visualization platform that combines crowdsourced data and machine learning.

In order to sustain the highest quality of data about all the current existing projects, Svandis internal analytics will only be able to support the curation and building of the community. To manage such a vast amount of new and changing information we will be highly dependent on a research community made up of decentralized actors. The research community will be divided in grades and "Svandis Power" to ensure the most reputable and trustworthy actors have the most weight in the system.

The cooperation of the Internal Svandis team with the Svandis Research Community is a pilar of the project, and as the project scales and grows, the philosophy is for the Research Community to require less dependence on the internal team over time. The final result is a curated registry of Cryptocurrency information that the Research Community can be proud to claim as their creation.

## Roles in the Research Community
### Newcomers
**Requirements:** Registered Svandis user (mandatory)

**Rights:** A newcomer logging into the research community interface will receive simple and easy data validation requests (grade 1 type) for research. Those requests will be the same ones that are being presently asked to be validated within the community. However, the newcomer’s results will not be recorded for the official consensus. The idea behind this is that data validated by newcomers should not count towards the consensus of data integrity. Their results are compared with the data of researcher’s data for personal statistics and, after a series of successful submissions, the user will prove himself as a trusted novice participant. This allows a sense of security and trust in the data; they do not have to worry about spam from malicious new users, egregiously  wrong data, or erroneous information. The system will automatically filter out the bad actors.

The main goal for a newcomer is to submit enough accurate data to become a researcher, at that point they unlock the possibility of receiving SVN rewards for the work accomplished. If a newcomer submits a complete KYC, he will receive a significant rating upgrade. 


### Researchers
**Requirements:** Light internal KYC

**Rights:** Researchers can start submitting data available in the grids. Once they reach rating level 5, they can submit anything. Data validation requests start at level 6 and increases until level 10 (see schema about rating levels below). Researchers can also suggest new project submissions and flag incorrect or false data in the ICO screener. Researchers get SVN token reward for their successful work. 

There will be a rating level from 1 to 20 where each level will unlock new actions or new fields to validate. Each data field will have a ‘’grade’’ linked to it for validation requests purposes. Evolving your profile as a researcher will unlock higher data grades and allow him to validate a wider area of data submission requests. The rating required for certified researcher rank (level 10) will be fairly easy to reach to let researchers submit and validate all the information about projects. The following ranks will be, on the other hand, significantly harder.


### Certified Researchers
**Requirements:** Ranking needed for a researcher to be able to submit and validate any type of data. (level 10) 

**Rights:** Certified researchers can submit, validate or modify any data field, but still need to be validated by research community. At this point, reaching higher levels allow users to obtain higher Svandis Power within the platform and also unlocks actions available on the Svandis Newsfeed feature. They will now be able to tag “sentiments” in the news articles in order to rate bullish - bearish. 


### Certified Analysts
**Requirements:** Extensive experience within svandis platform

**Rights:** Certified analysts can analyse all the processes of the data workflow on Svandis platform, enabling them to identify anomalies that might be occurring in the system. They are also in charge of submitting and validating data that requires rigorous methods of investigation. At this level, they have the ability to officially push the projects data into the ICO screeners. Furthermore, they get a basic training on algorithms and blockchain parameters that influences the way the community are incentivized towards gathering specific data. Certified Analysts can propose tweaks, ideas to the internal team. They may act as trainers for researchers as these individuals have shown their value and capacity to deliver on a fast and accurate manner. 


### Mediators
**Requirements:** Complete KYC and video interview  

**Rights:** Mediators act as a referee when a project submit conflictual data into the grid or when data cannot reach consensus on whether it is considered good or wrong. They communicate with projects to let them know about their grid submission on Svandis platform. They are the bridge between projects and Strategic Development office.  Analysing internal statistics and suggesting platform improvement are tasks that will be done at this optimal ranking level on the Svandis platform.


## Rating and Svandis Power
### Rating
Each researcher’s level, from 1 to 20, is directly calculated behind a hidden rating that is influenced by a range of variables based off a user’s productivity and effectiveness. Before reaching the certified researcher title, a user in the research community must climb and potentially increase his rating with:

1. Accuracy of data submission, validation and modification
2. Ability to perform and reach consensus with other users in a time box
3. Streaks of successful actions
4. Activeness on the platform
5. Difficulty of the data submitted 

On the other hand, participants who fails to reach consensus by submitting erroneous data for data submission or validation will be losing a considerable amount of rating points. There will also be penalties for participants who do not respond to data validation requests or who dismiss them on a regular basis.

### Svandis Power
The Svandis Power is the weight of the participant throughout the Svandis platform as a user of the research community. Everyone should thrive to increase their level in order to raise their power commitment in the community hierarchy. The Svandis Power will influence the participants actions in the following features:

1. Data validation consensus (Research Community)
2. News articles rating (Newsfeed)
3. Sentiment: Bearish / Bullish / Important (Newsfeed)

## Screeners Workflow for the Research Community

1. Data submission

Svandis internal team or certified analysts push a selection of ‘’Initial Coin Offering’’ projects from a suggestion form that can be provided by all ranks above Newcomer. There are some mechanisms to counter spam or nonexistent projects. This initial coin offering project will need to be filled with factual information about the project.

The research community receives a notification about new projects available to validate and submit data for.
Each data field has a unique SVN token reward attached to it.

 As soon as a data field is filled and submitted, it is sent to reviewers (Level 6 and above) dashboard. Within the grid, there will be a visual effect on the data field that it is currently ‘’validating’’.

While a field has the status ‘’validating’’, the researchers will still be able to submit data. If they end up having the right answer, they may get a reward depending on the accuracy and speed of their submission (ex. Only first X participants to submit correct data will get some reward).



2. Data validation

Once a user reach level 6, he will be able to set his profile to ‘’Active Validator’’, which will enable him to start receiving validation requests. Being efficient with this feature will be crucial for increasing their rating, many aspects of the research community are focused on activeness and accuracy of a user’s validation responses.

The data submission is sent to a fixed amount of Svandis Power among the users online with an appropriate rating level to receive the submitted data grade. There should be a mechanism where data submission is sent to analysts if not enough users are online for data approval. 

When data gets submitted, for example, ICO project X ''hardcap'', and reviewers do not see the answer, they are alerted that someone submitted a value for ICO project X ''Hardcap'' and has been randomly selected to find the correct answer as a reviewer. So instead of just seeing the answer and clicking on a button, they have to find the answer and submit it as well. Depending on the complexity of the value, the system will automatically compile the results and compare with the researcher’s submission. This system will be slightly modified for qualitative data that cannot be compared.

There is an option for a reviewer to dismiss a request, removing the user from the statistics. A user who dismisses too many requests might receive less review requests after a certain amount (algorithm parameters). The request will then be sent to another user with a similar Svandis Power.
 

If 75% consensus on reviewers data cannot be reached, it is disapproved. If 75% consensus is reached but is not the same data as the researcher’s submission, it is sent to analysts. There might be cases where not enough participants responds to a validation request. For this matter, a time box should be used and the request will be sent to another user when it expires.

A user who dismisses too many requests might receive less data requests while faster and accurate reviewers will be sent significantly more data requests to be validated (algorithm parameters). This setup will quicken the process of data validation consensus.


3. Data Publication

For a certain duration of the platform alpha release, certified analysts receive the result from data reviewers and which one has been accepted as a consensus. However, once the data is validated with 75% consensus, it should be pushed into the system automatically. At this time there is a mechanism to publish the state of this information to the blockchain and assure transparency for decentralized actors.

After analyzing the results, The analyst or the system publishes the data to the platform. The researcher who submitted the approved data gets the largest share of SVN rewards while the others who submitted the answer while ‘’validating’’ gets a lesser reward depending on the speed of their submission. (After a fixed number it should be very low.)

For quantitative data (those available to the newcomers), consensus from the certified reviewers will results in the data being published directly on the platform without having to be analyzed by certified analysts.


4. Data Modification

Each project’s grid has a ‘’flag’’ option available for any participant of the research community.

Once the researcher enters the updated data in the grid, it follows the same process as a new data validation. 

Some data fields may have to change constantly, example: the current amount of token sold during an ICO. Those will be reserved for the analysts to update them when needed.


Anyone (except newcomers) can suggest new project grids to be researched. The suggestion gets validated by certified researchers who reached level 12. When reviewers can approve the existence of the new project, it goes into an analyst dashboard. The analyst perform final verifications and can successfully push the grid.

There will be 2 types of users: Independent participants (newcomers, researchers, analysts) and project participants (CEO, Founders). The majority of the platform users will be independent but there will be an option to register as a user from an existent project / company. Each of those participants will require an extensive KYC to prove the relationship between him and the project itself. Once registered, the project participant will be able to submit his own project or contest data. Researchers are in charge of validating the data, while mediators take care of data contestation. 

Filtering the grids with relevant information will be valuable for the research community. They will be able to verify which grids has been released in the last 24 hour, watch their favorite grids and their modifications, etc. 

A rating ranking will be available to the research community with personal statistics: progression on a daily basis, amount of data entered, validated, etc.


# Blockchain Architecture
## ERC 725/735 Decentralized Identities

The methodology behind identity on the blockchain is an especially interesting topic in the Ethereum community today. There are various Ethereum Improvement Proposals that have been put forward, and groups (such as UPort, Status.im, Civic, Tenzorum, and the Ethereum organization) are seeking to provide their own innovative solutions. However what they share is decentralization of identities, key management, "claims" made by trusted parties, controlled by a smart contract. However the exact manner in which these solutions are formulated differ based on the exact business specifications of the organization.

Svandis is presenting a **decentralized first** and **low gas cost** solution for the Research Community. After research into the subject and carefully weighing the benefits of other open source solution, we decided to take a similar approach to identity such as the [Origin.js project](https://github.com/OriginProtocol/origin-js). This solution is compliant with [EIP725](https://github.com/ethereum/EIPs/issues/725) and [EIP735](https://github.com/ethereum/EIPs/issues/735) . 

In order to have a seamless solution, at the moment Svandis will post the identity of users on the blockchain for them. Users will have the choice of selecting beginner or expert users, which will translate to whether or not they would like Svandis to hold a key to their identity contract. Both beginner and expert users will generate, without the need for metamask- a local file in browser containing their web wallet that can only be opened with a password. Beginner users will allow Svandis to add the Svandis organization as the recovery key for this on chain contract (which contains their decentralized "reputation" on chain.) Expert users will have their own recovery mechanism, and will acknowledge that if they lose access to all their keys they will not be able to recover their on chain "reputation" connected to this smart contract. Users will be prompted to learn more about Blockchain and eventually use metamask or a hardware wallet to store their recovery key as beginners become experts. As the research community moves towards being completely on the blockchain, the recovery mechanism key may be potentially transferred to the custodianship of a decentralized autonomous organization. 

For KYC and social media connected accounts, we will also add trusted "claims" on the blockchain. This will be for users that authenticate a social media provider with Svandis. It will also cover users who wish to confirm their real identity on chain in exchange for token rewards for reducing spamming accounts onto the platform. 

As expert users will be able to take full control of their on chain identity, they will have the ability to confirm that they are the only users in control of their identity. This is a secondary authentication alongside their standard JWT Auth login which will enable these users to validate that they are truthfully attesting information to the research community, and it is not the action of the Svandis organization speaking on these specific expert user's behalf. Svandis is decentralized first. The Svandis organization will not contribute to bias expressions on the platform nor knowingly post non factual information onto the Blockchain.

[See our Identity Contracts on Github](https://github.com/svandisproject/svandis-backend/tree/master/contracts/identity)

## Data Signing and Screeners on the Blockchain

The solution Svandis serves is light weight and low cost, for which reason we don't intend on adding all information directly onto the blockchain. We have explored various solutions including IPFS, however at this time we will be using the Cassandra NoSQL database solution. The conceptual information on this database however, will be represented by specific structured data snippets from which we can extract a "data hash" and post the current state to the blockchain.

Each time users contribute to ICO or Token screeners, they will be coming to agreement with other users in the Svandis consensus mechanism. Each time a user fills out a set of new or updated fields to add to the information set for a screener- they will generate a "signature" of that decision in their browser. This means that only by unlocking your in browser Ethereum authentication, you can submit "signed" data to be considered in consensus and eventually published to the blockchain dependent on off chain results. This means that Svandis can confirm afterwards the exact on chain identity of the users who submitted to consensus were, and expert users will be able to attest that Svandis had no influence on their signed information.

[See our Contracts Backend for publishing signed data on Github](https://github.com/svandisproject/svandis-backend/tree/master/contracts/svandisdata)

## Consensus and Off Chain Settlement

Creating a random consensus for data validation, and all the cost of executing this logic is not a feasible solution to complete on the Ethereum blockchain today.

Every screener on the blockchain is a piece of "Svandis data", it can be upgraded from a ICO or Token offering to an exchanged cryptocurrency, and the original state is published when a new contract is created for a screener. That contract will be subject to having it's current "state" changed to the most recent hash for the structured data field associated with the screener.

To make a decision on behalf of beginner and expert accounts working together, there needs to be a consensus made. The power and rating effect on consensus and quantity of token rewards is subject to changes in the Research Community token economics. 

The mechanism of consensus will rely on **10 users** submitting their opinion on a qualitative or quantitative data field in the screener. These users must be randomnly selected by Svandis off chain and this will be based **on a randomized selection using entropy from the last Ethereum block hash**.  The 10 online users selected will first transmit a signed data hash with hidden data to Svandis. Once 10 online users have submitted to the consensus, they will reveal another signed "secret" which can be used for trustless confirmation of what they researched for this data field. Through a combination of Machine learning, data analyst parameters, and UX features Svandis will make a decision on whether a consensus was reached between users.

Successful consensus reached by over 75% of users based on the Svandis power and rating, means that there is a new hashed data state to characterize the structured data representing a screener. Svandis will at this point publish to the blockchain (in intervals and with confirmed transactions, as mentioned herein) alongside publishing the exact signed message hash that the decentralized community members originally submitted. If consensus is not reached there will be no change on the blockchain, if there is an action later on by Svandis Internal analytics team this might trigger an action being recorded on chain.

**To deal with the cost** of publishing information to the blockchain, we will not be publishing at a common interval. We will publish the state of the current database once per day publically on the chain. In real time, we will publically publish a feed on Svandis website where we will post signed transactions (that have not been submitted to the blockchain) with the current state of our information. This means that any user can submit this transaction on chain, so that Svandis maintains accountable and transparent for the actions of the backend whilst saving cost on updating every event to the blockchain. 

This process is necessary to provide a light weight and transparent layer to our offering. We have created our development plan for our solution balancing between the necessity for user friendliness, the growing desire for the cryptocurrency community to act in a decentralized manner, and responsibility to the community to create mechanisms in the smart contracts to promote truthfulness in our offering. 

Based on the state of consensus, there will be micro rewards associated with each field of a screener that a research community member successfully helps complete. These micro rewards will be facilitated in a low cost micro raiden solution, discussed further herein.

## SVN Token Economics

The SVN token is an ERC20 Compliant Token to be deployed on the blockchain. Our [Crowdsale Contract](https://github.com/svandisproject/smart-contract) contains an example of our current token contract.

We will provide several levels of access to our features with SVN tokens. Access will be given to token holders and we will also add the option to purchase access to products with SVN tokens. Basic-level access will be provided for free, including the screening functions and a newsfeed with a time delay. The main functions of the feature will only be accessible using SVN tokens. 

Levels of access to our products will be published after the release of products.

Our goal is to release products that will significantly improve the analytical rigour of the crypto markets, while reducing the time participants spend on such analysis. Professional traders are prepared to pay for valid and reliable information that can afford them a competitive advantage in trading on the markets. 

**Terms and Conditions**

By releasing SVN tokens, Svandis offers all crypto-market participants the opportunity to become part of a professional infrastructure that gathers data on cryptocurrency and token trading, as well as ICO and token sales. This infrastructure will include the following features: ICO and token sale screener, Cryptocurrency and Token Screener, Newsfeed, Charts, Catalysts Analysis, Heatmaps and Groups, Watchlists and Alerts, Marketplace, Portfolio Management Tools, and Customised Index Builder.

SVN token holders can receive access to the aforementioned products, with the level of product and tool access depending on the quantity of tokens in each holder's possession. In addition, we will develop a simple model for buying access to the Svandis features with SVN tokens.
Thus, the Svandis features will be available only through the ownership of SVN tokens and, in order to gain access to the products, a SVN token holder earns access by:

Buying tokens at any time and having access to the products as a token-holder (in accordance with defined access levels, to be published in due course), or;
Purchasing access to one or more features with SVN tokens.
The Svandis Community will receive rewards for expediting the process of data gathering (data miners) and submitting and verifying the information in the platform. This will ensure circulation of tokens in the Svandis ecosystem; tokens will be used as the key to access Svandis products and as the reward for bringing actual information to these products

**Expediency of Issuing SVN Tokens**

Issuing infrastructure tokens specific to Svandis will help limit the number of participants who have early access to the platform, which is currently a necessity due to the low liquidity of the cryptocurrency markets compared to traditional financial markets. Thus, a limited number of market participants (both individual traders and hedge funds) will be among the first to receive information, enabling them a greater time to react. The issuance of SVN tokens will help create a professional structure for a limited number of traders at first and then, with increasing liquidity in the cryptocurrency markets, for everyone.

## ERC20 Micro Rewards on MicroRaiden

To deal with quick token transfers, we can use a custom off chain settling solution. We hope to use MicroRaiden/ Raiden.network technology for SVN token rewards. At a high level, this works by opening up a payment channel between the Svandis rewards token account and the user working on the network. Micro rewards of SVN are given for each proper validation based on the parameters of the gamification. These micro rewards are settled in real time by the actors on the off chain solution. When users want to withdraw these rewards, basically they will close the channel using the most recent signed transaction between user and rewards token fountain. Using the Raiden network would be a great way to implement this payment channel, and must be further explored for viability of this approach.

Micro Raiden will be the specific implementation we will add, for quick svn token transfers facilitating plenty of micro rewards in wei. The exact integration with smart contracts and backend solutions is under development and is subject to the current best practices for token transfers.

# Conclusion

The Svandis team is proud to propose this technical solution for the creation of a Decentralized Research Community and platform which will enrich the cryptocurrency trading experience for beginners and seasoned crypto veterans alike. This document acts as a living technical whitepaper for the time being and we are open to the community proposing Pull Requests to improve the content or even propose new ideas or alternative opinions on the development of the Research Community.

Feedback and issues are welcome from the community. The goal of our solution is to be decentralized first and offer a lightweight solution to increase the transparency of our offering.
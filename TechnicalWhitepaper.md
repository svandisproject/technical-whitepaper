# Svandis.io Technical Whitepaper

**September 26, 2018**

**Abstract:** 
Svandis is developing a platform for crypto market participants, providing leading financial research, analytical and visualisation tools for anyone actively involved in the cryptocurrency space: short- and long-term traders, analysts, hedge funds, institutional investors, proprietary trading firms, venture capital funds, token sales contributors, and exchanges. 

The Svandis ecosystem is a collection of powerful tools, analytics, and indicators for professional traders in need of real-time, actionable data and analyses. Beginners will find it easy, professional traders will find it comprehensive. The Svandis ecosystem aggregates data from a wide range of sources into one place, transforming raw data into reliable and valuable information, and covering professional crypto market participants with up-to-the-minute news and updates filtered by the Svandis research community and analysts through a web-based application. 

Svandis provides users with a greater understanding of market conditions and trends, as well as a comprehensive platform for the evaluation of fundamentals behind cryptocurrency initiatives, e.g., initial coin offerings (ICOs) and token sales. Svandis aggregates data from a variety of sources; transforming data into reliable and actionable information for professional traders. 

The Svandis platform provides leading financial research, analytical and visualisation tools for anyone actively involved in the space: short-term and swing traders, traditional holders, analysts, hedge funds, institutional investors, proprietary trading firms, venture capital funds, token sale contributors, and exchanges.

Every feature proposed is part of a strategic vision to enhance the user’s overview of the cryptocurrency market. Svandis tools generate a customisable way to cross-check a wide range of data and gain a perspective for different values. 

Svandis will include the following features: 

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

The Svandis Community will be involved in producing crowdsourced information of value through the DataMining app, receiving Svandis tokens (SVN) for their participation. In addition, the Svandis Team will certify reviewers and external analysts to complete data verification regarding ICO and token sale projects and teams.

Svandis is a team of market traders, crypto enthusiasts, investors, engineers, and statisticians.  In crypto trading, timing is everything. Svandis aims to incorporate best practice from financial platforms to address the needs of everyone who is involved in the new era of cryptocurrency trading.


**DISCLAIMER:** 
This Whitepaper does not constitute an offer to sell or invitation to purchase any securities of any nature whatsoever, and the content of this presentation is not intended to constitute legal, commercial or tax advice. Some of the declarations contained in this WP constitute forward-looking statements and are subject to change.
 
The Svandis Whitepaper is intended for preparation, description and information purposes only, and does not constitute an offer or solicitation to buy or sell any securities or invest in any of all types of financial instruments. This document is not compiled in compliance with, and is not subject to, the laws and regulations of any jurisdiction created to protect the investors. Nothing published by Svandis or one any of its subsidiaries should be taken as investment advice. Please consult an appropriate licensed professional before engaging in any financial transaction, including any investment related to the ideas or opinions expressed, in the past, present or future, by Svandis or any future entity working for the parent entity. The information document below should not be seen as exhaustive and does not imply any element of a contractual relationship. Its sole aim is to submit relevant and reasonable information to potential token holders so that they can determine whether they should undertake an in-depth analysis of the company before intending to acquire tokens.
 
The Svandis token, or SVN, is a cryptographic token used to access the Svandis platform. In no circumstances should the SVN tokens be confused with security tokens. All SVN tokens purchases are non-refundable. SVN token ownership does not represent any future governance of the platform or Svandis. By purchasing the SVN token, you will be deemed to have carefully reviewed the purchase terms. In addition, you represent and warrant that you are of sufficient legal age to be bound by these terms and that you may not under any circumstances hold the company, its representatives, founders, affiliates or advisors, either now or in the future, liable for any loss or damage arising from the purchase or sale of the SVN token. The purchaser is solely and entirely responsible for all risks associated with the purchase of the SVN token, and warrants that this purchase is made to support the project development activities and not to make a speculative investment. Svandis recognises that the purchaser will have to meet KYC (Know Your Customer) and AML (Anti-Money Laundering) requirements when buying the SVN token. Svandis expressly disclaims any liability or responsibility for any direct or indirect loss or damage of any nature whatsoever, relating directly or indirectly to: (1) the reliance on any information content presented in this document, (2) any error, omission or inaccuracy relative to the information herein or (3) any action deriving from the information herein.

This Whitepaper, any portion or copy thereof shall not be brought, transmitted or distributed in any countries where the distribution or diffusion of the token sale or the initial coins offer described within the Whitepaper is prohibited or restricted. You are not eligible and you cannot buy any Svandis token if you are a citizen, resident or green card holder of the United States of America, or a resident of the People’s Republic of China, or Singapore.

**Technical Whitepaper**
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
  * [Data Analytics and Reviewers](#data-analytics-and-reviewers)
  * [Marketplace](#marketplace)
  * [Svandis Indices](#svandis-indices)
  * [Indices Builder](#indices-builder)
- [Data Mining Architecture](#data-mining-architecture)
  * [Data Mining Workers](#data-mining-workers)
  * [Machine Learning & Sentiment Analysis](#machine-learning-and-sentiment-analysis)
  * [Svandis Database](#svandis-database)
- [Blockchain Architecture](#blockchain-architecture)
  * [ERC 725/735 Identity](#erc-725-and-735-identity)
  * [Decentralization of Research Community](#decentralization-of-research-community)
  * [Data Signing & Screeners](#data-signing-and-screeners)
  * [Consensus & Off Chain Settlement](#consensus-and-off-chain-settlement)
  * [Token Economics](#token-economics)
  * [ERC20 Micro Rewards on MicroRaiden](#erc20-micro-rewards-on-microraiden)
- [Conclusion](#conclusion)

<!-- /MarkdownTOC -->

# Features

## Screeners
Svandis screeners will allow users to filter cryptoassets by numerous parameters using customised criteria to identify the best investment opportunities. Many relevant screeners already exist and are available via traditional financial platforms. It is therefore necessary to adjust existing financial tools, like screeners, to the crypto market.

The screeners API will be available for use in algorithmic trading strategies. Speed will be an advantage for users who want to use statistics for momentum-based strategy and statistical arbitrage, or news for event-driven strategy through a text analytics API. 

## ICO and Token Sale Screener
The ICO and token sale screener will sort and filter past and future ICO and token sales according to various parameters. A wide range of criteria will be available and customisable, providing myriad ways to fine-tune the screener. A full description of each ICO and token sale will be available, including the latest news about it.

<details><summary>Examples of filters available:</summary><br> 

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
</details>


We believe that the way ICOs and tokens sales are managed will be improved in the near future. The Svandis ecosystem will have standards in place for data verification, processing, and analytics. Companies will increasingly make their data more accessible to enhance their competitive position within the crypto space. As the number of parameters involved when buying a particular token also increases, the Svandis screeners will be adapted to reflect those continuous changes. 

## Cryptocurrency and Token Screener
The screener will sort and filter cryptocurrencies and tokens according to numerous parameters, both fundamental and technical. Brief information about the cryptocurrency or company will be posted on each cryptocurrency and token page, along with a chart showing technical indicators and news gathered from various resources. A vast range of criteria will be available to fine-tune to different parameters, providing thousands of ways to find and filter cryptocurrencies and tokens. 

<details><summary>Examples of filters available:</summary><br> 

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


## Visualisation Tools

## Charts
Charts will form an integral part of the Svandis platform. Whether a cryptocurrency is selected from the screener, index, heatmap or  group, a dedicated chart page will offer actionable information on a diverse range of technical indicators and catalysts. Svandis' charts will combine different types of data to provide actionable information and insights to professional traders who want to take a step back and analyse the elements that influence their investments in greater depth. With the ergonomics of Svandis tools a priority, close attention will be focused on all chart-related features, to optimise the user experience and with it the efficiency of the work of investors.

## Catalyst Analysis
Svandis will offer its users the opportunity to visualise the impact of a significant event on the price fluctuations of a cryptoasset. The objective is to identify price influencing events on a chart, e.g., an announcement or publication, partnership announcement, new product feature, analysts’ and influencers’ mention or ranking update, change in legislation, legal prosecution, critical hirings, or potential mergers and acquisitions.
These events might not have an immediate effect on a company’s fundamentals , but short-term traders will be able to benefit from the analysis of these elements on a cryptocurrency price fluctuations. This Svandis functionality will allow users to combine complementary data from multiple sources on a single chart. The data will be analysed by the Svandis Analytics Team to provide users with a better overview of the past and future impact of the various catalysts and related investment opportunities.

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

## Watchlists and Alerts
In order to to continuously monitor cryptoassets, users can access the Svandis Watchlist and Alerts features. The watchlists will quickly and easily gather into an editable list of cryptoassets that the user wants to monitor. It will be possible to assign tags and change the display order in simple steps. The watchlist will also incorporate a configurable alert function offering users a range of options to be notified about certain conditions via Telegram, SMS or email.

## Portfolio
The Svandis ecosystem provides a proficient and reliable tool for quick portfolio visualisation. The portfolio developed by Svandis will connect to several popular exchanges, allowing users to evaluate the impact of breaking news on their portfolio, as well as quickly applying heatmaps to their assets for decision making.

## Customisable User-Interface
Every Svandis feature will have a customisable user-interface to arrange and present data in the most suitable way for every trader. It will include differing colour schemes and layouts for added customisation.

## The Svandis Ecosystem

The power of the community is unparalleled in the cryptomarket and may increase the capability to detect opportunities or report organised information in a quick and efficient manner.
The Research Community and the Svandis Analytics Team are the central players in the Svandis ecosystem. Their roles, and in particular the Community’s role, will enable traders using the Svandis platform to receive all necessary crypto-data in one place before the majority of market participants.
Svandis Research Community - Trusted Reviewer and Data Verification
Svandis aims to create professional development opportunities for the most active community members who wish to complete data checks on ICOs and token sales. The goal is to check the validity of several categories of information published on an ICO or token sale. Using a standardised template to ensure consistency in the presentation of data, a checklist on various points will be available to verify and share with the community whether the given project is (1) legitimate and (2) technically feasible over a realistic period of time. Applying the diversity of expertise available among Svandis users will help target high potential projects, as well as share precautionary opinions on others. We believe that a community of reviewers can look at important elements, such as company and team backgrounds, and ICO metrics.
This dynamic system will be implemented in two phases. Phase 1 aims to develop a critical mass of trusted reviewers; all work will be verified by the Svandis Analysis Team to double check every piece of information. All participation will be rewarded with SVN tokens or higher additional access levels to the reviewers. Each item of valuable information will result in awarded reputation points to reviewers, as a means of building a reputable group of relevant experts. 
During Phase 2, Svandis will encourage users to double-check the analysis of previous reviewers. For every 10 users who approve a piece of data/information, the reviewer will gain a reputation point and consequent validation of their participation. Once they are approved over 10 times by over 10 separate users (i.e., ten sets of approvals by ten other users), they will be classified as a trusted reviewer. Over time, the best reviewers will be integrated into the Svandis Analysis Team.


## Svandis DataMining App
Svandis will offer users a data-mining functionality by using the cross-platform DataMining Application. The DataMining App is an open-source crawling application that users can install on their computers to participate into data crowdsourcing. Crawling is systematically visiting a number of web pages in order to create and index data. The DataMining App is an automated software that crawl websites, grabbing copies of pages to index. 
Receiving tasks from the Svandis command server, the DataMining App will grab website pages and social media content (all with user permission) to enable the analysis of a vast quantity of historical and real-time data. Once the encrypted data is sent to the Svandis servers, it is processed using machine learning algorithms to allow correlation analysis of variables affecting a cryptoasset’s price. This automated process will increase the speed and accuracy of the Svandis Newsfeed and Catalyst Analysis features (to be described in subsequent articles). Svandis will not collect personal data of any kind; Svandis adheres to the highest security standards with regard to personal information.

The type of data a miner’s device will grab will depend on the strength of their internet connection and device’s computing power. For example, those with a faster internet connection and a computer of higher processing power may grab real-time data, which should be more readily available to users in the Svandis ecosystem (e.g., prices, volume, news, etc.); those with a slower internet connection and a device of lower processing power may grab historical data.


## Svandis Data Analytics and Reviewers
The internal Svandis Analytics Team will provide the expertise necessary to conduct analysis and approve the content that is offered to users of the service. Like users in the Research Community, the Analytics Team will submit and verify data on cryptocurrencies and tokens.
They will be responsible for validating the input from the Svandis Community. Their work will cover ICOs, token sales, project updates, classification of the most important news to ensure that breaking news is promptly identified, and more. The growing team consists of senior analysts, researchers, editors, and developers working with data-grabbing technologies.
From launch, the Svandis ecosystem will include a comprehensive database of cryptoassets (tokens, coins, cryptocurrencies and ICOs), which aims to rival existing crypto-information sources. Users within the Svandis community will be invited into the Beta Community Research prior to a public launch.
The Svandis ecosystem will be an industry first — a comprehensive crypto-research and visualization platform that combines crowdsourced data and machine learning.
Business Model
Svandis will focus on a mixed B2C and B2B business model, as our target audience includes retail cryptocurrency traders, cryptoasset investors, crypto-hedge funds, analytics companies, and traditional retail traders planning to enter the cryptocurrency market.

Our goal is to release products that will significantly improve the analytical rigour of the crypto markets, while reducing the time participants spend on such analysis. Professional traders are prepared to pay for valid and reliable information that can afford them a competitive advantage in trading on the markets. 

We will provide several levels of access to our features with SVN tokens. Access will be given to token holders and we will also add the option to purchase access to products with SVN tokens. Basic-level access will be provided for free, including the screening functions and a newsfeed with a time delay. The main functions of the feature will only be accessible using SVN tokens. 

Levels of access to our products will be published after the release of products.

## Marketplace
The Svandis Marketplace will provide third-party access via the Svandis API. Svandis is planning to provide the access to Svandis products for corporate clients, as well as to Svandis Partners products for retail and corporate clients. This feature will help to distribute products of Svandis and company's partners.

## Indices
## Svandis Indices
The Svandis indices will be developed by the Internal Research and Analysis Team. For example, a major Svandis index will be an index of 30 cryptoassets issued by the highest ranked companies. The goal is to establish a leading performance indicator of largest cryptocurrencies and tokens in terms of market capitalisation. Other Svandis indices may include a volatility index showing a projected 30-day market volatility.

## Indices Builder
With Svandis, users will be able to formulate their own indices. This feature will allow the cryptocurrency market to be divided into user-defined subgroups for the tracking of price and volume changes. The Customised Index Builder will include varying parameters.

# Data Mining Architecture
## Data Mining Workers
## Machine Learning and Sentiment Analysis
## Svandis Database
# Blockchain Architecture
## ERC 725/735 Identity
## Decentralization of Research Community
## Data Signing and Screeners
## Consensus and Off Chain Settlement
## Token Economics
### SVN Token

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

# Conclusion

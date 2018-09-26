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
  * [Svandis DataMining App](#svandis-datamining-app)
  * [Certified Reviewer](#certified-reviewer)
  * [Data Analysis](#data-analysis)
  * [Marketplace](#marketplace)
  * [Svandis Indices](#svandis-indices)
  * [Indices Builder](#indices-builder)
- [Data Mining Architecture](#data-mining-architecture)
  * [Data Mining Workers](#data-mining-workers)
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
# Business Objective
The core business objective of this project is process data for Stocks, Options and Futures transactions that could not be delivered and hence failed settlement. This data can be transmitted in real-time or in batches. The goal is to effectively Ingest, Process, Cleanse, Enrich, Model, Serv and visualize the Failure To Deliver data for Financial Instruments using Microsoft Azure and Enterprise data technologies.

# What is Failure To Deliver and Settle Stocks, Options and Futures
Failure to deliver refers to a situation where one party in a trading contract does not deliver on their obligation. Such failures occur when a buyer (the party with a long position) does not have enough money to take delivery and pay for the transaction at settlement. A failure can also occur when the seller (the party with a short position) does not own all or any of the underlying assets required at settlement, and so cannot make the delivery.

Whenever a trade is made, both parties in the transaction are contractually obligated to transfer either cash or assets before the settlement date. Subsequently, if the transaction is not settled, one side of the transaction has failed to deliver. Failure to deliver can also occur if there is a technical problem in the settlement process carried out by the respective clearing house.

Failures to deliver may result from either a short or a long sale. There may be legitimate reasons for a failure to deliver. For example, human or mechanical errors or processing delays can result from transferring securities in physical certificate rather than book-entry form, thus causing a failure to deliver on a long sale within the normal three-day settlement period. A fail may also result from short selling. For example, market makers who sell short thinly traded, illiquid stock in response to customer demand may encounter difficulty in obtaining securities when the time for delivery arrives.

Subsequently, the pending failure to deliver creates what are called "phantom shares" in the marketplace, which may dilute the price of the underlying stock. In other words, the buyer on the other side of such trades may own shares, on paper, which do not actually exist.

# Chain Reactions of Failure to Deliver Events
Several potential problems occur when trades do not settle appropriately due to failure to deliver. Both equity and derivative markets can have a failure to deliver occurrence.

During the financial crisis of 2008, failures to deliver increased. Much the same as check kiting, where someone writes a check but has not yet secured the funds to cover it, sellers did not surrender securities sold on time. They delayed the process to buy securities at a lower price for delivery. Regulators still need to address this practice.

# Regulation SHO
Compliance with Regulation SHO began on January 3, 2005. Regulation SHO was adopted to update short sale regulation in light of numerous market developments since short sale regulation was first adopted in 1938 and to address concerns regarding persistent failures to deliver and potentially abusive “naked” short selling.

Due to continued concerns about failures to deliver, and to promote market stability and preserve investor confidence, the Commission has amended Regulation SHO several times since 2005 to eliminate certain exceptions, strengthen certain requirements and reintroduce the price test restriction.

As initially adopted, Regulation SHO included two major exceptions to the close-out requirement: the “grandfather” provision and the “options market maker” exception. Due to continued concerns about failures to deliver, and the fact that the Commission continued to observe certain securities with failure to deliver positions that were not being closed out under then existing requirements, in 2007 the Commission eliminated the “grandfather” provision and in 2008 the Commission eliminated the “options market maker” exception.

In addition, the Commission adopted temporary Rule 204T in 2008 and final Rule 204 in 2009, which strengthened further the close-out requirements of Regulation SHO by applying close-out requirements to failures to deliver resulting from sales of all equity securities and reducing the time-frame within which failures to deliver must be closed out.

In 2010, the Commission adopted Rule 201 of Regulation SHO. Rule 201 restricts the price at which short sales may be effected when a stock has experienced significant downward price pressure. Rule 201 is designed to prevent short selling, including potentially manipulative or abusive short selling, from driving down further the price of a security that has already experienced a significant intra-day price decline, and to facilitate the ability of long sellers to sell first upon such a decline.

# What you should know about the Datasets
This text file contains the date, CUSIP numbers, ticker symbols, issuer name, price, and total number of fails-to-deliver (i.e., the balance level outstanding) recorded in the National Securities Clearing Corporation's ("NSCC") Continuous Net Settlement (CNS) system aggregated over all NSCC members. Data includes all securities with a balance of total fails-to-deliver as of a particular settlement date. The data include fails-to-deliver in equity securities.

Each month is contained in two files. We cannot guarantee the accuracy of the data.

The price field includes the closing price of the security on the previous day as long as the price is available and is greater than one penny. When the price is not available or is less than a penny, the field is filled with a “.”. Even when prices are included in the data, we cannot guarantee that this price matches closing prices available from other sources.

The information in this file is raw data — data that are meant to be used as input to another program. The data items are provided as a "pipe delimited" text file. Although the file can be viewed in any program that accepts ASCII text (for example, a word processor), the data fields are best viewed when imported into a program that accepts delimited data, such as a spreadsheet or a statistical application. 

# Data Layout
![name-of-you-image](https://github.com/ketsha/Failure-To-Deliver-and-Settle-Financial-Instruments/blob/main/images/FTD-Dataset.jpg?raw=true)




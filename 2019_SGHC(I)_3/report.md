# B2C2 Ltd _v_ Quoine Pte Ltd  

<table id="info-table"><tbody><tr class="info-row"><td class="txt-label" style="padding: 4px 0px; white-space: nowrap" valign="top">Case Number</td><td class="txt-body">Suit No 7 of 2017</td></tr><tr class="info-row"><td class="txt-label" style="padding: 4px 0px; white-space: nowrap" valign="top">Decision Date</td><td class="txt-body">14 March 2019</td></tr><tr class="info-row"><td class="txt-label" style="padding: 4px 0px; white-space: nowrap" valign="top">Tribunal/Court</td><td class="txt-body">Singapore International Commercial Court</td></tr><tr class="info-row"><td class="txt-label" style="padding: 4px 0px; white-space: nowrap" valign="top">Coram</td><td class="txt-body">Simon Thorley IJ</td></tr><tr class="info-row"><td class="txt-label" style="padding: 4px 0px; white-space: nowrap" valign="top">Counsel Name(s)</td><td class="txt-body">Danny Ong, Sheila Ng and Jason Teo (Rajah &amp; Tann Singapore LLP) for the plaintiff; Paul Ong, Ivan Lim and Marrissa Karuna (Allen &amp; Gledhill LLP) for the defendant.</td></tr><tr class="info-row"><td class="txt-label" style="padding: 4px 0px; white-space: nowrap" valign="top">Parties</td><td class="txt-body">B2C2 Ltd — Quoine Pte Ltd</td></tr></tbody></table>

Contract – Breach

Contract – Mistake – Mistake of fact

Trusts – Breach of trust

14 March 2019

### Simon Thorley IJ:

## Introduction

1       This is an action for breach of contract and breach of trust. The Defendant (“Quoine”) is a Singapore-registered company which operates a currency exchange platform (the “Platform”) enabling third parties to trade virtual currencies for other virtual currencies or for fiat currencies such as Singapore or US dollars. The two virtual currencies (sometimes referred to as cryptocurrencies) involved in this action are Bitcoin (“BTC”) and Ethereum (“ETH”).

2       The Plaintiff (“B2C2”) is company registered in England and Wales trading _inter alia_ as an electronic market maker. As an electronic market maker, B2C2 provides liquidity on exchange platforms by actively buying or selling at the prices it quotes for virtual currency pairs, thereby generating trading revenue.

3       In recent years, there has been a significant growth in virtual currencies of which Bitcoin is perhaps the best known. They are not linked to any particular country nor regulated by any central monetary authority. They are traded for other virtual currencies or traditional currencies on computer networks such as the Platform.

4       B2C2’s claim arises out of an incident that occurred on the Platform on 19 April 2017 when, as a result of a series of events which I shall consider in more detail below, seven trades for the sale by the Plaintiff of ETH for BTC at an exchange rate of either 9.99999 or 10 BTC for 1 ETH were effected by the Platform. This was at a rate approximately 250 times the rate of about 0.04 BTC for 1 ETH which had been the previous going rate. The proceeds of the sale (3092.517116 BTC) were automatically credited to B2C2’s account by the platform and the corresponding amount of 309.2518 ETH was automatically debited from that account.[\[note: 1\]](#Ftn_1)

5       When Mr Mario Antonio Gomez Lozada (“Mr Lozada”), the Chief Technology Officer (“CTO”) of Quoine, became aware of the trades the following morning, he considered the exchange rate to be such a highly abnormal deviation from the previously going rate that the trades should be reversed. Accordingly, the seven trades were cancelled by Quoine and the debit and credit transactions were reversed.

6       B2C2 contends that Quoine had no contractual right unilaterally to cancel the trades once the orders had been effected and that its action in so doing was in breach of the version of the Terms and Conditions which regulated the trading relationship between Quoine and B2C2 at the material time. Additionally, B2C2 contends that Quoine holds the proceeds of B2C2’s account on trust for B2C2 and that the unilateral withdrawal of the BTC which had been credited to the account as a result of the trades was in breach of trust.

7       The writ was issued in the Singapore High Court on 18 May 2017, the Statement of Claim was served on that day and the Defence on 16 June 2017. With the agreement of the parties, the action was transferred to the Singapore International Commercial Court on 24 August 2017 and came on for trial before me on 21 November 2018.

8       There was an application for Summary Judgment under Order 14 of the Rules of Court (Cap 322, R 5, 2014 Rev Ed). I dismissed this application in a judgment delivered on 27 December 2017: see _B2C2 v Quoine Pte Ltd_ . Since then there has been further disclosure coupled with affidavit evidence and expert reports. As such, the actual facts of the case as detailed below are somewhat different from the facts as they appeared to be as at the time of that summary judgment application.

### Currency trading

9       There are a large number of trading platforms around the world and some of these provide for trading in virtual currencies. At a high level of generality, they operate in the same way. There are two types of traders, market makers and investor-traders. An investor-trader, as its name suggests, is a person who purchases a given commodity with a view to holding it for a period of time in the hope that its value increases so that it can be sold at a profit.

10     Market makers are more regular traders who provide liquidity to a given platform by quoting orders (both buy and sell orders) and seek to generate income by capturing what is known as the bid-ask spread. B2C2 is a market maker. Market makers will trade over a number of platforms (in B2C2’s case at the relevant time it was trading on 15) and do so by using sophisticated algorithmic trading software. At any one time a market maker may be seeking to sell a given currency on one exchange and buy it on another or, indeed, on the same exchange. The software monitors the trader’s position over all the platforms to regulate the exposure to any given currency and there will therefore be times when no buy quotes for a given currency are being placed on any of the platforms because the software has determined that the trader is over-exposed in that currency and is therefore, for the time being, only going to be a seller. The reverse can obviously also be the case.

11     Market makers can on occasions also be investor-traders but this action is concerned with B2C2’s activity as a market maker. Of more relevance is the fact that operators of currency exchange platforms can also trade as market makers on their own platform as Quoine did in the present case.

12     Whilst there are a number of ways in which an order can be placed on a platform, there are two types of orders that are material in this dispute:

(a)      _A market order_: This is an order which is to be executed immediately at the best available current market place. The buyer or seller (as the case may be) indicates what they wish to trade and the platform automatically identifies the best available trade in the opposite direction. At the time of order placement, the trader will not know precisely what the exchange rate will be, only that it will be the best available price offered on the Platform at the time by a trader seeking to trade in the opposite direction.

(b)      _A limit order_: This gives the trader greater control over the prices of a given trade but does not enable him to know when it will be executed. A limit order sets either the maximum price at which he is willing to buy or the minimum price at which he is willing to sell. If and when that price is reached, his order will be fulfilled. Market makers trade exclusively in limit orders.

13     As Mr Maxime Boonen (“Mr Boonen”), a director of B2C2, explained in his affidavit of evidence-in-chief (“AEIC”), B2C2 acted as a market maker on the Platform in the following manner:[\[note: 2\]](#Ftn_2)

12    As with other exchange platforms on which B2C2 conducts market making, the entire trading process is automated 24/7 through its algorithmic trading software (“**Trading Software**”), which I helped to develop as B2C2’s co-founder. Human traders are almost never involved in the trading process. Human involvement is in almost all cases limited to tasks like monitoring, IT maintenance and adjusting the parameters of the Trading Software from time to time. In April 2017, the only human traders at the time were the two founders of B2C2, including myself, and we would only monitor the trades during business hours i.e. 8 am to 6 pm Greenwich Mean Time (“**GMT**”)).

13    As a market maker, B2C2 endeavours to quote limit orders in both directions, continuously if possible, and generate income by capturing a bid-ask spread. The process of placing a limit order on the Platform can be briefly summarised as follows:

13.1   The Trading Software requests market data from Quoine’s API. In particular, the Trading Software requests, in respect of a given product, the Platform’s current order book, B2C2’s account balances with the Platform, and any current live orders B2C2 may have on the Platform.

13.2   The Trading Software determines what orders ought to be placed (and the price, size, and side), if any, based on the aforementioned data as well as other factors. The price is determined based on price formulation strategy that seeks to improve on the available prices at the top of the order book by a small amount, subject to a minimum bid-ask spread.

13.3   The Trading Software submits the orders via authenticated API messages, through which instructions to cancel or amend orders, and to retrieve the status of orders or trades and balances for each asset, can be sent to the Platform.

14    Unless a specific market making contract exists between the market maker and the Platform (which was not the case between B2C2 and Quoine), a market maker is considered like any other user of the Platform and its orders are therefore not treated any differently than other users’ orders. After an order is submitted by the Trading Software, on condition that it is not first rejected by the Platform (for example, if the user’s balance is too low), it is inserted into the Platform’s order book at the relevant price level and either (i) immediately matched with the best asks (i.e. orders to sell) (in the case of a buy order) or the best bids (i.e. orders to buy) (in the case of a sell order) up to the price quoted in the order, or (ii) left standing in the order book if it does not immediately match against an opposite order, until it is cancelled or matched with another order at a later time. When an order is filled, a completed trade arises and the relevant virtual currency ‘bought’ will be deposited by Quoine into the Account, whilst the relevant currency ‘sold’ will be deducted from the Account. The prevailing balance maintained under the Account is reflected on the user interface of the Platform, and **immediately updated** upon completion of a trade.

\[emphasis in bold in original\]

### The Platform

14     Quoine was cofounded by Mr Lozada together with Mr Mike Kayamori in 2014. It operates platforms in Japan and in Singapore. The Platform functions in the following way:[\[note: 3\]](#Ftn_3)

The Platform uses order books to record orders from buyers and sellers for each pair of currencies being traded on the Platform. An order book is essentially an electronic ledger containing all orders to buy or sell a virtual currency in exchange for another currency. The available buy and sell orders in the order book are displayed on the right hand side of the Trading Dashboard: all available buy orders are shown in the “Buys” section and all available sell orders are shown in the “Sells” section of the Trading Dashboard.

At the centre of the Trading Dashboard is a price chart which is designed to assist a trader in determining the best fair market price at which to buy or sell a particular currency for another currency. This price chart displays real-time pricing data for the relevant currency pair based on the (i) the real-time prices of completed trades for the currency pair executed on the Platform; and (ii) the real-time prices of completed trades for the currency pair executed on several other major cryptocurrency exchanges …

15     At the relevant time, Quoine offered three types of trading: spot trading (where trades are settled instantly), margin trading (which allows trading with borrowed funds) and futures trading (which involves both the buyer and seller agreeing to sell at a future date at a given price). Quoine no longer offers futures trading.

16     Margin trading is central to this dispute and therefore needs to be explained more fully. A trader may trade on the Platform using borrowed funds, borrowed either from Quoine or from other users who offer their funds to be used for peer-to-peer loans. The assets in the margin trader’s account serve as collateral for the loans. In the event that the collateral in the account falls below a pre-determined percentage of the loan, the Platform’s system takes action by making a margin call and closing out all or part of the trader’s positions to prevent further loss and to seek to avoid a default.

17     The system constantly monitors the margin trader’s profit and loss and is designed to force-close positions if it detects that the trader cannot pay back his loans from its collateral. These force-closures are automatically executed by the system as market orders to buy or sell the relevant commodity at the best available price. The margin trader does not have to be contacted in advance and may not know that the force-closure is going to occur. It certainly will not know the precise price at which the market order will be executed.

18     Quoine also acts on the Platform as a market maker “to provide liquidity and depth to the order books, minimise volatility in the marketplace and ensure that there is a continuous two-sided market on the Platform”.[\[note: 4\]](#Ftn_4) It did so using what is known as a Quoter Program in the following manner:

Such orders were generated and placed on the Platform by Quoine’s quoter software program, which was responsible for retrieving external market price information which the program would then use to create new orders for market making purposes. As of April 2017, the quoter program retrieved such external price information from the following external cryptocurrency exchanges: (i) Bitfinex; (ii) Bitstamp; (iii) bitFlyer; and (iv) itBit.

## The relationship between Quoine and B2C2

19     B2C2 was set up by Mr Boonen and a Mr Molendini. Mr Boonen was responsible for creating the vast majority of the algorithmic trading software which I accept is the life blood of B2C2’s business and therefore highly confidential. It has been necessary during the course of this action for steps to be taken to seek to ensure the maintenance of that confidentiality whilst also ensuring a fair and open trial. The way in which this was done and the reasons therefor are set out in an earlier judgment in this action: _B2C2 Ltd v Quoine Pte Ltd_ .

20     B2C2 opened an account on the Platform on 28 June 2015. This was done electronically online by Mr Boonen and Mr Boonen was asked to confirm that B2C2 accepted Quoine’s Terms and Conditions which Mr Boonen did.

21     Mr Boonen gave evidence that initially he had some concerns about trading on the Platform but following some reassurance from Mr Lozada in June 2016 and the provision of a line of credit from Quoine to B2C2, B2C2 commenced full trading on the Platform in January 2017. A good deal of written evidence and some cross-examination was directed to the reasons underlying those concerns and how and why they were alleviated but I am satisfied that this has no bearing on the matters in dispute.

## The Agreement and the Risk Disclosure Notice

22     The Terms and Conditions (“the Agreement”) which were on the Defendant’s website in June 2015 when B2C2 opened its account were stated to have been “Last updated April 2014”.

23     A great deal turns on the terms of the Agreement and its relationship with other documents that were on the website at the date of the incident. It is therefore included in full as Annex 1 to this judgment. The most important provisions are as follows:

TERMS AND CONDITIONS

This Agreement (the "Agreement"), effective upon the date of electronic acceptance (the "Effective Date"), pertains to the use of Quoine (the "Platform"), an Internet application fully owned by Quoine Pte. Ltd. (The "Company"), a Singapore based corporation with registration number 201414068E. This agreement is entered into by and between Quoine Pte.Ltd., and the user of Quoine ("User" or "Member") (each herein referred to individually as a "Party", or collectively as the "Parties"). In consideration of the covenants and conditions contained herein, the Parties hereby agree to the following terms and conditions:

General Terms

Quoine is a platform that provides services that allow the exchange of virtual currencies such as Bitcoin for fiat currencies. If you wish register \[_sic_\], engage in transactions on Quoine (The Platform), please fully read and understand the terms and conditions that follow.

This is a legal agreement (“Agreement”) between you and Quoine Pte. Ltd., which will apply to you regarding any and all services offered by or acquired (the “Services”) through the Platform.

This Agreement sets forth the terms and conditions governing the access and use of the Platform. This Agreement may be changed at any time by the Company. It is the responsibility of the User to keep himself/herself updated with the current version of the Agreement. Users and Members waive any claim regarding this issue. This Agreement may only be amended with the express consent of the Company. Unless otherwise explicitly stated, the Terms will continue to apply even after termination of your membership to the Platform. If any provision of this Agreement is held invalid, the remainder of this Agreement shall continue in full force and effect.

Legal Jurisdiction

You expressly agree that any claim or dispute arising from your use of our website and/or our services will be governed by the laws of Singapore without regard to the conflict of law provisions thereof. You further agree that any such claims or disputes shall be resolved in Singapore courts, and you agree to be subject to the personal jurisdiction in, and the exclusive venue of, such courts and waive any objection to such jurisdiction and venue for the purpose of litigating any such claim or dispute.

…

Trading & Order Execution

Only registered users or Members are allowed to buy, sell and use the services provided by the Platform. The exchange functions of The Platform will fill in orders at the best possible available market price. Note that as markets move continuously, the prices displayed on user interfaces, on our web app or on mobile apps are in no way guaranteed. The Platform, however, has been designed to allow members to fill at best possible prices and in a timely manner. Nevertheless the Company will not be liable under any circumstances for the consequences of any delay in order filling or failure to deliver or perform.

Furthermore, once an order is filled, you are notified via the Platform and such an action is irreversible.

…

Representations and Warranties

As a Member or User, you agree to the following:

…

h.

… You agree that the Company reserves the right to change any of the terms, rights, obligations, privileges or institute new charges for access to or continued use of services at any time, with or without providing notice of such change. You are responsible for reviewing the information and terms of usage as may be posted from time to time. Continued use of the services or non-termination of your membership after changes are posted or emailed constitutes your acceptance or deemed acceptance of the terms as modified.

\[emphasis added\]

24     Additionally, Quoine asserts that a Risk Disclosure Statement was uploaded onto the website on 22 March 2017. Whilst this was not admitted by B2C2, it was not seriously challenged and I accept the evidence demonstrating that it was. This document figures in one of Quoine’s proposed defences and, again, it is necessary to see the passages relied upon in context so this document forms Annex 2 to this Judgment. I shall revert to it later.

## The incident on 19 April 2017

25     Put in very simple terms, late in the evening of 19 April 2017 (all times are GMT/UTC), two margin traders, Pulsar Trading Capital and Mr Yu Tomita (“Pulsar” and “Mr Tomita” respectively, and “the Counterparties” collectively) were trading in the ETH/BTC market using ETH borrowed from Quoine. The Platform was alerted to the fact that both Counterparties’ collateral had fallen below the maintenance margins. The Platform thus automatically placed market orders to sell the Counterparties’ assets at the best available prices to repay the ETH loans. Some of those orders were met by limit orders which were subsequently placed on the Platform by B2C2’s trading software at the exchange rate of about 10 BTC to 1 ETH. There was no human intervention in this. It was all done by computers acting in accordance with their respective programs. Further, the placing of the orders by B2C2 was not the cause of the Counterparties’ collateral falling below the maintenance margins. This had occurred before the orders were placed on the order book.

26     As indicated above, Quoine reversed these orders on 20 April 2017, the next day. The background to these trades and the way in which they came to be carried out is complex and has been the subject of both fact evidence and expert reports.

**The Witnesses**

27     Evidence was given by Mr Boonen for B2C2 and by Mr Lozada and Mr Tseung, a co-founder of Pulsar, for Quoine. Expert evidence was given by Mr Alexis Atkinson (“Mr Atkinson”) on behalf of B2C2 and Mr Vikram Kapoor (“Mr Kapoor”) on behalf of Quoine.

28     Mr Boonen received a Bachelor of Engineering degree from the University of Louvain in Belgium and then a Master’s degree in Financial Economics from the University of Oxford in England. He was first employed by Google where he learned about electronic trading and then worked in the fixed income department of Goldman Sachs in London. He left Goldman Sachs in May 2015 to found B2C2.

29     Mr Boonen was well-informed as to the trading environment in which B2C2 operated and was plainly a highly experienced computer programmer who had successfully designed B2C2’s trading software. In the witness box, he was both reasoned and precise and explained technical matters with clarity. It became apparent in cross-examination that an aspect of his AEIC was overstated but in the event nothing turned on that. I found him to be an honest and straightforward witness who gave reliable evidence, even if, on occasions, his desire to be precise led to overlong answers. His demeanour as a witness was not the subject of any general criticism in Quoine’s closing submissions but it was suggested that his evidence was unbelievable in certain respects. I shall assess the weight that can be placed on aspects of Mr Boonen’s evidence later.

30     Mr Lozada has both an undergraduate and Master’s Degree in Computer Sciences from the University of Kansas, USA. Initially he was employed in Tokyo by Fusions Systems Japan which provided financial software for banks. He then spent 10 years with Merrill Lynch ending up as CTO for the fixed income business in Japan. He then moved to Credit Suisse in 2009 or 2010 where he was both CTO for the fixed income business and Chief Information Officer for the Japan business. He left Credit Suisse in 2013 to cofound Quoine. Mr Lozada was well informed as to Quoine’s trading environment and was an experienced computer programmer having designed the Platform’s system.

31     In B2C2’s closing submissions it was submitted that Mr Lozada was very unconvincing and far from forthcoming so that his evidence should be viewed with extreme circumspection. A number of aspects of his evidence were brought to my attention to support this assertion. These related in part to evidence which displayed an element of uncertainty in his overall evidence and in part to evidence given at trial which was inconsistent with earlier evidence given on the application for summary judgment. I have considered carefully each of these assertions as, at the time he gave his evidence, I perceived him to be an honest and straightforward witness. I consider that, at best, it could be said that Mr Lozada did not investigate the circumstances surrounding the incident of 19 April in sufficient detail before giving the evidence he did on the summary judgment application. But I am satisfied that this was not done with any intention to mislead the Court. The facts are complex and it is not surprising that they became clearer in the course of time. Equally where there were passages in his evidence which constituted assertions as to the intentions of B2C2, these were, I consider, honestly held beliefs. The areas of uncertainty in his evidence were due to imperfect recollection rather than any intention to deceive. All in all, I see no reason to alter my original perception that he was an honest and straightforward witness who was particularly frank in identifying the areas where the Quoine system had proved to be inadequate and the steps that he had taken to rectify this.

32     The final witness of fact was Mr Tseung of Pulsar. Once certain passages of his evidence were ruled to be inadmissible, the Plaintiff no longer sought to cross-examine him. Notwithstanding this, in its written closing, B2C2 asserted that Mr Tseung’s evidence was self-serving. But this was a criticism directed to the evidence which had been struck out and to Mr Tseung’s statements relating to the validity of the seven trades, which is a matter for me and not him.

33     Mr Atkinson has a BSc (Hons) in Mathematics and Statistics from the University of Sheffield, UK, and since graduating has been involved in designing and developing financial trading systems. In particular, whilst employed by Radobank International from 2008 to 2015, he was responsible for the development, maintenance and support of that bank’s EMarkets trading architecture and features, which included algorithmic market making and trading engines. He left Radobank in May 2105 to work for Nex Markets (now part of CME Group). Nex Markets provides electronic execution platforms to the financial trading sector. He is currently Head of Order Driven Markets where he is responsible for foreign exchange platforms. Mr Atkinson had not given expert evidence before.

34     Mr Kapoor has a BSc in Engineering from the University of Pune, India, and an MBA from the State University of New York at Buffalo, USA. He is a senior managing director at Ankura in New York specialising in quantitative finance valuation and data analytics. His work includes analyses of algorithmic trading and trade routing by financial institutions. He has given expert evidence on a number of occasions both in the US courts and in arbitrations.

35     Both Mr Atkinson and Mr Kapoor are well qualified to give expert evidence on the defined issues. Both spent a considerable amount of time reviewing B2C2’s software and presented their reports on the issues in a focussed and helpful way. They were, however, very different witnesses. Mr Atkinson was significantly more diffident and less articulate than Mr Kapoor. He was more hesitant in giving his answers compared to the more polished approach of Mr Kapoor.

36     In its closing submissions, Quoine questioned whether Mr Atkinson acted as independently or objectively as he should have done as an expert witness.[\[note: 5\]](#Ftn_5) Reliance was placed on three matters. First, in his first report at paragraph 78 he gave evidence that he had been present, in his capacity as Head of Order Driven Markets at Nex, at a small number of meetings with B2C2 before agreeing to act as an expert witness in this action. In cross-examination he plainly had little or no recollection of the number or substance of such meetings. I do not consider that he was being evasive in relation to his past dealings with B2C2 and previous contact with an expert witness does not prevent him giving evidence on that person’s behalf. It is a matter that should be taken into account in assessing whether the witness has lost a sense of perspective in preparing his expert report or in giving oral evidence. I do not consider that Mr Atkinson erred in this respect.

37     Secondly I was invited to place adverse weight on Mr Atkinson’s evidence because he had failed to sign a copy of a confidentiality undertaking supplied to him by B2C2. Plainly he should have done that and B2C2 should have chased him for a signature. But I do not see how this failure can be said to impact upon the evidence that he did give.

38     Finally, in the course of trial, when Mr Atkinson was in the witness box, he sought to introduce two further documents prepared by him. This was improper but understandable as he had had to deal with Mr Kapoor’s report in a short period of time. He explained that he was seeking to supplement his second report with these documents. I refused to allow one of them to be adduced in evidence but allowed the other, on the basis that, if necessary, Mr Atkinson could be recalled to be cross-examined on matters to which this document related later in the proceedings.[\[note: 6\]](#Ftn_6) In the event no application was made for Mr Atkinson to be recalled. I consider that this incident was but part of the normal vicissitudes of litigation and does not reflect adversely on Mr Atkinson’s evidence.

39     B2C2 levelled a number of criticisms at Mr Kapoor. Mr Kapoor was responding to Mr Atkinson’s first report which, in very simple terms, supported the assertion the B2C2’s software had been designed for wholly defensive purposes. It was plain that Mr Kapoor had been instructed to focus particularly on aspects of the software that might serve to identify the mindset of the writer as not being limited to defensive purposes. This was, as will become plain, a fundamental part of Quoine’s case. He cannot be criticised for doing this nor for highlighting aspects of the software which appeared to be indicative to him of an intention on B2C2’s part to program its software to take advantage of errors of others and, in the extreme, to manipulate the market. He raised technical matters which it was necessary for B2C2 to respond to and which needed to be resolved.

40     However, in two respects he strayed beyond permissible limits. First, he sought to draw his own conclusions as to the intentions of the writer of the software which is a matter for me and not for him and formed part of the evidence which I was asked to strike out. Conclusory assertions of this sort are not unusual in expert reports, particularly from experts more familiar in giving evidence in US courts and tribunals. It is no doubt what he was instructed to do and doing so does not add to or subtract from the technical evidence that he gave on the issues he was asked to address.

41     Secondly, he gave evidence on matters that were not within the scope of the issues on which expert evidence was to be adduced. Again, this was the subject of the application to strike out and I do not doubt that this is what he was asked to do. There is, to my mind, nothing untoward in this and it does not detract from the technical evidence that Mr Kapoor gave on the relevant issues.

42     All in all, I am satisfied that both experts were qualified to give the technical evidence that they did. They did so in support of their respective client’s cases but in an informed and coherent manner. At all times they were doing their best to assist the court and I am grateful to them for their patience in approaching the issues and in amplifying their reasoning in their oral evidence. It will be for me to assess the weight that I place on each expert’s evidence on these technical matters but I do not accept that either witness’ evidence should be discounted on the basis of the matters considered above.

## Inadmissible evidence

43     Prior to trial, both parties served notices identifying passages in the AEICs and expert reports of the other party which were contended to be inadmissible. Sensibly, counsel agreed that the question of admissibility should not be considered before the witnesses gave evidence but should be left to closing submissions.

44     However, in advance of the trial, B2C2 did issue a summons to strike out certain matters arising in the affidavits of Mr Lozada and Mr Tseung and in Mr Kapoor’s expert report. This was initially heard in chambers but by agreement of the parties was adjourned into court to be heard at a convenient moment during the trial.

45     The Court directed that so far as the application sought to strike out parts of the affidavits of the witnesses of fact, this should be determined at the outset of the trial with the objections to Mr Kapoor’s report being determined at a later time.

46     I therefore heard argument on the fact witnesses. I indicated at the conclusion of that argument that three paragraphs would be struck out and that I would give my reasons for so doing as part of the Judgment after trial. These are my reasons.

47     The paragraphs in question were paragraph 28 of Mr Lozada’s first AEIC and paragraphs 9 and 10 of Mr Tseung’s AEIC. These state:

\[From Mr Lozada’s AEIC\]

28    In the circumstances, I believe that Quoine acted properly in cancelling the Erroneous Trades and was entitled to do so with the view to maintaining a fair and orderly marketplace. Indeed, I consider it to be common practice for trading exchanges to deal with clearly erroneous transactions by cancelling them if it is in the best interests of the marketplace to do so. The major stock exchanges in the world, such as the Singapore Stock Exchange (“**SGX-ST**”), Nasdaq, the New York Stock Exchange (“**NYSE**”) and the London Stock Exchange (“**LSE**”), have the ability to cancel or reverse erroneous transactions. Similarly, several of the major cryptocurrency exchanges, including Coinbase, Kraken, Gemini and Poloniex, have the ability to reverse or cancel transactions which are clearly erroneous and/or for other reasons at their own discretion. In this connection, annexed hereto and collectively marked as “**MAGL-38**” are copies of the following documents: (a) the relevant rules of the SGX-ST; (b) the relevant rules of Nasdaq; (c) Rule 128 of the NYSE’s Exchange Rules; (d) the relevant trading rules of the LSE; (e) Coinbase’s User Agreement (see Clause 7.1); (f) Kraken’s Terms of Service (see Clause 5.3); (g) Gemini’s User Agreement (see the section entitled “_Clearly Erroneous Transaction Policy_”); and (h) Poloniex’s Terms of Use (see Clause 16).

\[From Mr Tseung’s AEIC\]

9    It is also relevant to mention that, based on my experience as a trader, it is regular practice for trading exchanges to cancel clearly erroneous trades, including trades that result from a human error or computer malfunction (such as the Erroneous Trades in the present case). The major stock exchanges of the world (for example, the Singapore Stock Exchange and New York Stock Exchange) and several major cryptocurrency exchanges that I know of (for example, Coinbase and Kraken) operate on the basis of rules or policies which allow for the cancellation of clearly erroneous transactions. Indeed, it is important that trading exchanges be allowed to cancel clearly erroneous trades as such trades could have a very disruptive or negative impact on the marketplace.

10    Finally, I would venture to say that, assuming that B2C2’s Orders were placed by B2C2’s algorithmic trading systems, it is possible that B2C2 had programmed its trading systems to place such abnormally priced orders in the event that there is a bug or glitch on the trading platform which could result in such abnormal orders being executed. In particular, B2C2 could have programmed its systems to place orders with abnormally high prices (which would never have been executed under normal market conditions) upon detecting an abnormal situation of low or zero liquidity on the trading platform. This may explain why B2C2’s Orders were placed at the ridiculously high price of 9.99999 BTC or 10 BTC for 1 ETH when there were no other sell orders on the ETH/BTC order book as a result of a system glitch. Based on my experience in the field of algorithmic trading, it is quite possible to program a trading system to take advantage of a system glitch or abnormal market conditions in this manner.

48     It is convenient to deal with paragraph 28 of Mr Lozada’s first AEIC and paragraph 9 of Mr Tseung’s AEIC together.

49     It will be seen that these paragraphs relate to an alleged common practice for trading exchanges to cancel clearly erroneous transactions. Mr Danny Ong for B2C2 contended that an investigation into how other exchanges approached the question of dealing with erroneous transactions was irrelevant to the issues arising on the pleadings in this action. He drew my attention to the fact that there is no express term in the Agreement providing for such cancellation and that the plea of an implied term to this effect contained in paragraph 19(d) of the Defence (Amendment No 4) (“the Defence”) was solely on the basis of giving business efficacy to the agreement and to give effect to the intentions of the parties. This did not, he submitted, provide for the implication of such a term on the basis that there was a common practice in the trade for this to be done. Further, he claimed that in any event the evidence constituted impermissible opinion evidence of what the witnesses perceived to be common practice. If the evidence was allowed to stand, it would be necessary for B2C2 to adduce further evidence to rebut the contention.

50     Mr Paul Ong for Quoine submitted, first, that the correct course was to deal with the question of admissibility by way of closing submissions as was being done in relation to the other disputed evidence. Secondly, whilst he accepted that there was no plea of common practice, he said that the evidence was relevant to demonstrate that this was a term to which the parties would have agreed had it been posed by the notional hypothetical onlooker at the time the Agreement was made. He said that if this was the policy of other trading platforms this would be an indication that it was more likely that the parties would have agreed. Thirdly, he contended that this was not impermissible opinion evidence.

51     Whilst I accept the third of these submissions, the agreements that are said to evidence such a common practice contain an express term to that effect; there is therefore no need for any implied term. There is no such express term in the Agreement. The pleading contends that one should be implied to give business efficacy to the Agreement. The mere fact that the parties might have agreed such a term had it been proposed is, of itself, insufficient for the term to be implied. If the needs of business efficacy do not require the implication of a term, it will not be implied even if, had it been proposed, it might have been accepted. I am therefore satisfied that the evidence contained in paragraph 28 of Mr Lozada’s first AEIC and paragraph 9 of Mr Tseung’s AEIC is irrelevant to any pleaded issue in this case.

52     Whilst there is often merit in adopting the course of leaving questions of admissibility to be discussed during closing submissions, equally there is merit in a clear case of striking out inadmissible evidence at an early stage if this is going to avoid the possibility of further evidence and/or cross-examination on the irrelevant material. I consider this to be a clear case.

53     Paragraph 10 of Mr Tseung’s AEIC falls into a different category. It is plainly speculation on the part of Mr Tseung as to why B2C2 programmed its trading systems in the way it did. Speculation by a witness of fact as to why another entity might have done something is of no assistance to the Court and time should not be spent at trial cross-examining Mr Tseung on the basis for his speculation.

54     Accordingly, I ordered that the three paragraphs should be struck out.

55     At a later stage in the trial before the expert witnesses were to be cross-examined, I heard submissions on the admissibility of the passages in Mr Kapoor’s expert report to which objection was taken. There was an earlier hearing in this case on 20 February 2018 at which the question of expert evidence was discussed. I made it clear that in a case of this nature, expert evidence would only be allowed in relation to specific issues which were to be determined by the parties and approved by the Court. The parties proposed a number of possible avenues of expert evidence. In particular, the Defendant proposed that there should be expert evidence on market manipulation. Having heard submissions, I directed that expert reports should be directed to (and limited to) certain specific issues concerned with the working of the B2C2’s trading algorithm and that if the parties wished at a later date to adduce expert evidence on different issues, they should make an application for permission in advance of doing so.

56     The specific issues were drafted by the parties and settled by the Court. They were as follows:

In placing each of the “Orders” as defined in paragraph 5 of the Statement of Claim on Quoine’s platform on 19 April 2017 at the limit price of either 9.99999 BTC or 10 BTC for 1 ETH:

General Issue

1\. What trading instructions, parameters, criteria, and strategies were used, and what factors were taken into account and relied upon, by B2C2’s automated and algorithmic trading system or software (the “**Trading Software**”). In particular, how did the Trading Software determine the limit price of either 9.99999 BTC or 10 BTC for 1 ETH for each of the Orders.

Specific Issues falling within the General Issue

2\. Was the Trading Software able to determine and did it determine in placing each of these Orders that:

A.    There was a situation of low and/or zero liquidity on the Platform;

B.    The placement of the Orders would or might cause the Platform to recalculate the open leveraged positions of the Defendant’s customers, based on the quoted prices of the Orders.

C.    Such recalculation would or might lead to and result in:

i.    The Platform force-closing such customers’ open short positions;

ii.    The Platform effecting such force- closure by executing forced stop orders on such customers’ open short positions; and

iii.   The Platform matching such forced stop orders with the Orders.

iv.    The Platform was affected by the technical glitch referred to in Paragraph 13 of the Defence (Amendment No. 3).

If so, how and to what extent, if any, were any of the above factors instrumental in determining the limit price for the Orders.

57     It was directed that the expert reports should be prepared sequentially which resulted in the first report of Mr Atkinson being sworn on 28 August 2018 and Mr Kapoor’s in reply being sworn on 5 November 2018. Mr Atkinson’s report addresses the issues but Mr Kapoor’s report went somewhat further and sought to give expert evidence on two other matters. First, he concluded on the basis of his review of the B2C2’s computer programs that the “deep quotes” set by the algorithm (_ie_, the price of 10 BTC to 1 ETH) were not merely a defensive measure (of which more below) but constituted what are known as “stub quotes”, a practice which Mr Kapoor opined constituted impermissible market manipulation which was contrary to some regulatory requirements. Secondly, he reviewed the Platform’s software and the Quoter Program and gave evidence on how the Platform calculated the position of margin traders and expressed the view that if the Quoter Program had been working properly there would not have been a margin call.

58     As regards the first aspect (the stub quotes issue), Mr Danny Ong contended that the evidence should be struck out primarily on the basis that it was not directed to the questions that the experts had been asked to address and that no application had been made for different issues to be the subject of expert evidence. Secondly, he said that Mr Kapoor was not qualified to give evidence on what was essentially a regulatory matter. Thirdly, the evidence went to an unpleaded issue of stub quotes. Lastly, the issue of market manipulation was a matter for the Court and not for a witness. He indicated that if the evidence was admitted it would be necessary for the Plaintiff to instruct a witness to respond to Mr Kapoor’s assertion.

59     Mr Paul Ong contended that Mr Kapoor’s qualifications (or lack of them) were not a ground for striking out the evidence. His degree of competence to give the evidence went to weight, not to admissibility. To a certain extent I agree with this unless it is apparent from the witness’ CV that he has no relevant qualifications. Had this been the only objection I would have allowed him to be cross-examined on his credentials and then ruled on admissibility.

60     He went on to submit that the evidence was relevant to understanding the nature of the strategy underlying the trading software, to demonstrate that it was not merely a defensive measure and had, as he put it, the more sinister objective of market manipulation. This had been pleaded in general terms and, in particular, was relevant to the issue of unconscionability under unilateral mistake in equity.

61     On the second aspect (the Platform and Quoter Program issue), the primary argument related to the fact that no issue concerning those programs had been included in the list of issues and that the code for the programs had not been disclosed or considered by the Plaintiff. It was therefore wrong at this late stage for the issue to be canvassed any further than had been done in the AEICs of the witnesses of fact.

62     The starting point on the stub quotes issue is that I was satisfied that justice could be done in this case without having expert evidence. The two experts have put in evidence saying how the B2C2 system works and why it works. Having heard all the evidence, including the factual evidence, it will then for me to draw the conclusion as to what were the motives behind B2C2's writing of the program in the way it was written. On the basis of that conclusion, I shall have to consider the question of unconscionability under Singapore law. In order to do this, it is not also necessary to reach a conclusion as to whether the writing of the program was or was not in breach of some particular regulatory requirements and my assessment on those motives cannot be delegated to an expert witness. Accordingly, I did not consider that I needed the assistance of experts in regulatory matters.

63     However, even if that was not the case, I concluded that it would be quite wrong to admit expert evidence on a new issue at this late stage. As I made clear at the earlier hearing, I consider that, in cases such as this, the expert evidence ought to be directed and only directed to specific defined issues. This enables the reports to be filed without unforeseen expert evidence being adduced which is likely to lead to delay and expense in dealing with that evidence in subsequent reports.

64     This is precisely what would happen in this case. Mr Paul Ong suggested that the stub quote issue could be hived off, B2C2 could adduce expert evidence in reply to Mr Kapoor and the matter could then be addressed at a subsequent hearing. I accept that Mr Kapoor had to prepare his report under certain time pressures and that his report contains material which he relies on as justifying the stub quote assertion, but this does not excuse the fact that Quoine could have sought leave to adduce expert evidence on the issue of market manipulation in advance of the service of his report.

65     For both these reasons, I ordered that the passages relating to the stub quotes issue should be struck out.

66     On the second issue, again I was satisfied that justice could be done without going into detail on Quoine’s programs. There is no dispute that the Platform did determine that the Counterparties were in breach of their respective margin limits nor is there a dispute as to when this happened. The reason why this happened was explained by Mr Lozada and it is not necessary to go into any greater detail as to the steps that the code goes through to reach this conclusion.

67     Equally, there is no dispute that the Quoter Program was inoperative after 13 April. Whether or not the consequent lack of liquidity would have occurred had it been operative is irrelevant.

68     Moreover, for the same reasons as are given above, I considered that it would be wrong to admit expert evidence on issues not covered in the current list of issues. Accordingly, I ordered that the passages relating to these issues should be struck out.

## The facts

69     I propose to consider the facts under the following headings:

(a)     The Quoter Program;

(b)     The Platform and the Margin Calls;

(c)     The B2C2 Trading Software; and

(d)     The mindset of Mr Boonen.

70     Many of the facts are either common ground or not in dispute. In so far as any matter was the subject of dispute, I have reached an assessment on the basis of the balance of probabilities.

### The Quoter Program

71     The causes of the incident on 19 April 2017 have their origin in some work done by Quoine on 13 April when changes were made to some login passwords for several critical systems on the Platform. This was done for security reasons. Due to an oversight, certain necessary changes to the Platform’s Quoter Program were not implemented.

72     The Quoter Program is responsible for retrieving external market prices from other exchanges which are then used to create new orders to be placed by Quoine on the Platform for market making purposes and to create liquidity. The Quoter Program is personal to Quoine and information generated by it is not available to other users of the Platform. The effect of the oversight was that it could not access data from those other exchanges and accordingly it became inoperative and stopped creating new ETH/BTC orders on the Platform. Unfortunately, this did not generate what is known as an exception message which would have alerted Quoine to the oversight as the notification flag for such messages had been disabled. Quoine did not become aware of the oversight until after the events of 19 April.

### The Platform and the Margin Calls

73     At this time, Quoine was the principal market maker on the Platform. Mr Lozada estimated that it was responsible for around 98% of market making trades. When the Quoter Program became inoperative, there were a number of orders previously on the Platform placed by Quoine and others which continued to be available for trading purposes. During the period between 13 and 19 April 2017 however, the volume of trading on the ETH/BTC order book was low and it was not until 19 April 2017 that the gradual depletion of the pre-existing orders and orders placed by traders other than Quoine, including B2C2, reached a level which Mr Lozada described as being “abnormally thin” which precipitated a number of events.[\[note: 7\]](#Ftn_7)

74     So far as concerns the Platform, it had the effect of causing the mechanism for calculating the margin traders’ positions to detect that Pulsar’s and Mr Tomita’s accounts were in what is known as “Margin Sell-out Position” which served to trigger the margin calls resulting in the placement of the market orders to buy ETH at the best available market price. This occurred, in the case of Pulsar at 11.31pm and in the case of Mr Tomita at 11.53pm. This can be seen on a print out of the force-closed orders executed on 19 April 2017[\[note: 8\]](#Ftn_8) (trader ID 5539 is Pulsar and trader ID 30742 is Mr Tomita). A copy of the print out forms Annex 3.

75     As Mr Lozada made clear in his evidence, the force-closed transactions were carried out notwithstanding that the available BTC balances in Pulsar and Tomita’s accounts were insufficient to meet B2C2’s orders at the limit price quoted by B2C2. This would not have happened if the Platform had a program to check whether there were sufficient available assets. There was however no such program at the time which Mr Lozada accepted in the course of cross-examination was the result of poor design:[\[note: 9\]](#Ftn_9)

<table align="left" cellpadding="0" cellspacing="0" class="Judg-2" frame="none" pgwide="1"><colgroup><col width="20.62%"> <col width="79.38%"> </colgroup><tbody><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">A:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">In this case, what happened is the system, because of poor design -- and I will acknowledge that -- was matching a forced-closed order resulting from a margin trade with a spot order placed by the plaintiff. So there were two different types of orders.</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">&nbsp;</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Under normal circumstances, if the prices are within the norm, they would have been matched properly, but in this case, because it's forced-closed, the system just forced the transfer of non-existing assets into the plaintiff's account which resulted in a negative balance in the other account, in a positive balance of non-existent Bitcoin in the plaintiff’s account.</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Q:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Thank you, Mr Lozada. As at April 2017, on the 19th, the system had matched B2C2's orders with the forced-closed orders as designed; correct?</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">A:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">What do you mean, "as designed"? You mean as intended or –</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Q:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Yes, as designed.</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">A:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Can I explain something here?</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Court:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Please.</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">A:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">So when you build -- these are really complex platforms, by the way, really complex systems, highly sophisticated. A lot of things can go wrong. It is very difficult to -- and that's why we have bugs in systems, you know, computers crash. Sometimes it's very difficult to foresee all the different things that could happen.</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">&nbsp;</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Normally what would you have is you have markets that are only margin or only spot. In this case we have margin and a spot happening within the same market.</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">&nbsp;</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">The system matched the forced close with the plaintiff's order, but that was -- the balance transfer was a result of an oversight. It shouldn't have happened. When the other party doesn't have enough balance, it doesn't make any sense to do the transfer to the other party. That was an oversight on the system. It was a bug, it was an architectural flaw. It was designed to do that, and it was a flaw on the system.</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Q:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Sorry, are you telling the court that the fact that the system was designed to match, even though a forced-closed customer had insufficient assets, was a bug in the system?</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">A:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">It was a flaw in the system, yes.</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Q:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">But it wasn't a bug?</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">A:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">It was not necessarily a bug. It was an oversight in the design of the system. So you design a system, you build specifications, this is what is going to happen. Then a programmer takes it and programmes it. If a designer, for some reason, forgets, or by oversight doesn't account for all these issues, then it will happen. So it's not necessarily a bug, it's more system design issue.</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">Q:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">You would then agree with me that as design, leaving aside the oversight, the B2C2's orders were correctly matched with the forced-closed orders?</p></td></tr><tr><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">A:</p></td><td align="left" class="" rowspan="1" valign="top"><p align="justify" class="QuoteList-Table-1">As designed, yes.</p></td></tr></tbody></table>

  
  

76     Mr Tseung, who in the event was not cross-examined on his AEIC, gave evidence that at the relevant time the balance on Pulsar’s account on 19 April contained only 13.5256945100 BTC yet the Platform debited Pulsar’s account with over 3000 BTC. He stated as follows:[\[note: 10\]](#Ftn_10)

The Platform should have been programmed to check whether the available BTC balances under Pulsar’s Account were sufficient before placing any orders to sell BTC under Pulsar’s Account and before proceeding to match such orders with any corresponding orders. This is how trading platforms are usually programmed to operate i.e., the platforms are configured to check whether a user’s balance is sufficient before placing any orders and proceeding to match any orders on behalf of the user. The Platform should not have placed the Force Closure Orders or matched the Force Closure Orders with B2C2’s Orders given that Pulsar’s Account did not have sufficient BTC to fulfil B2C2’s Orders.

77     This evidence reflects the admission by Mr Lozada that the Platform should have had such a feature but did not. Had there been such a feature, the Platform would have traded only the 13.5256945100 BTC in Pulsar’s account, leaving any outstanding deficit on Pulsar’s account due to the lender, in this case Quoine, to be recovered outwith the operation of the Platform.

78     Returning to Annex 3, it can be seen that when the margin call was made against Pulsar the initial trades were effected with the lowest sell orders then on the order book. Some had been placed by Pulsar (5539) and others by Quoine (3). These were orders from Quoine placed before the Quoter Program became inoperative. The price of these trades started at 0.03949 BTC/ETH and slowly increased (with three exceptions of what were new orders placed by Pulsar at 0.03944) until the last and highest order placed by Quoine at 0.04233 was filled. This demonstrates how the trades work when a margin call is made. The Platform starts to purchase the relevant currency at the lowest available price and then works through the existing orders sequentially in increasing value terms.

79     By 11.31pm, all the pre-existing orders by Quoine had been used up and the system had to search for the next lowest price available. As can be seen, these ranged from 0.05 to 1 BTC/ETH from traders other than Quoine including one from Pulsar itself at 0.07. It is thus apparent that the loss of liquidity was causing the trading systems of other traders to react by placing higher quotes, 1 BTC/ETH being some 25 times the 0.04 level. Exactly why this was so is unclear.

80     Then at 11.52pm, orders at 10 and 9.99999 from Trader 5776 (B2C2) were placed on the Platform and, since there were no lower priced orders, these were filled to complete the margin call on Pulsar. The position with regard to Mr Tomita is a little more complicated[\[note: 11\]](#Ftn_11) but it is not suggested that anything turns on this.

### The B2C2 Trading Software

81     The abnormally thin order book also had an effect on the B2C2 trading software. It was this issue that was the subject of the investigations by the expert witnesses.

82     The B2C2 trading software (“the Software”) is largely deterministic; it produces the exact same output when provided with the same input. Mr Atkinson explained that this was a benefit as it makes testing easier and the behaviour of the system is easier to understand, reason about and validate. It was devised almost exclusively by Mr Boonen and, as might be expected, had been the subject of a number of changes during the course of time. When the software was originally written, Mr Boonen included a number of routines designed both to maintain the integrity of the system and to ensure that it continued to operate in circumstances when there was insufficient liquidity in a given market for the system to operate normally.

83     The way in which the software determines what are appropriate prices at which to place Bid or Ask quotes is described in detail in paragraphs 42 to 52 of Mr Atkinson’s first report which was agreed to by Mr Kapoor. It is controlled by a strategy known as the PureQuote Strategy. For present purposes the effect of this strategy can be summarised relatively briefly. The software evaluates the first 20 price levels on a given platform on both the Bid and Ask side. It then excludes from that evaluation any price levels that relate to an order of a specified low volume. It then calculates an appropriate price at which to quote on either the Bid or Ask side as the case may be. However, it is accepted that there may be occasions when either the order book is empty or where it is populated by a large number of low volume orders within the first 20 that the strategy is unable to determine a price. One way to cater for this would be to introduce a circuit breaker so that the system would “error out”, _ie_, stop working. But this is undesirable in a program that is designed to work continuously without human oversight so Mr Boonen built into the software the requirement that at all times there should be added two “deep prices” to both the Bid side and the Ask side of the software’s internal representation of the order book. By this means there would always be prices which the software could draw upon so that the system would not error out.

84     Mr Atkinson described this in paragraph 54 of his first report:

By guaranteeing at least two price levels are available on both the bid and ask side of the Plaintiffs Trading Software's internal representation of the book before running the logic in Step 5, this means that there is always a front\_bid/front\_ask and next\_bid/next\_ask in the list of bids/asks. If the deep prices were not there, and there was an attempt to access two ask levels when the book contained no ask levels, this would cause an exception. Without these synthetic price levels, the PureQuote strategy would not be able to produce prices on either the bid or ask side of the book. In this regard, the PureQuote strategy produces both bid and ask prices at the same time and the existence of both bid and ask prices is relied upon by subsequent strategies in the pipeline, meaning that, in order to produce a bid price, the Trading Software also needed to produce an ask price. By the addition of the deep prices, the strategy needed no extra checking and also was guaranteed to produce an output. The addition of the deep prices simplifies the implementation of Step 5, but also all strategies that come after the PureQuote strategy in the market maker pipeline, in that these strategies can assume that a quote will always be produced by the PureQuote strategy. In software terms, this kind of programming is an example of a defensive programming technique. Wikipedia defines defensive programming as 'a form of defensive design intended to ensure the continuing function of a piece of software under unforeseen circumstances'. These pre-set synthetic deep price levels are to be distinguished from the prices of the Orders placed, which were generated by the PureQuote strategy.

85     These prices have to be chosen in a manner such that on the Ask side it is sufficiently large that the prospect of a trade at that level is both unlikely and, if it occurs, will adequately protect B2C2 against the risk of any adverse consequences of such a trade. Conversely, the chosen price on the Bid side needs to be low. As at 19 April 2017, these prices were, respectively, for the Ask side 10 BTC/ETH and for the Bid side 0.00001 BTC/ETH. As Mr Boonen put it, “the prices had to be sufficiently advantageous so that B2C2 would not regret it if orders place at or near those price levels were filled”.[\[note: 12\]](#Ftn_12) In cross-examination, he said that it was his “role as a trader to try to find numbers that make sense in a situation of very \[_sic_\] uncertainty as to the future”.[\[note: 13\]](#Ftn_13)

86     He also indicated that the choice of price had to be at a level that was not so low or high that the trading platform might be programmed to reject it and thus act as an undesirable circuit breaker.[\[note: 14\]](#Ftn_14)

87     Hence, when the order book became very low or empty in the late evening of 19 April the two deep prices on the Ask side came into effect and were placed on the order book. It is however to be noted that this did not happen immediately once the order book became illiquid. There was a delay because at the time B2C2 had sold sufficient ETH on other platforms in the recent past such that the software was not sending sell orders for ETH to the Platform to avoid accumulating too much risk.[\[note: 15\]](#Ftn_15)

88     Mr Atkinson described the placing of these deep prices as being a defensive programming technique. Mr Boonen identified this as being the role of a programmer to think of potential, even if unlikely events, and design the code to cater for the worst case scenario that could occur[\[note: 16\]](#Ftn_16). Mr Kapoor accepted that it was in part defensive but said there were aspects that were not necessary for defensive purposes and Mr Paul Ong relied on these aspects as indicating an adverse motive on the part of Mr Boonen to take advantage of a situation of low or no liquidity by triggering margin calls.

89     The first point made by Mr Kapoor was that he considered that the software was configured to place a deep quote only on the Ask side and not on the Bid side. He did a simulation in which the deep prices on both sides were entered into the PureQuote strategy and the result was that an Ask quote was sent to the Platform but not to the Bid side because the “Bid quantity (was) too small”. This he contends is because the software imposes a minimum order quantity equivalent to USD20 based on an internal global benchmark (being a notional USD/BTC conversion rate of USD1200/BTC) which in his simulation led to an order quantity of only USD2.43. On the other hand, Mr Kapoor identified that there was no equivalent maximum order size preventing a large-sized order being sent out.[\[note: 17\]](#Ftn_17) Mr Kapoor contended that this could have been done.

90     Mr Boonen accepted that this could have been done and that it had not been. He however drew attention to the fact that there was a provision whereby the code does not send out orders that exceed a certain USD amount. In cross-examination, he said:[\[note: 18\]](#Ftn_18)

My understanding of your first question is that we could have the same type of check on the smallest quantity as on the maximum quantity. I just spent some time explaining that the nature of the checks -- and really I would say that the smallest quantity check is indeed a check – but on the maximum side, it's not a check, per se. One gets to a maximum constrained by construction of the way the code is designed. So those are not exactly the same things, but by construction the code does not send out orders that exceed a certain dollar value, and this is important, as determined by our own internal calculation of the value of the order. And that calculation does not take into account the price of the order. It takes into account our global benchmark, our global dollar benchmark for Ethereum which we compute internally, and does not come from the market, because we do not want to use the market where we are going to send the order as the benchmark of the price for the purpose of that check.

91     It can thus be seen that the software does not take into account the actual price of the order (_ie_, 10 BTC for 1 ETH). What it does is to have regard only to the quantity of the order in terms of ETH and multiply that by the internal benchmark for the USD value of ETH which at that time was USD50. If the sum of those two numbers exceeded a set value, then the order would not be placed. Hence the maximum figure did not relate to the value of the order but only the quantity and thus served to ensure that an order for sale of ETH did not exceed a certain quantity. There were, Mr Boonen said, very serious risk management reasons for this, a statement which was not challenged.[\[note: 19\]](#Ftn_19)

92     The position therefore is that a Bid order below a given minimum USD value based on the notional BTC/USD conversion rate would not be placed but an Ask order would be placed unless it was for a quantity of ETH above a given threshold based on that notional ETH/USD regardless of what the BTC proceeds of such a sale were. The former is to avoid meaningless low value orders coming onto the Platform. The latter is to protect B2C2 from trading in large quantities of ETH which, when the program was written, Mr Boonen regarded as being the more volatile currency and thus was the major risk[\[note: 20\]](#Ftn_20). Mr Boonen did not include a maximum order limit on an Ask order to restrict the value of BTC which B2C2 might receive from any Ask order to sell a quantity of ETH which did fall below the maximum number. In the circumstances of this case, this would have acted to protect the Counterparties to B2C2’s detriment.

93     The second factor Mr Kapoor drew attention to was that there had been changes in the deep prices that had been set in the software since it was first written. When Mr Boonen initially wrote the program, he configured the software to quote a deep price on the Ask side at a BTC/ETH ratio which was close to infinity and subsequently altered this to a price which was equivalent to a ratio of 50 BTC/ETHJHH. On 16 June 2016 Mr Boonen altered the deep price to the 10 BTC/ETH level. Mr Kapoor suggested that this change was indicative of an intention on the part of the programmer to increase the likelihood that such deep prices would be executed. The basis for this was Mr Kapoor’s assertion that higher prices were likely to be rejected by the Platform whereas rejection at the 10:1 level was less likely.[\[note: 21\]](#Ftn_21)

94     Mr Boonen explained the reasons behind this change in his third AEIC and was then cross-examined at some length on it.[\[note: 22\]](#Ftn_22) Mr Boonen explained that in June 2016 there was what he called a refactoring of the code with the intention of making it clearer and safer. Whilst the close to infinity level had previously been altered to place another somewhat smaller but still large number for the deep price, both were a “one size fits all” number in that it applied across the board to all currency pairs traded by B2C2. It so happened that at that date the effect was that the BTC/ETH rate was around 50:1.

95     By 2016, B2C2 were trading in an increased number of trading pairs including ETH/BTC (ETH having come into existence after the B2C2 trading software had first been written in 2014). Mr Boonen particularly drew attention to the fact that B2C2 had by then started trading in BTC/South African Rand, a significantly more volatile currency than the USD and that he had concerns that the generic deep price might not be deep enough to protect B2C2 in the event of a significant change in the value of the Rand.

96     He therefore concluded that the “one size fits all” number was no longer appropriate and he placed individual deep prices for each currency pair. Mr Boonen considered the 50BTC:1ETH ratio was too high and he selected the 10BTC:1ETH level. He accepted that one of the reasons for doing this was to ensure that any sell orders placed at that level would not be rejected by the Platform. He gave evidence that the price was chosen so as to be sufficiently advantageous to cover the risks to B2C2 of trading in a potentially illiquid market and again emphasised that he regarded ETH as being the greater risk at the time. He also explained that he used the same deep price to act as a circuit breaker to protect either against the risk of a significant change in the actual market price of a given currency pair or against the possibility that there might be bugs in other parts of the B2C2 trading system. He asserted that it was his role as a trader to find numbers which made sense to him in an uncertain market.

97     In re-examination,[\[note: 23\]](#Ftn_23) he amplified upon the circuit breaker aspect by giving an example of a case where with a different currency pair the actual market prices broke through the upper range and the deep price acted as a circuit breaker. He indicated that he felt that the 50:1 ratio was so high that it would be highly unlikely ever to be activated as a circuit breaker and thus would not adequately protect B2C2 and that he also chose the 10:1 ratio with this in mind. I accept this evidence.

98     The third factor to which Mr Kapoor drew particular attention was his assertion that certain portions of B2C2’s code were changed after the glitch occurred on 13 April 2017 which he suggested might have caused the software to quote more frequently or to quote more in total than it was quoting before the glitch.[\[note: 24\]](#Ftn_24) The underlying thrust behind this suggestion was that B2C2 had appreciated sometime between 13 and 19 April that something was causing illiquidity on the Platform and that the changes were implemented with a view to triggering force-closures.

99     As Mr Kapoor fairly acknowledges, he was unable to review the actual code for the suggested change, but he surmises that it did occur since the initial cycle frequency was set at 10 seconds and by 19 April the frequency was 5 seconds.

100    In his third AEIC, Mr Boonen rejected the implicit suggestion that any change to B2C2’s code configuration files was in response to or motivated by the glitch which he contended did not come to his notice until after the orders were fulfilled on 19 April. He went on to explain that the amendments made on 13 April were part of a routine change to the Inventory Strategy which adjusts prices to maintain a target balance of B2C2’s assets on the Platform.[\[note: 25\]](#Ftn_25)

101    Mr Atkinson also considered this suggestion in detail in his second report.[\[note: 26\]](#Ftn_26) He concluded that there was no evidence to suggest that there were any configuration changes made in April other than those which reflected configuration changes in inventory on the Platform. All the witnesses were cross-examined on this issue.

102    Mr Boonen was challenged on his evidence[\[note: 27\]](#Ftn_27) that he did not become aware of the glitch until after the orders were filled. He explained that B2C2 was connected to 15 exchanges at the time, on some of which up to ten pairs were traded. The market for BTC/ETH on the Platform was relatively small and he would not look at it on a day-to-day basis so that it was unlikely that he would have checked it on 13 April. In any event, he said, the Platform did not allow him to see the actual orders of others on it at any given time and there was no access to the number of orders at any one time. He rejected the assertion that he did notice a drop in the volume of orders on the ETH/BTC order book on 13 April. The reasons he gives for not noticing this are cogent and again I accept his evidence.

103    Mr Atkinson and Mr Kapoor metaphorically crossed swords on the technical aspects of this issue. Since I have accepted that Mr Boonen did not notice the drop in the volume of orders on 13 April, it is less important that I consider the technical aspects in detail. In brief, Mr Atkinson contended that Mr Kapoor’s analysis was flawed in that it sought to determine an undefined average cycle frequency but failed to distinguish between Bids and Asks and failed to consider the mode average. He pointed to the fact that that there was a large difference between the mean and the mode average which suggested that the approach of Mr Kapoor was not appropriate. He concluded that the data available to him, properly analysed, showed that the cycle frequency was set to 5 milliseconds before 13 April and remained the same through until 19 April.[\[note: 28\]](#Ftn_28)

104    In cross-examination,[\[note: 29\]](#Ftn_29) Mr Kapoor accepted that in the absence of full details of the changes implemented on 13 April he could not be certain that changes had been made which would reflect an intention to take advantage of the drop in orders but maintained that this was a possibility.

105    I consider that the data analysed by Mr Atkinson and his reasoning are sufficient to satisfy me that the changes made on 13 April were not changes designed to take advantage of any perceived loss in the order book. I do not question that Mr Kapoor genuinely held a suspicion that the changes might have been for an ulterior motive but, having read and heard all the evidence, I am unpersuaded that this was the case.

### The mindset of Mr Boonen

106    For reasons which I shall amplify upon when considering the law of mistake, I have concluded that when the law is faced with a contention that a contract made by and between two computer systems acting as programmed but otherwise without human intervention is void or voidable for mistake, it is necessary to have regard to the mindset of the programmer when the relevant programs, or the relevant part of those programs, were written. The knowledge of the programmer in question is to be inferred by the Court from the evidence adduced and from all the surrounding circumstances.

107    In the case of the seven contracts made on 19 April 2017, the offer for sale at the 10 BTC/ETH price was made by the B2C2 trading system. It was accepted by the Platform in filling the market orders already placed on the Platform by the action of a separate program which had identified that the Counterparties’ collateral was insufficient. The Counterparties in their loan arrangement with Quoine had agreed that this could be done if the Platform determined that the collateral was insufficient. There was no human intervention in this process. Mr Boonen, Mr Lozada and the Counterparties were unaware what had happened until after the event.

108    Mr Boonen had written the trading software originally in 2014 and the 10:1 ratio had been included in June 2016. Quoine’s case on knowledge is set out in the particulars to Paragraph 14 of the Defence. It alleges knowledge in two respects. First, Particulars (a)–(e) focus on the Plaintiff’s alleged knowledge at the time of the incident, seeking to draw the inference that the prices at which the orders were fulfilled were so abnormal that a reasonable person (and hence the Plaintiff) would have known or harboured a real suspicion that the rate was inaccurate and therefore a mistake. However, it is now clear from the evidence that no one was “in the know” at the time of the incident what orders were on the order book when the margin trades were placed or what the prices of those orders were. Further it is clear that the placing of the orders at the 10:1 ratio was not itself the cause of the force-close margin orders being placed. Accordingly, this aspect of knowledge has not been demonstrated.

109    The second aspect is pleaded in Particular (f) which reads as follows:

The Orders were placed because the Plaintiff had programmed its algorithmic trading software to place limit orders on the ask side of the ETH/BTC order book at the irrational prices of 9.999995 or 9.99999 BTC for 1 ETH when the order book was ‘thin’ and/or empty. The Plaintiff did so with the intention and/or objective and/or purpose of taking advantage of and/or exploiting an abnormal situation of low and/or zero liquidity on the Platform which could allow such orders to be executed at such irrational prices.

110    This is a clear allegation that Mr Boonen included the 10:1 ratio when writing the program with the knowledge not only that it would lead to orders being placed on the Platform at that level in cases of low liquidity but also with the knowledge that there were circumstances in which such orders might be met. Quoine amplified upon this in its written opening submissions. The suggestion that the placing of the deep prices was strictly the result of an innocuous defensive programming strategy was said to be highly artificial and strained. It was also suggested that the Plaintiff was being opportunistic in seeking to take advantage of forced and/or erroneous liquidations by programming its trading software to place orders at the deep prices which were not bona fide. Mr Atkinson’s analysis, it was said, was overly simplistic and failed to take into account the overall manner in which the code had evolved over time. Reliance was placed on the evidence of Mr Kapoor to support an allegation that Mr Boonen had put thought into what the trading software should do if the ETC/BTH order book became empty and that he had placed the 10:1 ratio into the code with the intention of triggering and thereafter benefitting from such forced or erroneous liquidations.[\[note: 30\]](#Ftn_30)

111    In its Reply, the Plaintiff denied that it had any knowledge of the trades at the time they were made and asserted that it was speculative to assert that it had “any form of knowledge of any purported system failure, loss of order book, force-closure or otherwise of any alleged mistake” and denied that its trading software was programmed with the intentions and/or objectives alleged in particular (f) to paragraph 14 of the Defence.[\[note: 31\]](#Ftn_31)

112    In his written evidence, Mr Boonen said that he was not aware that the Platform was affected by any glitch, that the trading software was not programmed to detect such glitches and that the orders were placed because of the deep pricing strategy referred to in \[83\] above. He accepted that there was always a possibility that such orders would be filled and that, if they were, B2C2 would be bound by them. It was for this reason that he pre-programmed the code so that the prices were sufficiently advantageous to cover the risk to B2C2 of uncertain liquidity and market conditions. He frankly stated that “the price levels had to be sufficiently advantageous so that B2C2 would not regret it if orders placed at or near those levels were filled”.[\[note: 32\]](#Ftn_32)

113    Early in his cross-examination, when considering the extent to which the deep prices were present to cover the risks of illiquidity Mr Boonen said this:[\[note: 33\]](#Ftn_33)

Now, this check or this feature that we’re talking about, that price of 10, it’s not the sort of day-to-day measure, right. It is a circuit-breaker. It is when something very unusual happens. It’s when the unfathomable actually crystallises. I think it’s important to add that clarification.

In its written closing, Quoine repeatedly referred to this passage as being an indication that Mr Boonen must have known that if the very unusual or unfathomable were to occur this was likely to be the result of a serious error or glitch.

114    Thereafter, Mr Boonen gave evidence that he was surprised when he first saw that the orders had been filled and that he considered the possibility that there was an error on the Platform or an error in the B2C2 system. Having checked that there were no apparent errors in either system he thought “Wow, there must have been something incredible happened \[_sic_\] in the market overnight”.[\[note: 34\]](#Ftn_34)

115    Later on, he accepted that he was aware when programming the code that it was possible that such a quote could be transacted and executed when the order book was empty but that this was an unlikely possibility. However, he rejected the suggestion that he knew that putting in an order at such a high price could potentially cause traders who were short on ETH to close out their positions or for exchanges to force-close ETH short positions.[\[note: 35\]](#Ftn_35)

116    Matters came to a head in this passage of cross-examination:[\[note: 36\]](#Ftn_36)

I disagree. I could not even know that this situation would have occurred. If you had told me when I left my job at Goldman Sachs – and actually I remember I told my partner, my line manager, the guy I had to officially resign to, “I'm thinking that Bitcoin thing has some legs, I’m going to do it for maybe six months. Hopefully I can sell the company for $2 million". That's what I said, "$2 million", "then I'll come back". If you had told me at the time, "Max, your company is going to make tens of millions of dollars and you're going to be in a courtroom in Singapore in 2018", I would have thought that -- I would have re-evaluated my life's choices. So, no. My objective here, in setting that specific value at 10, was not that I was about to make obscene profit.

117    Mr Boonen was affronted at the suggestion that he had designed his software with the specific purpose of taking advantage of the errors of others and, in the result, he did become over-loquacious but the thrust of his answers was always to the effect that Quoine were seeking to read far too much into the insertion of the deep prices than was warranted. His position can be illustrated by two further extracts of the oral evidence he gave on the second day of his trial:[\[note: 37\]](#Ftn_37)

You're saying that my mind was set to try to do something nefarious for seven little orders that you agree were unlikely to ever trade anyway, it was unlikely that such a situation would ever occur. But if I had done that, I would have missed out on tens of millions of dollars of profit for my firm, because that's what I was focused on. You know, if I'm spending all my time trying to find some work-around to try to take advantage of Quoine, a tiny platform that I -- I'm not sure in November 2014 they existed, maybe the company was created around that time, that makes absolutely no sense because it would have diverted so much focus away from all the other platforms, from all the other parts of the code. Frankly, that deep price stuff is minor.

…

And so I completely disagree. It makes no sense. It doesn't make any sense for me to have focused so much, with perfect foresight, on trying to take advantage of Quoine, when I did not need that at all. I did not need those trades. The reason I'm here is because I'm entitled to a profit. My profit has been illegally clawed back from me, and it simply is a big enough number that I have to be here.

118    What then was his mindset? At the time the original program was written, ETH did not exist. In June 2016 when the 10:1 ratio was added, it was a fledgling currency and I accept Mr Boonen’s evidence that he regarded it as representing the most risk. I also accept that his primary concern when writing the program was to protect the integrity of the B2C2 trading system so as to minimise the risk of any unwarranted exposure.

119    He was particularly careful because of the fact that the markets in virtual currencies were unregulated. He saw the need to protect B2C2 and anticipated that other traders and the platform operators would take similar steps. He appreciated that the way he had written the software, the deep prices could go on the Platform and that it was possible, although unlikely, that a trade would be executed at that level. It would only be, as he put it in the passage quoted above, when something very unusual happened or when the unfathomable actually crystallised. He frankly conceded that were this to happen he would hope to make a profit and that the price chosen was selected so as to maximise the possibility of not making a loss. His strategy was therefore not wholly defensive.

120    Mr Paul Ong submitted that the facts supported the conclusion that when Mr Boonen configured the code he knew of the possibility that the order book might become empty and that in that event there was a real possibility of the deep price orders being executed. He therefore designed the software to take advantage of that. It was sufficient, he said, for me to conclude that Mr Boonen programmed the code to include a deep price which was irrational and that no trader would agree to buy ETH at such a price unless by mistake.[\[note: 38\]](#Ftn_38)

121    I do not believe that Mr Boonen turned his mind in any detail to the circumstances in which such an order might be executed although plainly he had well in mind that these virtual currencies were highly volatile.[\[note: 39\]](#Ftn_39) Equally, at a high level of generality, he would have appreciated that the deep prices would only be likely to be executed when there was illiquidity in the order book for that was one of the reasons underlying the addition of the deep prices in the software in the first place. His reasoning was however directed to ensuring the B2C2 system remained operational in such circumstances rather than exploiting the existence of illiquidity.

122    He might have appreciated that one contributing factor to illiquidity could be due to an oversight or error on the part of someone but there are no grounds for concluding that he considered that these would be the only circumstances that would lead to illiquidity. His attitude was well demonstrated by his reaction on seeing the outcome of the trades, when his first concern was that there might have been an error in the B2C2 code and then that there might have been an error in the Platform.

123    I therefore accept that when Mr Boonen configured the code he knew of the possibility that the order book might become empty and that in that event the deep prices would be placed on the order book but I do not accept that he ever considered that there was a real possibility of the deep price orders being executed. He considered that this was unlikely and I do not believe that he turned his mind in any detail to the circumstances in which this might happen. That was not the motivation for designing the software as he did. He did not consider that the deep prices were irrational. Indeed he gave cogent reasons for the selection of the prices which were directed to protecting the integrity of his system but at a level which he felt would not be so high as to cause a circuit break on the Platform: see \[86\] above. This last factor is inconsistent with any assertion that Mr Boonen understood that trades would only be matched by the Platform at prices at or near the previously existing prevailing market price: see \[230\] below.

124    The evidence does not support the conclusion that when designing the code Mr Boonen perceived that no trader would ever agree to buy ETH at such a price unless he had made a mistake and included the deep prices with this in mind. More specifically, there are no grounds for concluding that he ever turned his mind to the relationship between the margin traders and those who had loaned them money, far less that he programmed the code with a view to exploiting that relationship by causing the deep prices to lead to a margin call and hence a force-close position. Equally there are no grounds for concluding that Mr Boonen wrote the code in the way that he did with an underlying intention of manipulating the market. I therefore reject Quoine’s assertions in those respects.

125    His mindset therefore, in summary, was that he intended the 10:1 ratio to act primarily to protect B2C2 against the risks of illiquidity but that he was aware of the unlikely possibility that trades might be executed at that level. He did not turn his mind in any detail to the circumstances that might lead to such trades being executed but he would have been aware that one possibility was that it could be the result, wholly or in part, of some error or omission on the part of someone, including himself. He intended that B2C2 should be best placed to make a profit, not a loss, if the unlikely became a reality, whatever the cause. In this respect his programming was opportunistic but it is in no respect sinister. It is not sinister to give yourself the opportunity of making a profit rather than a loss in the case of a wholly unlikely event occurring for whatever reason.

## The Contractual Relationships

126    There is more than one contractual relationship that will exist when parties trade on a currency platform. First, all traders, whether buyers and sellers, will have a contract with the platform operator to regulate the relationship between that trader and the platform owner so that they can trade on the platform (“Platform contracts”). It is the Platform contract between B2C2 and Quoine that Quoine is alleged to have breached when it reversed the trades. Secondly, where there are margin traders, there will be a separate contract between the borrower and the lender (in this case Quoine on the one hand and the Counterparties on the other) which will regulate their lending relationship (“Margin contracts”). Finally, when a trade is executed, the buyer and seller will have some form of contractual relationship _inter se_ (“Trading contracts”).

127    Quoine contended that the relationship between buyer and seller in a trading contract was a direct one. In the case of the seven trades, B2C2 had placed a limit order offering to buy BTC and sell ETH at the rate of 10 BTC for 1 ETH. The Counterparties had previously placed a market order to sell BTC and buy ETH at whatever prices were available on the order book at the time. The orders were matched by the Platform acting as programmed to perform an exchange function so as to complete the contract for those trades between the respective parties by the operator of the Platform, Quoine, which was not itself a party to the contract. The fact that neither party knew the identity of the other was irrelevant. Pursuant to the Platform contracts, all traders knew that any orders would be matched with other traders who were subject to the same Platform contract.

128    Mr Danny Ong for B2C2 submitted that the relationship was, as he put it, a spider’s web of contracts with Quoine in the middle.[\[note: 40\]](#Ftn_40) Quoine was thus a party to a contract with the buyer and a separate contract with the seller, acting as an intermediary. He contended that Mr Boonen had accepted in evidence that B2C2 always considered that the contractual counterparty to trade on the Platform was Quoine and that Quoine must necessarily act as a central counterparty to both customers since the Platform operated on an anonymous basis.

129    It is relevant to decide this issue as it will be necessary to identify what the mistake was, if there was one, and who the mistaken party was. It should, however, be noted that the answer to this question has no bearing on whether or not Quoine is liable to B2C2 for breach of the Platform contract.

130    Resolution of this issue requires the Terms and Conditions of the Agreement to be interpreted. These make it plain that Quoine as the Platform operator is providing a service to the “Users and Members” (hereinafter “Members”) using the Platform. The first paragraph of the Section headed “Trading & Order Execution” reads:

“Only registered users or Members are allowed to buy, sell and use the services provided by the platform. The exchange functions of the Platform will fill orders at the best possible available market price.”

And the third paragraph reads:

“The Company and its affiliates assume no responsibility for any loss or damage incurred by members or users as a result of their use of the Platform … The Company provides its Users and Members with a service via which they can exchange, buy, sell and/or store certain virtual currencies …”

131    The remainder of the Terms and Conditions make it plain that Quoine is solely providing the Platform and that the parties are themselves responsible for determining whether and on what terms they shall place or fill orders. The actual contract of sale is therefore a contract directly between buyers and sellers whose rights _inter se_ are determined by the Terms and Conditions. In my judgment, therefore, Quoine’s approach is the correct one. The Members have agreed that they can use the Platform to buy and sell currencies using limit or market orders on the understanding that if the Platform matched two orders a contract would ensue between those Members. Each of the offers to buy and sell made by B2C2 and Quoine was made at large to all other users of the Platform. When the orders were matched the identities of the actual buyers and the sellers were ascertainable.

132    Since it is irrelevant in law who Mr Boonen considered he was contracting with, I shall not review the evidence that B2C2 drew my attention to. Suffice it to say that I do not consider that it is at all clear that Mr Boonen had the impression that he was contracting solely with Quoine.[\[note: 41\]](#Ftn_41)

**The Issues**

133    There are three main issues to be canvassed:

(a)     First, the Plaintiff’s Claim. There are essentially two prongs to the claim: (1) Quoine’s breach of contract in reversing the trades; and (2) Quoine’s breach of trust in disposing of the Plaintiff’s assets.

(b)     Second, the Defendant’s Defences. The Defendant raised a number of potential defences which, logically, I consider should be considered in the following order:

(i)       It is entitled to reverse the trades on the basis of implied terms of the Agreement.

(ii)       It is entitled to reverse the trades on the basis of an express term of the Agreement when read in conjunction with the Risk Disclosure Statement.

(iii)       It is entitled to reverse the trades on the basis that the contacts between B2C2 and the Counterparties were void under the doctrine of unilateral mistake at common law.

(iv)       It is entitled to reverse the trades on the basis that those contracts were voidable under the doctrine of unilateral mistake in equity.

(v)       It is entitled to reverse the trades on the basis that those contracts were void under the doctrine of mutual mistake at common law.

(vi)       It is entitled to reverse the trades on the basis of unjust enrichment.

(c)     Third, the relief to be ordered if Quoine is liable. In particular, If B2C2 is entitled to relief both in law for breach of contract and in equity for breach of trust, what relief is it entitled to?

### Bifurcation

134    I do not have to address the issue of damages or monetary compensation in this judgment because the parties agreed that the proceedings would be bifurcated into findings on liability and damages, respectively. By a consent order dated 20 February 2018 it was ordered that:

1.    There be a bifurcation of the trial in that the questions relating to the following issues be tried after the trial of this action in such manner as may be directed by the trial judge or by further order:

a.    the assessment of loss, damage, cost and/or expense, as prayed for in paragraph 13(4) of the Statement of Claim; and

b.    the assessment of equitable compensation and/or damages, as prayed for in paragraph 13(5) of the Statement of Claim…

135    Accordingly, if B2C2’s claim succeeds in any respect, the amount of any monetary compensation will be determined at a later hearing. As indicated at the hearing, this will include resolution of an issue concerning an alleged limitation of liability pursuant to Clause (d) under Owner Responsibilities in the Agreement.

## The Plaintiff’s Claim

### Breach of Contract

136    B2C2’s case is straightforward and short. The seven trades were executed as a result of the market orders placed (albeit unknowingly) by the Counterparties which were filled by the limit orders placed by B2C2 at the deep price of 10 BTC for 1 ETH. The proceeds were debited from and credited to the relevant accounts for the amounts of ETH and BTC respectively. The parties were notified of this in the usual way. The Agreement expressly provides that “once an order is filled, you are notified via the Platform and such an action is irreversible”.[\[note: 42\]](#Ftn_42)

137    On that basis, B2C2 contends that the reversal of the orders on the following day was in breach of the express term that the filling of an order is “irreversible”. Unless Quoine succeeds on one or more of its defences, this claim will succeed.

### Breach of Trust

138    Quoine contended that it was clear that it did not hold any assets belonging to any Member on trust for that party. There was no provision to that effect in the Agreement and paragraph 9 of the Risk Disclosure Statement, “Bankruptcy Risk” expressly alerted the customer to the fact that although it managed any assets deposited by Members separately from Quoine’s assets, those assets were held by Quoine itself and were not on deposit in a separate account with a trust bank. Accordingly, if Quoine were to go bankrupt, it would be unable to return those assets. This was inconsistent with the assets being held on trust.

139    B2C2 drew my attention to the answers to a Request for Further and Better Particulars of the Defence[\[note: 43\]](#Ftn_43) which stated that all funds deposited by all traders were stored in a single cryptocurrency wallet which was owned and maintained by Quoine. This was consistent with a provision in the Terms and Conditions under “Withdrawals” which made it clear that in order to protect Members no currencies were kept in online wallets and was also consistent with the statement in the Risk Disclosure Statement that Member’s assets would be managed separately from Quoine’s assets. This was, he said, evidence of an intention to create a trust.

140    The factual position is therefore that whilst separate accounts are maintained for all Members, the actual virtual proceeds are stored together off line but are maintained separately from Quoine’s own assets.

141    So far as concerns the law, there was a measure of agreement between the parties. Both accepted that there were three certainties that had to be present for the creation of a trust, namely, certainty of intention, certainty of subject matter and certainty of objects.

142    It is convenient to consider the second certainty, certainty of subject matter, first. Quoine was prepared to assume that cryptocurrencies may be treated as property that may be held on trust. I consider that it was right to do so. Cryptocurrencies are not legal tender in the sense of being a regulated currency issued by a government but do have the fundamental characteristic of intangible property as being an identifiable thing of value. Quoine drew my attention to the classic definition of a property right in the House of Lords decision of _National Provincial Bank v Ainsworth_ at 1248:

“it must be definable, identifiable by third parties, capable in its nature of assumption by third parties, and have some degree of permanence or stability”.

Cryptocurrencies meet all these requirements. Whilst there may be some academic debate as to the precise nature of the property right, in the light of the fact that Quoine does not seek to dispute that they may be treated as property in a generic sense, I need not consider the question further.

143    The third certainty, certainty of objects, requires that the intended beneficiaries have to be identifiable so that it is possible to ascertain those who have the standing to enforce the trustee’s duties under the trust: _Guy Neale v Nine Squares Pty Ltd_ (“_Guy Neale_”) at \[60\]. This requirement is met in the present case. The beneficiaries are identifiable from the individual accounts of each of the Members.

144    The dispute arises on the first certainty, certainty of intention to create a trust. In ascertaining the requisite intention, it is not necessary for express words to that effect to be used. The Court must have regard to the conduct of the alleged settlor, the words used in any relevant documents and all the surrounding circumstances: _Guy Neale_ at \[52\]–\[58\].

145    In the present case there are no express words in the Agreement creating a trust. The necessary intention is thus to be determined from the wording of the document as a whole and from Quoine’s conduct when handling the assets. That practice has not changed since the Platform began to operate. More specifically, its practice did not alter when the Risk Disclosure Statement was uploaded onto the website in March 2017. To my mind, the decisive factor is that the assets are held separately as Member’s assets rather than as part of Quoine’s trading assets. This is a clear indication, not surprisingly, that Quoine claims no title to those assets and acknowledges that it is holding them to the order of the Member who can demand withdrawal at any time. This is sufficiently clear evidence that Quoine intended to hold the assets on trust for the individual Member. What will be the effect of such an arrangement were Quoine to go “bankrupt” is not a matter for me to decide.

146    Accordingly, if Quoine was not entitled to reverse the trades, the reversal and hence the unilateral removal of the Bitcoin from B2C2’s account was in breach of trust.

## The Defendant’s Defences

### Defence 1: Is Quoine entitled to reverse the trades on the basis of implied terms of the Agreement?

147    Quoine accepted that, as a matter of law, a term could not be implied into a contract if it contradicted an express term of that contract. If it did not contradict an express term, then a term could be implied if it was necessary to give business efficacy to the contract and to give effect to the intentions of the parties.

148    In paragraph 152 of its written closing submissions, Quoine sought to rely on two implied terms:

(a)     Quoine may reverse any trades which are executed at any abnormal rate or price as a result of any technical and/or system failure and/or error affecting the Platform;

(b)     Quoine may reverse any trades resulting from orders placed in breach of the terms of the 2014 Terms & Conditions, including any trades resulting from any orders which amounted to market manipulation and/or abuse and, therefore, an “_unauthorised use_” of the Platform.

149    There was no dispute between the parties as to the legal approach. In particular, Quoine accepted that the applicable principles were laid down by the Court of Appeal in _Sembcorp Marine Ltd v PPL Holdings Pte Ltd_ . In paragraph 153 of its written closing submissions Quoine correctly summarised the position as follows:

Based on _Sembcorp Marine_, the applicable principles are as follows:

(a)     First, the process of implication of terms is “_best understood as an exercise in giving effect to the parties’ presumed intentions_”. It is “_an exercise in filling the gaps in the contract_.”

(b)     Secondly, it is only in the scenario where “_the parties did not contemplate the issue at all and so left a gap_” that it would be appropriate to imply a term into the contract.

(c)     Thirdly, the business efficacy and officious bystander tests “_remain the prevailing approach for the implication of terms under Singapore law_”. On that basis, “_a term that is not reasonable, not equitable, unclear, or that contradicts an express term of the contract, will not be implied_” as it “will _necessarily fail the officious bystander test_”.

(d)     Fourthly, there may be more than one legal basis on which it may be determined that a term \[accords\] with the parties’ presumed intentions. The business efficacy basis is “_clearly favoured in the commercial context as it is safe to assume that commercial parties are rational, and as such, seek business efficacy in their transaction._”

(e)     Fifthly, the threshold for implying a term is “_necessarily a high one_” i.e., a term should only be implied if it is necessary.

(f)    In the premises, the implication of terms should be considered using a “three-step process”:

“_The first step is to ascertain how the gap in the contract arises. Implication will be considered only if the court discerns that the gap arose because the parties did not contemplate the gap._

_At the second step, the court considers whether it is necessary in the business or commercial sense to imply a term in order to give the contract efficacy._

_Finally, the court considers the specific term to be implied. This must be one which the parties, having regard to the need for business efficacy, would have responded “Oh, of course!” had the proposed term been put to them at \[the\] time of the contract. If it is not possible to find such a clear response, then, the gap persists and the consequences of the gap \[ensue\]._”

150    B2C2’s primary contention in relation to the first proposed term is that such a term would contradict the express term in the Agreement under “Trading & Order Execution” that:

“Furthermore, once an order is filled, you are notified by the Platform and such an action is irreversible.”

This is, it is said, indicative that the parties had turned their minds to the question of the reversibility of completed orders and had concluded that this should not be permitted. There was therefore no gap to be filled by the proposed implied term permitting reversibility in particular circumstances.

151    Quoine contends, however, that “irreversible”, properly interpreted, does not preclude Quoine, as opposed to the contracting parties, from reversing trades. Whereas the individual parties to the transaction should not be able unilaterally to reverse a completed trade, giving the clause a purposive construction, the same was not true for Quoine. I am unable to accept this submission. The Platform contract is between Quoine and any given Member of the Platform. The immediately preceding sentence expressly limits Quoine’s liability in relation to delays in execution and the following sentence again limits its liability in terms of loss or damage incurred by a Member as a result of its “failure to understand the nature and mechanics of virtual currencies or the markets under which such virtual currencies operate”. Furthermore, the wording of the clause itself relates not only to the filling of the order but also to the notification via the Platform, which is also consistent with all parties, including the Platform, being bound by the trade.

152    The word “irreversible” is not qualified in any way and when it is read in the context of the passage as a whole, the proper inference to be drawn is that the provision was included to ensure certainty for all parties including Quoine as soon as the transaction was notified as being filled. To interpret “irreversible” in a manner such that orders executed at what Quoine considered to be at an abnormal rate could subsequently be reversed thereafter runs contrary to this. Accordingly, the terms sought to be implied do contradict an express clause of the Agreement and therefore cannot be implied.

153    Even if this were not the case, I do not see that it is necessary for the terms to be implied to give business efficacy to the Agreement. The Agreement seeks to provide clarity as to the trading relationship between Quoine and the Members and between the Members _inter se_ and, in doing so, to apportion risk clearly between the parties. In the case of a new trading platform clarity is essential to give confidence to traders, especially market makers who are trading on a minute-by-minute basis over a number of exchanges and who regulate their exposure across those exchanges. Any uncertainty on one exchange can have a material effect on its position overall. Mr Boonen gave evidence that if he had been asked to agree a term that Quoine could unilaterally reverse a trade, he would not have done so because he was concerned about Quoine as a platform operator.[\[note: 44\]](#Ftn_44)

154    The clause which provides for irreversibility does introduce certainty and places the risk of entering any given trade on the parties to that trade. Where one knows that the filling of an order brings finality to a transaction, the parties can thereafter carry out their business in the knowledge that the past will not be undone. They must however ensure that procedures are in place to ensure that any risks involved in algorithmic trading are guarded against. Mr Boonen suggested that in this field, “_caveat emptor_” applied. In truth I consider that in an unregulated field, it is in fact “_caveat omnes_”. There is thus no need to imply the terms to give business efficacy to the Agreement.

### Defence 2. Is Quoine entitled to reverse the trades on the basis of an express term of the Agreement when read in conjunction with the Risk Disclosure Statement?

155    There are four relevant passages in the Agreement. First, under the heading “General Terms” it is provided:

This Agreement may be changed at any time by the Company. It is the responsibility of the User to keep himself/herself updated with the current version of the Agreement. Users and Members waive any claim with regarding this issue.

Secondly, under “Membership and Users of the Platform” it is provided:

This agreement may be changed at any time by the Company. It is the responsibility of the user to keep himself/herself updated with the current version of the Agreement.

Third, clause (b) of the “Representation and Warranties” section provides:

b.    You will follow all acceptable use policies and all other terms and conditions relating to the use of the services in respect of the website, and will not transmit offensive material, junk messages, advertisements or any type of solicitation whatsoever of any products or services to other members of the service.

Fourth, clause (h) of the “Representation and Warranties” section provides:

h.    You agree that the Company reserves the right to change any of the terms, rights, obligations, privileges… with or without providing notice of such change. You are responsible for reviewing the information and terms of usage as may be posted from time to time. Continued use of the services or non-termination of your membership after changes are posted or emailed constitutes your acceptance or deemed acceptance of the terms as modified. \[emphasis added\]

156    Clause (h) is a somewhat unusual clause which permits Quoine unilaterally to alter the Agreement without notice but it unclear as to precisely how this can be done. The use of the expression “_rights, obligations, privileges_” in addition to the word _“terms_” introduces a measure of uncertainty as does the reference not merely to the _terms of usage_ but also to _the information_ which may be posted. The last sentence, however, refers solely to the _“_terms as modified”. Clause (h) encompasses the first two passages cited above and thus it is only necessary to consider the scope of that clause.

157    The Risk Disclosure Statement does what its name suggests. It is entitled “Risks in Virtual Currency Transactions” and the introduction states:

There are many risks associated with virtual currency transactions. Please read the following to gain a sufficient understanding of the features, mechanisms, and risks in virtual currency transactions. _Please execute your transaction with understanding such features, mechanisms and risks without objection_ and based on your own judgment and responsibility. \[emphasis added\]

158    Ten separate risks are described, two of which are material in this case. The first, “Risks due to Stop-Out”, relates to the right of Quoine unilaterally to place a market order to force-close a margin trader’s positions in the event that the trader’s liability exceeds its collateral:

**7**.     **Risks due to Stop-Out**

<Characteristics of margin trading>

The stop-out system allows the Company to cancel non-executed new orders and **_forcibly execute a reversing trade, and settle all, of a customer’s positions to protect the customer from escalating losses when the customer’s margin falls short of the Company’s prescribed ratio of the margin to required margin_** **(the “stop-out,”** which the Company may change at its discretion).

The amount of a loss will not be determined until the settlement is completed **_because the final settlement price in the case of a stop-out is determined by market prices_****.**

If market circumstances shift dramatically or something else happens, **_the final settlement price may significantly differ from the one at the time the transaction was initiated, and it is possible that a customer’s loss may exceed the amount that the customer has deposited with the Company_**_._ Customers must promptly deposit any shortfall in funds with the Company. \[emphasis added\]

159    The second, “System Risks”, applies to both spot and margin traders:

**8**.     **System Risks**

<For both spot and margin trading>

Customers execute transactions using an electronic transaction system. If a customer incorrectly enters an order, the customer’s intended order may not be executed, or an unintended order may be executed.

The electronic transaction system may be unusable temporarily or for a certain period for many reasons, such as malfunctioning telecommunications or system equipment, or telecommunication network problems at the Company or a customer, or an order may be invalidated if a customer's instructions for placing an order arrive late (or not at all) to the Company's system. In addition, a customer's ability to transact may be suspended in some cases whenever there is an electronic transaction system failure.

If there is a sudden and severe change in the market, etc., the retrieval of price information may be delayed, leading to discrepancies between the price information on the electronic transaction system and the actual market prices.

If information such as the login ID or password used for electronic verification on the electronic transaction system is leaked due to a theft or intrusion, etc., the information may be fraudulently used by a third party, and the relevant customer may suffer losses.

There is the risk that a system failure may occur due to changes to the external environment, etc., and this may disrupt a customer’s ability to execute transactions. A “system failure” is when the Company finds that a malfunction (not including the obstructed network lines or problems with a customer's computer, etc.) has clearly arisen in the system required to provide the Company’s services, and customers are no longer able to place orders over the Internet (the Company's website, mobile site, or applications) or customers' orders arrive late or cannot be placed.

Please be aware that in the event that a customer loses any opportunity (e.g., the Company is unable to receive a customer’s order and the customer therefore loses the opportunity to place the order, losing profits that he or she ordinarily would have earned) due to emergency system maintenance or a system failure, the Company will not be able to execute a process to fix the error because it will be unable to identify the order details that the customer intended to place (the original order). **_The system may produce an aberrant value for the buy or sell price of the virtual currency calculated by the system. Please be aware that if the Company finds that a transaction took effect based on an aberrant value, the Company may cancel the transaction. Your understanding is appreciated._** \[emphasis added\]

160    Quoine contends that when the Risk Disclosure Statement was uploaded onto the website on 22 March 2017, it had the effect, _inter alia_, of introducing a new term into the Agreement expressly permitting the Defendant to cancel a transaction if it had taken place based at an aberrant value (the “aberrant value clause”). It accepts that no express notice was placed on the website drawing attention to the fact that the Agreement had been modified as a result of the uploading of the Risk Disclosure Statement. It contends, however, that on its true interpretation the combined effect of clause (h) with the preceding clause (b) of the Agreement does not require this to be done. The mere uploading of the Terms and Conditions was sufficient to modify the Agreement to incorporate the aberrant value clause which automatically came into effect without notice to the users of the Platform and regardless of whether they had seen it or not. The Risk Disclosure Statement constitutes “information” and/or “terms of usage” within the meaning of clause (h) because it changed the terms on which users could trade on the Platform and altered their rights. Finally, it contends that the seven trades on 19 April 2017 were based on an aberrant value so it was contractually entitled to reverse the trades.

161    B2C2 disputes these contentions. It asserts:

(a)     that the Risk Disclosure Statement was not within the scope of clause (h); more specifically that since the Risk Disclosure Statement and the Agreement were accessible via different links on the website, the two could not be read together and there was no other indication on the website that the Risk Disclosure Statement did contain additional terms of the Agreement;

(b)     that the Risk Disclosure Statement was a mere summary of risks and was not a document which a reasonable reader would expect to contain contractual terms; more specifically that the aberrant value clause was too vague and imprecise to constitute a contractual term and was inconsistent with the express irreversibility term;

(c)     that clause (h) was contrary to section 3(2)(_b_)(i) of the Unfair Contract Terms Act (Cap 396, 1994 Rev Ed) (“UCTA”); and

(d)     that under common law where a condition is particularly onerous and unusual, the party seeking to enforce it must show that the condition was brought to the notice of the other party, relying on _Interfoto Picture Library Ltd v Stiletto Visual Programmes Ltd_ .

162    The following preliminary matters therefore need to be considered.

(a)     First, what is the effect in law of a unilateral variation clause such as clause (h)?

(b)     Second, when can an alleged term be incorporated into an existing contract in circumstances where that term is contained in a separate document and itself has no independent contractual effect?

163    As to the first, unilateral variation clauses are not unlawful _per se_, in the sense that a party can reserve to itself the right to amend a contract without first obtaining the consent of the other party, but it is an unusual power and thus there must be clear language to reserve this sort of power: see _Wandsworth London Borough Council v D’Silva_ \[1998\] IRLR 193 and _OCBC Capital Investment Asia Ltd v Wong Hua Choon_ . I accept therefore that clause (h) is a lawful clause, the meaning and scope of which is a matter of contractual interpretation. Whilst it is not necessary for the consent of the other party to be obtained to any such modification, it must be a requirement that the other party has the means of knowing that there has been a modification and what that modification is. Again the way in which this is to be done will be a matter of interpretation of the clause in question.

164    As to the second, it was contended that it was not legally necessary for a document, parts of which contained terms which were said to be incorporated into a contract, itself to have contractual force so long as the particular terms sought to be incorporated were capable of having contractual effect. Reliance was placed on passages in Sir Kim Lewison’s _The Interpretation of Contracts_ (Sweet & Maxwell, 6th Ed, 2015) (“_Lewison_”) at pp 127–128:

(_c_)     _Incorporation of other documentary material_

It is not necessary for the incorporated document itself to have any contractual force or indeed any legal effect; it may be merely a printed form. The terms of the incorporated document must, however, be capable of having contractual force. In _Keeley v Fosroc International Ltd_, Auld L.J. said:

“On the question of construction… where a contract of employment expressly incorporates an instrument such as a collective agreement or staff handbook, it does not necessarily follow that all the provisions in that instrument or document are apt to be terms of the contract. For example, some provisions, read in their context, may be declarations of an aspiration or policy falling short of a contractual undertaking; see e.g. _Alexander and others v Standard Telephones and Cables Ltd. (No.2)_ \[1991\] I.R.L.R. 286, per Hobhouse J, as he then was, at paragraph 31; and _Kaur v MG Rover Group Ltd_ \[2005\] I.R.L.R. 40, CA, per Keene L.J., with whom Brooke and Jonathan Parker L.J.J. agreed, at paragraphs 9, 31 and 32. It is necessary to consider in their respective contexts the incorporating words and the provision in question incorporated by them.”

Likewise, in _Martland v Co-operative Insurance Society Ltd_, Elias P. said:

“Not all terms typically found in a collective agreement will be incorporated. That is so, even where the contract of employment ostensibly incorporates all relevant terms from the collective agreement. In order to be apt for incorporation the terms must, by their nature and character, be suitable to take effect as contractual terms. Some collective terms will not do so because, for example, they are too vague or aspirational, or because their purpose is solely to regulate the relationship between the collective parties.”

In _Harlow v Artermis International Corp Ltd_, an employee’s letter of engagement stated that: “All other terms and conditions are as detailed in the Staff Handbook as issued to you, and subject to its most recent update”. It was held that certain paragraphs of the employer’s redundancy policy described in the Staff Handbook had been incorporated into the contract.

In _Hyundai Merchant Marine Co Ltd v Americas Bulk Transport Ltd (The Pacific Champ)_, the effect of the parties’ dealings was to incorporate a pro forma charterparty which had no independent contractual effect, although it was held on the facts that no contract came into existence.

165    I therefore accept that it is legally permissible for a term of a contract to be contained in another document which is not itself a document having contractual effect, but it must be clear that the term in question is intended to have contractual effect and the term itself must have sufficient clarity to be contractually enforceable. Again this will be a matter of interpretation.

166    However, in the case of the employment law authorities cited in _Lewison_, the contract of employment expressly referred to the fact that some additional terms and conditions were to be found in the other document and in the _Hyundai_ case the contention was that the previous dealings between the parties had served to incorporate some additional terms from another document (the _pro forma_ charterparty) into the alleged agreement even though it had no independent contractual effect. The parties have not referred me to any authority or work of reference which considers the question that arises here; where it is contended that a document which is not identified in the main agreement as containing additional terms of the contract or has not come by the dealings between the parties to be accepted as containing such clauses is said to contain an additional term, being a term which constitutes a fundamental variation to the existing terms of the contract.

167    I do not consider that it would be legally impermissible for such a term to be incorporated from a document which had not been previously accepted by the parties for one reason or another as containing additional clauses, even if those clauses were such as to introduce a fundamental change in the contractual relationship. In my judgment, clauses could be incorporated from such a document in an appropriate case but it is likely to be an exceptional case where a document which had not previously been specifically identified by the parties as likely to contain any terms would be effective to introduce a term modifying an existing term. It will be a question of fact in each case whether the document in question could properly be said to be one which the parties intended and understood to be capable of effecting such a change.

168    With that background I can turn to consider the interpretation of clause (h). It must be read as a whole in the context of the Agreement and in the light of the surrounding circumstances when the Agreement was made: _Zurich Insurance (Singapore) Pte Ltd v B-Gold Interior Design & Construction Pte Ltd_ ; _Y.E.S. F&B Group Pte Ltd v Soup Restaurant Singapore Pte Ltd_ . The first sentence reads:

“You agree that the Company reserves the right to change any of the terms, rights, obligations, privileges… with or without providing notice of such change”

This sentence is clear on its face. It gives the Company the right to alter the Agreement without the consent of the Members and it is not required to give express notice to them.

169    The fact that it is express notice that is being excluded is apparent from the subsequent sentences. The second sentence reads:

“You are responsible for reviewing the information and terms of usage as may be posted from time to time”.

which makes it clear from this that any changes can be communicated indirectly by being posted on the website.

170    This is confirmed by the third sentence:

“Continued use of the services or non-termination of your membership after changes are posted or emailed constitutes your acceptance or deemed acceptance of the terms as modified.”

which serves to highlight that notice of change may be communicated directly to each Member by e-mail or indirectly by posting it on the website. The Member is then given the opportunity to terminate its membership in consequence.

171    This clause therefore indicates the way in which each Member is to be informed of changes. It can be done by posting the changes on the website. On its true interpretation the clause does not permit Quoine to change the terms without drawing this to the attention of the Members in some way. It is not enough merely to upload an amended agreement and expect the Members diligently to review the Terms and Conditions on the website at regular intervals and seek to discern any changes. Read as a whole, I have concluded that the use of the word “information” in the second sentence means information relating to the terms of usage, such as a notice on the website that the terms have changed.

172    But this does not answer the question of how the requisite notice can be given. The most natural way of doing it, other than by way of an e-mail directly to each of the Members, would be either to upload the new agreement containing the modified or additional terms together with a notice on the website drawing attention to the fact that changes had been made or, alternatively, to set out the changes in full in a notice on the website.

173    Quoine did not do this but instead merely uploaded the Risk Disclosure Statement onto the website. It did not otherwise draw attention to the fact that this document was intended to contain modifications to the Agreement. The following questions therefore arise on the first two contentions of B2C2 set out in \[162\] above.

(a)     Could uploading the Risk Disclosure Statement onto the website on 22 March 2017 have served to amend the Agreement pursuant to Clause (h)?

(b)     If it did, is the aberrant value clause sufficiently clear to be enforceable?

(c)     Finally, do the provisions of clause (b) affect matters?

#### (a)   Could the uploading the Risk Disclosure Statement onto the website on 22 March 2017 have served to amend the Agreement pursuant to Clause (h)?

174    As to the first of these, the starting point is that at the date B2C2 became a Member there was no Risk Disclosure Statement. The only document which could contain terms of the contract between the parties was the Agreement. Hence a Member reading the Agreement at the date it was signed by B2C2 would perceive that the only “terms, rights, obligations, privileges” that could be changed were those in the Agreement and would therefore naturally assume that any changes would be incorporated directly into the Agreement. There is no evidence that the Members were ever informed that changes would be implemented in any other way. It is therefore necessary to have regard to the events on 22 March 2017 when the Risk Disclosure Statement was uploaded to see whether this makes it clear that the Risk Disclosure Statement was one which the parties intended and understood to be capable of effecting such a change and which indicated with sufficient clarity that changes were to be made.

175    Quoine’s then webpage looked like this:

![]([2019] SGHC(I) 0003_Image/[2019] SGHC(I) 0003_image1.png)

176    The Risk Disclosure Statement can be found by clicking on the “Risks in Virtual Currency Transactions” link seen at the bottom of the right hand column whereas the Terms and Conditions (the Agreement) are towards the top of the left hand column. There is nothing in either document which invites the reader to read the two together. On its face the Terms and Conditions plainly are intended to have legal effect. The introduction states _“This agreement is entered into by and between Quoine Pte Ltd and the user of Quoine (User or Member)…”._ On the other hand, the Risk Disclosure Statement purports to be a summary of risks with no indication that it is intended to have legal effect. I do not consider that even the most assiduous reader of the website would have any reason to believe when reading the Risk Disclosure Statement that hidden within it there would be amendments to the Terms and Conditions. He or she would not be reading them with this in mind. The aberrant value clause forms part of a larger paragraph dealing with lost opportunities due to system failure and the possibility that the system might wrongly produce a wrong price. Although it purports to give Quoine a discretion to reverse trades in certain circumstances, this is to my mind far too tangential a passage to constitute any form of notice that changes were to be made to the Agreement.

177    For all these reasons I have concluded that the uploading of the Risk Disclosure Statement onto the website on 22 March 2017 could not serve to amend the Agreement.

#### (b)   If it did, is the aberrant value clause sufficiently clear to be enforceable?

178    If I were to be wrong on this, I would have concluded that the aberrant value clause was sufficiently clear to be enforceable. Evidence was adduced of not dissimilar express clauses in agreements for use of other platforms and, although the word “aberrant” begs the question “how aberrant?”, this is a matter of judgment in each case which courts and tribunals are used to exercising.

#### (c)   Do the provisions of clause (b) affect matters?

179    Quoine refers to this as the “Incorporation Clause” and contends that in combination with clause (h), this indicated that the parties had contemplated and agreed that the Agreement could be supplemented by other terms and conditions which may be posted on the website; that such terms and conditions could be amended from time to time; and that when posted on the website would be incorporated as part of the terms and conditions governing use of the Platform.

180    I cannot accept this. It is reading far too much into clause (b) which, read as a whole, is merely requiring Members to comply with existing use policies and not to misuse the Platform. It is nothing to do with supplementing the Agreement with other terms and conditions. If clause (h) by itself cannot assist Quoine, clause (b) cannot make things any better.

181    Quoine was accordingly not entitled to reverse the trades on the basis of an express term of the Agreement when read in conjunction with the Risk Disclosure Statement.

182    It is therefore not necessary to decide on the assertions made by B2C2 in (c) and (d) at \[161\] above. Both arguments, that clause (h) was contrary to section 3(2)(_b_)(i) of the UCTA and that under common law where a condition is particularly onerous and unusual, the party seeking to enforce it must show that the condition was brought to the notice of the other party, were directed to Quoine’s assertion that no notice of any form, whether direct or indirect, was necessary. I have not accepted that this was the case on the true interpretation of clause (h).

### Defence 3. Is Quoine entitled to reverse the trades on the basis that the contracts between B2C2 and the Counterparties were void under the doctrine of unilateral mistake at common law?

183    This contention is raised on the basis that, contrary to the previous argument, there was a breach of contract in reversing the seven trades. In these circumstances, Quoine asserts that the doctrine of unilateral mistake, either at common law or in equity, renders the Trading contracts void or voidable. If this was the case, then Quoine would not be in breach of the Platform contract when it reversed the seven trades. I have found this issue to be the most troubling and difficult in this case.

#### The Law on Unilateral Mistake

184    The law in relation to unilateral mistake has been developed over the years in common law jurisdictions and was comprehensively considered in Singapore by the Court of Appeal in _Chwee Kin Keong and others v Digilandmall.com Pte Ltd_ (“_Chwee_”).

185    In _Chwee_, the defendant sold products over the internet using two different websites. A particular Hewlett Packard laser printer was advertised for sale on both websites at a price of $3,854. One afternoon, an employee of the defendant mistakenly altered the price of the printers to $66. The error was not identified until the following morning when a potential customer checked with the defendant whether the price was correct. The error was then corrected.

186    During the period while the mistaken price was left uncorrected, 784 people made a total of 1,008 purchases for 4,086 printers. On discovering the mistake, the defendant informed all the purchasers that it would not honour the orders because of the mistake. The plaintiffs who between them had ordered hundreds of printers brought an action to enforce the sales and were met with a defence of unilateral mistake. The defendant succeeded at trial before V K Rajah JC (as he then was). The plaintiffs appealed to the Court of Appeal.

187    The judgment of the Court of Appeal was delivered by Chao Hick Tin JA. The following passages should be noted:

**Unilateral mistake in common law**

30    We will first consider the statements of law advanced by the judge below. It is trite law that, as a general rule, a party to a contract is bound even though he may have made a mistake in entering into the contract. The law looks at the objective facts to determine whether a contract has come into being. The real motive or intention of the parties is irrelevant: see Treitel, _The Law of Contract_ (Sweet & Maxwell, 11th Ed, 2003) at 1. The _raison d’etre_ behind this rule is the promotion of commercial certainty.

31    However, there is an exception to this rule when the offeree knows that the offeror does not intend the terms of the offer to be the natural meaning of the words: see _Shogun Finance Ltd v Hudson_ (“_Shogun Finance_”) at \[123\] and _Hartog v Colin & Shields_ \[1939\] 3 All ER 566 (“_Hartog_”). The reason behind this exception is self-evident, as a party who is aware of the error made by the other party cannot claim that there is _consensus ad idem._ The law should not go to the aid of a party who knows that the objective appearance does not correspond with reality. It would go against the grain of justice if the law were to deem the mistaken party bound by such a contract.

…

33    Indeed, in law, there are three categories of mistake, namely, common, mutual and unilateral mistakes. In a common mistake, both parties make the same mistake. In a mutual mistake, both parties misunderstand each other and are at cross-purposes. In a unilateral mistake, only one of the parties makes a mistake and the other party knows of his mistake. For the purpose of the present proceedings, we are only concerned with the effect of a unilateral mistake.

34    However, it does not follow that every mistake would vitiate a contract. It has to be a sufficiently important or fundamental mistake as to a term for that to happen. There is no doubt that the error in the present case as to the price is a fundamental one. Accordingly, it is wholly unnecessary for us to deal with the question as to what nature of mistake would constitute a serious mistake sufficient to vitiate a contract. It is also unnecessary for us to address a related controversial question whether a mistake as to quality, or the substance of the thing contracted for, is of sufficient gravity to negate an agreement.

…

37    Accordingly, the law will declare void a contract which was purportedly entered into where the non-mistaken party was actually aware of the mistake made by the mistaken party. This proposition is not in dispute. But should this rule also apply to a case where the non-mistaken party did not have actual knowledge of the error but ought to have known about the other party’s mistake, _ie_, where there is constructive knowledge? The judge below thought that it should be the case.

38    Rajah JC found, at \[140\] and \[142\], that the appellants had actual knowledge that the price stated on the websites was a mistake. However, he also found, in the alternative, that the appellants had constructive knowledge (at \[144\]–\[145\]):

I find, in the alternative, that the \[appellants\], given each of their backgrounds, would in any event, each have separately realised and appreciated, before placing their purchase orders, that a manifest mistake had occurred – even if no communications on the error had taken place between them. Further, the character of the mistake was such that any reasonable person similarly circumstanced as each of the \[appellants\] would have had every reason to believe that a manifest error had occurred. ...

If the price of a product is so absurdly low in relation to its known market value, it stands to reason that a reasonable man would harbour a real suspicion that the price may not be correct or that there may be some troubling underlying basis for such a pricing. ...

…

40    It is clear that the state of a person’s mind is a question of fact. It has to be proved like any other fact. In _Vallance v The Queen_ (1961) 108 CLR 56, Windeyer J put the point very eloquently at 83:

A man’s own intention is for him a subjective state, just as are his sensations of pleasure or of pain. But the state of another man’s mind, or of his digestion, is an objective fact. When it has to be proved, it is to be proved in the same way as other objective facts are proved.

41    As is so often alluded to in the cases, in the absence of an express admission or incontrovertible evidence, the fact of knowledge would invariably have to be inferred from all the surrounding circumstances, including the experiences and idiosyncrasies of the person and what a reasonable person would have known in a similar situation. If a court, upon weighing all the circumstances, thinks that the non-mistaken party is probably aware of the error made by the mistaken party, it is entitled to find, as a fact, that the former party has actual knowledge of the error. Following from that holding, the court should declare the contract so formed as void on the ground of unilateral mistake.

42    In order to enable the court to come to the conclusion that the non-mistaken party had actual knowledge of the mistake, the court would go through a process of reasoning where it may consider what a reasonable person, placed in the similar situation, would have known. In this connection, we would refer to what is called “Nelsonian knowledge”, namely, wilful blindness or shutting one’s eyes to the obvious. Clearly, if the court finds that the non-mistaken party is guilty of wilful blindness, it will be in line with logic and reason to hold that that party had actual knowledge.

43    This then gives rise to the question as to the circumstances under which a party should make inquiry. When should such a party make inquiries failing which he would be considered to be shutting his eyes to the obvious? We do not think this question is amenable to a clear definitive answer. Situations in which such a question could arise are infinite. But we could accept what Mance J said in _OT Africa Line Ltd v Vickers Plc_ \[1996\] 1 Lloyd’s Rep 700 (“_OT Africa_”) at 703 that there must be a “real reason to suppose the existence of a mistake”. What would constitute “real reason” must again depend on the circumstances of each case. Academicians may well query whether this should be based on an “objective” or “subjective” test. At the end of the day, the court must approach it sensibly. The court must be satisfied that the non-mistaken party is, in fact, privy to a “real reason” that warrants the making of an inquiry.

44    Here, we would reiterate that expressions such as “taking advantage”, “good faith”, “snapping up”, used by the courts to describe the situations under consideration were often just the bases upon which the court, in each case, had come to its conclusions as to whether the non-mistaken party had actual knowledge of the error made by the mistaken party. While we recognise that the distinction between actual knowledge and constructive knowledge can be a fine one and can often be difficult to discern, it is nonetheless not something unfamiliar to the courts. The courts are accustomed to making such a distinction.

…

53    In our opinion, it is only where the court finds that there is actual knowledge that the case comes within the ambit of the common law doctrine of unilateral mistake. There is no _consensus ad idem_. The concept of constructive notice is basically an equitable concept: see _The English and Scottish Mercantile Investment Company, Limited v Brunton_ at 707 _per_ Lord Esher MR. In the absence of actual knowledge on the part of the non-mistaken party, a contract should not be declared void under the common law as there would then be no reason to displace the objective principle. To the extent that the judge below seems to have thought otherwise, _ie_, that where the non-mistaken party has constructive knowledge of the mistake the contract thus entered into would be void under common law, we would respectfully differ. (emphasis added)

188    Accordingly, in order to succeed in rendering a contract void under the common law doctrine of unilateral mistake, the Defendant must show, first, that there was a sufficiently important or fundamental mistake as to a term of the contract, in the sense that the offeror did not intend the terms of the offer to be that which on its face was offered and, secondly, that the Plaintiff who is seeking to enforce that contract must have actual knowledge of the mistake. Actual knowledge is to be determined by the court as a question of fact and it is sufficient if the court concludes that the person in question was probably aware of the mistake or that he or she was shutting her mind to the obvious. The principle or purpose underlying the doctrine is set out in _Chwee_ at \[31\]:

The law should not go to the aid of a party who knows that the objective appearance does not correspond with reality. It would go against the grain of justice if the law were to deem the mistaken party bound by such a contract.

189    The distinction between actual knowledge and constructive knowledge, which acts not to render the contract void at law but to make it voidable in equity is, as the Court of Appeal accepted, a narrow one. The distinction lies in the difference between actual knowledge, determined as set out above, and constructive knowledge in the sense that although the person in question did not have actual knowledge, he or she ought to have known about the other’s mistake.

190    Chao Hick Tin JA considered the equitable jurisdiction in the following passages in _Chwee_:

62    The equitable jurisdiction of the courts has developed over the years to ameliorate the rigours of the common law and to give relief where justice so requires. The main authority which the court below relied upon to reject the existence of an equitable jurisdiction in the courts to deal with unilateral mistake is _Great Peace Shipping_ where Lord Phillips of Worth Matravers MR, who delivered the judgment of the English Court of Appeal, found difficulties with Denning LJ’s broad formulation of the equitable jurisdiction in _Solle v Butcher_ because of his failure to distinguish between what was void in law and what was voidable in equity.

63    However, it seems to us that there is probably another reason why the court below had to come to that conclusion. By holding that the doctrine of unilateral mistake in common law encompasses even situations where the non-mistaken party does not have actual knowledge but only constructive knowledge of the mistake, there will hardly be any need or room for the intervention of equity. This is of great importance for, as we will come to later, even in equity, constructive knowledge _per se_ will not entitle the mistaken party to relief. Rajah JC’s concept of the common law doctrine of unilateral mistake would be wider than what we envisage the scope of the court’s equitable jurisdiction should be.

…

70    … The case of _Riverlate Properties Ltd v Paul_ \[1975\] Ch 133 is instructive as it illustrated the circumstances under which the court should exercise its equitable jurisdiction. There, the plaintiff lessor, through its agent, had mistakenly omitted to insert a clause to place the defendant lessee under an obligation to bear a part of the cost of the exterior and structural repairs of the demised premises. The lessor sought rectification, or, alternatively, rescission in equity on the ground that the lessor had made a mistake which the lessee and/or her agent knew. The English Court of Appeal held that as the error was purely that of the lessor and/or its solicitors and the lessee and/or her solicitors had no knowledge of such error and were not guilty of anything approaching sharp practice, there were no grounds to intervene. Russell LJ said (at 141):

If reference be made to principles of equity, it operates on conscience. If conscience is clear at the time of the transaction, why should equity disrupt the transaction? If a man may be said to have been fortunate in obtaining a property at a bargain price, or on terms that make it a good bargain, because the other party unknown to him has made a miscalculation or other mistake, some high-minded men might consider it appropriate that he should agree to a fresh bargain to cure the miscalculation or mistake, abandoning his good fortune. But if equity were to enforce the views of those high-minded men, we have no doubt that it would run counter to the attitudes of much the greater part of ordinary mankind (not least the world of commerce), and would be venturing upon the field of moral philosophy in which it would soon be in difficulties.

…

74    A simple way to distinguish _Great Peace Shipping_ from the present case would be to say that it was a case on common mistake and, to that extent, what was discussed therein could not be applicable to a case involving unilateral mistake. However, we would go further than that. We would be loath to hold that there is no equitable jurisdiction in the courts with regard to unilateral mistake just because it may be difficult to delineate the scope or extent of that jurisdiction. By its very nature, the manner in which equity should be applied must depend on the facts of each case and the dictates of justice. Equity has intervened in many aspects of human dealings in the contractual setting. For example, it has rescinded a contract induced by innocent misrepresentation: see _Redgrave v Hurd_ (1881) 20 Ch D 1. Often, a case on innocent misrepresentation does raise issues of mistake. Equity has also intervened where there is undue influence. As such, we see no logic in denying the existence of this jurisdiction in the area of unilateral mistake. Additionally, it should be noted that two subsequent English High Court decisions, _Huyton SA v Distribuidora Internacional de Productos Agricolas SA de CV_ \[2003\] 2 Lloyd’s Rep 780 and _Harrison v Halliwell Landau_ \[2004\] EWHC 1316, had accepted that the equitable remedy of rescission for unilateral mistake still survived _Great Peace Shipping_.

75    We appreciate that there are difficulties in delineating precisely the considerations which should apply for equity to intervene. One suggested way to differentiate the application of the common law rule and equity would be to hold that the former is limited to mistakes with regard to the subject matter of the contract (like that in _Bell v Lever Bros_), while the latter can have regard to a wider and perhaps open-ended category of “fundamental” mistake: see _William Sindall Plc v Cambridgeshire County Council_ _per_ Hoffmann LJ at 1042.

76    In view of the difficulties, one may be tempted to take a clear simplistic approach, namely, where there is actual knowledge, the contract would be void at common law. But where there is no actual knowledge, the contract ought to be performed. There would then be no room for equity to operate. But we believe that simplicity may not always lead to a just result, especially where innocent third parties are involved.

77    We do not think this court should approach the issue in a rigid and dogmatic fashion. Equity is dynamic. A great attribute, thus an advantage, of equity, is its flexibility to achieve the ends of justice. Constructive notice is a concept of equity and whether constructive notice should lead the court to intervene must necessarily depend on the presence of other factors which could invoke the conscience of the court, such as “sharp practice” or “unconscionable conduct”. Negligence _per se_, on the other hand, should not be sufficient to invoke equity. Parties to a contract do not owe a duty of care to each other.

78    However, “unconscionability” cannot be imputed based on what a reasonable person would have known. It must be based on matters the non-mistaken party knows: see _Can-Dive Services v Pacific Coast Energy Corp_ (2000) 74 BCLR (3d) 30 (“Can-Dive”) per Southin JA at \[142\]. One cannot act unconscionably if one does not know of facts which could render an act so. Thus, we do not think we can accept the views of Shaw J, the lower court judge in _Can-Dive_, that constructive knowledge alone would suffice to invoke equity’s conscience. However, as we have indicated earlier, Canadian jurisprudence has moved in that direction.

79    The point is raised by the appellants as to the relevance of the negligence of the mistaken party. Clearly, more often than not, whenever a mistake has occurred, there would have been carelessness, though the degree may vary from case to case. This will be a factor which the court should take into account to determine where equity lies. All we would add is that carelessness on the part of the mistaken party does not, _ipso facto_, disentitle that party to relief.

80    To the extent that the court below thought that there is no equitable jurisdiction in the courts to deal with the situation where one party is mistaken as to an important or fundamental term, we would respectfully disagree. Where the case falls within the common law doctrine of unilateral mistake, there is, in effect, no contract. There will be no room for equity to intervene. But where it does not and the court finds that there is constructive knowledge on the part of the non-mistaken party, the court would, in the exercise of its equitable jurisdiction, be entitled to intervene and grant relief when it is unconscionable for the non-mistaken party to insist that the contract be performed. Accordingly, we accept the _amicus curiae_’s submission that constructive knowledge alone should not suffice to invoke equity. There must be an additional element of impropriety. The conduct of deliberately not bringing the suspicion of a possible mistake to the attention of the mistaken party could constitute such impropriety.

…

83    In contrast, once the court should hold that a contract comes within the common law principle of unilateral mistake, it is void _ab initio_ for all purposes. Moreover, as pointed out earlier, the line between actual knowledge and constructive knowledge may often be hard to draw. In a difficult case where the court is not convinced that the non-mistaken party has actual knowledge but is well satisfied that there is constructive knowledge and where there is evidence of unconscionable conduct or sharp practice on the part of the non-mistaken party, relief in equity may be granted on terms to ensure that justice is attained with regard to all affected parties.

191    There thus must not only be constructive knowledge but, in addition, there must be an element of impropriety. Further, carelessness on the part of the mistaken party does not of itself disentitle it to relief but is a factor to be taken into account. Regard may be had to any loss or damage to innocent third parties in weighing the equitable balance.

192    Although _Chwee_ involved the use of computers as the means by which the plaintiffs placed their orders at the erroneous price, it was otherwise no different from a classic case such as _Hartog v Colin & Shields_ \[1939\] 3 All ER 566. In _Chwee_, the first plaintiff was well aware that the offer was too good to be true and alerted his friends who also bought the printers. The mistake was a mistake by a human in getting the price wrong and the knowledge was actual knowledge of the other party to the contract at the time the contract was made. The price was a fundamental term of the contract.

193    The only difference between the facts in _Chwee_ and in _Hartog_ was that in the latter there was only one contract whereas in the former, because of on-line buying, there were a number of contracts before the mistake was spotted.

194    On the facts in _Chwee_, it was a plain case. Here, computers are involved in a different way. There was no human intervention at the time the seven trades were effected. On the facts, no human was aware of the trades until after they had been happened.

195    The doctrine of unilateral mistake is well developed in circumstances where the error is a human error and the nature of the error and the knowledge or lack of it is directly ascertainable from the humans involved. Where computers are concerned, the law is less well developed. In his judgment at first instance in _Chwee Kin Keong and others v Digilandmall.com Pte Ltd_ , V K Rajah JC made the following observation at \[102\]:

Inevitably mistakes will occur in the course of electronic transmissions. This can result from human interphasing, machine error or a combination of such factors. Examples of such mistakes would include (a) human error (b) programming of software errors and (c) transmission problems in the communication systems. Computer glitches can cause transmission failures, garbled information or even change the nature of the information transmitted. This case is a paradigm example of an error on the human side. Such errors can be magnified almost instantaneously and may be harder to detect than if made in a face to face transaction or through physical document exchanges. Who bears the risk of such mistakes? It is axiomatic that normal contractual principles apply but the contractual permutations will obviously be sometimes more complex and spread over a greater magnitude of transactions. The financial consequences could be considerable. The court has to be astute and adopt a pragmatic and judicious stance in resolving such issues. (emphasis added)

196    Quoine relied on this passage in support of a submission that in a case such as the present, where algorithmic trading is involved, the court should adopt a pragmatic and judicious stance such that, although there may be a need for certainty that an executed trade will stand, there is a greater need to protect the market from the potentially harmful consequences of a clearly erroneous trade. Quoine went on to submit that, in consequence the court “should intervene where the trade is clearly erroneous and it would be unjust to allow the trade to stand having regard to the circumstances in which it was executed”.[\[note: 45\]](#Ftn_45)

197    I do not read the observations of Rajah JC as justifying a fundamental change in the law of mistake which as it currently exists requires a mistake in a fundamental term coupled with knowledge or constructive knowledge of that mistake. Quoine’s formulation accepts the need for a clearly mistaken trade but does not focus on the requisite knowledge. The law is clear, regardless of whether relief is sought in law or in equity, it will not be granted unless it is shown that the non-mistaken party had the requisite knowledge of the mistake. The potential magnitude of the consequences of the mistake cannot serve to change the law.

198    That said, it is plain that applying the law to a case where algorithmic trading is involved does raise new questions. What mistakes have been made and to what extent are they fundamental? How does one assess knowledge or intention when the whole operation is carried out by computers acting as programmed? Whose knowledge is relevant? At what date is this knowledge to be assessed?

199    The researches of counsel and by the court have failed to identify any authority dealing directly with these questions.

200    Quoine submits that the Court should consider what the parties are likely to have known and intended if, hypothetically, they had met on the “floor of the exchange” for the purpose of reaching an agreement on the trades on 19 April 2017. On this basis, as I understand it, it is contended that mistakes can be identified by comparing theoretically what would have happened in face-to-face negotiations with what actually happened at the computer interface.

201    Quoine further submits that the law should treat the algorithms or computers used to enter contracts as the legal agents of their human principles and relied on two learned articles in support, namely L Scholz “Algorithmic Contracts” (2017) 20 Stanford Technology Law Review 128 and S Chopra & Laurence White “Artificial Agents and the Contracting Problems: A solution via an Agency Analysis” (2009) University of Illinois Journal of Law, Technology & Policy. On the basis of this, Quoine went on to contend that in answering the hypothetical question as to knowledge or intention on the part of the non-mistaken party, the Court should consider what the programmer of the software in question would have known and intended when writing the software at the time that software was written.

202    B2C2 contends that there must be a mistake as to a term of the contract and that the party placing the order, albeit by a computer, must be the person mistaken. It was not sufficient if there was a mistake as to facts surrounding that term. In this respect therefore B2C2’s position was that the assessment of a relevant mistake was no different in the case of computer transactions than in face-to-face transactions.

203    Further, relying on _Chwee_, B2C2 contends that the only relevant knowledge is knowledge at the time of contracting and suggests that it is wrong to assess knowledge or constructive knowledge at the time the deep price mechanism was programmed.

204    So far as concerns the nature of the mistake, I cannot accept Quoine’s hypothetical meeting contention. The question is not what would have happened if the computer element was absent. The parties have chosen to use computers as the means of entering the Trading contracts. They have entered Platform contracts with Quoine so as to be able to enter Trading contracts and, in the case of margin traders, they have entered the Margin trading contracts to regulate their position vis-à-vis the lender, in this case Quoine. All parties were therefore aware that there was to be no human element in the trades and it is wholly artificial to work on the basis of what might have happened if a human element was involved. Equally whilst B2C2’s position identifies what the nature of the mistake must be, it does not assist in determining how and when to identify it.

205    In the circumstances of this case, I have concluded that the relevant mistake must be a mistake by the person on whose behalf the computer placed the order in question as to the terms on which the computer was programmed to form a Trading contract in relation to that order. This mistake will have to be in existence at the date of the contract in question but may have been formed at an earlier date. The existence of a relevant mistake will be a question of fact in each case.

206    Turning to knowledge of the mistake, the law in relation to the way in which ascertainment of knowledge in cases where computers have replaced human actions is to be determined will, no doubt, develop as legal disputes arise as a result of such actions. This will particularly be the case where the computer in question is creating artificial intelligence and could therefore be said to have a mind of its own.

207    As Lord Briggs observed in a recent UK Supreme Court decision, _Warner-Lambert Co Ltd v Generics (UK) Ltd_ \[2018\] UKSC 56, at \[165\]:

Even if the manufacturer is a corporation using a factory entirely staffed by robots, if the manufacturing process is only protected by the patent if it is carried out for a particular purpose, the requirement to identify a mental element on the part of the manufacturer is simply inescapable. The court is well versed in identifying the governing mind of a corporation and, when the need arises, will no doubt be able to do the same for robots. \[emphasis added\]

208    So also with computers used for trading purposes. Where the law is in a formative state it is, I think, appropriate for a court (of first instance at any rate) to develop the law only so far as necessitated by the facts of the case before it. With this in mind I do not intend to express any views on the precise legal relationship between computers and those who control or program them. The algorithmic programmes in the present case are deterministic, they do and only do what they have been programmed to do. They have no mind of their own. They operate when called upon to do so in the pre-ordained manner. They do not know why they are doing something or what the external events are that cause them to operate in the way that they do.

209    They are, in effect, mere machines carrying out actions which in another age would have been carried out by a suitably trained human. They are no different to a robot assembling a car rather than a worker on the factory floor or a kitchen blender relieving a cook of the manual act of mixing ingredients. All of these are machines operating as they have been programmed to operate once activated.

210    Where it is relevant to determine what the intention or knowledge was underlying the mode of operation of a particular machine, it is logical to have regard to the knowledge or intention of the operator or controller of the machine. In the case of the kitchen blender, this will be the person who put the ingredients in and caused it to work. His or her knowledge or intention will be contemporaneous with the operation of the machine. But in the case of robots or trading software in computers this will not be the case. The knowledge or intention cannot be that of the person who turns it on, it must be that of the person who was responsible for causing it to work in the way it did, in other words, the programmer. Necessarily this will have been done at a date earlier than the date on which the computer or robot carried out the acts in question. To this extent I reject B2C2’s contention that that the only relevant knowledge is knowledge at the time of contracting. I agree with Quoine that regard should be had to the knowledge and intention of the programmer of the program in issue when that program (or the relevant part of it) was written.

211    Accordingly, in my judgment, in circumstances where it is necessary to assess the state of mind of a person in a case where acts of deterministic computer programs are in issue, regard should be had to the state of mind of the programmer of the software of that program at the time the relevant part of the program was written. In the present case that person is Mr Boonen.

#### Applying the Law to the Facts: Obvious Mistake at common law.

212    Stepping back, it is clear that if a number of errors or omissions had not occurred, Quoine would have, or would very likely have, avoided any liability.

(a)     Quoine could have included a specific clause in the Agreement entitling them to reverse abnormal trades. Other platform operators had done so. Quoine was considering this and did so in September 2017.

(b)     The failure properly to update the login credentials in Quoine’s Quoter Program.

(c)     The failure to incorporate an exception message in the Quoter Program to alert Quoine to the fact that it was not working.

(d)     The failure to incorporate a circuit breaker in the Platform’s software to prevent trades when the order book was empty.

(e)     The failure to incorporate a circuit breaker to prevent orders at an abnormal price from being placed on the order book.

(f)     The failure to ensure that, in the case of a force-closure, the forced sales were only within a given price range.

(g)     The failure to ensure that, in the case of a force-closure, only assets which were actually held by a counterparty in its account at the time were the subject of a market order.

213    Mr Lozada very fairly conceded that many of these steps could have been taken and were not.[\[note: 46\]](#Ftn_46) It is with this background that I turn to consider what are said to be the mistakes which it is alleged that Mr Boonen had either actual or constructive knowledge of when he wrote the relevant part of the program. The substantive plea is in paragraph 16 of the Defence:

In the circumstances, the Counterparties were not bound by the Trades and/or the Defendant had the right and/or was entitled to reverse and/or cancel the Trades and/or deduct the proceeds received by the Plaintiff from the Trades from the Account on the basis that (a) the Trades and/or Contracts were entered into by a unilateral mistake on the part of the Counterparties and (b) consequently, the Contracts were void _ab initio_ for unilateral mistake at common law or voidable for unilateral mistake in equity.

214    Particulars are then given. Particulars (b) and (c) read as follows:

(b)    The Counterparties did not intend to enter into the Trades and the Contracts and/or to transact at the prices of 9.99999 or 10 BTC for 1 ETH.

(c)    Further and/or in the alternative, the Defendant avers that at the time that the Trades were executed, the Counterparties held and/or were operating under the mistaken belief and/or assumption and/or understanding that (i) the Plaintiff and the Counterparties were contracting to buy or sell BTC or ETH at the actual market prices of ETH/BTC pursuant to the Trades and/or Contracts; and/or (ii) the price of 9.99999 or 10 BTC for 1 ETH accurately represented the actual market prices of ETH/BTC which were or ought to have been available on the Platform on 19 April 2017; and/or (iii) the Force Closure Orders were placed and the Trades were executed in circumstances where the Platform operated in the correct manner and/or as it was intended to function and under normal market conditions on the Platform.

215    These particulars were refined in paragraph 38 of the Defendant’s Closing Submissions:

38.    In our submission, the Court is entitled to and ought to find that the Contracts were void for unilateral mistake in common law on the following grounds:

(a)    The Counterparties entered into the Contracts under the mistaken belief, understanding and/or assumption that it was necessary to close out their positions in response to the margin calls which the Platform made on them _i.e._, that it was necessary enter into the Contracts.

(b)    The Counterparties entered into the Contracts under the mistaken belief, understanding and/or assumption that they were buying ETH for BTC under the Contracts at prices which accurately represented or did not deviate significantly from the true market value and/or price of ETH relative to BTC on the Platform as of 19 April 2017.

(c)    B2C2 had actual knowledge of the mistakes made by the Counterparties.

216    As to the first of these, Quoine submits that if the Quoter Program had not malfunctioned the Platform would not have detected the Counterparties to be in breach of their margin requirements and the force-closure orders would never have been placed. On this basis it is said that if B2C2 and the Counterparties had hypothetically met on the exchange floor for the purpose of reaching agreement, they would not have agreed to enter into contracts at the deep prices. As indicated above, I do not accept that this is the correct approach. The question that must be asked is whether the Counterparties mistakenly believed that the Platform computer was so programmed as to ensure that it was necessary to close out their positions in response to the margin calls.

217    There is no suggestion that the Platform computer acted otherwise than in accordance with its instructions. It is not suggested that in the circumstances which had occurred, including in particular the absence of sufficient liquidity as a result of the Quoter Program not working properly, the Platform computer was in error in assessing that a margin call was necessary. The question is directed to the Counterparties’ beliefs as to what would happen in relation to margin calls in circumstances of illiquidity.

218    The evidence in relation to this aspect of the case is sparse. There is nothing in the Risk Disclosure Statement which supports the asserted belief. Indeed, it points in the other direction as Risks 6 and 7 demonstrate:

**6**.     **Risks Due to Leverage Effects, etc.**

<Characteristics of margin transactions>

In virtual currency margin trading, the margin principal and profit are not guaranteed.

Virtual currency margin trading involves significant risks due to leveraging. The more leverage you use, the more you can trade relative to the actual amount of money that you invest (including the amount of deposited margin), so you may reap bigger profits, but your losses may also similarly increase significantly if market prices are inconsistent with your expectations.

Therefore, the Company may execute a compulsory reversing trade of your entire position and settle the transaction using the Company’s prescribed methods to protect you from escalating losses in the case that the market moves in a direction that is unfavorable to your position, and you may suffer greater losses than the money you invested (including the amount of deposited margin).

**7**.     **Risks Due to Stop-Out**

<Characteristics of margin trading>

The stop-out system allows the Company to cancel non-executed new orders and forcibly execute a reversing trade, and settle all, of a customer’s positions to protect the customer from escalating losses when the customer’s margin falls short of the Company’s prescribed ratio of the margin to required margin (the “stop-out,” which the Company may change at its discretion).

The amount of a loss will not be determined until the settlement is completed because the final settlement price in the case of a stop-out is determined by market prices.

If market circumstances shift dramatically or something else happens, the final settlement price may significantly differ from the one at the time the transaction was initiated, and it is possible that a customer’s loss may exceed the amount that the customer has deposited with the Company. Customers must promptly deposit any shortfall in funds with the Company.

219    It is therefore necessary to have regard to Mr Tseung’s evidence to see whether, notwithstanding this, he held the asserted belief. Mr Tseung was one of the co-founders of Pulsar, the primary Counterparty. He gives evidence that when he identified that a margin call had been made on Pulsar he was both alarmed and surprised because he considered that because of the fact that Pulsar’s leveraged positions with Quoine were not substantial, there should have been no risk of Pulsar breaching Quoine’s margin requirements.[\[note: 47\]](#Ftn_47) He then discussed the incident with Mr Lozada and concluded that the depletion of the order book and/or the placement of B2C2’s orders had caused the Platform wrongly to evaluate Pulsar’s positions and detect that Pulsar had breached its margin requirements[\[note: 48\]](#Ftn_48). Two points should be made. First the evidence shows that the margin call was not caused by B2C2’s orders and secondly, there is no evidence that the margin call was wrongly made in the circumstances that did exist due to the illiquidity in the order book.

220    Mr Tseung went on to give evidence that he considered that the Platform should have been programmed to check whether the available balances under Pulsar’s account were sufficient before placing any orders to sell and that, accordingly the Platform should not have placed the market orders in excess of this. As indicated above, Mr Lozada accepted that this was an error on his part but I do not consider that it is an error which is material to the Trading contracts. It may (but I make no finding of this) have given Pulsar a claim against Quoine under the Margin contract but that is all.

221    Mr Tseung was not cross-examined on his evidence and it therefore stands unchallenged. The belief which is asserted is that the Platform computer was so programmed as to ensure that it was necessary to close out their positions in response to the margin calls. In one respect it was necessary to close out the positions because the illiquidity had caused the computer to identify the need for a margin call. It had acted as programmed. The point that I think is being made is that Mr Tseung believed that the computer would not get it wrong and would only force-close in circumstances that would have led to a margin call if everything was operating properly. Again, therefore, it is hard to see how this could be an error which is material to the Trading contracts. Mr Tseung does not give evidence that he believed that once a margin call had been made the relevant market orders would not be placed.

222    Whilst I therefore accept that Mr Tseung genuinely held the belief that there would only be a margin call if everything was working properly and one was then justified, I do not accept that this was a mistaken belief which is in any way fundamental to a term of the Trading contracts.

223    In any event, on the basis of the findings of fact as to Mr Boonen’s knowledge in \[124\] above that were no grounds for concluding that he ever turned his mind to the relationship between the margin traders and those who had loaned them money, it must follow that even if the mistaken belief was relevant to the Trading contracts, the requisite actual knowledge cannot be ascribed to Mr Boonen. The Trading contracts thus cannot be avoided on the basis of this alleged belief on the grounds of a unilateral mistake at common law.

224    The second alleged mistaken belief is that the Counterparties entered the contracts under the mistaken belief that they were buying at prices which accurately represented or did not deviate significantly from the true market price as of 19 April 2017. This is therefore a plea that Mr Tseung believed that, whatever happened on the Platform, if there was to be a margin call, this call would only be executed at or near the prevailing “world-wide price” (_ie_, an average of the prices available on all BTC/ETH exchanges and not the actual price on Quone’s Platform at the time of the trades). Mr Tseung was no doubt familiar with the concept of market making and would therefore have known that the market making system on the Platform would have involved a process akin to that which should have been the case if Quoine’s Quoter Program had been working properly. On that basis he formed the belief that no trade would be carried out otherwise than at what I have called the world-wide price.

225    Again there is no support for this belief in the Agreement or in the Risk Disclosure Statement as the following passages demonstrate:

\[From the Agreement\]

**Trading & Order Execution**

Only registered users or Members are allowed to buy, sell and use the services provided by the Platform. The exchange functions of The Platform will fill in orders at the best possible available market price. Note that as markets move continuously, the prices displayed on user interfaces, on our web app or on mobile apps are in no way guaranteed. The Platform, however, has been designed to allow members to fill at best possible prices and in a timely manner. Nevertheless the Company will not be liable under any circumstances for the consequences of any delay in order filling or failure to deliver or perform. Furthermore, once an order is filled, you are notified via the Platform and such an action is irreversible.

\[From the Risk Disclosure Statement\]

**Risks in Virtual Currency Transactions**

There are many risks associated with virtual currency transactions. Please read the following to gain a sufficient understanding of the features, mechanisms, and risks in virtual currency transactions. Please execute your transaction with understanding such features, mechanisms and risks without objection and based on your own judgment and responsibility.

1.     **Price Fluctuation Risk**

<For both spot and margin trading\*>

Virtual currency is not legal tender and does not have legal tender as an underlying asset. The value of virtual currency fluctuates all the time. The value of virtual currency may be affected by trends in the prices of goods, legal tender, the securities market, and other markets, natural disasters, war, political upheaval, strikes, increased regulation, the spread of other similar virtual currencies, or an unexpected or extraordinary event that occurs in the future. Therefore, the value of the virtual currency that you hold or the value of your virtual currency transaction may change rapidly or drop sharply. Please also be aware that the value of virtual currency may fall below the purchase price or may drop to zero.

\* “Margin trading” in this material means contract for difference (CFD) trading.

**3**.     **Liquidity Risk**

<For both spot and margin trading>

Depending on market trends or trade volumes, etc., your transaction may be difficult or impossible to execute, or you may be forced to execute it at a very unfavorable price.

<Characteristics of margin trading>

Depending on market trends or trade volumes, etc., it may be difficult to execute a reversing trade of your position, potentially widening your losses.

226    The expression “best possible available market price” in the Agreement must be a reference to the best price available on the Platform rather than on other platforms as is made clear by the later statement under the “The Platform Data & Content Copyright” section of the Agreement which draws a distinction between the actual price available on the Platform and “live market value data” provided by Quoine for which Quoine accept no responsibility.

227    Mr Tseung, however, gives evidence[\[note: 49\]](#Ftn_49) that because the trades were carried out at the highly abnormal price, they were clearly invalid and that Pulsar did not consider them to be valid. He went on to state “\[i\]t was never contemplated by Pulsar that any trades may be transacted on the Platform at prices which deviated so substantially from the actual market prices”. Although he gave no reasons for holding this belief, he was not cross-examined on this statement and I therefore accept that this was a genuinely held belief. Indeed, having heard all the evidence, I can well understand that a trader on the Platform who was not a market maker might well have formed such a belief even having read the Agreement and the Risk Disclosure Statement. It is a belief which is founded on the premise that the Platform would either always operate as intended or, alternatively, if for some reason it did not, there would be adequate error identification and protection systems in place to prevent trading continuing in such circumstances.

228    I therefore accept that the Counterparties held this mistaken belief and that it is a belief which is fundamental to the Trading contracts.

229    It is next necessary to determine whether Mr Boonen had actual knowledge of the mistaken belief at the time he inserted the deep prices and I thus return to the findings of fact in \[118\]–\[125\] above. Can it be said that Mr Boonen knew that “it was never contemplated by \[any trader\] that any trades would be transacted on the Platform at prices which deviated so substantially from the actual market prices”? This amounts to a belief held by Mr Boonen at that date that the price was so abnormal that no trader would trade at that price otherwise by way of a mistake.

230    This is the aspect of this case that I have found to be most troubling but I have concluded on the basis of those findings of fact that Mr Boonen did not insert the deep prices with that belief. He foresaw that a number of factors might arise which would cause the deep prices to be inserted and the overriding reasons for them being inserted was to protect B2C2 in the event of the unexpected happening. He did not exclude the possibility of trades at those prices being executed. Whilst he was aware that one possible cause was that it could be the result, wholly or in part, of some error or omission on the part of someone, including himself, he did not turn his mind in any detail to the circumstances that might lead to such trades being executed. He knew that the Platform was an automated system and that therefore no opportunity would arise for any particular trade to be reviewed by the parties in advance. In the circumstances of this case, in order for him to have actual knowledge that other traders believed that in no circumstances would a trade be transacted on the Platform at prices which deviated so substantially from the actual market prices, I consider that it would be necessary for it to be demonstrated that he held that belief himself, which he did not: see \[123\] above.

231    Accordingly, whilst I accept that the Counterparties held the second mistaken belief relied upon by Quoine, I do not accept that Mr Boonen had actual knowledge of that belief. The defence of unilateral mistake at common law therefore fails.

### Defence 4. Is Quoine entitled to reverse the trades on the basis that those contracts were voidable under the doctrine of unilateral mistake in equity?

232    In order to succeed in equity, Quoine must prove first, that notwithstanding the fact Mr Boonen did not have actual knowledge, he had constructive knowledge, in the sense that he ought to have known about the Counterparties’ mistaken belief. Secondly, the requisite impropriety must be shown to exist.

233    For constructive knowledge to exist on the facts of this case it must be demonstrated that Mr Boonen was acting irrationally in forming the views that he did and that any reasonable person in his position would have known that no other trader would have contemplated trades being executed at those prices. However, that person has to be placed in the exact position of Mr Boonen, knowing the reasons why he acted as he did and his motivation for inserting the deep prices. It would then be necessary to conclude that such a person could not have had the mindset of Mr Boonen. Having read Mr Boonen’s written evidence and heard him give evidence in a lengthy cross-examination, I am satisfied that his thought processes were rational and that he did not turn a blind eye to that which would have been obvious to everyone else in his position. On the facts of this case therefore, once actual knowledge has been rejected there is no place for a finding of constructive knowledge.

234    In these circumstances, it not necessary to consider the question of impropriety. It was however argued and I shall therefore give brief reasons for concluding that the required impropriety was not present. The impropriety in question must lie in some form of unconscionable conduct or sharp practice; mere carelessness on the part of the mistaken party does not disentitle it to relief in equity but due consideration must be given to the position of innocent third parties.

235    On the facts of this case there are no innocent third parties. Although not a party to the Trading contract, Quoine was the only other party involved and it cannot be thought of as an innocent third party. Indeed, had Quoine acted as it accepted it could and should have acted there would have been no margin call.

236    On the back of its assertions that Mr Boonen deliberately included the deep prices with the intention of triggering a margin call and/or with an underlying intention of manipulating the market, Quoine submitted at various times that B2C2’s conduct was predatory, opportunistic, unethical, improper, unconscionable and tantamount to sharp practice. I have however rejected those assertions and have concluded that although opportunistic, this was not sinister (see \[125\] above) but was the result of a business decision to ensure that an unlikely event resulted in a profit not a loss. There is nothing unconscionable in this when all relevant factors are taken into account – particularly the number and extent of the errors and omissions that played a part in the trades being executed: see \[212\] above. Had I concluded that there was constructive knowledge I would nonetheless have held that there was no impropriety. The defence of unilateral mistake in equity therefore fails.

### Defence 5. Is Quoine entitled to reverse the trades on the basis that those contracts were void under the doctrine of mutual mistake at common law?

237    The law in relation to mutual mistake was not in dispute. B2C2 referred me to the Court of Appeal decision in _Olivine Capital Pte Ltd v Chia Chin Yan_ and Quoine to the recent decision of the English High Court in _Triple Seven MSN 27251 Ltd v Azman Air Services Ltd_ \[2018\] EWHC 1348. It is common ground that four requirements, in particular, have to be met. First, at the time of the contract, there must be an assumption shared by both parties as to a particular state of affairs. Secondly, that assumption must be fundamental to the performance of the contract. Third, the assumption must have been wrong and fourth, performance of the contract must either be impossible or be radically different to what was contemplated. There are other aspects to the defence but in the circumstances of this case I need not consider the law further.

238    As with the defence of unilateral mistake, Quoine contends that the correct approach is to ask the hypothetical “meeting on the floor of the exchange” question: see \[200\]–\[204\] above. For the same reasons I reject that approach in relation to mutual mistake as well. Quoine went on to submit that at the time the trades were executed both parties wrongly assumed that (i) the Platform was working correctly and (ii) that therefore the trades were being transacted at normal market conditions, (_ie_, at prices which accurately reflected or did not deviate significantly from the world-wide price).

239    Even if Quoine held the mistaken belief as to price, on the facts as they have been found, it is plain that Mr Boonen did not. Once therefore the hypothetical meeting on the floor of the exchange is rejected, it must follow that, if the defence of unilateral mistake fails, the defence of mutual mistake must fail also.

### Defence 6. Is Quoine entitled to reverse the trades on the basis of unjust enrichment?

240    Paragraph 18 of the Defence pleads:

Further and/or in the alternative, the Defendant had the right to and/or was entitled to reverse and/or cancel the Trades and/or deduct the proceeds received by the Plaintiff from the Trades from the Account in order to prevent the Plaintiff from being unjustly enriched, at the expense of the Counterparties and/or the Defendant, if it was allowed to retain the proceeds from the Trades executed at the Abnormal Rate by mistake.

241    The doctrine of unjust enrichment provides a cause of action for one party against another party who has received a benefit from the first party in circumstances which make it unjust for the second party to retain the benefit. There are three elements to the claim: _Singapore Swimming Club v Koh Sin Chong Freddie_ at \[90\]. First there must have been a benefit that was received by or which accrued to the second party. Second the benefit or enrichment must be at the expense of the first party. Thirdly, that enrichment must be unjust.

242    Had Quoine not reversed the seven trades, B2C2 would have received a substantial benefit in terms of the BTC that had been transferred into its account. This benefit would have been at the expense of the Counterparties who would have had to make up the shortfall between the BTC actually in their accounts and those that had been transferred pursuant to their margin trading contracts with Quoine. As a matter of legal formality therefore, on the facts of this case, the cause of action does not accrue until after B2C2 succeeds in this litigation and has the benefit that it should have had if Quoine had not wrongly reversed the trades. Further, technically, it is a cause of action vested in the Counterparties who are not parties to this action rather than in Quoine.

243    This, however, is a matter of form rather than substance. If as a result of this action B2C2 receive money or money’s worth whether as a result of damages for breach of contract or by way of specific performance (and the magnitude of that sum is not limited by the limitation of liability clause) then this would technically be at the expense of the Counterparties.

244    In this case, however, it has been pleaded as a defence and B2C2 has not sought to strike it out. It joined issue with it in its Reply and the case was argued on the basis that it was properly raised as a defence. It was only in B2C2’s written closing submissions that the legal position was first raised. I therefore propose to treat it as a defence so that the substance of the matter may be decided.

245    The first two requirements of unjust enrichment are satisfied in this case. The sole issue is whether it would be unjust in the circumstances of this case for B2C2 to retain the proceeds of the Trades. Both parties drew my attention to the decision of the Court of Appeal in _Wee Chiaw Sek Anna v Ng Li-Ann Genevieve (sole executrix of the estate of Ng Hock Seng, deceased)_ (“_Anna Wee_”) together with extracts from the well-known works of reference, _Goff & Jones: The Law of Unjust Enrichment_ (Sweet & Maxwell, 9th ed, 2016) (“_Goff & Jones_”) and Andrew Burrows_, The Law of Restitution_ (Oxford University Press, 3rd ed, 2011) (“_Burrows_).

246    It is sufficient to cite the following passage from _Anna Wee_ at \[132\]–\[134\] where the Court of Appeal quoted from both _Burrows_ and an earlier edition of _Goff & Jones_:

132    This list of “unjust factors” has been catalogued in academic treatises. _Burrows_ …, for example, summarised the unjust factors as follows (at p 86):

As regards the cause of action of unjust enrichment, the main unjust factors can be listed as follows: mistake, duress, undue influence, exploitation of weakness, human incapacity, failure of consideration, ignorance, legal compulsion, necessity, illegality and public authority ultra vires exaction and payment.

133     _Goff & Jones_ summarised them as follows (at para 1-22):

Lack of consent and want of authority; mistake; duress; undue influence; failure of basis; necessity; secondary liability; _ultra vires_ receipts and payments by public bodies; legal incapacity; illegality; and money paid pursuant to a judgment that is later reversed.

134    It is important to reiterate that there is no freestanding claim in unjust enrichment on the abstract basis that it is “unjust” for the defendant to retain the benefit – there must be a particular recognised unjust factor or event which gives rise to a claim. The following observations by Prof Birks in a seminal article are, in this regard, apposite (see Peter Birks, “The English recognition of unjust enrichment” \[1991\] LMCLQ 473 (at 482)):

‘Unjust’ is the generalization of all the factors which the law recognizes as calling for restitution. Hence, at the lower level of generality the plaintiff must put his finger on a specific ground for restitution, a circumstance recognized as rendering the defendant’s enrichment ‘unjust’ and therefore reversible.

247    In this case Quoine maintains that the unjust factors are mistake and lack of consent due to ignorance. It contends that in the circumstances in which the trades were executed, they were executed as a result of the automated actions taken by Quoine’s systems which would not have occurred if the Quoter Program was operating properly. Essentially the mistakes relied upon are the same as were raised in respect of unilateral mistake. First, the mistake as to the necessity of making the margin call, which I have rejected as being a mistaken belief and therefore need not be considered further. Secondly, the mistake as to the “world-wide price” which I have held to be an honestly held but mistaken belief.

248    Thirdly, it is asserted that the benefit had been conferred upon B2C2 without the consent of the Counterparties because the Counterparties believed, wrongly, that the margin call would only relate to BTC which were actually held in their accounts. I have held that this is not a mistake which is relevant to the Trading contracts.

249    B2C2, however, contends that regardless what the mistakes or lack of consent were, if the defences of mistake fail then the case on unjust enrichment must also necessarily fail. The contract is valid and therefore the fact that one party has made a bad bargain does not prevent the other party who has made a good bargain from keeping the fruits of the contract. My attention was drawn to two passages, one from _Burrows_ and the other from _Goff & Jones_:[\[note: 50\]](#Ftn_50)

\[From _Burrows_\]

(**a**)     **Defendant’s legal entitlement**

(_i_)     _The general rule_

Where the defendant is legally entitled to the enrichment – in the sense that that enrichment is owed to it by the claimant under a valid legal obligation – there can normally be no liability to make restitution despite there being an unjust factor. The reason for this is that the prima facie injustice established by the unjust factor is normally outweighed by the fact that the defendant is legally entitled to the enrichment. Overall, therefore, the enrichment is not unjust. Although sometimes overlooked, this qualification should be seen as a significant qualification to the width of the unjust factors.

\[From _Goff & Jones_ at para 9-94\]

Where a benefit is mistakenly conferred by one party on another under a contract, a claim in unjust enrichment will commonly fail even if the mistake would otherwise support such a claim. As we explain in \[Chapter 3\], the contract will bar the claim, to the extent that it entitles the defendant to receive the relevant benefit. For the claim to succeed, the claimant will need to show that the contract is invalid, being either non-existent, void or voidable. This is not a matter for the law of unjust enrichment, but the law of contract.

250     _Burrows_ goes on to consider exceptions to the general rule as being in cases where the _prima facie_ injustice constituted by there being an unjust factor is not outweighed by the Defendant’s contractual entitlement to the enrichment.

251    The question was considered in a Privy Council decision in _Fairfield Sentry Ltd (in Liquidation) v Migani_ \[2014\] UKPC 9 where at \[18\], Lord Sumption said this:

The basic principle is not in dispute. The payee of money “cannot be said to have been unjustly enriched if he was entitled to receive the sum paid to him”: _Kleinwort Benson Ltd v Lincoln City Council_ at 408B (Lord Hope). Or, as Professor Burrows has put it in his _Restatement of the English Law of Unjust Enrichment_ (2012) at §3(6), “in general, an enrichment is not unjust if the benefit was owed to the defendant by the claimant under a valid contractual, statutory or other legal obligation.” Therefore, to the extent that a payment made under a mistake discharges a contractual debt of the payee, it cannot be recovered, unless (which is not suggested) the mistake is such as to avoid the contract: _Barclays Bank Ltd v W.J. Simms Son & Cooke (Southern) Ltd_ , 695. So far as the payment exceeds the debt properly due, then the payer is in principle entitled to recover the excess.

252    I therefore accept that it is only in exceptional circumstances that a claim for unjust enrichment can succeed where a contract has been held valid. I do not consider that this is such a case. B2C2 was enriched because Quoine failed to take any of the steps necessary to protect itself or the margin traders identified in \[212\] above and the Counterparties did not take any sufficient steps to ensure that their beliefs were correct. This is not a case of B2C2 getting an unjustified windfall, it is the inevitable result of the way the parties have chosen to trade with each other. The defence of unjust enrichment thus fails.

253    The action therefore succeeds both in breach of contract and in breach of trust.

## Relief if Quoine is liable

254    The primary relief sought by B2C2 is specific performance coupled with additional damages. It however accepts that specific performance is a discretionary remedy and will only be ordered where it is just and equitable to do so. The two primary considerations are whether damages would be an adequate remedy and whether the person against whom the relief is being sought would suffer substantial hardship: see _Lee Chee Wei v Tan Hor Peow Victor and others_ at \[53\], and _Lim Beng Cheng v Lim Ngee Sing_ at \[97\].

255    B2C2 asserts that this is a case where damages will not be an adequate remedy because cryptocurrencies in general and BTC in particular are highly volatile so that the inherent value is difficult to ascertain and will thus make damages difficult to assess. I do not accept this. Courts are accustomed to assess damages in relation to volatile assets and this case will be no different.

256    To my mind the compelling factor against ordering specific performance is that it would serve to require Quoine to transfer BTC to B2C2 which it would have to obtain at today’s price which is substantially higher than the price in April 2017 when the trades were executed. B2C2 are market makers, not investors. When the BTC were originally credited to its account the B2C2 software immediately began to hedge the proceeds by selling BTC. Before the trades were reversed, B2C2’s systems had sold slightly under one third of proceeds on nine different exchanges.[\[note: 51\]](#Ftn_51) In these circumstances granting specific performance would cause substantial hardship to Quoine which any potential difficulty in assessing damages does not outweigh.

I therefore decline to order specific performance. B2C2 will be left to a claim in damages for both breach of contract and breach of trust which, if not agreed, will be assessed at a subsequent hearing.

**Conclusion**

257    The action succeeds both in respect of breach of contract and breach of trust but B2C2 are not entitled to an order for specific performance. Its remedy lies only in damages. The parties should liaise in drafting an appropriate order which will be settled at a subsequent hearing.

258    I would like to express my thanks to all the representatives of both parties for the assistance I have received in this case which raised complex questions of both law and fact.

## Annex 1: The Agreement

TERMS AND CONDITIONS

Last updated April 2014

This Agreement (the "Agreement"), effective upon the date of electronic acceptance (the "Effective Date"), pertains to the use of Quoine (the "Platform"), an Internet application fully owned by Quoine Pte. Ltd. (The "Company"), a Singapore based corporation with registration number 201414068E. This agreement is entered into by and between Quoine Pte. Ltd., and the user of Quoine ("User" or "Member") (each herein referred to individually as a "Party", or collectively as the "Parties"). In consideration of the covenants and conditions contained herein, the Parties hereby agree to the following terms and conditions:

General Terms

Quoine is a platform that provides services that allow the exchange of virtual currencies such as Bitcoin for fiat currencies. If you wish register, engage in transactions on Quoine (The Platform), please fully read and understand the terms and conditions that follow.

This is a legal agreement ("Agreement") between you and Quoine Pte. Ltd., which will apply to you regarding any and all services offered by or acquired (the "Services") through the Platform. This Agreement sets forth the terms and conditions governing the access and use of the Platform. This Agreement may be changed at any time by the Company. It is the responsibility of the User to keep himself/herself updated with the current version of the Agreement. Users and Members waive any claim regarding this issue. This Agreement may only be amended with the express consent of the Company. Unless otherwise explicitly stated, the Terms will continue to apply even after termination of your membership to the Platform. If any provision of this Agreement is held invalid, the remainder of this Agreement shall continue in full force and effect.

## Legal Jurisdiction

You expressly agree that any claim or dispute arising from your use of our website and/or our services will be governed by the laws of Singapore without regard to the conflict of law provisions thereof. You further agree that any such claims or disputes shall be resolved in Singapore courts, and you agree to be subject to the personal jurisdiction in, and the exclusive venue of, such courts and waive any objection to such jurisdiction and venue for the purpose of litigating any such claim or dispute.

Membership And Users Of The Platform

Quoine is a platform that provides services that allow the exchange of virtual currencies such as Bitcoin for fiat currencies. If you wish register, engage in transactions on Quoine (The Platform), please fully read and understand the terms and conditions that follow.

This is a legal agreement ("Agreement") between you and Quoine Pte. Ltd., which will apply to you regarding any and all services offered by or acquired (the "Services") through the Platform. This Agreement sets forth the terms and conditions governing the access and use of the Platform. This Agreement may be changed at any time by the Company. It is the responsibility of the User to keep himself/herself updated with the current version of the Agreement. Users and Members waive any claim regarding this issue. This Agreement may only be amended with the express consent of the Company. Unless otherwise explicitly stated, the Terms will continue to apply even after termination of your membership to the Platform. If any provision of this Agreement is held invalid, the remainder of this Agreement shall continue in full force and effect.

## Age Restrictions

Use of the Platform is strictly prohibited to minors or any person under the legal age in his or her country. If you provide inaccurate information about your age in violation of this rule, your registration as a member will be cancelled. By using the Platform, you confirm and guarantee that you meet age requirements.

Personal Information & Privacy Policy

In order to use the Platform services, including but not limited to buying or selling virtual currencies, Users must create an account on The Platform (the "Account"). Your Account will be used to keep various virtual currency amounts as deposited by you as a Member. During The Account creation process, You will be asked to provide certain registration details such as legal names, residential address, scans of personal identification documents and other personal information. This information will be used by The Company in order to verify your identity and for other internal processes related but not limited to Anti-Money laundering, Politically Exposed People, and others as required. In relation with the completion of the registration form, you as a User agree to provide truthful, accurate, current and complete information about Yourself as asked in the registration form and You additionally agree to maintain and immediately update and inform us in writing or via email of any changes to your personal and registration data. As such you agree to keep all personal data and data provided during registration true, accurate, current and complete at all times while You are a Member of The Platform.

Your private information is not displayed to any member or other users of the Platform. The Platform uses industry standards, such as firewalls and SSL for communications between browsers, user interfaces such as mobile apps, and server processes, to safeguard the confidentiality of your personal private information. Note that despite the fact that measures in line with industry standards are taken to prevent disclosure of your private information, all security measures are subject to possible attacks, break-in’s. The Company cannot and does not provide any guarantees regarding the effectiveness of the measures utilized or our ability to prevent other parties, acting unlawfully, from gaining access to information that you provide to us. While the Company will do its utmost to prevent data leaks and illegal break-ins, we cannot and do not guarantee that any personally identifiable information provided to it will not become public under any circumstances.

The Platform may archive information on a regular basis. Archived data may include personal information you provide while using the Platform’s services. The Platform stores that information on servers under the Company’s control or under third parties who have agreed to comply with The Company’s commitments made under this Privacy Policy and with whom the Company has a contractual relationship. Archived information may not be erased even in cases when you terminate your membership on the Platform. Having said this, the Company is under no obligation or guarantee to keep or archive any information and does not warrant that any archived information will later be made available to Members or Users.

The Company may use personal information and Original Content for research for operational purposes or to improve the services it offers or for auditing purposes. The Company will not share your information with third parties, with the exception of disclosures pursuant to lawful requests from legal bodies, such as subpoenas or court orders, or in compliance with applicable laws. Additionally, the Company may share account or other information when it believes it is necessary to comply with law or to protect the Company’s interests or property. This may include sharing information with other companies, lawyers, agents or government agencies.

Fees, Funding & Withdrawals

## Fees

As compensation for The Platform services, including the Exchange and other services provided to you as a Member, The Company charges a fee on each transaction initiated by Members of the Site ("Transaction Fee"). Details of Transaction Fees are found on the main Platform’s site. The Company reserves the right to change, modify or increase Transaction Fee from time to time as it sees fit within reason. Any such updates, modifications or increases will take effect upon posting such changes, modifications or increases on the Platform’s site at www.quoine.com. It is the Member’s responsibility to keep updated with any changes to this agreement and fees.

Transaction Fees are charged to both the buyer and seller. The XBT buyer will be charged a fee in USD/EUR/SGD and the XBT seller will be charged a fee in XBT. Furthermore, Fees are automatically deducted and account balances adjusted accordingly as Members execute buy or sell transactions on the platform.

If You believe that You have been erroneously charged a Transaction Fee, notify The Company immediately and provide all information concerning the transaction. Claims of errors older than 30 days will not be accepted.

## Withdrawals

The Platform will process withdrawals on demand. However, as we follow strict processes of reconciliation with our internal books and records, as well as other processes related to anti-money laundering, and in order to protect the best interests of our members against hacker attacks, we do not keep any bitcoin or any other virtual currencies wallets on line. Therefore, withdrawals can take up to one business day for crypto-currency and three business days for fiat currency to be processed.

By default, Individual user withdrawals in both fiat and bitcoin are limited to 30,000 USD daily and 300,000 USD monthly. Corporate user withdrawals, in both fiat and bitcoin, are limited to a maximum of 100,000 USD daily, and the monthly aggregate total of withdrawals may not exceed 1,000,000 USD in any calendar month.

Limits may be raised upon request of the customer, NOT above the following thresholds:

\- Individual users: up to 50,000 USD daily and 500,000 USD aggregated total in a calendar month

\- Corporate users: up to 150,000 USD daily and 1,500,000 USD aggregated total in a calendar month

## Funding

Regarding funding, funding is accepted via bank wire to local banks in countries covered. Wire instructions and other details are provided to individuals during the funding process.

Furthermore, The Company reserves the right to hold withdrawal requests if the source of the funds is suspected to be illegal. Any funds coming from an account having made a fraudulent deposit will be immediately placed on hold.

Trading & Order Execution

Only registered users or Members are allowed to buy, sell and use the services provided by the Platform. The exchange functions of The Platform will fill in orders at the best possible available market price. Note that as markets move continuously, the prices displayed on user interfaces, on our web app or on mobile apps are in no way guaranteed. The Platform, however, has been designed to allow members to fill at best possible prices and in a timely manner. Nevertheless the Company will not be liable under any circumstances for the consequences of any delay in order filling or failure to deliver or perform.

Furthermore, once an order is filled, you are notified via the Platform and such an action is irreversible.

The Company and its affiliates assume no responsibility for any loss or damage incurred by members or users as a result of their use of The Platform or for a member’s or user’s failure to understand the nature and mechanics of virtual currencies or the markets under which such virtual currencies operate. The Company provides its Users and Members a service via which they can exchange, buy, sell, and/or store certain virtual currencies, and The Company and its affiliates makes no representations or warranties concerning the value, stability, or legality of supported virtual currencies.

The Platform Data & Content Copyright

All content on the Platform is protected under copyright and may not be copied, distributed, modified, published, or transmitted in any means. Violation of this policy may result in infringement of intellectual property rights and could result in significant civil and criminal penalties. Quoine, Quoine Logos, Website Art, and other identifying marks of Quoine are proprietary to the Company. You may not use these marks for any purpose without the express prior written consent of the Company. Except as expressly set forth above, this Agreement does not grant you any express, implied or other license or right under any patent, trademark or copyright of the Company.

The Platform may make market data (pricing and other information related to the virtual currencies supported) available to Members and Users and such data may also be publicly displayed. To the extent that you as a Member or as a User receive access to such data, you expressly agree that you will not redistribute, retransmit, duplicate, or otherwise make such data available in any way, either through automated, manual, or any other means. Any distribution or transmission of The Platform’s live market data is a material breach of this Agreement. Furthermore You, as a Member or a User, agree that The Company is not responsible for any failure or outage in the live market value data provided by The Company.

Representations and Warranties

As a Member or User, you agree to the following:

a.     You will use the website and the services only in a manner that is accepted and legal according to all applicable laws and regulations.

b.     You will follow all acceptable use policies and all other terms and conditions relating to the use of the services in respect of the website, and will not transmit offensive material, junk messages, advertisements or any type of solicitation whatsoever of any products or services to any other Members of the service.

c.     You agree that by posting information or content to any public area of the Platform, you automatically grant, and you represent and warrant that you have the right to grant the Company and other Members an irrevocable, perpetual, non-exclusive, fully-paid, worldwide license to use, copy, perform, display and distribute such information and content and to prepare derivative works of, or incorporate into other works, such content, and to grant and authorize sublicenses of the foregoing.

d.     You agree that use of the service is at your own risk and you are solely responsible for interactions, whether it be written, verbal or in person, with any other Member or User of the service. The Company and its officers, directors, employees, agents, affiliates and third parties assume no responsibility whatsoever for harm that may come to you as a result of your interactions with any other Member or User of the service, including but not limited to verbal and physical abuse or assault.

e       You will not communicate, publish, or display to any other Member or User any form of discriminatory, defamatory, slanderous, offensive, inaccurate, abusive, profane, obscene, sexually offensive, threatening, harassing, racial, or illegal material, including but not limited to nude photos of yourself or others, pornographic images, or images and any other type of unlawful or unacceptable material, as determined by the Company in its sole discretion.

f.     You will not engage in, and the Company is not be responsible for, any form of harassment, offensive or abusive behavior of any kind whatsoever that may be armful to any other Member or User of the service, including but not limited to physical and emotional damage.

g.     You will not conduct any illegal and/or unauthorized uses of the Platform, including but not limited to collecting usernames and/or email addresses of members by electronic or other means for the purpose of sending unsolicited email, forwarding commercial or other offers to other Members either via the Platform messaging tools or by email or by any other means external to the Platform, and unauthorized framing of or linking to the website will be investigated, and appropriate legal action will be taken, including without limitation, civil, criminal, and injunctive redress.

h.     You agree that the Company reserves the right to change any of the terms, rights, obligations, privileges or institute new charges for access to or continued use of services at any time, with or without providing notice of such change. You are responsible for reviewing the information and terms of usage as may be posted from time to time. Continued use of the services or non-termination of your membership after changes are posted or emailed constitutes your acceptance or deemed acceptance of the terms as modified.

i.     You agree to defend, indemnify, and hold harmless the Company, its officers, directors, employees, agents, affiliates and third parties, for any losses, costs, liabilities and expenses (including reasonable attorney’s fees on a solicitor and his own client basis) relating to or arising out of your use of the Platform or services, including any breach by you of this Agreement or other terms and conditions posted on the website from time to time.

Owner Responsibilities

a.     The services we provide are not financial services and the products you buy or sell are not financial products. The Company is not a regulated entity. The Company does not pay interest on funds deposited with The Company in order to buy/sell virtual currencies. As The Company is not a regulated financial institution, funds or virtual currency deposits are not insured by the Company or any government as such.

b.     You, as a Member of the Platform understand and agree that, due to technical and other restrictions, the virtual currency prices displayed by The Platform may be delayed and therefore not reflect the current, live market value of such currency.

c.     Unless otherwise stated at time of posting of information, neither the Company nor its affiliates guarantee the accuracy, completeness, or usefulness of any information on the Platform, and neither adopts, endorses, nor is responsible for the accuracy or reliability of any opinion, advice, or statement made.

d.     The Company reserves the right but has no obligation, whether on the basis of complaints or on its own initiative, to monitor any messaging or other activity and the materials posted in the public areas of the Platform, and to review usage, activity or the content of any messages, materials or other interchanges which are otherwise posted, sent or transmitted via the website. The Company shall have the right in its sole discretion to remove any material or posts, regardless of whether the Company determines that such materials or profiles violate, or are alleged to violate, the law or this agreement. Notwithstanding the foregoing, the Company does not undertake to monitor, control or edit any communications between its Members, and such communications may be offensive to you. You assume full responsibility and you assume all risk for the use of the services, and you are solely responsible for evaluating the accuracy, completeness, and usefulness of all services, products, communications, and other information. In no event the Company or its affiliates will be liable for any incidental, consequential, or indirect damages (including, but not limited to, any deaths, threats, torts or injuries committed by any other users, damages for loss of data, loss of programs, cost of service interruptions or procurement of substitute services) directly or indirectly arising out of the use or inability to use the services, even if the Company, its agents or representatives know or have been advised of the possibility of such damages. Notwithstanding anything to the contrary contained herein, the Company’s liability to you by the Company, its affiliates, for any cause whatsoever, and regardless of the form of the action, will at all times be limited to the amount paid, if any, by you for the services herein. The services are provided on an "as is" basis without any warranties or conditions of any kind, express, implied, statutory, in all communication with the Company, its affiliates or its representatives, or otherwise with respect to the services. The Company and/or its affiliates specifically disclaim any implied warranties of merchantability, fitness for a particular purpose, or non-infringement. Neither the Company nor its affiliates warrant that your use of the services will be secure, uninterrupted, always available, error-free, will meet your requirements, or that any defects in the website will be corrected. The Company and its affiliates disclaim all liability, regardless of the form of action, for the acts or omissions of other Members or Users (including unauthorized users, or "hackers") of the website or services.

## Annex 2: the Risk Disclosure Statement

## Risks in Virtual Currency Transactions

There are many risks associated with virtual currency transactions. Please read the following to gain a sufficient understanding of the features, mechanisms, and risks in virtual currency transactions. Please execute your transaction with understanding such features, mechanisms and risks without objection and based on your own judgment and responsibility.

## 1.   Price Fluctuation Risk

<For both spot and margin trading\*>

Virtual currency is not legal tender and does not have legal tender as an underlying asset. The value of virtual currency fluctuates all the time. The value of virtual currency may be affected by trends in the prices of goods, legal tender, the securities market, and other markets, natural disasters, war, political upheaval, strikes, increased regulation, the spread of other similar virtual currencies, or an unexpected or extraordinary event that occurs in the future. Therefore, the value of the virtual currency that you hold or the value of your virtual currency transaction may change rapidly or drop sharply. Please also be aware that the value of virtual currency may fall below the purchase price or may drop to zero.

\* “Margin trading” in this material means contract for difference (CFD) trading.

## 2.   Business Hours Risk

<For both spot and margin trading>

The value of virtual currency may in some cases fluctuate widely when the Company is not open for business (including when we are performing maintenance). The Company bears no liability whatsoever if you are unable to execute a virtual currency transaction outside of business hours.

## 3.   Liquidity Risk

< For both spot and margin trading >

Depending on market trends or trade volumes, etc., your transaction may be difficult or impossible to execute, or you may be forced to execute it at a very unfavorable price.

<Characteristics of margin trading>

Depending on market trends or trade volumes, etc., it may be difficult to execute a reversing trade of your position, potentially widening your losses.

## 4.   Risks Due to Virtual Currency Networks

When a virtual currency transaction is executed, the transaction will not take effect and will be on hold for a certain period until sufficient transaction confirmation (block chain transaction verification) is completed.

Verification is not required for executing a spot or margin transaction that uses Bitcoin (BTC) or Ethereum (ETH), but the transfer of the virtual currency between the Company and yourself must be verified. Therefore, it is possible that your transaction will not be reflected in your user account balance, the transfer of virtual currency between the Company and yourself may not be completed, or your transaction may be canceled, before sufficient confirmation of the transaction is made in the virtual currency network.

Furthermore, virtual currency may be deleted because it is recorded electronically and its transfer is executed over a network.

## 5.   Risks Due to Changes in Fees, Required Margin, etc.

<For both spot and margin trading>

The Company may amend its rules, etc. on transactions using Bitcoin (BTC) and Ethereum (ETH) in the future. In particular, the Company may change its fees (including the fee rate), the required margin, or the stop order rate, etc. depending on the situation. If these rule changes are made, extra funds may be required due to that change and the chances of being subject to a lstop-out may increase.

## 6.   Risks Due to Leverage Effects, etc.

<Characteristics of margin transactions>

In virtual currency margin trading, the margin principal and profit are not guaranteed.

Virtual currency margin trading involves significant risks due to leveraging. The more leverage you use, the more you can trade relative to the actual amount of money that you invest (including the amount of deposited margin), so you may reap bigger profits, but your losses may also similarly increase significantly if market prices are inconsistent with your expectations.

Therefore, the Company may execute a compulsory reversing trade of your entire position and settle the transaction using the Company’s prescribed methods to protect you from escalating losses in the case that the market moves in a direction that is unfavorable to your position, and you may suffer greater losses than the money you invested (including the amount of deposited margin).

## 7.   Risks Due to Stop-Out

<Characteristics of margin trading>

The stop-out system allows the Company to cancel non-executed new orders and forcibly execute a reversing trade, and settle all, of a customer’s positions to protect the customer from escalating losses when the customer’s margin falls short of the Company’s prescribed ratio of the margin to required margin (the “stop-out,” which the Company may change at its discretion).

The amount of a loss will not be determined until the settlement is completed because the final settlement price in the case of a stop-out is determined by market prices.

If market circumstances shift dramatically or something else happens, the final settlement price may significantly differ from the one at the time the transaction was initiated, and it is possible that a customer’s loss may exceed the amount that the customer has deposited with the Company. Customers must promptly deposit any shortfall in funds with the Company.

## 8.   System Risks

<For both spot and margin trading>

Customers execute transactions using an electronic transaction system. If a customer incorrectly enters an order, the customer’s intended order may not be executed, or an unintended order may be executed.

The electronic transaction system may be unusable temporarily or for a certain period for many reasons, such as malfunctioning telecommunications or system equipment, or telecommunication network problems at the Company or a customer, or an order may be invalidated if a customer’s instructions for placing an order arrive late (or not at all) to the Company’s system. In addition, a customer’s ability to transact may be suspended in some cases whenever there is an electronic transaction system failure.

If there is a sudden and severe change in the market, etc., the retrieval of price information may be delayed, leading to discrepancies between the price information on the electronic transaction system and the actual market prices.

If information such as the login ID or password used for electronic verification on the electronic transaction system is leaked due to a theft or intrusion, etc., the information may be fraudulently used by a third party, and the relevant customer may suffer losses.

There is the risk that a system failure may occur due to changes to the external environment, etc., and this may disrupt a customer’s ability to execute transactions. A “system failure” is when the Company finds that a malfunction (not including obstructed network lines or problems with a customer’s computer, etc.) has clearly arisen in the system required to provide the Company’s services, and customers are no longer able to place orders over the Internet (the Company’s website, mobile site, or applications) or customers’ orders arrive late or cannot be placed.

Please be aware that in the event that a customer loses any opportunity (e.g., the Company is unable to receive a customer’s order and the customer therefore loses the opportunity to place the order, losing profits that he or she ordinarily would have earned) due to emergency system maintenance or a system failure, the Company will not be able to execute a process to fix the error because it will be unable to identify the order details that the customer intended to place (the original order). The system may produce an aberrant value for the buy or sell price of the virtual currency calculated by the system. Please be aware that if the Company finds that a transaction took effect based on an aberrant value, the Company may cancel the transaction. Your understanding is appreciated.

## 9.   Bankruptcy Risk

<For both spot and margin trading>

The Company may not be able to continue its business if the external environment changes (including more stringent regulations regarding virtual currency), the Company’s financial condition deteriorates, or a service provider, etc. retained to provide systems or necessary services to the Company goes bankrupt, etc.

If the Company is no longer able to operate its business, it will carry out procedures under the Bankruptcy Act, the Civil Rehabilitation Act, the Corporate Reorganization Act, the Companies Act, and other applicable laws and regulations, including matters with respect to customer assets.

The Company may receive deposits of money or virtual currency from customers, but the assets deposited by customers will be managed separately from the Company’s assets. The Company does not, however, take client fund safety measures such as depositing them in an account with a trust bank, etc. regarding these assets, so if the Company goes bankrupt, the Company will not be able to return customer assets, and customers may suffer losses.

## 10.   Risks Due to Changes to Legislation and the Tax Code

<For both spot and margin trading>

Many changes are taking place now regarding the laws, regulations, and tax code in relation to virtual currency that applies to individuals who execute virtual currency transactions. In the future, virtual currency may be banned, restrictions or taxes may become more onerous, etc. and holding or trading virtual currency may be restricted or treated less favorably than it is now due to changes to laws, regulations, the tax code, or government policy, etc. In that case, customers may suffer unexpected losses.

Please consult with your tax adviser, certified public tax accountant, lawyer, or other professional for details.

This document is only a summary of risks and does not provide an exhaustive list of all the risks associated with virtual currency trading.

Effective: March 22, 2017

## Annex 3: Copy of the print out forms

![]([2019] SGHC(I) 0003_Image/[2019] SGHC(I) 0003_image2.png)

![]([2019] SGHC(I) 0003_Image/[2019] SGHC(I) 0003_image3.png)

![]([2019] SGHC(I) 0003_Image/[2019] SGHC(I) 0003_image4.png)

* * *

[\[note: 1\]](#Ftn_1_1)Maxime Boonen’s 1st AEIC, para 19.

[\[note: 2\]](#Ftn_2_1)Boonen’s 1st AEIC, paras 12–14.

[\[note: 3\]](#Ftn_3_1)Lozada’s 1st AEIC (undated), paras 9(e) and (f).

[\[note: 4\]](#Ftn_4_1)Lozada’s 1st AEIC, para 11(j).

[\[note: 5\]](#Ftn_5_1)Defendant’s Closing Submissions (“DCS”) at para 63.

[\[note: 6\]](#Ftn_6_1)Certified Transcript (26 November 2018) (in camera) at pp 1 (line 8) to 10 (line 9).

[\[note: 7\]](#Ftn_7_1)Lozada’s 1st AEIC, para 23(a)–(d).

[\[note: 8\]](#Ftn_8_1)Agreed Bundle (“AB”) C 5/338-340 (Exhibit MAGL-28).

[\[note: 9\]](#Ftn_9_1)Lozada’s 1st AEIC, para 20; Certified Transcript (23 November 2018) at pp 86 (line 4) to 88 (line 17).

[\[note: 10\]](#Ftn_10_1)Tseung’s AEIC, para 7.

[\[note: 11\]](#Ftn_11_1)AB C5/341.

[\[note: 12\]](#Ftn_12_1)Boonen’s 1st AEIC, para 62.

[\[note: 13\]](#Ftn_13_1)Certified Transcript (22 November 2018) at p 57 (lines 11-13).

[\[note: 14\]](#Ftn_14_1)Certified Transcript (22 November 2018) at pp 58 (lines 2-6) and 162 (lines 7-13).

[\[note: 15\]](#Ftn_15_1)Certified Transcript (21 November 2018) at p 176 (lines 6-18); Certified Transcript (22 November 2018) at pp 175 (line 4) – 176 (line 4).

[\[note: 16\]](#Ftn_16_1)Certified Transcript (22 November 2018) at p 175 (lines 18-24).

[\[note: 17\]](#Ftn_17_1)Mr Kapoor’s Report, para 131.

[\[note: 18\]](#Ftn_18_1)Certified Transcript (22 November 2018) at pp 19 (line 12) to 20 (line 12).

[\[note: 19\]](#Ftn_19_1)Certified Transcript (22 November 2018) at pp 20 (line 25) to 23 (line 2).

[\[note: 20\]](#Ftn_20_1)Certified Transcript (22 November 2018) at p 60 (lines 2-15).

[\[note: 21\]](#Ftn_21_1)Kapoor’s report, paras 165-167.

[\[note: 22\]](#Ftn_22_1)Boonen’s 3rd affidavit, paras 6-9; Certified Transcript (22 November 2018), pp 38 (line 5) to 58 (line 13).

[\[note: 23\]](#Ftn_23_1)Certified Transcript (22 November 2018) at pp 162 (line 7) – 165 (line 23).

[\[note: 24\]](#Ftn_24_1)Kapoor’s report, paras 153-159.

[\[note: 25\]](#Ftn_25_1)Boonen’s 3rd affidavit, paras 16.3 and 16.4.

[\[note: 26\]](#Ftn_26_1)Atkinson’s 2nd affidavit, paras 30-54.

[\[note: 27\]](#Ftn_27_1)Certified Transcript (22 November 2018) at pp 86 (line 24) to 91 (line 11).

[\[note: 28\]](#Ftn_28_1)Certified Transcript (26 November 2018) (in camera) at pp 32 (line 19) to 36 (line 17).

[\[note: 29\]](#Ftn_29_1)Certified Transcript (26 November 2018) (in camera) at pp 109 (line 7) to 113 (line 10).

[\[note: 30\]](#Ftn_30_1)Defendant’s Opening Statement paras 14 and 27-33.

[\[note: 31\]](#Ftn_31_1)Reply (Amendment No. 3) paras 3.7 and 3.9.

[\[note: 32\]](#Ftn_32_1)Boonen’s 1st AEIC at paras 59-63.

[\[note: 33\]](#Ftn_33_1)Certified Transcript (22 November 2018) at p 62 (lines 2-8).

[\[note: 34\]](#Ftn_34_1)Certified Transcript (21 November 2018) at pp 168 (line 20) to 169 (line 23).

[\[note: 35\]](#Ftn_35_1)Certified Transcript (22 November 2018) at pp 26 (line 7) to 28 (line 3); 35 (line 22) to 36 (line 21).

[\[note: 36\]](#Ftn_36_1)Certified Transcript (22 November 2018) at p 62 (line 14) to 63 (line 5).

[\[note: 37\]](#Ftn_37_1)Certified Transcript (22 November 2018) at pp 97 (lines 3-19); 98 (lines 10-18).

[\[note: 38\]](#Ftn_38_1)Certified Transcript (29 November 2018) at pp 39 (line 22) to 46 (line 2).

[\[note: 39\]](#Ftn_39_1)Certified Transcript (21 November 2018) at p 165 (lines 2-6).

[\[note: 40\]](#Ftn_40_1)Certified Transcript (29 November 2018) at p 165 (lines 7-10).

[\[note: 41\]](#Ftn_41_1)Certified Transcript (22 November 2018) at pp 171 (line 22) to 172 (line 7).

[\[note: 42\]](#Ftn_42_1)See Agreement under “Trading & Order Execution”.

[\[note: 43\]](#Ftn_43_1)AB A Tab 6 at page 107.

[\[note: 44\]](#Ftn_44_1)Certified Transcript (21 November 2018) at p 69 (lines 3 -21); and p 89 (lines 4-8).

[\[note: 45\]](#Ftn_45_1)DCS at para 3.

[\[note: 46\]](#Ftn_46_1)Certified Transcript (23 November 2018) at pp 84 (line 8) – 88 (line 17); 94 (line 23) – 95 (line 9); 125 (lines 2-7); 140 (lines 1 -22); 142 (line 19) – 143 (line 15).

[\[note: 47\]](#Ftn_47_1)AB B3-6 Paragraph 6(1**).**

[\[note: 48\]](#Ftn_48_1)AB B3-8 Paragraph 6(3)(d).

[\[note: 49\]](#Ftn_49_1)AB B3-9 paragraph 8.

[\[note: 50\]](#Ftn_50_1)Plaintiff’s Bundle of Authorities vol 2, tab 32 at p 88; Tab 33 at p 345.

[\[note: 51\]](#Ftn_51_1)Boonen 1st AEIC at paragraph 21.


Source: [link](https://www.lawnet.sg:443/lawnet/web/lawnet/free-resources?p_p_id=freeresources_WAR_lawnet3baseportlet&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&_freeresources_WAR_lawnet3baseportlet_action=openContentPage&_freeresources_WAR_lawnet3baseportlet_docId=%2FJudgment%2F22927-SSP.xml)
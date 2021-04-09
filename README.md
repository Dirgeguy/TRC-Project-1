## Tower Research Capitol
## *Impact of coronavirus pandemic on ETF market*

Hypothesis:
The outbreak of coronavirus has affected the performance of ETF market.

Datasets under study:
1. ETFs of multiple sectors and the SPY index closing price from March 1st 2020 till October 2020.
2. Closing price of random picked common stocks in each sector under study, from March 1st till October 2020.
3. Coronavirus data including, positive test results, negative test results, and death cases across USA.

Structuring the datasets:

The data sets has been divided into two timeframes.
1. From March 1st 2020 till March 31st 2020, in order to capture the initial hit due to pandemic.
2. Timeframe for April 2020 till October 2020, to capture the response of ETF markets to the pandemic.

Sectors under study and corresponding stocks and ETFs:

Materials

    Eagle Materials
    Freeport-McMoRan Inc
    Huntsman Corporation
    Scotts Miracle-Gro Co
    Newmont Corporation
    Materials Select Sector SPDR Fund

Communications

    Discovery Inc
    Face Book
    Google
    AT&T Inc
    CBS Corporation
    Communication Services Select Sector S Fund

Energy

    ConocoPhillips
    Cheniere Energy, Inc
    Murphy Oil Corporation
    ONEOK, Inc.
    Valero Energy Corporation
    Energy Select Sector SPDR Fund

Finance

    Brighthouse Financial Inc
    Citizens Financial Group Inc
    China Life Insurance Co Ltd
    Metlife Inc
    Unum Group
    Financial Select Sector SPDR Fund

Consumer staples

    Campbell Soup Company
    Coca-Cola Co
    Kroger Co
    PepsiCo, Inc
    Procter & Gamble Co
    Consumer Staples Select Sector SPDR F

Consumer discretionery

    Astro Resources N.L.
    EBAY
    Mcdonald's Corp
    MGM Resorts International
    Ross Stores, Inc
    Consumer Discretionary Select Sector SP

Health care

    BIOTON SA
    CVS Health Corp
    Intuitive Surgical, Inc.
    Vertex Pharmaceuticals Incorporated
    Health Care Select Sector SPDR Fund

Real Estate

    Agree Realty Corporation
    AGNC Investment Corp
    Alexander's, Inc
    Alexandria Real Estate Equities Inc
    Real Estate Select Sector SPDR Fund

Technology

    Dell Technologies Inc
    Microsoft Corporation
    NCR Corporation
    NortonLifeLock Inc
    Xerox Holdings Corp
    Technology Select Sector SPDR Fund

Utilities

    American Water Works Company Inc
    Brookfield Infrastructure Partners L.P.
    NRG Energy Inc
    PPL Corp, Sempra Energy
    Utilities Select Sector SPDR Fund

Industrials

    Air Lease Corp
    Huntington Ingalls Industries Inc
    GrafTech International Ltd
    FedEx Corporation
    Vertiv Holdings Co
    Industrial Select Sector SPDR Fund


Assumptions:
1. The data set for covid has significant numbers that can be used for study starting from March 1st. So, underlying assumption is that are no cases before March 1st 2020.

Limitations:
1. The common stocks picked for study in each sector are very random and may not cover the full scope of the sector.

Structure of study:

Step 1: Market Analysis of ETFs from 11 sectors and the SPY index for the two different time frames.

Step 2: Evaluating the impact of pandemic on the markets for the two time frames.

Step 3: Comparing ETF and common stocks of all the 11 sectors along with SPY index for the two time frames and analysing any difference in correlation with covid data.

Statistical methods used:

1. Correlation analysis
2. Standard deviation
3. Beta - to calculate volatility
4. Sharpe ratio - to calculate return per unit of risk

Visual representations used:

1. Heatmap
2. Boxplot
3. scatter diagram
4. Interactive hvplot
5. **Panel dashboard**

The following analysis has been deduced:

Market Analysis :
Sector wise Analysis:
1. Materials:

In March month, the commons stocks and ETF are negatively correlated with covid data.

3% to 40% with positive cases, 1.6% to 45% with negative cases and 6.7% to 36% with death cases. On an average the materials sector was hit by the pandemic and the impact was 35% negative performance.

From April month however, all the stocks and ETF are positively correlated to the covid data, with a range of 55% to 97% with positive cases, 50% to 96% with negative cases and 57% to 96% with death cases.

This shows that market performance improved over the time period despite the pandemic. There has also been a gradula decrease in the volatility in returns for the sector.

2. Communiations:

In March month, the commons stocks and ETF are negatively correlated with covid data.

21% to 60% with positive cases, 24% to 63% with negative cases and 13% to 50% with death cases. On an average the communications sector was hit by the pandemic and the impact was 56% negative performance.

From April month however, except one common stock under comparison, all the others are positively correlated to the covid data, with a range of 29% to 95% with positive cases, 28% to 94% with negative cases and 32% to 98% with death cases.

The volatility of returns remained almost same for the securities under study.

3. Energy:

In March month, the commons stocks and ETF are negatively correlated with covid data.

26% to 45% with positive cases, 29% to 48% with negative cases and 21% to 38% with death cases. On an average the energy sector was hit by the pandemic and the impact was 43% negative performance.

From April month however, couple of common stocks and the ETF under comparison are still negatively correlated and only one common stock is positively correlated to the covid data, with a range of 37% to 52% with positive cases, 39% to 56% with negative cases and 15% to 31% with death cases.

This shows that market performance deteriorated over the time period due to the pandemic. There has also been a decrease in the volatility in returns for the sector.

4. Finance:

In March month, the commons stocks and ETF are negatively correlated with covid data.

2.3% to 38% with positive cases, 0.3% to 41% with negative cases and 8.2% to 29% with death cases. On an average the finance sector was hit by the pandemic and the impact was 33% negative performance.

From April month however, all the stocks and ETF are positively correlated to the covid data, with a range of 37% to 72% with positive cases, 34% to 70% with negative cases and 53% to 77% with death cases.

This shows that market performance improved over the time period despite the pandemic. There has also been a gradula decrease in the volatility in returns for the sector.

5. Industrials:

In March month, most commons stocks and ETF are negatively correlated with covid data. A couple of stocks under study are positively correlated. The magnitudes of positive correlations and negative correlations are similar.

10% to 35% with positive cases, 13% to 35% with negative cases and 19% to 37% with death cases. On an average the industrials sector was hit by the pandemic and the impact was 36% positive to 36% negative performance.

From April month , most of the stocks and ETF are positively correlated to the covid data, the stock that performed better despite the pandemic started going down in performance, with a range of 35% to 98% with positive cases, 32% to 92% with negative cases and 33% to 98% with death cases.

The performance of this sector was mixed during the pandemic. The volatilities of returns increased from April month.

6. Technology:

In March month, most commons stocks and ETF are negatively correlated with covid data. A couple of stocks under study are positively correlated. The magnitudes of negative correlations are greater than that of positive correlations.

13% to 54% negative and 2.1% to 33% positive with positive cases, 1.1% to 57% negative and 30% to 31% positive with negative cases, and 6.4% to 45% negative and 10% to 38% positive with death cases. Over all, 50% negative and 33% postively correlated with pandemic.

From April month however, all the stocks and ETF are positively correlated to the covid data, with a range of 41% to 92% with positive cases, 42% to 96% with negative cases and 26% to 96% with death cases.

The performace of the sector is more stabilised and improved from April. Volatilities of the stocks remained same.

7. Consumer Staples:

In March month, the commons stocks and ETF are negatively correlated with covid data.

29% to 66% with positive cases, 32% to 69% with negative cases and 19% to 54% with death cases. On an average the consumer staples sector was hit by the pandemic and the impact was 61% negative performance.

From April however, except one of the common stock under comparison, all the other stocks and ETF are positively correlated with the covid data, with a range of 62% to 95% with positive cases, 66% to 95% with negative cases, and 58% to 94% with death cases, with an average of 95% positive correlation with the pandemic.

The performance of the sector improved from April and the volatility of returns reduced to a significant extent.

8. Health Care

In March month, the commons stocks and ETF are negatively correlated with covid data.

4% to 38% with positive cases, 2.8% to 41% with negative cases and 10% to 30% with death cases. On an average the health care sector was hit by the pandemic and the impact was 36% negative performance.

From April, most of the securities under comparison are positively correllated with the coronavirus data. The ETF is positively correlated. This shows that, most of the entities in the sector performed well and some of the entities failed to. There is a mild pattern that, the retail outlets in the industry failed to perform well. The range of correlation being, 1.6% to 60% negattive and 77% to 93% positive with positive test cases, 44% to 60% negatively and 73% to 92% positively with negative cases, and 9.6% to 68% negatively and 82% to 94% positively with death cases, with an average of 63% negatively and 93% positively with the pandemic.

The volatilities of returns reduced.

9. Consumer Discretionary

In March month, the commons stocks and ETF are negatively correlated with covid data.

23% to 39% with positive cases, 26% to 57% with negative cases and 14% to 41% with death cases. On an average the consumer discretionary sector was hit by the pandemic and the impact was 45% negative performance.

From April month however, all the stocks and ETF are positively correlated to the covid data, with a range of 25% to 94% with positive cases, 24% to 94% with negative cases and 33% to 97% with death cases. Average performance correlation being, 95% positive.

The sector performance improved after the initial impact from the pandameic. The volatility of returns reduced.

10. Real Estate

In March month, the commons stocks and ETF are negatively correlated with covid data.

20% to 51% with positive cases, 23% to 55% with negative cases and 10% to 42% with death cases. On an average the real estate sector was hit by the pandemic and the impact was 46% negative performance.

From April, almost all the securities performed well and have a positive correlation with the increasing covid test numbers. The magnitude being, 61% to 89% with positive cases, 41% to 81% with negative cases and 51% to 94% with death cases, average correlation being, 90% Positive.

The sector performance improved and volatility of returns increased.

11. Utilities

In March month, the commons stocks and ETF are negatively correlated with covid data.

5.4% to 36% with positive cases, 8.1% to 39% with negative cases and 1.2% to 24% with death cases. On an average the real estate sector was hit by the pandemic and the impact was 33% negative performance.

From April however, the sector performance is mixed. Some securities under test are correlated positively and some are correlated negatively with a negative performance, magnituded being, 1.7% to 4% negative and 51% to 91% positive with positive test cases, 4.5% to 9.1% negatively and 54% to 92% positively with negative cases, and 7.1% to 15% negatively and 52% to 94% positively with death cases, with an average of 5% negatively and 93% positively with the pandemic.

The performance of the sector improved on an average and volatily of returns reduced to a significant level.


Summary

![Summary of all Sectors](Images/ExcelSector.png)




# Capstone_Project-ETFs
For week 1, you will required to submit the following:

1. A description of the problem and a discussion of the background. (15 marks)
2. A description of the data and how it will be used to solve the problem. (15 marks)

# Submission Week 1: ETFs World Map and (smoothing) Returns

1. Problem description / background discussion (who would be interested in this project)

   (Passive) Investors in ETFs might want to over-/underweight, or even exclude certain countries from their portfolios from time to time due to their negative performance in the past and for increased portfolio return in the future.

    Such data in a choropleth map might be supportive for the (1) individual client or the (2) sales management department of a bank as well and helps identifying regions of interest for the sales of ETFs tracking such indices.  A heat map would show consistent returns over the years as an additional investment argument.

2.	Data description (and use to solve the problem) and source (acquisition/cleaning)

    For simplicity reasons I first checked the largest issuer, iShares (BlackRock) for any data available on Equity ETFs.
With the link below you can access the file as well if you plan to build something similar with it. This data made my Bloomberg Terminal access obsolete for now but BBG might be an additional source for later, if needed (e.g. missing volume for a risk/return scatter plot).
I only included Equity ETF (asset class) in the data file. The data is already sorted by Net asset (USD) so the choropleth map should choose the largest ETF for each country. There are different YTD returns available as well for the heat map. A comparison of the TER (total expense ratio) is also possible with the data set and important for the investors.

    iShares ETFs USA (no specific investor type): 
https://www.ishares.com/us/products/etf-investments#!type=ishares&view=keyFacts

For week 2, I need a solution how to over-/underweight the Top 5 positive return performers and over-/underweight the Worst 5 positive return performers, or vice versa, to see which strategy works best. Above description will be summarized in a PPP or LinkedIn-post later on.

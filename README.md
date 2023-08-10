# Media-Coverage-And-Stock-Returns

Mass media outlets, notably newspapers, serve as crucial channels for disseminating information to a diverse audience, with individual investors relying heavily on such sources for financial guidance. Building on this foundational understanding, our research seeks to bridge a gap in current literature by investigating the nuanced cross-sectional relationship between mass media coverage and stock returns. By understanding this dynamic, we aim to provide a clearer framework for investors and scholars alike, illuminating the tangible effects of media narratives on market outcomes. In navigating this intricate terrain, our study offers both empirical depth and broader implications for market behavior in an information-driven age.

Our study extends the methodology in prior literature such as Fang(2007) and Tetlock(2008). Whileprior studies only examined stock coverage for four major US Newspapers (NYT, USAT, WSJ and WP), we examine coverage from all major US News Publishers. Furthemore our study explores the impact of online news as well as traditional print news.

Our sample consists of all companies listed on the NYSE between 2017 and 2022. Following prior work, we exclude stocks with prices below $5 to ensure that results are not driven by small illiquid stocks or bid-ask bounce.

We use the number of newspaper articles about a stock to proxy for the stock’s overall media exposure. To collect this information, we systematically search the LexisNexis database for articles published in major U.S. newspapers that refer to the companies in our sample. For each company in our sample we obtain the company name from CRSP. To capture articles with a primary focus on a given company, we retain articles with a relevance score of 90% or above, which LexisNexis describes as “Major References.” This process returns 124,327 news articles covering 2634 stocks from 2017-2022.

We obtain stock return, market capitalization, and trading volume data from CRSP, and accounting data, such as book value of assets, from Compustat. Analyst coverage data are collected from I/B/E/S summary files. We measure analyst coverage for each firm and year in our sample by counting the number of analysts making fiscal year-end forecasts.

![image](https://github.com/shantanu2383/Media-Coverage-And-Stock-Returns/assets/123670210/2525199a-fe32-4820-a9e1-5b6fc8b37a15)

Overall news coverage is surprisingly low. Over 65% of NYSE stocks are not featured in the press in a typical year. The conditional statistics also reveal that coverage is highly skewed.

If it were the case that media coverage is biased toward some industries, any cross-sectional return pattern we document could be a disguised industry effect. Figure 1 graphs the industry distributions for the no- and high-coverage stocks, and shows that they are virtually identical, save for financial firms (SIC:6) of which a high number of stocks receive no coverage. 

![image](https://github.com/shantanu2383/Media-Coverage-And-Stock-Returns/assets/123670210/97bb8dd2-ed74-494f-b4ea-cf69f084c41e)

Table II examines the determinants of media coverage in a regression setting. The dependent variable is the number of articles published about a stock over a year. Because media coverage is persistent, we correct the standard errors for autocorrelation using the Newey-West (1987) procedure with one lag. While we find that firm size has an overwhelming effect on media coverage with large firms much more likely to be covered, the other variables are not significant at the 5% level.

![image](https://github.com/shantanu2383/Media-Coverage-And-Stock-Returns/assets/123670210/4b2b744f-5e4e-4ad7-8341-ef5bf91245c7)

Table III reports average returns of stocks double-sorted by firm characteristics and media coverage. We first sort stocks into terciles by various firm characteristics, such as size. Terciles are used to ensure adequate sample size and diversification. Next we sort each characteristic-based tercile into three media portfolios: no coverage, low coverage, and high coverage. Stocks with no newspaper coverage are first identified; the remaining stocks are divided into the low- and high-coverage groups using the median number of articles published. The equal-weighed return of each portfolio during the following month is then tabulated.

![image](https://github.com/shantanu2383/Media-Coverage-And-Stock-Returns/assets/123670210/fabb1b17-4d9d-4fe2-ba56-8f7db4aaf915)



To examine the media effect controlling for risk factors, we form long–shortportfolios of stocks sorted by media coverage. Each month, we divide the stock sample into no-media, low-media, and high-media coverage groups as before.

We then compute the return in the following month on a zero-investment portfolio that longs the stocks with no media coverage and shorts the stocks with high media coverage. Repeating this every month yields a time series of returns for this zero-investment portfolio. The time-series returns are then regressed on factors known to affect the cross-section of returns. We examine four different factor models: the market model, the Fama-French (1993) three-factor model.
the Carhart (1997) four-factor model, and a five-factor model that includes the Pastor-Stambaugh (2003) liquidity factor. The Pastor-Stambaugh liquidity factor controls for stocks’ exposure to the aggregate (market-wide) liquidity risk.

![image](https://github.com/shantanu2383/Media-Coverage-And-Stock-Returns/assets/123670210/1a2d538b-9903-439e-83f1-fa8899f2761c)



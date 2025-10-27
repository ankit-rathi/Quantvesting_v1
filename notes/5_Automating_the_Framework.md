## Automating the Framework

This session suggests how we can build a framework to enter and exit stocks from your universe and automate it.

From your **universe of high-quality and robust businesses**, you can identify two types of stocks:

1. **Portfolio Stocks** – the ones you already own.  
2. **Prospects** – the ones that are not in your portfolio but are part of your stock universe.

By bringing together all the **fundamental** and **technical metrics** for every stock in your universe, you can easily:

- **Filter prospects** based on your criteria or strategies.  
- **Identify new opportunities** to invest or trade.

Once you take positions, you can **continuously track your portfolio** to see if any stock meets the **exit conditions**.  
When a stock nears its **target or exit criteria**, you can **rotate your funds** into new opportunities that meet your **entry conditions**.

This process of **fund rotation** helps maximize returns while staying disciplined, which can be automated using any programming language (python).

I’ll explain these **rotational strategies** step-by-step later.

> 🧠 Note:  
> - **Smart traders** use these rotation and exit strategies actively.  
> - **Smart investors**, on the other hand, can keep investing based on entry criteria and need not worry much about rotation or exit rules.


myProspects_Upside_Analysis_v2 (metrics explained)

> - Symbol - NSE Scrip
> - FTT - Final Technical Target
> - Dev%_200 - Deviation from 200 DMA
> - Dev%_PE - Deviation from median PE (5Y)
> - Spread% - Spread b/w price, 50 and 200 DMA
> - Conviction - my conviction in the business
> - Cyclical - whether the business is non, shallow or deep cyclical
> - RSI_14 - RSI 14 D
> - FTT% - % upside till FTT
> - ATH% - % upside till prev ATH
> - Gained% - % gained from 52W low
> - CumlRnk - Cumulative rank based on various factors
> - ROE%/PE - ROE% vs PE Ratio
> - Criteria - Stock selection criteria
> - Strategy - when to exit (NTT/ATH/BTT)
> - Category - sector of the stock
> - InFolio - whether the stock is in portfolio

myStocks_Portfolio_Analysis_v2 (metrics explained)

> - Current - Current amount 
> - Current P/L - Current P/L amount
> - FTT Amt - FTT Amount 
> - Today P/L% - Today's P/L %
> - Current P/L% - Current P/L %
> - OTT% - Overall Technical Target
> - RRR Ind - Risk Reward Ratio Indicator
> - CurrAlloc% - Current allocation in portfolio


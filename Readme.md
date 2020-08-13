# Auto Portfolio Management
---

* In this project, we select 505 stocks of `S&P 500` companies as our initial stock pool. Then we crawl some key financial ratios from Yahoo Finance to filter these stocks. After several rounds of filter based on their financial ratio performance, we keep **68 stocks**. 
* Then we crawl news of these 68 companies from Yahoo Finance and make sentiment analysis, the result of which is also taken into their final evaluation. Based on the financial ratio performance and sentiment analysis result, we score these stocks with our model and select the _top 20_ as our final portfolio. Lastly, we use `Monte Carlo` method to determine the allocation of our investment amount on each stock. 

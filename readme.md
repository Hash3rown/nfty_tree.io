# Welcome to NFTYtree.io
The NFT marketplace focused on the tokenised gaming arena. 
Your one stop shop for gaming tokens, collectibles and in game items.
Trade/browse/invest in one of the fastest growing areas of cryptocurrency.
****
​
## 1. What is an NFT? Why would anyone invest in them?
> According to Google, Non-Fungible Token (NFT) can be defined as:</br>
> </br>
> <em>A unit of data stored on a digital ledger, called a blockchain, that certifies a digital asset to be unique and therefore not interchangeable.</em> </br>
> </br>
> They can represent items such as photos, videos, audios etc. Here's a breakdown of the the last month's NFT sales by category according to non-fungible.com (2021-04-13):</br>
> </br>
> ![NFT_Monthly_Category_Sales_(USD)_March-April_12th,_2021](/Images/1.11_nft_category_sales_USD_piechart.png)
> </br>
> ![NFT_Monthly_Category_Sales_Transactions_March-April_12th,_2021](/Images/1.12_nft_category_transactions_piechart.png)
> </br>
> As you can see, sporting NFTs account for a large number of transactions, but only a comparatively small amount of total revenue. This is a direct indicator that sporting ETFs are comparatively low-value and less premium, relative to NFTs such as Art, Collectibles etc.
> </br>
> </br>
​
## 2. Are Gaming NFTs specifically a good investment?
​
### 2.1 Building an NFT Market Index
> Before we can answer the question ‘Why Gaming NFTs’, we need to answer the question ‘Why NFTs’.</br>
> </br>
> Now, because the market is relatively new, there’s no NASDAQ or market index to provide a reference point as to the state of the overall market. So, we built one. 
> We took the top 30 NFTs by market cap from Coingecko, from all categories (gaming, sports, art etc.).  </br>
> ![Coingecko_Top_NFTs](/Images/other_images/coingecko_top_nfts.png)
> </br>
> Unfortunately, you need to pay for APIs to get historical sales prices, so we just downloaded 30 csvs from coingecko and analysed it that way. As you can imaging, it was a real hoot importing everything. </br>
> ![Top_NFT_csvs](/Images/other_images/coingecko_csv_files.png)
> </br>
> Here's a quick snapshot of their correlations:
> ![Index_Correlations](/Images/2.1_index_tokens_correlations.png)
> </br>
> Now, a lot of the top 30 tokens are very new and have only launched in the past few months. So, for the sake of comparing everything on an even scale, we started tracking everyone in late January.
> So the next task was to throw all the asset prices into a dataframe, and multiply them against a dataframe including their daily market cap in proportion to the total sample market cap. The result is a diversified, pseudo NFT market index.
> ![Index_Prices](/Images/2.2_pseudo_index_price_plot.png)
> </br>
> As you can see, If you invested $10K in January into the overall NFT space, you’d likely be sitting on nearly $40K by now.
> ![Index_returns](/Images/2.3_cumulative_returns_pseudo_index.png)
> </br>
> </br>
​
### 2.2 Building a Gaming NFT Portfolio for Comparison with the Index
> Next, we built a simple gaming NFT portfolio incorporating the token price history of five of the top performing gaming NFTs trading on the market. These included: $MANA, $CHAIN, $AXS, $SAND and $MEGA.</br>
> </br>
> Each of them yields the following Sharpe Ratios: </br>
> ![Gaming_Sharpes](/Images/2.5_gaming_portfolio_token_sharpe_ratios.png)
> </br>
> </br> Giving each of the tokens even weightings of 20%, we were left with a new Gaming NFT Portfolio which we could compare against the index. </br>
> </br>
> #### Gaming NFT vs NFT Index by Price
> ![Gaming_vs_Index_Prices](/Images/2.6_games_portfolio_vs_nft_index_prices.png) </br>
> </br>
> #### Gaming NFT vs NFT Index by Cumulative Returns
> ![Gaming_vs_Index_Cumulative_Returns](/Images/2.7_recent_cumulative_performance_nfts_vs_index.png) </br>
> As you can see, if you’d invested that same $10K into a gaming portfolio, you’d be sitting on 8x gains by now. </br>
> </br>
> Admittedly, the Beta of the gaming portfolio is <em>11</em>. This indicates that gaming NFTs are significantly more volatile than the overall NFT market. </br>
> However, it’s also worth pointing out that in analysing the sharpe ratios of the of the gaming assets and the the gaming portfolio, they generally outperform the market yielding greater returns for each unit of risk. Technical analysis describes sharpe eatios above 1 as good, and above 2 as very good. </br>
> ![Gaming_vs_Index_Sharpes](/Images/2.8_sharpe_ratios_games_vs_index.png) </br>
> </br> 
> #### Other Interesting Findings
> ##### Prices of top Gaming NFTs
> ![Prices_of_top_Gaming NFTS](/Images/2.41_gaming_portfolio_prices_before_scaling.png) </br>
> </br> 
> ##### Scaled Prices of top Gaming NFTs
> ![Scaled_Prices_of_top_Gaming_NFTS](/Images/2.42_gaming_portfolio_prices_after_scaling.png) </br>
> </br> 
> As you can see, the correlations between some gaming NFTs are higher than others.
> </br>
> </br>
​
​
​
## 3. How do gaming NFTs generate profit and how much can they make?
> 
> We’ve shown what an NFT is, how much growth the space is seeing and why we’re narrowing it down to the gaming arena, the following is a look into one specific project, NFT gaming project: “Axie Infinity”. 
> 
Axie Infinity is an Ethereum based blockchain game, loosely base on the world of Pokemon.
There are multiple streams of revenue generated on the platform such as Sales/Ownership of land and Axies, Breeding of Axies (where users pay a breeding fee), Trading on a secondary market (where the platform takes a trading fee) and ultimately Battling Axie's where players can earn crypto and potentially spend it back into the game.
Trading fees are of the most interest to us because as an NFT trade platform we would hope to capture some of this revenue.

It is also interesting to note the AXS token has seen a 1000% price increase since it was launched approximately 6 months ago.

> ![acies_price_vs_date](/Images/3.1_acies_price_vs_date.png) </br>
> </br> 
> 
> The cumulative revenue collected was initially mostly from initial Land and Axie sales, however more recently the secondary marketplace fees collected have risen rapidly.
> ![axies_revenue_vs_time](/Images/3.2_axies_revenue_vs_time.png) </br>
> </br> 
> 
> 
> ![axies_revenue_composition](/Images/3.3_axies_revenue_composition.png) </br>
> </br> 
> 
> 
> ![axies_unique_holders](/Images/3.4_axies_unique_holders.png) </br>
> </br> 
> 
> 
> ![cumulative_Transaction_volume_holders](/Images/3.5_cumulative_Transsaction_volume_holders.png) </br>
> </br> 
> 
> 
> ![scaled_volume_vs_holders_vs_Price](/Images/3.6_scaled_volume_vs_holders_vs_Price.png) </br>
> </br>
> </br>
​
## 4. Why are gaming NFTs becoming so popular?
> 
> 
> ![chain_vs_index](/Images/4.2_chain_vs_index.png) </br>
This chart shows the closing prices of Chain Games vs. the NFT market index which includes other NFT data types such as Art, Collectibes and Sport. 
There is a massive jump in price in the middle of March which apparently represents Chaingames making their Fortnite announcement - which was that they had added the game to its platform.
The Chain Games platform allows users to bet on each other's wins using cryptocurrency. As you can see there is a clear relationship between Chain Games closing prices and the market as a whole.
​
> </br> 
> 
> 
> ![twitter_vs_btc](/Images/4.4_twitter_vs_btc.png) </br>
The following chart shows the rise of Bitcoin prices with the other line showing the rise of Twitter followers. This was created using the community data from Coingecko's API gathered on Bitcoin. This is an important chart to display the rising popularity of Bitcoin and its effect on the price. A lot of the popularity can be explained by a look at public announcements made on Twitter or other news outlets. For example, when Elon Musk tweeted that his Electrical Car company, Tesla was now accepting bitcoin as payment, there was a jump in the price. 
> </br> 
> 
> 
> ![recent_chain_prices](/Images/4.5_recent_chain_prices.png) </br>
This chart shows the recent prices for Chain Games. It is interesting to view that at the end of 2020, the price was pretty consistent. But we can see there was a massive jump after March of 2021 which continues to shoot up this month. The indication we get from this chart is that Chain Games as an NFT platform is having consistent successes. 
> </br> 
> 
> 
> ![chain_vs_index_price](/Images/4.11_chain_vs_index_price.png) </br>
This chart shows how Chain Games is outperforming the market. As it is a platform that allows users to bet on their gameply using cryptocurrency, this performance demonstrates that people are becoming increasingly interested in the potentials of cryptocurrencies. 
> </br> 
> 
> 
> ![chain_vs_index_price_scaled](/Images/4.12_chain_vs_index_price_scaled.png) </br>
This chart is scaled to further illustrate Chain Games performance in comparison to the market. 
> 

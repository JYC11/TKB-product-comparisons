# TKB-product-comparisons

Comparing products from the Toys Kids Babies categories by brand, price from 5 different countries:
* Singapore - Fair Price
* Malaysia - Mydin
* Philippines - SM Store
* Indonesia - Hypermart
* South Korea - Danawa(an aggregation site that lists many different prices and ranks the best one)

Scraped Fair Price, Mydin and Danawa. Used work database for SM Store and Mydin(I wish I could have written the SQL query myself but there's a handy extraction tool built by Business Intelligence so oh well).

Project is sorta done because all I wanted was a groupby table. Overall I just wrote terrible terrible code and ended up doing the last parts of data cleaning on excel(shame). My excuse is that I didn't have enough time because my job is kinda time consuming.
Lessons learned from my project(will do code clean up when I have more time-which may be never):
1. Do some googling on the topic of anlaysis and set up a plan before cleaning and especially merging data from many sources
2. Have a more specific goal in mind than just "Hurr durr compare prices haha"
3. Investigate all the edge cases for regex. When you think you investigated them all, look over again and again and again. This will save you tons of time
4. When dealing with currencies, make sure to find out how they show thousands
5. Try to do everything in python. I think this project was 66% python 34% excel.

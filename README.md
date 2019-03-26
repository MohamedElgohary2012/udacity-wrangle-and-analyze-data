## Wrangle and Analyze Data

###  介紹

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "[they're good dogs Brent](http://knowyourmeme.com/memes/theyre-good-dogs-brent)." WeRateDogs has over 4 million followers and has received international media coverage.

### 作業要求文件

1. `wrangle_act.ipynb` 
   - Gather：至少 3個不同資料來源，3種不同 DataFrame
   - Accessing：每份 gathering data 至少可用兩種方式來進行評估（excel, python）
   - Cleaning data：列出 8 點 quality issues, 2 點 tidiness issues
   - Analyze and visualize：3 項 insights 和 1 項 visualization(必須提供自定義圖標標籤)

2. `twitter_archive_master.csv`

   合併及清理過的數據需存在這份文件或是 SQLite

3. wrangle_report.html` (or pdf)

   提交一份 300-600 字內部文件報告，簡短描述 wrangling efforts

4. `act_report.html` (or pdf)

   提交一份至少 250 字外部報告用在 blog post，描述我在 wrangling data 裡面的發現，解釋我的 insights 並且要視覺化

5. `twitter_archive_enhanced.csv`

   The WeRateDogs Twitter archive 作業提供

6. `image-predictions.tsv`

   The tweet image predictions 作業提供

7. `tweet_json.txt`

   Each tweet's retweet count and favorite ("like") count at minimum, and any additional data you find interesting. 自行從 twitter api 取得回應的資料

8. `tweet_api.py`

   使用 twitter api 的程式（請勿提供自己的公私鑰），列為 ignore 文件


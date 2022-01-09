專案目的: 透過過去資料建立使用者曾經購買的商品加以推薦使用者商品，增加成交率。

專案預期結果：使用者可因商品推薦而進一步購買推薦的商品，增加客戶單筆客單價。
分別用以下三種實作 collaborative filtering 的方法，找出你會推薦 top 10 的商品＆分數，並比較這三種方法產生的結果。

目前推薦分數及使用方法：
- User-based collaborative filtering: Recall 皆無提升
- Item-based collaborative filtering: 在新增相似item數量後，有些許提升至0.001694915254237288
- 套件 surprise 實作 collaborative filtering： colab 及手邊電腦跑不動 無法得知
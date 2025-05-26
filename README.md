

# Project Gutenberg
此程式碼的目的是從[古騰堡計劃](https://www.gutenberg.org/)爬取中文書籍，保存為txt檔。
目前爬取 201 本作為範例。

## 安裝套件
- requests (2.32.3)
- beautifulsoup (4.13.4)

## 成果
[古騰堡中文書爬取](https://youtu.be/J1HBzZlKoWM)

## 功能描述
* 程式會訪問[古騰堡計劃](https://www.gutenberg.org/browse/languages/zh)，抓取標題為中文之書籍，將書中的中文字（連同全形標點符號）保存為{序號}. {標題}.txt。
* txt檔將保存至資料夾project_gutenberg（若不存在將自動新增）。
* 若書籍標題重複，將直接跳過。
* 為避免多餘換行，連續 3 次以上的換行將被替換為 2 次。
* 可修改程式碼以調整下載數量，目前設定為 201 本。

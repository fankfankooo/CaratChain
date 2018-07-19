# CaratChain



- 1. 發行一種雙軌 CaratChain 幣，共有兩版本：
 
 > - CaratChain 幣erc-20版 及 CaratChain 幣erc-721版。

------

- 2. 雙軌同名

 > - 先發行erc-20。

------

- 3. 雙軌用途

 > - CaratChain 幣erc-20版，用於上架在交易所
 > - CaratChain 
 erc-721版，用於每幣的獨立內容(如汽車持有證明，稀有品持有證明等。)
 
 `要決定721版有多少內容，如每一幣有多少項參數例如:幣名，網址，發行上限，獨立圖示等等，必須例出所有項，因寫好就不能修改。`

------

- 4. CaratChain 幣流通性

 > - 系統先發行erc-20，再加上銷毀及兌換功能，客戶可各自交易erc-20及erc-721
 
 > - erc-20跟erc-721兩者不能互換
 
------

- 5. CaratChain 幣銷毀或回收系統

 > - 每當客戶需要由 erc-20 兌換做 erc-721 ，可將 erc-20 存入一個智能合約，合約自動銷毀 erc-20 及依當時兌換價，發出  erc-721 給客戶。
 
`兌換價是否要固定，固定的好處是可以設定總上限量，客戶比較有信心，問題是不能根據市場情況轉變策略`

`不固定的好處是能根據市場情況轉變策略，但不設總上限量，可能有過量發行問題(因為您要綁定721的內容是實物，實物是有限量的)`


------

`如用這方法，兩版本的上限數應該要不同，甚至要沒有上限才安全。`


------

- 6. CaratChain 幣erc-20版內容:

 > - 1. 幣名稱 Carat Chain

 > - 2. 總上限量 120000000 1.2億
 
 > - 3. 幣圖示 CRT

 > - 4. 小數位 0
 
------

- 7. CaratChain 幣erc-721版內容:

 > - 1. 幣名稱(不能修改)

 > - 2. 總上限量(可選是否需要)
 
 > - 3. 幣圖示(不能修改)
 
 > - 4. 每一幣的獨立網址(可由admin修改)

 > - 5. 其他(可選是否需要)
 
------
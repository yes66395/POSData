# 速食店POS機點餐demo
底下是POS速食資料 (練手的小項目) 

初始網址 https://yes66395.github.io/POSdemo/
<br/>
速食資料
一般商品:https://yes66395.github.io/POSdemo/commonfood.json  <br/>
分類商品 :https://yes66395.github.io/POSdemo/sortfood.json

用到的技術
<br/>
Vue2語法 + Vite環境 + Vue-Router(簡單配置) + Axios(簡單串接) + Element-Plus

<br/>
完成畫面(沒有RWD)
<img src="https://github.com/yes66395/testjson/blob/main/Untitled.png?raw=true" />

<br/>
你可以學到的知識點

<br/>

1. v-for雙重嵌套 以及v-for一層嵌套
2. axios的使用 
3. Element-plus在vite.config.js的配置使用
4. Vue-Router的基礎使用(配置)
5. created，生命週期函數，資料直接出現
6. 從原生JavaScript ->不操作DOM->只操作資料，驅動畫面，這邊需要一點時間適應

<br/>

功能的說明
<>
1. 新增商品，直接點擊右邊的標籤，或是下面的分類商品的圖案，就可以新增
2. 數量，如果點選重複的商品，數量會遞增
3. 商品單一新增數量功能，以及商品單一刪除功能
4. 全部刪除商品
5. 送出單子，當沒有商品，會貼出警語
6. 變成單子，自動計算數量以及總金額
7. 結帳，這裡只是模擬真實的結帳情況，結帳之後，這個單子就會不見

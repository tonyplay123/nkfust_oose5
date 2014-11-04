# 題目：模型比價系統 #

組員:<br>
0124016曾柏勳<br>
0124026楊琮堡<br>
0124054葉人慶<br>
0124064陳德威<br>
0124094陳義勇<br>

## 研究動機 ##
本小組有名成員為模型愛好者，由於現今的模型市場通路並不廣泛，導致在其在模型選購上十分不便，因此他希望能有個整合模型通路的網站平台。而經過小組討論，本組決定設計一個模型比價網，讓眾多模型愛好者有夠方便比較、購買模型的網站空間。

## 研究目的 ##
製作出一個能夠滿足模型愛好者需求的網站，模型愛好者可以使用該網站查詢許多模型商品資訊，並且讓他們能夠方便的比較許多店家的價格，以找出價格合理、便宜的購物店家網站。此網站也會附上模型訂購的店家連結，為許多店家打開新的行銷通路。
<br>

## 利害關係人目標表 ##
<table border="1" cellspacing="0" cellpadding="0">
  <tr>
    <td width="170" valign="top"><p>利害關係人(參與者)</p></td>
    <td width="383" valign="top"><p>目標</p></td>
  </tr>
  <tr>
    <td width="170" valign="top"><p>顧客</p></td>
    <td width="383" valign="top"><ul>
      <li>能夠方便查詢模型商品資訊</li>
      <li>能夠快速比較模型商品的不同販售店家的價格</li>
      <li>能夠了解販售模型的店家資訊</li>
      <li>能夠連結至販售模型的店家網站上訂購商品</li>
    </ul></td>
  </tr>
  <tr>
    <td width="170" valign="top"><p>專案人員</p></td>
    <td width="383" valign="top"><ul>
      <li>能夠快速新增模型商品資訊</li>
      <li>能夠方便的隨時維護更新(修改或刪除)商品資訊</li>
      <li>能夠方便管理會員資料</li>
      <li>能夠即時公告網站更新內容</li>
    </ul></td>
  </tr>
</table>
<br>
## 事件與使用案例表 ##
<table border="1" cellspacing="0" cellpadding="0">
  <tr>
    <td width="368" valign="top"><p>事件名稱</p></td>
    <td width="185" valign="top"><p>使用案例名稱</p></td>
  </tr>
  <tr>
    <td width="368" valign="top"><p>新增及維護更新商品資訊</p></td>
    <td width="185" valign="top"><p>商品資料作業</p></td>
  </tr>
  <tr>
    <td width="368" valign="top"><p>查詢模型商品資訊</p></td>
    <td width="185" valign="top"><p>查詢商品</p></td>
  </tr>
  <tr>
    <td width="368" valign="top"><p>比較模型商品的不同販售店家的價格</p></td>
    <td width="185" valign="top"><p>比價商品</p></td>
  </tr>
  <tr>
    <td width="368" valign="top"><p>管理會員資料</p></td>
    <td width="185" valign="top"><p>會員資料作業</p></td>
  </tr>
</table>
## 使用案例圖表 ##
<img src="https://images.plurk.com/3Ub4XLoIqFgJGYqDawhyEj.jpg">

#整個系統的初步類別圖 #
<img src="https://cacoo.com/diagrams/9V3DqxESZEIuFCm7-993B8.png">
----------
----------
----------
#商品基本資料作業#
----------
# 建立商品基本資料流程圖 #
<img src="https://cacoo.com/diagrams/aBtAbmOwF8GdAPDv-D17FF.png">
----------
# 建立商品基本資料作業使用案例的描述 #
----------


<table>
<tr>
<td markdown="1">使用案例名稱</td>
<td markdown="1">建立商品基本資料作業</td>
</tr>
<tr>
<td markdown="1">使用案例描述</td>
<td markdown="1">當連結的模型店家有新的商品上架時，專案人員啟動系統新增、修改、刪除商品基本資料。</td>
</tr>
<tr>
<td markdown="1">主要參與者</td>
<td markdown="1">專案人員</td>
</tr>
<tr>
<td markdown="1">利害關係人與目標</td>
<td markdown="1">專案人員：能夠正確記錄商品基本資料。</td>
</tr>
<tr>
<td markdown="1">前置條件</td>
<td markdown="1">無</td>
</tr>
<tr>
<td markdown="1">後置條件</td>
<td markdown="1">正確建立、修改、刪除商品基本資料</td>
</tr>
<tr>
<td markdown="1">主要成功情節</td>

<td>
<table>
<tr>
<td markdown="1">參與者</td>
<td markdown="1">系統</td>
</tr>
<tr>
<td markdown="1">1  當連結的模型開發公司新增了新商品，專案人員進入商品基本資料作業畫面，並啟動新增按鍵。
<br>
2  專案人員輸入商品基本資料，包括商品編號、商品名稱、商品介紹、商品價格及店家編號、店家名稱、店家網址。
<br>
3  輸入完畢後，選取儲存健，或取消鍵。
<br>
系統重複1-3的動作。
<br>
4  如果要進行修改，選取修改按鈕，並可依據任一個欄位進行查詢，讀取所要修改之商品或店家記錄。修改完，按確認鍵或取消鍵。
<br>
5  如果要進行刪除，選取刪除按鍵，並可依據任一個欄位進行查詢，讀取所要刪除之商品或店家記錄。
</td>
<td markdown="1">1.1  系統開啟新增商品基本資料畫面。
<br>
2.1  系統檢查輸入格式，如果有誤要求重新輸入。檢查是否有重覆商品編號或店家編號。
<br>
3.1  選取儲存按鍵，系統將商品資料存入資料庫。如果按取消鍵，系統回至新增畫面。
<br>
4.1  根據輸入欄位資料，搜尋舊商品記錄，並顯示至畫面。<br>
4.2  選取儲存鍵，儲存商品記錄，如果按取消鍵，則回到商品基本資料作業畫面。<br>
5.1  根據輸入欄位資料，搜尋舊商品記錄，並顯示至畫面。<br>
5.2  出現確認鍵，按確認進行刪除動作，按取消則不做刪除動作。<br>
5.3  回到商品基本資料作業畫面。
</td>
</tr>
</table>
</td>
</tr>
<tr>
<td markdown="1">例外情節</td>
<td markdown="1">*a. 如果有欄位無法輸入，或資料無法儲存，系統需要顯示警告訊息並中止輸入。</td>
</tr>
<tr>
<td markdown="1">其他需求</td>
<td markdown="1">無。</td>
</tr>
</table>





----------
# 使用案例的名詞與概念類別列舉表 #

----------
<table>
<tr>
<td markdown="1">名詞</td>
<td markdown="1">原因</td>
<td markdown="1">結果(是否為概念類別)</td>
</tr>
<tr>
<td markdown="1">專案人員</td>
<td markdown="1">專案人員帳戶資料。</td>
<td markdown="1">是。</td>
</tr>
<tr>
<td markdown="1">帳號</td>
<td markdown="1">為專案人員屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">密碼</td>
<td markdown="1">為專案人員屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">商品</td>
<td markdown="1">商品基本資料，重要。</td>
<td markdown="1">是。</td>
</tr>
<tr>
<td markdown="1">商品編號</td>
<td markdown="1">為商品屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">商品名稱</td>
<td markdown="1">為商品屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">商品介紹</td>
<td markdown="1">為商品屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">商品價格</td>
<td markdown="1">為商品屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">店家</td>
<td markdown="1">店家基本資料，重要。</td>
<td markdown="1">是。</td>
</tr>
<tr>
<td markdown="1">店家編號</td>
<td markdown="1">為店家屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">店家名稱</td>
<td markdown="1">為店家屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">店家網址</td>
<td markdown="1">為店家屬性。</td>
<td markdown="1">否。</td>
</tr>
</table>

----------
# 使用案例的初步類別圖 #

----------
<img src="https://cacoo.com/diagrams/3mSCV7b6pPDjFvo6-5A984.png">

----------
# 使用案例主要成功情節之英文名稱事件對應 #

----------
<table>
<tr>
<td markdown="1">使用案例：建立商品資料作業</td>
</tr>
<tr>
<td markdown="1">
<table>
<tr>
<td markdown="1">主要成功情節：<br>
1	當連結的模型開發公司新增了新商品，專案人員進入商品基本資料作業畫面，並啟動新增按鍵。<br>

2	專案人員輸入商品基本資料，包括商品編號、商品名稱、商品介紹、商品價格及店家編號、店家名稱、店家網址。<br>

3  系統檢查輸入格式，如果有誤要求重新輸入。檢查是否有重覆商品編號或店家編號。<br>

4  輸入完畢後，選取儲存健，或取消鍵。<br>

系統重複1-3的動作。<br>

5  如果要進行修改，選取修改按鈕，並可依據任一個欄位進行查詢，讀取所要修改之商品或店家記錄。修改完，按確認鍵或取消鍵。<br>

6	系統檢查輸入格式，如果有誤要求重新輸入。檢查是否有重覆商品編號或店家編號。<br>

7	如果要進行刪除，選取刪除按鍵，並可依據任一個欄位進行查詢，讀取所要刪除之商品或店家記錄。<br>

8	回到商品基本資料作業
</td>
<td markdown="1">
checkadmin(account,password)
<br>
inputProduct()<br>
inputStores()<br>
<br><br><br><br>
<br>
<br><br><br><br><br>
checkItem(ProductItem)<br>
checkItem(StoresItem)<br>

saveProductRec(Product Rec)<br>
saveStoresRec(Stores Rec)
<br><br><br>
modifyProduct(productID,PoductName, productDemo, productPrice)<br>
modifyStores(storesID,storesName,storesInfo)<br>
<br>
checkItem(ProductItem)<br>
checkItem(StoresItem)<br>
saveProductRec(Product Rec)<br>
saveStoresRec(Stores Rec)
<br><br><br><br>
deleteProduct(productID, productName, productDemo, productPrice)<br>
deleteStores(storesID,storesName,storesInfo)
</td>
</tr>
</table>
</td>
</tr>
</table>

----------
# 每個名稱事件之合約 #

----------
<table>
<tr>
<td markdown="1">合約1：checkadmin(account,password)</td>
</tr>
<tr>
<td markdown="1">操作：checkadmin(account,password)<br>
交互參照：商品基本資料作業<br>
前置條件：存在類別Admin之實例admin<br>
後置條件：-檢查admin之account,password是否正確<br>
-正確則回傳signinSuccess<br>
-錯誤則回傳signinFail
</td>
</tr>
</table>

<table>
<tr>
<td markdown="1">合約2：inputProduct()</td>
</tr>
<tr>
<td markdown="1">操作：inputProduct()<br>
交互參照：商品基本資料作業<br>
前置條件：存在類別Product之實例newProduct<br>
後置條件：-檢查並確認實例newProduct之productName、productDemo、productPrice屬性隻起始值為空白<br>
-給定實例 newProduct之屬性productID最新商品編號<br>
-回傳productID
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約3：inputStores()</td>
</tr>
<tr>
<td markdown="1">操作：inputStores()<br>
交互參照：商品基本資料作業<br>
前置條件：存在類別Stores之實例newStores<br>
後置條件：-檢查並確認實例newStores之storesName、storesInfo、屬性隻起始值為空白<br>
-給定實例 newProduct之屬性productID最新商品編號<br>
-回傳productID
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約4：checkItem(ProductItem)</td>
</tr>
<tr>
<td markdown="1">操作：checkItem(ProductItem)<br>
交互參照：商品基本資料作業<br>
前置條件：已開啟：Product物件<br>
後置條件：-檢查Product之屬性productName、productDemo、productPrice之格式是否正確與是否重複<br>
-回傳itemMessage
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約5：checkItem(StoresItem)</td>
</tr>
<tr>
<td markdown="1">操作：checkItem(StoresItem)<br>
交互參照：商品基本資料作業<br>
前置條件：已開啟：Stores物件<br>
後置條件：-檢查Product之屬性storesName、storesInfo之格式是否正確與是否重複<br>
-回傳itemMessage
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約6：saveProductRec(product Rec)</td>
</tr>
<tr>
<td markdown="1">操作：saveProductRec(Product Rec)<br>
交互參照：商品基本資料作業<br>
前置條件：存在類別Product實例product<br>
後置條件：-將product存入資料庫中<br>
-回傳saveSuccess
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約7：saveStoresRec(stores Rec)</td>
</tr>
<tr>
<td markdown="1">操作：saveStoresRec(Stores Rec)<br>
交互參照：商品基本資料作業<br>
前置條件：存在類別Stores實例stores<br>
後置條件：-將stores存入資料庫中<br>
-回傳saveSuccess
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約8：modifyProduct(productID,PoductName, productDemo, productPrice)</td>
</tr>
<tr>
<td markdown="1">操作：modifyProduct(productID,PoductName, productDemo, productPrice)<br>
交互參照：商品基本資料作業<br>
前置條件：存在類別Product實例product<br>
後置條件：-根據productID或productName讀取商品基本資料productRec，並存入至物件product之屬性中<br>
-回傳productRec
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約9：modifyStores(storesID,storesName,storesinfo)</td>
</tr>
<tr>
<td markdown="1">操作：modifyStores(storesID,storesName,storesinfo)<br>
交互參照：商品基本資料作業<br>
前置條件：存在類別Stores實例stores<br>
後置條件：-根據storesID或storesName讀取商品基本資料storesRec，並存入至物件stores之屬性中<br>
-回傳storesRec	
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約10：deleteProduct(productID, productName, productDemo, productPrice)</td>
</tr>
<tr>
<td markdown="1">操作：deleteProduct(productID, productName, productDemo, productPrice)<br>
交互參照：商品基本資料作業<br>
前置條件：存在類別Product實例product<br>
後置條件：-根據productID或productName讀取商品基本資料productRec<br>
-刪除商品基本資料productRec<br>
-回傳deleteSuccess
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約11：deleteStores(storesID,storesName,storesinfo)</td>
</tr>
<tr>
<td markdown="1">操作：deleteStores(storesID,storesName,storesinfo)<br>
交互參照：商品基本資料作業<br>
前置條件：存在Stores實例stores<br>
後置條件：-根據storesID或storesName讀取商品基本資料storesRec<br>
-刪除店家基本資料storesRec<br>
- 回傳deleteSuccess
</td>
</tr>
</table>

----------
----------
----------
#商品查詢作業#
----------
# 商品查詢作業使用案例的描述 #

----------

<table>
<tr>
<td markdown="1">使用案例名稱</td>
<td markdown="1">商品查詢作業</td>
</tr>
<tr>
<td markdown="1">使用案例描述</td>
<td markdown="1">系統接獲顧客查詢需求,系統根據顧客描述所需,顯示相關的商品資訊於畫面上。</td>
</tr>
<tr>
<td markdown="1">主要參與者</td>
<td markdown="1">顧客</td>
</tr>
<tr>
<td markdown="1">利害關係人與目標</td>
<td markdown="1">顧客：能夠正確查詢所需商品的基本資料。</td>
</tr>
<tr>
<td markdown="1">前置條件</td>
<td markdown="1">無</td>
</tr>
<tr>
<td markdown="1">後置條件</td>
<td markdown="1">正確查詢所對應商品基本資料</td>
</tr>
<tr>
<td markdown="1">主要成功情節</td>

<td>
<table>
<tr>
<td markdown="1">參與者</td>
<td markdown="1">系統</td>
</tr>
<tr>
<td markdown="1">1 當顧客使用本網站並有查詢動作時，網站起動查詢系統。
<br>
2 顧客輸入所需的商品基本資料，像是商品名稱、商品介紹、商品價格、模型店家名稱。
<br>
3 輸入完畢後，進行查詢動作。
<br>
系統重複1-3的動作。

</td>
<td markdown="1">1.1 系統開啟查詢商品畫面。
<br>
2.1 系統檢查輸入格式，如果有無法辨識之符號則要求重新輸入。
<br>
3.1 選取確認按鍵,系統將根據輸入欄位資料,搜尋商品,並顯示至畫面。如果按取消鍵,系統回至主畫面。

</td>
</tr>
</table>
</td>
</tr>
<tr>
<td markdown="1">例外情節</td>
<td markdown="1">*a. 如果有欄位無法輸入，或資料無法儲存，系統需要顯示警告訊息並中止輸入。</td>
</tr>
<tr>
<td markdown="1">其他需求</td>
<td markdown="1">無。</td>
</tr>
</table>

----------
# 商品查詢作業流程圖 #

----------
<img src="https://cacoo.com/diagrams/CwDMlKPUZgObgMjf-AC336.png">


----------
# 使用案例的名詞與概念類別列舉表 #

----------
<table>
<tr>
<td markdown="1">名詞</td>
<td markdown="1">原因</td>
<td markdown="1">結果(是否為概念類別)</td>
</tr>
<tr>
<td markdown="1">顧客</td>
<td markdown="1">顧客帳戶資料。</td>
<td markdown="1">是。</td>
</tr>
<tr>
<td markdown="1">會員帳號</td>
<td markdown="1">為顧客屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">會員密碼</td>
<td markdown="1">為顧客屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">商品</td>
<td markdown="1">商品基本資料，重要。</td>
<td markdown="1">是。</td>
</tr>
<tr>
<td markdown="1">商品編號</td>
<td markdown="1">為商品屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">商品名稱</td>
<td markdown="1">為商品屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">商品介紹</td>
<td markdown="1">為商品屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">商品價格</td>
<td markdown="1">為商品屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">搜尋</td>
<td markdown="1">顧客輸入的需求資料。</td>
<td markdown="1">是。</td>
</tr>
<tr>
<td markdown="1">搜尋編號</td>
<td markdown="1">為搜尋屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">搜尋名稱</td>
<td markdown="1">為搜尋屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<tr>
<td markdown="1">搜尋價格</td>
<td markdown="1">為搜尋屬性。</td>
<td markdown="1">否。</td>
</tr>
</table>

----------
# 使用案例的初步類別圖 #

----------
<img src="https://cacoo.com/diagrams/ldkKjRkWoXCUcCut-4EEAC.png"></a>

----------
# 使用案例主要成功情節之英文名稱事件對應 #

----------
<table>
<tr>
<td markdown="1">使用案例：查詢商品作業</td>
</tr>
<tr>
<td markdown="1">
<table>
<tr>
<td markdown="1">主要成功情節：<br>
1	當顧客進入商品查詢作業畫面,並啟動查詢系統。<br>

2	顧客輸入搜尋商品需求,包括搜尋編號、搜尋名稱、搜尋價格。<br>

3   系統檢查輸入格式,如果有誤要求重新輸入。<br>

4   輸入完畢後,選取搜尋鍵,於系統主畫面顯示相關連結資料。<br>


</td>
<td markdown="1">
inputSearch()
<BR><BR>
getsearchitem(sNumber,sName,sPrice)
<BR><BR>
checksearch(getsearchitem)
<BR><BR>
printItem(proNumber,proName,proPrice)
<br>

</td>
</tr>
</table>
</td>
</tr>
</table>

----------
# 每個名稱事件之合約 #

----------
<table>
<tr>
<td markdown="1">合約1：inputSearch()</td>
</tr>
<tr>
<td markdown="1">操作：inputSearch()<br>
交互參照：商品查詢作業<br>
前置條件：存在類別Search之實例newSearch<br>
後置條件：-檢查並確認實例newSearch之sNumber、sID、sPrice屬性之起始值為空白<br>
-給定實例 newSearch之屬性Search最新查詢編號<br>
-回傳Search
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約2：getsearchitem(sNumber,sName,sPrice)</td>
</tr>
<tr>
<td markdown="1">操作：getsearchitem(sNumber,sName,sPrice)<br>
交互參照：商品查詢作業<br>
前置條件：已開啟:Search物件<br>
後置條件：-建立類別SearchItem的實例Searchitem<br>
-實例Searchitem與實例newSearch形成關聯<br>
-實例Searchitem根據sNumber或sName或sPric讀取資料<br>
-searchRec存入實例SearchItem<br>
-回傳searchRec記錄
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約3：checksearch(getsearchitem)</td>
</tr>
<tr>
<td markdown="1">操作：checksearch(getsearchitem)<br>
交互參照：商品查詢作業<br>
前置條件：已開啟：Search物件<br>
後置條件：-檢查Search屬性sNumber、sName、sPrice之格式是否正確與是否重複<br>
-回傳itemMessage
</td>
</tr>
</table>
<br>
<table>
<tr>
<td markdown="1">合約4：printItem(proNumber,proName,proPrice)</td>
</tr>
<tr>
<td markdown="1">操作：printItem(proNumber,proName,proPrice)<br>
交互參照：商品查詢作業<br>
前置條件：存在一個查詢實例newSearch<br>
後置條件：-存在實例printitem<br>
-實例searchitem與實例printitem取得關聯<br>
-實例printitem根據searchitem讀取資料<br>
-searchRec存入printitem<br>
-回傳printitem
</td>
</tr>
</table>
<br>
<table>
<tr>




-------
-------
-------


<img src="https://images.plurk.com/7pqZUWOKxXDS17cTNmNWhu.jpg">
<table border="0" cellspacing="0" cellpadding="0" width="557">
  <tr>
    <td width="104" nowrap="nowrap"><p>使用案例名稱 </p></td>
    <td width="454" nowrap="nowrap" colspan="2"><p>比價作業 </p></td>
  </tr>
  <tr>
    <td width="104" nowrap="nowrap"><p>使用案例描述 </p></td>
    <td width="454" nowrap="nowrap" colspan="2"><p>顧客欲購買商品時，可以在本系統查詢品在不同店家有不同價格。 </p></td>
  </tr>
  <tr>
    <td width="104" nowrap="nowrap"><p>主要參與者 </p></td>
    <td width="454" nowrap="nowrap" colspan="2"><p>顧客、模型店家 </p></td>
  </tr>
  <tr>
    <td width="104" nowrap="nowrap"><p>利害關係人與目標 </p></td>
    <td width="454" nowrap="nowrap" colspan="2"><p>顧客：能夠在短時間內了解到同一個產品在不同店家有不同價格，進而挑選對自己最滿意價格的產品。 <br />
      模型店家：增加新的通路以提升銷貨量。 </p></td>
  </tr>
  <tr>
    <td width="104" nowrap="nowrap"><p>前置條件 </p></td>
    <td width="454" nowrap="nowrap" colspan="2"><p>專案人員必須隨時更新各店家產品的價格 </p></td>
  </tr>
  <tr>
    <td width="104" nowrap="nowrap"><p>後置條件 </p></td>
    <td width="454" nowrap="nowrap" colspan="2"><p>正確顯示產品價格和店家資訊 </p></td>
  </tr>
  <tr>
    <td width="104" nowrap="nowrap" rowspan="2"><p>主要成功情節 </p></td>
    <td width="217" nowrap="nowrap"><p>參與者 </p></td>
    <td width="236" nowrap="nowrap"><p>系統 </p></td>
  </tr>
  <tr>
    <td width="217" nowrap="nowrap"><ol>
      <li>當使用者鎖定特定的產品，可以在基本作業畫面，選取商品比價查詢按鍵。 </li>
    </ol>
      <p>2  選取「比價」後，網站將顯示目前記錄上的店家資訊及價格等資料。 <br />
        3  查詢完畢後，使用者可點選店家，網站會開啟店家的商品購物連結。 <br />
        4  想查詢其他商品時，可點選「商品查詢」，網站將回到建立商品資料作業 </p></td>
    <td width="236" nowrap="nowrap"><p>1.1  系統開啟商品比價畫面。 </p>
      <p>&nbsp;</p>
      <p>2.1  系統呼叫資料庫中的店家資訊，並顯示在網站上。 </p>
      <p>3.1  點選店家，系統將開啟店家網站連結。 </p>
      <p>4.1  點選商品查詢」，系統將回到查詢作業。 </p></td>
  </tr>
  <tr>
    <td width="104" nowrap="nowrap"><p>例外情節 </p></td>
    <td width="454" nowrap="nowrap" colspan="2"><p>*a. 如果有欄位無法輸入，或資料無法儲存，系統需要顯示警告訊息並中止輸入。 </p></td>
  </tr>
  <tr>
    <td width="104" nowrap="nowrap"><p>其他需求 </p></td>
    <td width="454" nowrap="nowrap" colspan="2"><p>無。 </p></td>
  </tr>
</table>



# 使用案例名詞與類別圖 #
-----------
<table border="1" cellspacing="0" cellpadding="0">
  <tr>
    <td width="186" valign="top"><p align="center">名詞 </p></td>
    <td width="186" valign="top"><p align="center">原因 </p></td>
    <td width="186" valign="top"><p align="center">結果(是否為概念類別)</p></td>
  </tr>
  <tr>
    <td width="186" valign="top"><p>顧客 </p></td>
    <td width="186" valign="top"><p>顧客帳戶資料。 </p></td>
    <td width="186" valign="top"><p>是。 </p></td>
  </tr>
  <tr>
    <td width="186" valign="top"><p>會員帳號 </p></td>
    <td width="186" valign="top"><p>為顧客屬性。 </p></td>
    <td width="186" valign="top"><p>否。 </p></td>
  </tr>
  <tr>
    <td width="186" valign="top"><p>會員密碼 </p></td>
    <td width="186" valign="top"><p>為顧客屬性。 </p></td>
    <td width="186" valign="top"><p>否。 </p></td>
  </tr>
  <tr>
    <td width="186" valign="top"><p>商品 </p></td>
    <td width="186" valign="top"><p>商品基本資料，重要。 </p></td>
    <td width="186" valign="top"><p>是。 </p></td>
  </tr>
  <tr>
    <td width="186" valign="top"><p>商品編號 </p></td>
    <td width="186" valign="top"><p>為商品屬性。 </p></td>
    <td width="186" valign="top"><p>否。 </p></td>
  </tr>
  <tr>
    <td width="186" valign="top"><p>商品名稱 </p></td>
    <td width="186" valign="top"><p>為商品屬性。 </p></td>
    <td width="186" valign="top"><p>否。 </p></td>
  </tr>
  <tr>
    <td width="186" valign="top"><p>商品介紹 </p></td>
    <td width="186" valign="top"><p>為商品屬性。 </p></td>
    <td width="186" valign="top"><p>否。 </p></td>
  </tr>
  <tr>
    <td width="186" valign="top"><p>商品價格 </p></td>
    <td width="186" valign="top"><p>為商品屬性。 </p></td>
    <td width="186" valign="top"><p>否。 </p></td>
  </tr>
  <tr>
    <td width="186"><p>關鍵字 </p></td>
    <td width="186"><p>為商品屬性。 </p></td>
    <td width="186" valign="top"><p align="center">否，但是可以和商品編號、商品名稱組成新的類別，稱為比價資訊。 </p></td>
  </tr>
</table>

# 使用案例主要成功情節之英文名稱事件對應 #
-----------
<table border="1" cellspacing="0" cellpadding="0" width="100%">
  <tr>
    <td width="63%" valign="top"><p>主要成功情節：</p>
      <ol>
        <li>當顧客想查詢商品資訊時，進入商品基本資料作業畫面，並啟動查詢按鍵。</li>
        <li>顧客輸入商品資料，包括商品名稱。</li>
        <li>系統檢查輸入格式，如果有誤要求重新輸入。檢查資料庫是否有顧客輸入的資訊。</li>
        <li>輸入完畢後，選取查詢健，或取消鍵。</li>
        <li>系統抓到顧客的資料，並在資料庫中選取並顯示出來。</li>
        <li>回到商品基本資料作業</li>
      </ol></td>
    <td width="37%" valign="top"><p>&nbsp;</p>
      <p>inputProduct()    inputStores();&nbsp;</p>
      <p>&nbsp;</p>
      <p>&nbsp;</p>
      checkProduct()
checkStore()

catchstores()
      <p>showProduct(ProductItem).showStore(StoreInfo) </p></td>
  </tr>
</table>
# 每個名稱事件之合約 #
--------------
<table border="1" cellspacing="0" cellpadding="0">
  <tr>
    <td width="557" valign="top"><p>合約1：inputProduct()</p></td>
  </tr>
  <tr>
    <td width="557" valign="top"><p>操作：inputProduct()<br />
      交互參照：比價作業 <br />
      前置條件：檢查並確認實例newProduct之productName、productDemo、productPrice<br />
      後置條件：無<br />
      - -給定實例 newProduct之屬性productID最新商品編號 <br />
      -回傳productID、    productName、productDemo、productPrice</p></td>
  </tr>
</table>
<br>
<table border="1" cellspacing="0" cellpadding="0">
  <tr>
    <td width="557" valign="top"><p>合約2：inputStores() </p></td>
  </tr>
  <tr>
    <td width="557" valign="top"><p>操作：inputStores()<br />
      交互參照：比價作業 <br />
      前置條件：檢查並確認實例newStores之StoresName、StoresDemo、StoresPrice<br />
      後置條件：無 <br />
      - -給定實例 newStores之屬性StoresID最新商品編號 <br />
      -回傳StoresID、StoresDemo、StoresPrice</p></td>
  </tr>
</table>
<br>
<table border="1" cellspacing="0" cellpadding="0">
  <tr>
    <td width="557" valign="top"><p>合約3：showProduct(ProductItem) </p></td>
  </tr>
  <tr>
    <td width="557" valign="top"><p>操作：showProduct(ProductItem) <br />
      交互參照：比價作業 <br />
      前置條件：已開啟：Product物件 <br />
      後置條件：將productName、productDemo、productPrice顯示出來 <br />
      - -給定實例 newProduct之屬性productID最新商品編號 <br />
      -回傳printSuccess</p></td>
  </tr>
</table>
<br>
<table border="1" cellspacing="0" cellpadding="0">
  <tr>
    <td width="557" valign="top"><p>合約4：showStore(StoreItem) </p></td>
  </tr>
  <tr>
    <td width="557" valign="top"><p>操作：showStore(StoreItem) <br />
      交互參照：比價作業 <br />
      前置條件：已開啟：Store物件 <br />
      後置條件：將StoreName、StoreDemo、StorePrice顯示出來 <br />
      - -給定實例 newStore之屬性StoreID最新商品編號 <br />
      -回傳printSuccess</p></td>
  </tr>
</table>



# 使用案例的初步類別圖 #
-------
<img src="https://cacoo.com/diagrams/0EAiJp7LyBz2u8d4-ED47C.png">

-----------
-----------
-----------
#客戶基本資料作業#
-----------
# 客戶基本資料作業使用案例的描述 #

----------

<table>
<tr>
<td markdown="1">使用案例名稱</td>
<td markdown="1">客戶基本資料作業</td>
</tr>
<tr>
<td markdown="1">使用案例描述</td>
<td markdown="1">當有客戶資料更動時,專案人員啟動系統新增、修改、刪除客戶基本資料</td>
</tr>
<tr>
<td markdown="1">主要參與者</td>
<td markdown="1">專案人員</td>
</tr>
<tr>
<td markdown="1">利害關係人與目標</td>
<td markdown="1">專案人員：能夠正確記錄客戶基本資料。</td>
</tr>
<tr>
<td markdown="1">前置條件</td>
<td markdown="1">無</td>
</tr>
<tr>
<td markdown="1">後置條件</td>
<td markdown="1">正確建立、修改、刪除客戶基本資料</td>
</tr>
<tr>
<td markdown="1">主要成功情節</td>

<td>
<table>
<tr>
<td markdown="1">參與者</td>
<td markdown="1">系統</td>
</tr>
<tr>
<td markdown="1">1  當有新客戶申請帳號，專案人員進入客戶基本資料作業畫面，並啟動新增按鍵。
<br>
2  專案人員輸入客戶基本資料，包括客戶編號、客戶名稱、客戶地址、客戶電話。
<br>
3  輸入完畢後，檢查格是正確後，選取儲存鍵。
<br>
系統重複1-3的動作。
<br>
4  如果要進行修改，選取修改按鈕，並可依據任一個欄位進行查詢，讀取所要修改客戶記錄。修改完，按確認鍵或取消鍵。
<br>
5  如果要進行刪除，選取刪除按鍵，並可依據任一個欄位進行查詢，讀取所要刪除之客戶記錄。
</td>
<td markdown="1">1.1  系統開啟新增客戶品基本資料畫面。
<br>
2.1  系統檢查輸入格式，如果有誤要求重新輸入。檢查是否有重覆客戶編號，如果有，顯示"客戶編號重複"訊息
<br>
3.1  選取儲存按鍵，系統將客戶資料存入資料庫。如果按取消鍵，系統回至新增畫面。
<br>
4.1  根據輸入欄位資料，搜尋舊客戶記錄，並顯示至畫面。<br>
4.2  選取儲存鍵，儲存客戶記錄，如果按取消鍵，則回到客戶基本資料作業畫面。<br>
5.1  根據輸入欄位資料，搜尋舊客戶記錄，並顯示至畫面。<br>
5.2  出現確認鍵，按確認進行刪除動作，按取消則不做刪除動作。<br>
5.3  回到客戶基本資料作業畫面。
</td>
</tr>
</table>
</td>
</tr>
<tr>
<td markdown="1">例外情節</td>
<td markdown="1">*a. 如果有欄位無法輸入，或資料無法儲存，系統需要顯示警告訊息並中止輸入。</td>
</tr>
<tr>
<td markdown="1">其他需求</td>
<td markdown="1">無。</td>
</tr>
</table>




----------
# 使用案例的名詞與概念類別列舉表 #

----------
<table>
<tr>
<td markdown="1">名詞</td>
<td markdown="1">原因</td>
<td markdown="1">結果(是否為概念類別)</td>
</tr>
<tr>
<td markdown="1">專案人員</td>
<td markdown="1">負責記錄所有客戶資料。</td>
<td markdown="1">是。</td>
</tr>
<tr>
<td markdown="1">客戶</td>
<td markdown="1">記錄客戶基本資料，重要。</td>
<td markdown="1">是。</td>
</tr>
<tr>
<td markdown="1">客戶編號</td>
<td markdown="1">為客戶屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">客戶名稱</td>
<td markdown="1">為客戶屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">客戶地址</td>
<td markdown="1">為客戶屬性。</td>
<td markdown="1">否。</td>
</tr>
<tr>
<td markdown="1">客戶電話</td>
<td markdown="1">為客戶屬性。</td>
<td markdown="1">否。</td>
</tr>

</table>

----------
# 使用案例的初步類別圖 #

----------
<img src="https://cacoo.com/diagrams/gXBY2mto9uFrDMrv-F6B22.png">

----------
# 使用案例主要成功情節之英文名稱事件對應 #

----------
<table>
<tr>
<td markdown="1">使用案例：建立客戶資料作業</td>
</tr>
<tr>
<td markdown="1">
<table>
<tr>
<td markdown="1">主要成功情節：<br>
1 當有新客戶申請帳號，專案人員進入客戶基本資料作業畫面，並啟動新增按鍵。<br>

2 專案人員輸入客戶基本資料，包括客戶編號、客戶名稱、客戶地址、客戶電話。<br>

3 輸入完畢後，檢查格是正確後，選取儲存鍵。<br>

4 系統重複1-3的動作。<br>

5 如果要進行修改，選取修改按鈕，並可依據任一個欄位進行查詢，讀取所要修改客戶記錄。修改完，按確認鍵或取消鍵。<br>

6 如果要進行刪除，選取刪除按鍵，並可依據任一個欄位進行查詢，讀取所要刪除之客戶記錄。<br>

7 回到客戶基本資料作業。<br>

</td>
<td markdown="1">
<br>
inputCustomer()
<br><br><br><br><br><br>
saveCustomerRec(customer Rec)
<br><br><br><br>
modifyCustomer(customerID,customerName)<br>checkItem(customerItem)<br><br><br><br><br><br>
delectCustomer(customerID,customerName)<br><br><br><br><br>
</td>
</tr>
</table>
</td>
</tr>
</table>

----------
# 每個名稱事件之合約 #

----------
<table>
<tr>
<td markdown="1">合約1：inputCustomer()
</td>
</tr>
<tr>
<td markdown="1">操作：inputCustomer()
<br>
交互參照：客戶基本資料處理<br>
前置條件：-存在類別Customer之實例newCustomer<br>
後置條件：-檢查並確認newCustomer內的customerName、customerNO、customerPhone屬性質起始質為空白<br>
-給定實例 newcustomer之屬性customerNO為最新編號<br>
 -回傳給customerID
</td>
</tr>
</table>

<table>
<tr>
<td markdown="1">合約2：modifyCustomer()
</td>
</tr>
<tr>
<td markdown="1">操作：modifyCustomer(customerID)<br>
交互參照：客戶基本資料處理<br>
前置條件：-存在類別Customer之實例customer<br>
後置條件：:-根據customerID讀取客戶基本資料customerRec,並存到customer中<br>
-回傳customerRec
</td>
</tr>
</table>


----------



----------
# 使用案例之系統循序圖 #

----------
### 商品資料作業 ###
<img src="https://cacoo.com/diagrams/nISlnpmoZTMrT5Va-11858.png">
### 查詢商品 ###
<img src="https://cacoo.com/diagrams/NGY3r0Cic91WjzIf-D9C48.png">
###比價商品###
<img src="https://cacoo.com/diagrams/Z6QJ3mIMpgb2mBWF-11858.png">
###客戶基本資料作業###
<img src="https://cacoo.com/diagrams/DilT8PH823MI8zHf-AA261.png">

# ViewBag attr
## intro
ViewBag 用於獲取頁面資料。它允許在一個動態對象上定義任意屬性，

這些屬性可以在頁面中訪問，使控制器與視圖之間的簡單數據傳遞。

在 About() 方法中，

我們給 ViewBag 定義了一個 Message 屬性

![image](https://github.com/user-attachments/assets/3998defe-2e18-4b0b-8870-d1ef934de45b)

在這段程式碼中，
我們自己定義了一個名為 UserName的屬性，

並指定值為 Nash。ViewBag 是一個動態型 其類型為 dynamic。

ViewBag 定義的屬性也是 dynamic 類型，

這個類型會在運行時解析 UserName 屬性的具體類型。

## reference
[ViewBag 屬性](https://ithelp.ithome.com.tw/articles/10319693)

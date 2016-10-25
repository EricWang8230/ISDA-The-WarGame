# Level5: Cookie Bypass / Cookie管控

看了一下好像沒有前面幾題的漏洞，於是想到web常見的SQL Injection，但簡單的是了幾個基本的注入語句都沒有反應。

最後想到還有cookie bypass這招，打開cookie可以看到login和level5的值，發揮你的想象力讓他登入吧XD

![1](https://raw.githubusercontent.com/EricWang8230/ISDA-The-WarGame/master/2016-10-15-ISDA-%E7%99%BD%E5%B8%BD%E8%8F%81%E8%8B%B1%E5%85%A5%E9%96%80(1%2B2)/JPG/GAME%231-LEVEL5-1.png)

<br>

## 瀏覽器修改Cookie的方式

Example: Chrome
      
    document.cookie="CookieName=CookieValue"

or 

Google Search: 

    Cookie edit

都會找到很多套件(不管是firefox,chrome等)，安裝後就可以直接修改。

# Level8: binary分析

題目給了一個exe檔案，看到exe檔案直覺先丟IDA Pro，不過手上沒有Windows VM，所以先使用Linux指令簡單看一下。

Linux:

    xxd level8.exe
    
or

    strings level8.exe
    
 
觀察一下內容，即可發現key。

<br>

## 開發者需要注意的點：
<ol>
  <li>
    執行檔案是可以被逆向工程拆解的。
  </li>
  <li>
    對程式進行混淆以保護原始碼。
  </li>
</ol>

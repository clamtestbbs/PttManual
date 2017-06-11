# 完全批踢踢使用手冊

This repository is an experimental project.

This content is origin from [PttBBS](http://github.com/ptt/pttbbs).

## 安裝方法:

### 1. 首先請先安裝 PttBBS

   安裝方法見: http://github.com/ptt/pttbbs 參考 doc/INSTALL，或是裡面的 [wiki](http://github.com/ptt/pttbbs) 專區.

   或是確認在所管理的 BBS 站台，有系統方面的 **bbsadm權限** 以及站務方面的**開板權限** 的相關人員可以協助

### 2. 進入自己主機的 bbsadm 帳號後, 將資料匯入:

`$ cd ~/man/boards/P/`

`$ git clone https://github.com/holishing/PttManual`

### 3. 利用 BBS 連線軟體登入自己帳號後，至自己有管理權限的合適群組按大寫 R 開板

### 完成!!


***

## 相關進階設定: (需有站長 + bbsadm 權限或同時有相關權限者彼此配合)

設定 symbolic link:

登入站務介面，到 `(A)nnounce【 精華公佈欄 】` 按小g 建立目錄，並將該目錄檔名記錄下來

進入自己主機的 bbsadm 帳號, `cd ~/man/;rm `【該目錄檔名】` `

以相關系統指令 `ln -s `【欲連結檔案】` `【幫該symlink取的名稱】` `

將完全使用手冊連結至公佈欄給站台內其他使用者參考


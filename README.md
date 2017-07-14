<br><br>
# 完全批踢踢使用手冊

This repository is an experimental project.

This content is origin from [PttBBS](https://www.ptt.cc/man/PttNewhand/DAE3/index.html).

## 安裝方法:

### 1. 首先請先安裝 PttBBS

   安裝方法見: http://github.com/ptt/pttbbs 參考 doc/INSTALL，或是裡面的 [wiki](http://github.com/ptt/pttbbs/wiki) 專區.

   或是確認在所管理的 BBS 站台，有系統方面的 **bbsadm權限** 以及站務方面的**開板權限** 的相關人員可以協助

### 2. 進入自己主機的 bbsadm 帳號後, 將資料匯入 PttManual 看板:
(也可以視需求fork此專案成不同的名字以便匯入不同的板名, 或自行做其他調整)

`$ cd ~/man/boards/P/`

`$ git clone https://github.com/holishing/PttManual`

### 3. 利用 BBS 連線軟體登入自己帳號後，至自己有管理權限的合適群組按大寫 R 開板

### 4.完成!!


## 連結至站台公佈欄 (需有站長 + bbsadm 權限或同時有相關權限者彼此配合)

設定 symbolic link:

登入站務介面，到 `(A)nnounce【 精華公佈欄 】` 按小g 建立目錄，並將該目錄檔名記錄下來

進入自己主機的 **bbsadm** 帳號, `cd ~/man/;rm `【原目錄檔名】` `

以相關系統指令 `ln -s ~/man/boards/P/PttManual/D6B0 `【原被刪目錄的檔名】` `

將原本只在 PttManual 板精華區的完全使用手冊連結至公佈欄給站台內其他使用者參考


***

# 相關版權宣告 (by Ptt站方聲明)

《完全批踢踢使用者手冊》系列手冊根據 Ptt Open Source 的精神，所有使用 PttCurrent 的機器以及使用者，均可使用本手冊。各 BBS 站台並可根據該站台特性，將本手冊做適度修改，以符合該站之各式功能按鍵及風格。
<br><br>

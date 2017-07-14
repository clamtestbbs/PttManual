# 完全批踢踢使用手冊

This repository is an experimental project.

This content is origin from [PttBBS](https://www.ptt.cc/man/PttNewhand/DAE3/index.html).

Encoding: Big-5 (for BBS system)

## 安裝方法:

### 1. 首先請先在安裝 PttBBS

   安裝方法見: http://github.com/ptt/pttbbs 參考 doc/INSTALL，或是裡面的 [wiki](http://github.com/ptt/pttbbs/wiki) 專區.

   或是確認在所管理的 BBS 站台，有工作站(系統)方面的 **bbsadm權限** 以及站務方面的**開板權限** 的相關人員可以協助

### 2. 進入工作站的 bbsadm 帳號後, 將資料匯入你所要匯入的看板
(以下以 NewHand 板為例, 也可以視需求匯入不同的看板, 或自行做其他調整)

`$ cd ~/man/boards/N/NewHand`

`$ git clone https://github.com/holishing/PttManual`

### 3. 設定 symbolic link

先到你要放資料的看板(如: NewHand 板)裡的精華區, 小寫g建立目錄, 並在該目錄前按大寫N查看檔名

回去工作站, 將該目錄刪除後, 建立相同檔名的 symbolic link

`$ rm -r <目錄檔名>; ln -s PttManual <檔名與原目錄相同的symbolic link>

### 4.完成!!


## 連結至站台公佈欄 (需有站長 + bbsadm 權限或同時有相關權限者彼此配合)

設定 symbolic link:

登入站務介面，到 `(A)nnounce【 精華公佈欄 】` 按小g 建立目錄，並將該目錄檔名記錄下來

進入自己主機的 **bbsadm** 帳號, `cd ~/man/;rm `【原目錄檔名】` `

以相關系統指令 `ln -s ~/man/boards/<板名開頭字母>/<你匯入的板名>/PttManual `【原被刪目錄的檔名】` `

將原本只在 PttManual 板精華區的完全使用手冊連結至公佈欄給站台內其他使用者參考


***

# 相關版權宣告 (by Ptt站方聲明)

《完全批踢踢使用者手冊》系列手冊根據 Ptt Open Source 的精神，所有使用 PttCurrent 的機器以及使用者，均可使用本手冊。各 BBS 站台並可根據該站台特性，將本手冊做適度修改，以符合該站之各式功能按鍵及風格。


***

## CHANGELOG:

1.註冊帳號介面更新, 補充保留天數資訊 (6/23)

2.排版頁末皆多加一空行以利pmore介面閱讀 (6/23)

3.統一"Ctrl+按鍵"樣式


以GPT4o-mini寫，沒有技術量去修bug，一切錯誤問AI。


配合[UnpackKindleS](https://github.com/Aeroblast/UnpackKindleS)使用藍疊，而不必打開calibre一鍵出epub

結合

日亚4月23日后新书提取[教程](https://books.fishhawk.top/forum/680f133909bd607077257da8)

日亚4月23日后新书提取改高清图[教程](https://books.fishhawk.top/forum/6810a15109bd6070772647fc)


### 做法

1)打開藍疊(1個)

2)下載書

3)雙擊_Tool_adb_bs_calibre_epub.py

4)輸出epub

注意：當你拆完一次後，如果你不刪android資料夾，第二次拆書會重複拆


### 注意你的calibre暫存檔位置，預設是C:\Users\使用者名\calibre 書庫

`calibre_library_path = os.path.join(os.path.expanduser('~'), 'calibre 書庫')`  # 預設為用戶目錄下

`calibre_library_path = r'D:\Calibre Library'`  # 可修改為其他語言的實際路徑


如果你的UnpackKindleS放在別地方，可以改位置

`unpack_kindle_base_path = current_dir`  # 預設為當前目錄

`unpack_kindle_base_path = r'E:\UnpackKindleS'`  # 可修改為實際路徑


### 事前是你已經成功過一次，本python用於第二次以後
據體位置是，你已經入了backup.ab後，而試了一本prc書入calibre是自動變azw代表成功

1)自動找到端口

2)自動加書calibre

3)自動拆成epub(res)

4)自動刪calibre書庫


### 準備的東西

UnpackKindleS

python

calibre，AZW6 Image Merge，dedrm，backup.ab

藍疊

SDK Platform Tools放在UnpackKindleS資料夾

### UnpackKindleS資料夾目錄下要有(全路徑不可以有中文)

UnpackKindleS/app

UnpackKindleS/platform-tools

UnpackKindleS/_Tool_adb_bs_calibre_epub.py




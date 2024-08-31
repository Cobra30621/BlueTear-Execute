# 藍眼淚執行檔(Unity)

Cilab 與曹松清畫家合作設計出以馬祖藍眼淚為主題的互動式畫展，畫作內可以以手勢來控制畫作的光影變化隨時欣賞藍眼淚的奇異美景
- [Demo 影片](https://www.youtube.com/watch?v=u5FYUrtseUc)


## 相關連結

- [手勢偵測專案](https://github.com/Cobra30621/Blue_tear_pose_detection)
- [Unity 藍眼淚專案](https://github.com/Cobra30621/BlueTear_unity)
- [Unity 執行檔](https://github.com/Cobra30621/BlueTear-Execute)
- [總交接文件目錄](https://hackmd.io/bshavgPmR7iQqVW_mfMg6Q)

## 輸出專案

- 在 Unity build 時，選擇這個資料夾


## 執行專案

- 需要把手勢偵測專案輸出的執行檔 socket_client.exe 放入(該檔案大於 100MB ，無法進行 Git 版控)
- 詳情請看 [使用說明.docx]


### 開發者工具


- Unity 端
  - 點擊 ese，可以顯示偵錯畫面
  - 點擊 R 重新開始遊戲
  - 點擊 Q 離開遊戲
- 攝影機設定
  - 可以在 camera_setting.txt 中，指定攝影機要使用的編號 (內建攝影機預為為0，外接攝影機為 1)

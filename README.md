# Project_FirstGroup
### 系統分析專題 
### 組長：林莉庭　組員：陳冠穎、巫易駿、許育碩

### 題目:愛情限時批（劈）

### 創意發想
雖然市面上已有許多交友軟體，但因為沒有條件的限制，因此容易產生配對，這個現象雖然讓人們更容易地交到朋友，但也在無意間影響了大眾的愛情價值觀。像這樣一對多的聊天型態，從中挑選自己喜愛的，而那些沒被選到的則被放著不理或是塑膠回覆的模式，改變了人與人之間認識的真正意義，進而造成現今速食愛情風氣越來越盛行（因為都是草率的認識、草率的交往、草率的分手:unamused:）。為了改善人們交友的壞習慣以及更精準的配對到喜愛的對象，本團隊預計開發『愛情限時批』強大APP，造福大眾！！:heart::heart::heart:

### 專題內容
開發一新穎的交友軟體，改善人與人之間的互動模式與價值觀。<br>
提供一良好管道讓不擅長交友的人拓展人際關係 ; 讓孤單多年的單身狗更快找到等待已久的那...個...人！！:heart::heart::heart:

### 工作分配
- 後端開發，勞工擔當『陳冠穎、巫易駿』:vibration_mode:<br>
- 創意發想、報告、送茶按摩，耍酷擔當『許育碩』:file_folder:<br>
- 書面及PPT報告製作、前端設計，顏值擔當『林莉庭』:crystal_ball:

### 圖表
![GANTT](系統圖.png "gantt")

### 功能性需求
 1. **個人化喜好設定**：根據使用者設定的條件（不抽菸、不喝酒、不嚼檳榔）進行對象篩選，避免因為只看長相而忽略內在的錯誤配對發生。
 2. **限量配對**：也叫「舊的不去，新的不來」之專情模式，每次配對只能跟一個對象聊天，養成謹慎選擇的想法。
 3. **取消配對**：一旦覺得對方不適合，可立即取消配對。而除了解除配對外，沒有別的選擇，否則將無法進行下一段的愛情配對。
 4. **情感互評**：持續聊天超過五天將進行對象互評，雙方看不到對方評分結果以免發生走心的狀況，彼此分數未達門檻將自動結束這段配對，且對話紀錄會全被消除；分數達到門檻則會繼續發展這段關係。

### 非功能性需求
- 反應時間：將使用者觸發事件所須花費之時間控制在1.5秒內。
- 使用性：APP介面簡易不複雜，人人都能立馬上手。
- 可靠度：使用者設定的特徵篩選需有高度的準確性，因此本團隊預期透過更大量的訓練與分析將錯誤率降至<20%。
- 效能：能以很快的速度過濾頁面資料而執行下一步動作 ; 能確保聊天過程的執行順暢，且所有記錄與資料都受到加密的高度保護。
- 維護性：定期進行系統的維護與測試，並將每次的檢查進行事件記錄，對其中發現的問題進行根本原因分析。

### 功能分解圖(functional decomposition diagram, FDD)
![FDD](FDD.png "FDD")

### 需求分析的文字描述
1. 用戶可以藉此軟體找到速配的另一半
2. 用戶可以藉此軟體設定配對的條件
3. 透過AI分析用戶喜好推薦適合的異性
4. 用戶首次進入軟體，將會填寫個人資料
5. 首次配對前，要求用戶設定配對異性的條件
6. 配對成功後，雙方將可以透過本軟體聊天
7. 聊天過程中，隨時可以退出本次配對，去尋找下一位異性；但過於頻繁退出會有冷卻機制
8. 聊天結束後，系統將會讓雙方互評，若分數未達門檻，將會結束此次配對
9. 聊天結束後分數，如果分數達到門檻，雙方能夠交換聯絡方式

### 使用案例圖
![案例圖](圖.jpg "圖")
### 使用案例說明
使用案例名稱 | 配對設定
--- | --- 
行動者	 | 用戶
說明	 | 說明及設定本軟體如何透過篩選條件進行配對
完成動作	 | 1.用戶了解如何設定條件2.設定戀愛性向3.設定個資4.提供清晰正臉照檢核
替代方法   |	1.用戶了解如何設定條件2.設定戀愛性向3.設定個資4.不提供正臉照檢核
先決條件   |用戶願意提供真實個資及正臉照
後置條件	 |設定完成後，即可開始配對
假設      |用戶要求配對的對象應是人類

使用案例名稱 | 聊天室
--- | --- 
行動者	 | 用戶
說明	 | 配對成功的對象聊天的地方
完成動作	 | 1.進入聊天室2.提供話題3.開始聊天
替代方法   |	1.進入聊天室2.提供話題3.選擇已提供的話題4.開始聊天
先決條件   |用戶需要先配對完成
後置條件	 |退出聊天室會清空對話紀錄，再配對成功才能再進入聊天室
假設      |無

使用案例名稱 | 帳號設定
--- | --- 
行動者	 | 用戶
說明	 | 讓用戶對自己的帳號進行各種設定
完成動作	 | 1.進入設定頁面2.更改各項設定3.儲存變更
替代方法   |	1.進入設定頁面2.更改各項設定3.不儲存變更
先決條件   |用戶需要先建立帳號
後置條件	 |設定結束，可繼續配對
假設      |無
### 系統分析圖

### 資料流向圖


### 推薦:
#### 知名愛情獵人羅志祥強力推薦:heart:
#### 愛情公寓CEO強力推薦:heart:

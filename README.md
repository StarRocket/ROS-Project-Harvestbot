# 【Star Rocket】從 Farmbot 到採果機器人
介紹 FarmBot Taiwan User Group 與開源採果專案，分享建構採果機器人時 ROS 的學習歷程與研發成果。

本次課程活動頁面：[連結](https://www.accupass.com/event/1811010804218309270900)

！！！號召對於 ROS 開源機器人開發系統或是機器人開發有任何興趣的好朋友們一同加入我們，歡迎告訴我們你想要聽見 ROS 的什麼 >>>[點這裡](http://bit.ly/2BKieyB)

## 課程重點（哈爸分享內容）
1. Farmbot Taiwan User Group(FBTUG) 
    1. 社群的發起：自業界工作超過 20 年的哈爸，工程師出身，2017/03/18 一起找了社群朋友開箱，大家花了兩天時間組了起來，大致完成 Farmbot 的組裝，但是加上軟硬體整合後，真的算完成是花了一個多月的時間，完成台灣第一台 Farmbot；陸續的社群活動與共創，實作了不少子專案，包含研究型的系統 Mini FarmBot, FBTUG Commander，針對農場設計的農場版，使眾多農務數據資料能夠回到雲端系統上，開始做數據分析與視覺辨識。
    2. Mini farmbot：當時在美國做了 Farmbot 這台機器，是一個很棒的貢獻，因為這樣的開源農業機器，將會帶來一個新的時代，所以在台灣深耕與推展是很重要的，所以對技術本身必須要完全的掌握，研究、複製與改裝是一開始最重要的事情，同時也是確認這是全開源的一個重要步驟，在主力 Joe Ho 的貢獻下，社群有了 Mini farmbot 的雛形，之後由 iCShop 改善了量產的問題，也進而有了部分的小量產，目前也有教育單位的共創投入。
    3. 開放社群的協作：由於開源專案有它學習實作上的部分挑戰，也使哈爸在這過程中看見開放社群的優點，在這樣的環境底下能夠讓人更加速學習，跨領域的合作，特別在 ROS 系統學習中更是明顯，能夠使用現有資源就能夠快速學習與進步，並且能夠透過其他專業夥伴的建議更容易突破瓶頸；也有人曾詢問過哈爸，做開放如何賺錢呢？但就哈爸個人的理解，如果企業採用封閉型態卻無法做得比開放系統棒的情況，我們起碼需先學會開放的設計，在開放設計的基礎上，繼續精進，而不是不了解開放系統的能耐，閉門造車。
    4. 產業價值：FarmBot 在軟韌體與機構的整合，且專注在農業的情境，加上開放的特性，本來就具備技術價值，能提供給相關的產業，目前 FBTUG 已經是個滿完整的社群體系，藉由更多的開放式教育訓練，透過社群匯集與整合各類型專家，更落地到教育以及場域情境，使像 Farmbot 這樣的產品更能夠跟產業接軌，有效改善更多農務上的突破跟需要。
    5. 接下來的目標：
        1. 大數據 AI 走向：將所蒐集到的農務數據做更近一步的分析，並回饋在相關應用上，做更精準的農務作業。
        2. 自動化系統：將原有系統更朝向全自動化的方向去發展，減少人力及維護成本。
    6. 需要突破三件事：
        1. 場域挑戰：持續研發與驗證，將設備推進場域。
        2. 落地教育：在地的教育資源和教育人才。
        3. 走上國際：將社群的成果推展上國際，對國際社群帶來貢獻。
2. 採果機器人
    1. 起源和目標：從起初 Farmbot 能夠做基礎的農務後，要進而能夠自動化採集果實為目標而開啟了這個專案，目標是催生這樣的機器能夠在台灣能夠商業化，功能是能夠讓機器透過視覺辨識去看水果在哪裡，並且用手臂去採集，並且聯網，利用手機定位，而就哈爸的調查了解下來，目前全球沒有人完整的做出相關產品出來。哈爸也將此專案完全的開源出來，邀請社群夥伴共同參與，就階段性不追求到完美，但目標是需要具有一定水準的產出，而此專案也於 2018/08/15 正式想出來，正式於 2018/08/28 開始這個專案，以及當時的合作夥伴：台灣人工智慧學校共同參與。
    2. 面臨的挑戰：
        1. 財務需求：此專案依據以往評估沒有 500 萬是很難去完成的，特別現在是開放的作法，目前透過社群夥伴的贊助，有贊助意願表達共約 18 萬元整。
        2. 技術門檻：此項目最麻煩的地方就是即便集合頂尖的人士仍舊還有很多整合層面的技術不會做，因為是全新的東西，而 ROS 是很多機器人的核心系統，這部分社群夥伴不是很熟悉。
    3. 階段性成果：但哈爸沒有因為以上挑戰就此停止，反倒是自行實作開始積極學習 ROS 走過許多專案，從小鴨城、霹靂車，及至目前針對採果機器人已經有了初步的小城果，有了第一版夾具的釋出，也嘗試了第一此的訓練，及至目前專案花不到 3 萬元整，且持續的研究進行中。
3. ROS 學習歷程
    1. 學習原由：為了做出採果專案因此開始了學習 ROS 的旅程，即使有專案各領域的專業夥伴，還是有很多的整合與設計是不知道該怎麼做的，只覺得 ROS 是個正確的方向，很多絢麗的功能與相關的研究成果，即使最後不適合，也是重要的學習過程，主因也是開源，開放的體系，適合開源專案的推展。
    2. 面對挑戰
        1. 大海中學習：於 2018/09/06 哈爸打開第一份文件要學習 ROS，在 ROS 環境中假設採收水果的機器人，邊走邊看，一個一個採收完繼續前進，所以的內容都要寫 Code，寫完總共花了三天的時間，超出哈爸的想像，因為在 ROS 裡面什麼都有，學無止境，像掉在海裡一樣，無所適從，看了什麼也不會，照做了一次會動了也不知道原因，不會動也不知道錯誤在哪，在這種情況下要清楚知道自己要什麼？解決什麼？哈爸的目的很清楚，很專心，花了三天，過程很多錯誤是沒有很懂，但也大概知道一些了。到現在十二月多，哈爸學 ROS 的速度就是這樣一關一關打下去。
        2. 硬體的價格：哈爸在研究資料後似懂非懂，但較完整的設備價格不便宜，還好後來認識到了有小鴨城的專案，就趕緊去嘗試，以及霹靂車，開始從這兩個著手，只需花幾千元，特別在 ROS 系統上，有實機的學習跟沒有實機效率才是有很大的差異。
        3. 需要學習如何 Debug：在還沒拿到機器之前，哈爸不知道 Debug ROS 系統，那時候還不懂 ROS，找一份速查手冊，ROS 文件在關鍵的部分寫得很清楚，哈爸的第一步就是把小抄本內容全部打一遍，就先去熟悉這件事情，ROS 是一個分散式的系統，一般系統，適合從設計文件才能知道整件事，ROS 不用，這是分散式系統好處，系統架構看圖可以藉由觀察資料流與介面就可以知道，這是一開始不會用 ROS 走的過程。最後產出自己的 Debug ROS 系統文件與工具，因為 ROS 沒有完整的 Debug ROS 流程。
    3. 學習與練習：
        1. 小鴨城專案：[連結](https://www.duckietown.org/)
        2. Turtlebot3：[連結](http://emanual.robotis.com/docs/en/platform/turtlebot3/overview/)
        3. DOT (graph description language)：[連結](https://en.wikipedia.org/wiki/DOT_(graph_description_language))
        4. MoveIt! Move Group Python Interface Tutorial Demo：[連結](https://www.youtube.com/watch?v=3MA5ebXPLsc&feature=youtu.be)
        5. MoveIt! Setup Example：[連結](https://www.youtube.com/watch?v=asg-thB3mwA)
        6. ROS Tutorial：Create an arm on a mobile robot using Moveit：[連結](https://www.youtube.com/watch?v=l4dtSRvlAjg)
        7. 霹靂車：[連結](https://www.icshop.com.tw/product_info.php/products_id/26775)
    5. 學習技巧：
        1. 學習與教學同步：要自己實際做出專案，但這些仍舊是表面，試著教，在教的過程中確認自己的思路是否清楚正確。
        2. 開始前先寫文件：開始以前，先寫文件，邊做邊寫，不要做完再寫，不會的東西找到一個 package，先弄一點懂，再寫再做，不要做完才公開。
        3. 要多看原始編碼：做開源專案要看素材的原始編碼 Source Code，不懂的東西一定要看 Code，開始做研究筆記，讓你清楚整件事情的思路與脈絡。
        4. Dot Graph 習慣：看不懂就把它給畫出來，看清出也整理自己的思路。
        5. 開源分享的心態：保持開放公開分享，讓你學得更快，更知道錯誤在哪，會有更多人跟你一起學習。
        6. 要善用搜尋工具：學習 Google，沒有什麼是找不到的。
        7. 想要超越先學抄：不要先想如何做出新的，先學會別人的再說。
        8. 不太會就自己寫 QA：讓自己更清楚學習的問題在哪裡，藉此找到正確的答案。
4. 與哈爸的 Q&A
    1. Ｑ：在開源會遇到問題是，怎麼判對是否需要學習這個或是學習那個？Ａ：東西找個三五分鐘找不出來就放棄，先把困難得擺著，我不會碰到什麼就去弄到全懂，我只學我需要的部份。
    2. Ｑ：有些在做這方面的硬體，大量能做比較便宜，台灣有在做這方面的硬體嗎？採菜，如果是量產會比較便宜嗎？Ａ：就階段性來説，台灣目前沒有人會做，台灣整合看似好像比較弱，但現在的重點在我們需要從零到一做出來都很困難。

## 本次課程資源：
* 課程簡報：[連結](https://drive.google.com/drive/folders/1EoFXTLb8Z40Jb0Daifq7tuchAjVljeI0?usp=sharing)

## 推薦學習資源：
* FarmBot Taiwan User Group - FBTUG：[連結](https://www.facebook.com/groups/FarmBotTUG/)
* 採果機器人專案首頁：[連結](http://bit.ly/2Qqgz79)
* 採果機器人專案 - Github：[連結](https://github.com/FBTUG)
* 採果機器人專案 - 網站：[連結](https://fbtug.github.io/FarmHarvestBot/)

## 課程媒體紀錄
* 照片：[連結](https://drive.google.com/drive/folders/1EdVMi9yEEG1kAlrEjz3XSMJjSxBoaCQC?usp=sharing)
* 影片（完整課程回顧）：[連結](http://bit.ly/2PTTPM4)


！！！號召對於 ROS 開源機器人開發系統或是機器人開發有任何興趣的好朋友們一同加入我們，歡迎告訴我們你想要聽見 ROS 的什麼 >>>[點這裡](http://bit.ly/2BKieyB)

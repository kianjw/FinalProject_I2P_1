NTHU_I2P_Project
主題：Flappy Bird
製作人： SCLemon、Kian、孟哲

主要作法：Bird在 y 軸座標移動而 x 軸固定，利用管子向左移動的方式降低實作的複雜度。
附加功能：管子長度的變更以及擺放位置還有撞到後的終結事件。
素材來源：https://github.com/ianitow/flappy-bird-game/tree/main/images
參考資料：
1. Github: https://github.com/ianitow/flappy-bird-game
2. Youtube: https://www.youtube.com/watch?v=fDdwCTbZL5c
3. Youtube: https://www.youtube.com/watch?v=b6A4XHkTjs8&t=896s
3. Allegro tutorial: https://www.youtube.com/watch?v=27G-2-wn41w&t=2202s
and etc (but almost with C++)...
分工表：
第一部分（SCLemon）：主要架構、Makefile、素材建立、程式初始化製作
第二部分（Kian）：影音設計、使用者操作、角色設定
第三部分（孟哲）：障礙物、按鍵事件、角色陣亡事件
特點一：善用I/O將最高紀錄撰寫成文件檔儲存在本地端中作為記憶最高分使用，並在下一輪遊戲開始時，將其分數讀出，當刷新最高分數時，重新撰寫並儲存。，
特點二：為了避免程式碼出現異常（must_init）函式可以在任何一個程式碼運行或繪製圖案時出錯而立即中止並彈出提示信息，可以避免使用者在操作上出現錯誤的可能性。
特點三：利用buffer來緩衝圖層繪製，避免破圖並提高執行效率。
and etc...
（建議）客制化難度調整：
1. 調整螢幕縮放比例 （程式碼第68行）
2. 調整管口間距（程式碼第383行）
3. 調整單位得分（程式碼第433行）
4. （不建議）角色屬性設定（程式碼第369~373行）
製作日誌：
2023.06.02 討論主題
2023.06.03 收集素材（ Mario / Flappy bird）
2023.06.03 提議反駁（ 2048 小遊戲 ）不符合操蹤角色
2023.06.03 暫定主題 ( Flappy bird )
2023.06.07 提議主題 ( Teris ) 並取得素材
2023.06.07 最終抉擇 ( Flappy bird )
2023.06.07 開始討論
2023.06.07~2023.06.08 完成第一部分功能與註解 （ SCLemon ）
2023.06.10~2023.06.11 探討與思考 proposal 撰寫
2023.06.11 完成第二部分與第三部分功能與註解 （ Kian / 孟哲 ）
2023.06.14~2023.06.15 How to write a game proposal
2023.06.16 重新上傳 Github 倉庫
2023.06.16~2023.06.17 撰寫 proposal
2023.06.19 現場 Demo 小作品
How to Use?
Download ZIP -> drop the folder into VScode -> create Terminal -> cd flappy/src -> make -> ./game.out -> start to play!!
Tutorial Created by SCLemon 2023.06.02~2023.06.19

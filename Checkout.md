? 如何叫出所有版本紀錄？
指令是  git log
會得到 Head -> master 由新到舊的版本紀錄
內容包括：提交者、日期、提交主題
master 是任務主線
head 是任務進度（最新存檔點）
！！若沒有修改，好像無法替換版本

MH@Mac-mini VScode % [輸入] git log （跳出 log 要按Ｑ）
［得到］

commit 01d8983d5bcb4392f538d6ccaee46ec09eb9a663 (HEAD -> main)
Author: SandraYangTW <sandra.f.y.yang@gmail.com>
Date:   Sat Oct 12 19:38:50 2024 +0800
    基礎規則

commit a0909ec3dbbc6e9acce01eda8f45a506538049fa
Author: SandraYangTW <sandra.f.y.yang@gmail.com>
Date:   Sat Oct 12 19:35:19 2024 +0800
    基礎規則
!!!!!!!!!!!!!!!!!!!!!!!!!
真正的還原是找到 git log --oneline 數字標籤後
下指令
git checkout ******(數字標籤) -- 檔名.副檔名

為了練習checkout指令的亂寫

幾乎可以換前換後調整

MH@Mac-mini VScode % git checkout 8422196 -- Checkout.md
MH@Mac-mini VScode % git checkout c014c94 -- Checkout.md
MH@Mac-mini VScode % git checkout 8422196 -- Checkout.md
MH@Mac-mini VScode % git checkout c014c94 -- Checkout.md
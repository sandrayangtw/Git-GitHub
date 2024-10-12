比較各版本還原點
git diff f56ad3c -- Checkout.md
[得到非常精細的比較]

MH@Mac-mini VScode % git diff f56ad3c -- Checkout.md
--f56ad3c 是版本的數字標籤，輸入後會跟目前版本作比較

diff --git a/Checkout.md b/Checkout.md
index dc9c1b3..34df5e3 100644
--- a/Checkout.md
+++ b/Checkout.md
@@ -1,8 +1,12 @@
 ? 如何叫出所有版本紀錄？
 指令是  git log
 會得到 Head -> master 由新到舊的版本紀錄
+內容包括：提交者、日期、提交主題
+master 是任務主線
+head 是任務進度（最新存檔點）
+！！若沒有修改，好像無法替換版本
 
-MH@Mac-mini VScode % [輸入] git log
+MH@Mac-mini VScode % [輸入] git log （跳出 log 要按Ｑ）
 ［得到］
 
 commit 01d8983d5bcb4392f538d6ccaee46ec09eb9a663 (HEAD -> main)
@@ -13,4 +17,4 @@ Date:   Sat Oct 12 19:38:50 2024 +0800
 commit a0909ec3dbbc6e9acce01eda8f45a506538049fa
 Author: SandraYangTW <sandra.f.y.yang@gmail.com>
 Date:   Sat Oct 12 19:35:19 2024 +0800
-    基礎規則
\ No newline at end of file
+    基礎規則
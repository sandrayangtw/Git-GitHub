新增檔案要加副檔名
連續新增檔案時，以空格分開，每個檔案都要加副檔名
或是 git add ＾．＾ 可追蹤所有檔案
或是 git add *.md 來限制追蹤檔案類型
最後Save指令是 Command+Save
可以用 git.status 檢查狀態
clear => 清空所有指令紀錄

每次修改檔案後的存檔，都必須 git add 告知要 commit 什麼
否則會出現 =>

no changes added to commit (use "git add" and/or "git commit -a")
若 git add 後，可以一口氣家所有檔案的新版本嗎？

是的一次可以幫所有檔案留下新版本

[main f26beb8] 若 git add 後，可以一口氣家所有檔案的新版本嗎？
 4 files changed, 34 insertions(+), 3 deletions(-)

 所以 diff / checkout + 版本數字標籤後，都必須加檔案
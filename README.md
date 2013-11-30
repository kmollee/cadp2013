cadp2013
========
CADP 2013 秋季

期中報告範例 cherrypy on openshift

# 2013-11-07 

update template 結構 更新

新增 ia 範例

參數 category 與 temp

category 代表所屬的課程 (目前有 cadp and ia 範例)

temp 則是在此 category 下所要採用的 template (如想使用哪個 .html)

此版本也把 檔案下載的位置做些改變 放在 kmol/${category}/

如有問題請至研究室詢問

# 2013-12-01

更改 applcation conf 使得 cherrypy 能在近端正常啟動

其效果應該和 openshift 上一模一樣

切記! downloads 目錄 應該用 .gitignore 來將其區隔

自己用 sftp 上傳至 openhsift 'OPENSHIFT_DATA_DIR' 區

git 是用來管理程式 而不是檔案

======================================

範例網站 [here](http://python33-adminformosa.rhcloud.com/)
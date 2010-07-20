本範本是由元智大學碩博士論文latex範本改編而來
目前主要是修改了以下幾個東西
1.浮水印
2.封面格式
3.加入教授推薦書頁面
4.刪除無用的頁面
5.更改檔案結構

在進行論文寫作時，只需改變所有檔名為my_XXXXXXX.XXX之文件，將這些文件中論文相關的資訊取代。
本tex之主結構檔為thesis.tex，其中需要修改的東西為在frontpages及backpages之文件。
論文主結構及內容請分類放置於sections目錄中，而references的bibtex檔請放置於目錄第一層之my_bib.bib。
在編譯thesis.tex檔時，請記得要使用 pdflatex 編譯1次，接著執行 bibtex 1次，最後用 pdflatex 編譯2次。


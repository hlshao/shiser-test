# shiserTestFile
R Shiny Server Test File

進行 R Shiny 進行測試的檔案，當中匯入 ggplot2 套件的資料。

除了要預先安裝好 R 也要將 ggplot2, shiny 套件在 R 安裝好，如果是在 R Shiny Server 上要注意套件庫的來源與在 Linux 的權限。

1.RStudio Desktop

setwd("[指定目錄]")
getwd()
library(shiny)
runApp("haoyehowld")


2.RStudio Server

將整個目錄放置該路徑下 : /srv/shiny-server/

/srv/shiny-server/haoyehowld

瀏覽器

https://[ your IP ]:3838/haoyehowld

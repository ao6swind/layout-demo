[點此觀看](https://ao6swind.github.io/layout-demo)  

## murmur ##
本來想趁著過年期間把Angular跟Firebase的應用練起來，沒想到卡在身分驗證卡這麼久，為了轉換心情就換個題目練習一下後台的排版。這種排版的右邊內容區域我一直不知道怎麼讓它有一個最小高度，所以在沒有內容的時候整個版會變短（若您是有經驗的前輩還請賜教 Orz）。  

之前指導新同事進_navbar.scss去改樣式，讓橫的導覽列變成直的，但後來建了.net core angular範本，發現只要會用clearfix就可以解決這個問題，一直以來都沒有空嘗試看看，這次就加了這個部分進來，一樣也是用bootstrap@3.3.7。但加入了clearfix樣式後，原本導覽列中的li就失去了block的特性，為了讓使用者在選取子導覽列中的功能時能順利些，額外調整li、a標籤的寬度變成100%  

本來想用webpack打包scss和js，但實在是讀不懂config要怎麼寫... ... ˊ_>ˋ  
  
## 套件來源 ##
1. [Fullcalendar](https://fullcalendar.io/)
2. [dhtmlxGantt](https://dhtmlx.com/docs/products/dhtmlxGantt/)
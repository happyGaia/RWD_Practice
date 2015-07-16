# RWD練習
   
## 使用技術
   RWD, sass, jquery

## 自適應範圍(參考檔案) - 說明

  有關RWD設定請看all.sass。
   * phone-small: 400px以下 ( _phone_s_400.sass ) - 在試chrome測試 iphone 4和 google nexus 4，發現約在400px下，因此設定。
   * phone-big: 768px以下 ( _phone.sass ) - 在看模仿的網站時，發現他大約在這範圍menu會到極限，並縮成下拉式選單。
   * pad: 991px以下 ( _pad.sass )
   * common: 全域，pc(含)以下設備都會讀到此檔 ( _common.sass )
   
## 其餘檔案說明
   * _setting.sass : 主要放需要共用顏色、width、height與長寬計算設定。
   * _extend.sass : 某段程式碼會被共用到，會放此 ex @extend %clearfix等。
   * _mixin.sass : 某段程式碼會被共用到，並且會傳參數設定。
   * index.html : 所有html內容皆在此。由於此是為了練習RWD，並未將header、content、footer分開共用，正常可以用jquery .load() 或 Erb的方式共用header、footer。
   
## 測試的瀏覽器
   * PC上，下列瀏覽器 x 自適應範圍
     * chrome (Mac)
     * safari (Mac)
     * firefox (Mac)
   * 用chrome 檢查元素(Inspec Element) 裡面的 Device - 目前chrome裡面切換不同Device，狀況與實際手機板面(google nexus 5、iphone  5)實際呈現狀況蠻相符的，如沒有實機，可以用chrome來測。
     * iphone 4
     * iphone 5
     * nexus 4
     * nexus 5
     * ipad
   * 實機
     * iphone 5
     * google nexus 5
   

## 學到了什麼
   * 有關phone版頁面
   
      * 由於有phone上，是用手指點某個地方，手指占手機比例比較多(相較於滑鼠占電腦營幕)，因此如有需要點擊的地方，文字、間距、圖示最好加大(至少要是手指大小)，大到不會點到其它東西為止。
      * 不要讓版面看起來很滿，文字大小、圖片依phone版調過，pc版資訊也無需全部呈現。
      * 如果有使用到google map，滿版呈現就好，不然只呈現部分時，在上下滑手機時，很容易滑到地圖內部(Jawawa時用到遇到的困擾，後來覺得不好用，改成在另一頁滿版呈現)。
      * 在header部分，最好有可以回到首頁的連結，當user迷路時，可以點此連結回去。
      * 額外話：減少使用alert視窗(除非視窗占不到手機視窗一半)，如果一定要有的話，關閉按鈕做大一點;曾有遇到網站廣告alert出(幾乎滿版)，想點右上角關掉，因為按鈕不到手指大，常會點到廣告。
   

   * 有關sass、css學到的應用
   
## 實際畫面

* PC (991px以上)
   
  ![PC](https://github.com/happyGaia/RWD_Practice/raw/master/snapshot/rwd1.png)


* pad (991px以下)

  <img src="https://github.com/happyGaia/RWD_Practice/raw/master/snapshot/rwd2.png" width="500px" alt="pad: 991px以下" title="pad: 991px以下">


* phone-big (768px以下)
   
  <img src="https://github.com/happyGaia/RWD_Practice/raw/master/snapshot/rwd3.png" width="400px" alt="phone-big: 768px以下" title="phone-big: 768px以下">


* phone-small (400px以下)
   
  <img src="https://github.com/happyGaia/RWD_Practice/raw/master/snapshot/rwd4.png" width="300px" alt="phone-small: 400px以下" title="phone-small: 400px以下">
  <img src="https://github.com/happyGaia/RWD_Practice/raw/master/snapshot/rwd41.png" width="300px" alt="phone-small: 400px以下: 選單展開" title="phone-small: 400px以下: 選單展開">

## 參考連結

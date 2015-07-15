# RWD練習
   
## 使用技術
   RWD, sass, jquery

## 自適應範圍(參考檔案) 

  有關RWD設定請看all.sass。
   * phone-small: 400px以下 ( _phone_s_400.sass )
   * phone-big: 768px以下 ( _phone.sass )
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
      * 
   * 有關sass、css學到的應用
   
## 實際畫面

## 參考連結

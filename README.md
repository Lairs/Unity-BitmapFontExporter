# Unity-BitmapFontExporter
Fork from : home.gamer.com.tw/creationDetail.php?sn=2858718

原本UP主的檔案中，在Unity5.4的環境下無法執行，原因出在ScriptableWizard在存檔時的檔案類型可能修改了判定，導致無法存檔。

修改了檔案類型的判定後，又遇到Unity產生出的字型在顯示上產生錯位，事後發現是textureFile的寬高並非本來圖片大小，而是2次方的容器。

目前計算用的材質寬高需要手動設定，指定路徑時也有多餘的字符，介面有些瑕疵但是功能上是可運作的。

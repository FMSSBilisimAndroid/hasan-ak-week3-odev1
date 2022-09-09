## Önemli Not!!
Bu uygulamada onViewStateRestored ve onSaveInstanceState metotlarının **işleyişini anlamak için** edittextin `android:saveEnabled="false"`
özelliği **devre dışı bırakılmıştır.**

## GIF 1 

Bu gif'de  onViewStateRestored ve onSaveInstanceState metotları metotları **kullanılmadığındaki** durumu ele alınmıştır.
Burada görüleceği üzere **ekran yatay moda geçtiğinde edittext içindeki veri kaybolmakta ve textview içindeki sayıda 0 olmakta
ve yeniden dikey moda geçtiğinde ise yine veriler sıfırlanmakta.**

<img src ="https://github.com/FMSSBilisimAndroid/hasan-ak-week3-odev1/blob/master/Media_220909_231618.gif" width = 300 height = 500/>


## GIF 2

Bu gif'de  onViewStateRestored ve onSaveInstanceState metotları metotları **kullanıldığı** durumu ele alınmıştır.
Burada görüleceği üzere **ekran yatay moda geçtiğinde edittext içindeki veri kaybolmuyor ve textview içindeki sayıda değişmemekte
ve yeniden dikey moda geçtiğinde ise veriler kaybolmamaktadır.**

<img src ="https://github.com/FMSSBilisimAndroid/hasan-ak-week3-odev1/blob/master/Media_220910_014206.gif" width = 300 height = 500/>

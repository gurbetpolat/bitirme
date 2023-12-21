# bitirme


## V2-CIFAR

Bu calismada fashion mnist yerine daha karmasik goruntuler iceren cifar uzerinde
deneme yaptim. Sonuclar pek ic acici olmadigindan 3 kanalda boyle karmasik bir
veri setinde gan egitmek zor olacagindan bir sonraki calismam ve branchim
v3-cifar-gray 'de sadece siyah beyaz cifar dataseti ile calismaya geciyorum.

## V3-CIFAR    
Bu calismamda ise 10 label iceren CIFAR-10 datasetini gri skalaya (tek kanala)
cevirerek calistim. Sonuc olarak ise, renklerin kaybi ile objeleri ayir etmemizi
saglayacak bir cok ozelligin de kayboldugunu kesfettim. Bu hali ile cifar10
dataseti elimdeki donanim gucu ile saglikli sonuc alabilecegim bir dataset degil.

Sonuc olarak dataset arastirmasinda bulundum ve fer2013 yuz - duygu goruntulerinden
yararlanarak insan yuz goruntuleri olusturmak istedim.

## V4-FER2013
generator ve discriminatorun loss lari ayni anda dusmekte.
Bu durum anormal geldi. Ayrica egitim cok uzun
epochlar boyunca devam etse de kalitede bir duzelme gormemekteyim.
ayrica bir overfitting durumu soz konusu mu bilmiyorum.
bunlari inceleyip duzeltebilmek adina V5-FER2013 branchinde calismama
devam edecegim.
sonuc olarak tam da kabul edilebilir olmasa da insan yuzune cok benzer
goruntuler elde etmekteyim.

Son olarak yapmak istedigim sey, guzel bir sinir agi mimarisi olusturup,
guzel bir gurultu boyutu belirleyip, kendi gercek resmimden kendi 
gurultumu cikararak kendime gercek olmayan goruntuler olusturmak.
Tabii ki bunun yaninda fer2013 icin guzel bir GAN da olusturmus olacagim.

Okulumun bitirme dersi olan bu dersteki projemde guttugum temel amac,
beni ise biraz daha tecrube sahibi olarak basvurmami saglamasi.

## V5-FER2013
bu calismamda cikti olarak verimli sonuc alamadim ama egitimin iki 
model icinde tek asamada olmasini sagladim.
sonuclar 'v5_fer2013_OUTPUT' klasorunde bulunmaktadir
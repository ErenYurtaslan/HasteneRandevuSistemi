# Hastane Randevu Sistemi
Hastane Randevu Sistemi Web Programlama Projesi

Admin girişi, hasta girişi ve girişsiz olarak 3 parça olan sitemizde; sunucu tarafında doktorların branşları, isimleri, fotoğrafları, çalışma gün ve saatleri, ekleme-güncelleme-silme işlemleri(CRUD), tüm bu bilgilerin çekildiği SQLServer veri tabanı bulunmakla beraber, hem hastaların hem de adminin randevu kaydı oluşturabileceği ve bunların veri tabanında aynı tabloya kaydedileceği bir algoritma düzenlenmiştir.
Proje kodlarımızın, S.O.L.I.D. prensiplerine uygun olarak yazılmasına gayret edilmiştir.(esnek, clean code'a uygun, arabirimli, gereksiz koddan ve sınıftan kaçınma)
Login yapılmadığı takdirde sadece "Anasayfa" ve "Bize Ulaşın" butonları aktif olurken, hasta olarak login yapıldığında bu ikisine ek olarak "Doktorlar" butonu da gelmektedir. Bu 3. butonun içeriğinde hasta, doktorun kendisini ilgilendiren verilerini görmekle beraber sadece randevu alma işlemi yapabilmektedir.
Admin ise yukarıda belirtildiği gibi tüm verilere erişebilir ve değiştirebilir pozisyondadır.
Asp.Net Core 7.0 sürümüne uyumlu olarak yabancı dil dosyaları eklenmiş olup, hem Türkçe hem de İngilizce ayarı sağlanmıştır.
Ek olarak, veri tabanından gelen sabit değerlerin de İngilizce olabilmesi için veri tabanındaki tablolar güncellenmek suretiyle aynı isimlerin tablo sütunu olarak İngilizcesi eklenmiştir ve cshtml dosyalarında sorguya alınarak dil değişimlerinde o verilerin de değişmesi sağlanmıştır.

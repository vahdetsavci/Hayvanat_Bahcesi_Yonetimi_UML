# Hayvanat_Bahcesi_Yonetimi_UML
Bu proje **PatikaAcademy.dev** platformunun **Başlangıç Seviyesi .Net Core Patikası** eğitimi kapsamında **Ödev - Hayvanat Bahçesi Yönetimi** dersi için yapılmıştır. İçerisinde 1 README, 1 LICENSE ve 1 .png dosyası barındırır.

.png dosyası hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için kullanılan bir sistemin UML diyagramıdır. Bu diyagram da Polimorfizm modeli kullanılarak, aşağıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlanmıştır.

Hayvanlar:
* Atlar (atlar, zebralar, eşekler vb.),
* Kedigiller (kaplanlar, aslanlar vb.),
* Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
* Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
* tür adı, ağırlığı, yaşı vb.
* Sistem ayrıca her hayvan için belirli ilaçların dozajını ayarlayabilmeli => **calcDosage(): Double**
* Sistem Yem verme zamanlarını hesaplayabilmelidir => **calcFeedSchedule(): DateTime**

Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklıdır. Örneğin, atlar için yem verme algoritması farklı, kaplanlar için farklıdır.

## LICENSE
[MIT](LICENSE)

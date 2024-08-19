# 👋 Merhaba, ben @YusufEminoglu

## 📖 Proje Hakkında
Bu repository, Türkiye Mekansal Planlar Yapım Yönetmeliği (MPYY) tarafından belirlenen 1:1000 ölçekli Uygulama İmar Planı stil ve çizim standartlarına uygun olarak Quantum GIS (QGIS) platformu için bir veritabanı ve stil kitaplığı içerir. Bu kitaplık, Türkiye Planlama Okullarında eğitim Görmekte Olan Öğrenciler ve Resmi işlemlerde kullanılmamak üzere diğer ilgilelerin uyumlu ve standartize edilmiş çizimler yapabilmesi için gereken tüm araçları sağlar.

### 👀 İlgi Alanlarım
- Mekansal planlama ve şehir planlaması
- Uzaktan Algılama sistemleri
- GEE,  Qgis, ArcgisPro, Planetary Computer, Python
- Açık kaynak GIS teknolojileri
- Sürdürülebilir kentsel gelişim
- Kentsel İklim Dayanıklılığı
- 
### 🌱 Şu Anda Öğreniyorum
- NextGIS, LeafMap, PostgreSQL, R
- Veri görselleştirme ve otomasyon
- Python Plugin Oluşturma

### 💞️ İşbirliği Yapmak İstediğim Alanlar
- Açık kaynak GIS projeleri
- Mekansal veri analizi
- Eğitim ve bilgilendirme çalışmaları

### 📫 Bana Nasıl Ulaşabilirsiniz
- GitHub üzerinden [buraya tıklayarak](https://github.com/YusufEminoglu)
- E-posta yoluyla: [yusuf.emnglu@gmail.com](mailto:yusuf.emnglu@gmail.com), [geospacephilo@gmail.com](mailto:geospacephilo@gmail.com), veya [yusuf.eminoglu@deu.edu.tr](mailto:yusuf.eminoglu@deu.edu.tr)

<!---
Bu README.md dosyası @YusufEminoglu kullanıcısının GitHub profilinde öne çıkan bir dosyadır. Projeye dair değişiklikleri gözlemlemek için önizleme bağlantısına tıklayabilirsiniz.
--->

## 🗺️ Nasıl Kullanılır
Bu repository'deki veritabanını ve stil dosyalarını kullanmak için aşağıdaki adımları takip edin:
1. **Repository'i Klonlayın**: `git clone https://github.com/YusufEminoglu/1_1000_Uygulama_Imar_Plani_QGIS.git`
2. **QGIS'te Açın**: Browser Panelinde GeoPackage VT altında yeni bağlantı oluşturun ve indirdiğiniz dosyayı seçin ve yalnızca proje dosyasını QGIS'e yükleyin.
3. **Stilleri Uygulayın**: 1:1000 Ölçekli Uygulama İmar Planı Stilleri için .XML dosyasını Qgis stil panelinde import edin ve katmanlarınıza uygun stil dosyalarını yükleyin ve uygulayın. Alternatif olarak .SLD dosyaları nokta, çizgi ve alan katmanları için tek tek uygulanabilir.
4. **Stiller İçin Öneri**: Mevcut çizgi, alan ve nokta katmanlarına harici katmanlardaki nesneler (features) join veya copyPaste işlemi uygulanarak aktarılır. 'uipfonksiyon' isimli sütuna uygun bilgiler otomatik eşleştirilir ve katman sembolojilerinden categorized seçilerek sınıflandıktan sonra advance kısmından match to saved symbol tercihi uygulanır ve a-z tüm plan MPYY diline uygun haritalanır.
5. **ÖNEMLİ NOT**: geopackage veri tabanı dosyasını (.gpkg uzantılı dosya) ve içindeki Qgis proje dosyası (.qgs zuantılı dosya) hariç alan, çizgi, nokta ve tablo katmanlarını adlarını değiştirmeyin yerlerine başka katman eklemeyin. Aksi takdirde attribute form, attribute table, relation, relation reference ve stil dosyalarınız eşleşme sağlayamayacaktır.

## 📜 Lisans
Bu projede [MIT Lisansı](LICENSE) kullanılmıştır. Detaylar için lisans dosyasına bakınız.
 

# Northwind Mobil Uygulaması

Bu proje, Microsoft'un örnek Northwind veritabanını kullanarak React Native ve Tailwind CSS ile geliştirilmiş bir mobil uygulamadır. Uygulama, Northwind veritabanındaki verileri (örneğin, müşteriler, siparişler, ürünler) görüntülemek ve yönetmek için kullanıcı dostu bir arayüz sunar.

## Özellikler
- **Veri Görüntüleme**: Northwind veritabanındaki müşteriler, siparişler ve ürünler gibi verileri listeleme.
- **Responsive Tasarım**: Tailwind CSS ile mobil cihazlara uyumlu, modern ve estetik bir arayüz.
- **Performans**: React Native ile hızlı ve akıcı bir kullanıcı deneyimi.
- **Filtreleme ve Arama**: Veriler arasında kolayca arama yapma ve filtreleme imkanı (isteğe bağlı, uygulamanıza göre eklenebilir).
- **Çevrimdışı Destek**: Veritabanı verilerinin yerel olarak önbelleğe alınması (isteğe bağlı, uygulamanıza göre eklenebilir).

## Kullanılan Teknolojiler
- **React Native**: Mobil uygulama geliştirme için platformlar arası çerçeve.
- **Tailwind CSS**: Hızlı ve özelleştirilebilir stil oluşturma için CSS framework'ü.
- **Northwind Veritabanı**: Örnek veri kaynağı olarak Microsoft'un sağladığı Northwind veritabanı.
- **(Opsiyonel)**: Veritabanı bağlantısı için kullanılan API veya yerel SQLite (projenize göre belirtin).

## Kurulum

1. **Repoyu Klonlayın**:
   ```bash
   git clone https://github.com/kullanici-adiniz/northwind-mobile-app.git
   cd northwind-mobile-app
   ```

2. **Bağımlılıkları Yükleyin**:
   ```bash
   npm install
   ```

3. **Tailwind CSS Kurulumu**:
   - Tailwind CSS, React Native ile kullanılmak üzere `react-native-tailwindcss` veya benzeri bir kütüphane ile entegre edilmiştir. Tailwind yapılandırmasını `tailwind.config.js` dosyasından kontrol edin.

4. **Veritabanı Bağlantısı**:
   - Northwind veritabanına erişim için bir API kullanıyorsanız, `.env` dosyasına gerekli API anahtarlarını veya bağlantı bilgilerini ekleyin.
   - Yerel bir SQLite veritabanı kullanıyorsanız, veritabanı dosyasını proje dizinine ekleyin.

5. **Uygulamayı Çalıştırın**:
   - iOS:
     ```bash
     npx react-native run-ios
     ```
   - Android:
     ```bash
     npx react-native run-android
     ```

## Kullanım
- Uygulama başlatıldığında, ana ekranda Northwind veritabanındaki temel veriler (örneğin, müşteriler veya ürünler) listelenir.
- Üst menüden farklı kategorilere geçiş yapabilir veya arama çubuğunu kullanarak verileri filtreleyebilirsiniz.
- Her bir veri öğesi, detaylı bilgilere erişmek için tıklanabilir.

## Katkıda Bulunma
Katkıda bulunmak isterseniz, lütfen aşağıdaki adımları izleyin:
1. Repoyu fork edin.
2. Yeni bir özellik dalı oluşturun (`git checkout -b feature/yeni-ozellik`).
3. Değişikliklerinizi yapın ve commit edin (`git commit -m 'Yeni özellik eklendi'`).
4. Dalınızı push edin (`git push origin feature/yeni-ozellik`).
5. Bir Pull Request oluşturun.

## Lisans
Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.

## İletişim
Sorularınız veya önerileriniz için alpsarikisla@hotmail.com adresinden bana ulaşabilirsiniz veya GitHub üzerinden bir issue açabilirsiniz.

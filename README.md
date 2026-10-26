# 📚 YÖK Atlas Veri Tabanı (2024)

Bu depo, 2024 yılına kadar olan güncel YÖK Atlas üniversite ve bölüm verilerini içermektedir. Veriler veri analizi yapılabilmesi için hem **CSV** hem de **SQLite** veritabanı formatında sunulmuştur.

## 📂 Dosya İçeriği

- `universiteler.csv`: Üniversitelere ait genel bilgilerin bulunduğu veri seti.
- `tum_bolumler.csv`: Tüm üniversitelerdeki bölümlerin (kontenjan, puan vb.) detaylı veri seti.
- `yokatlas.db`: Tüm bu verilerin kullanıma hazır, birleştirilmiş SQLite veritabanı hali.

## ⚙️ Nasıl Kullanılır?

- **CSV dosyalarını:** Excel, Google Sheets ile açabilir veya Python (Pandas kütüphanesi) ile veri analizinde kullanabilirsiniz.
- **SQLite veritabanını (.db):** DB Browser for SQLite veya DBeaver gibi bir programla açarak doğrudan SQL sorguları çalıştırabilirsiniz.

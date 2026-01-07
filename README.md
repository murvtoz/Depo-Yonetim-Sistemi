
📦 **Depo Yönetim Sistemi (Warehouse Management System)**         
Bu proje, modern depo yönetim ihtiyaçlarını karşılamak üzere tasarlanmış, Java programlama dili ile geliştirilmiş bir envanter ve raf yönetim simülasyonudur. Proje, Nesne Yönelimli Programlama (OOP) prensiplerini gerçek dünya senaryolarına uygulamak amacıyla hazırlanmıştır.

📖 **Proje Hakkında**         
Depo Yönetim Sistemi, bir deponun dijital ikizini oluşturarak; ürünlerin raflara yerleştirilmesi, stok takibi, kapasite yönetimi ve verilerin kalıcı olarak saklanması süreçlerini optimize eder. Proje kapsamında verimlilik, veri bütünlüğü ve kullanıcı dostu bir yönetim arayüzü hedeflenmiştir.

🛠️ **Temel Özellikler**         
Raf ve Envanter Modeli: Her bir rafın kapasite, kategori ve doluluk oranı gibi özelliklerini Nesne Yönelimli mimariyle yönetir (Raf.java).

Dinamik Yönetim: Rafların eklenmesi, güncellenmesi ve stok durumunun anlık takibi için merkezi bir yönetim motoru sunar (RafManager.java).

Veri Kalıcılığı (Persistence): Sistemdeki tüm hareketler ve mevcut stok durumu, program kapatılsa dahi kaybolmaması için dosya sistemine kaydedilir (DosyaIslemleri.java).

Raporlama Sistemi: Depo doluluk oranlarını ve kritik stok seviyelerini içeren detaylı raporlar üretir.

📂 **Proje Yapısı ve Mimari**         
Projenin dosya düzeni, temiz kod (clean code) prensiplerine uygun olarak src klasörü altında yapılandırılmıştır:

Depo-Yonetim-Sistemi/           
 ├── src/   
 │   ├── Raf.java                  # Raf nesnesinin blueprint'i (özellikler ve kapsülleme)   
 │   ├── RafManager.java           # İş mantığı ve operasyonel yönetim sınıfı   
 │   ├── DosyaIslemleri.java       # Veri okuma/yazma ve I/O işlemleri   
 │   └── Main.java                 # Uygulamanın giriş noktası    
 ├── Raporlar/                     # Proje analiz ve sonuç dökümanları    
 └── README.md                     # Proje tanıtım belgesi    

🚀 **Teknolojik Stack**         
Dil: Java (JDK 8+ veya 11+)         

Paradigma: Nesne Yönelimli Programlama (OOP - Encapsulation, Abstraction)   

Versiyon Kontrol: Git & GitHub      

👥 **Proje Ekibi**         
Bu proje, üniversite bünyesinde yürütülen bir geliştirme çalışması olup aşağıdaki ekip üyeleri tarafından tasarlanmıştır:

Geliştiriciler,    
Murat Efe Özoğul    
Berat Güngör      
Ömer Çelik      

📝 **Kurulum ve Çalıştırma**         
Depoyu bilgisayarınıza klonlayın: git clone https://github.com/murvtoz/Depo-Yonetim-Sistemi.git

Proje ana dizinine gidin: cd Depo-Yonetim-Sistemi

src klasöründeki dosyaları derleyin ve Main.java üzerinden çalıştırın.

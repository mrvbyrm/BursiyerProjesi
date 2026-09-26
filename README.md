# BursiyerProjesi

[![C#](https://img.shields.io/badge/C%23-ASP.NET%20MVC-512BD4?style=flat-square&logo=csharp&logoColor=white)]()

Bursiyer (burs alan öğrenci/üretici) takibi için geliştirilmiş bir ASP.NET MVC web uygulaması.

## Proje Hakkında

Uygulama; giriş yapan kullanıcıların (admin/üretici) bursiyer kayıtlarını yönetebildiği bir web arayüzü sunar. `Controllers/` altında `LoginController`, `HomeController` ve `ProducerController` bulunur; `Models/` katmanı veri modellerini, `Views` (Content/Scripts ile birlikte) ise arayüz tarafını oluşturur.

## Kullanılan Teknolojiler

- C# / ASP.NET MVC (.NET Framework)
- JavaScript, CSS
- IIS Express / Visual Studio

## Kurulum ve Çalıştırma

1. `BursiyerProjesi/burs-main/MyAdmin.sln` dosyasını Visual Studio ile açın.
2. NuGet paketlerini geri yükleyin (`packages.config`).
3. `Web.config` içindeki bağlantı ayarlarını kendi ortamınıza göre düzenleyin.
4. Projeyi derleyip (F5) çalıştırın.

## Proje Yapısı

```
burs-main/
├── Controllers/    # Login, Home, Producer, Base controller'lar
├── Models/         # Veri modelleri
├── Scripts/        # İstemci tarafı script'ler
├── Content/        # CSS ve statik içerik
└── Web.config      # Uygulama yapılandırması
```

## İletişim

Merve — [GitHub](https://github.com/mrvbyrm)

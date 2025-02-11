# 🎯 .NET Web API Rezervasyon Uygulaması
 
<div align="center">
 
![.NET](https://img.shields.io/badge/.NET%208.0-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=for-the-badge&logo=.net&logoColor=white)
 
</div>
 
## 📋 Proje Hakkında
 
Bu proje, modern teknolojiler kullanılarak geliştirilmiş kapsamlı bir rezervasyon sistemidir. Güvenlik ve performans odaklı tasarlanmış API endpoints'leri sunar.
 
### 🚀 Özellikler
 
* 🔐 JWT tabanlı kimlik doğrulama ve yetkilendirme
* 📦 PostgreSQL veritabanı 
* 🛠 Entity Framework Core ORM
* ⚡ Yüksek performanslı API endpoints
 
## 🔧 Gereksinimler
 
* **.NET 8.0** veya daha yeni bir sürüm
* **PostgreSQL** veritabanı
 
## 🛠️ Kurulum
 
### 1️⃣ Repo'yu Klonlayın
 
```bash
git clone https://github.com/safatosun/Reservation-App.git
cd proje-klasoru
```
 
### 2️⃣ Yapılandırma
 
`appsettings.json` dosyasındaki veritabanı connection string verisini doğru bilgilerle aşağıdaki gibi düzenleyin:
 
```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Host=localhost;Database=veritabani_adi;Username=postgres;Password=sifre"
  }
}
```
 
### 3️⃣ Veritabanı Migration
 
```bash
dotnet ef database update
```
 
### 4️⃣ Uygulamayı Çalıştırın
 
```bash
dotnet run
```
 
## 📚 API Dokümantasyonu
 
Swagger UI üzerinden API dokümantasyonuna erişebilirsiniz:

## 📝 Lisans
 
Bu proje [MIT](LICENSE) lisansı altında lisanslanmıştır.
 
---
<div align="center">
⭐️ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!
</div>

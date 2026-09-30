# 🎵 Müzik Kulağı

Blazor WebAssembly tabanlı modern bir **müzik kulağı eğitim uygulaması**. Kullanıcılar ritim kalıplarını dinleyip doğru dizilimi tahmin ederek müzikal işitme ve ayırt etme becerilerini geliştirebilir.

---

##  Özellikler

- Ritim kalıplarını tanıma soruları (Dörtlük, Sekizlik, Onaltılık vb.)
- Seviyeye dayalı ilerleme sistemi (Kolay → Orta → Zor)
- Seviye kilit/açma mekanizması
- Kullanıcı yüksek skor takibi
- Çoklu enstrüman desteği

---

## Teknolojiler

| Teknoloji | Versiyon |
|-----------|----------|
| .NET | 8.0 |
| Blazor Server | - |
| Bootstrap | 5.x |
| C# | 12 |

---

## 📁 Proje Yapısı
 
```
MuzikKulagiTesti/
├── wwwroot/
│   ├── css/
│   │   └── app.css
│   ├── lib/
│   │   └── bootstrap/          # Bootstrap kütüphanesi
│   ├── sample-data/
│   │   └── weather.json
│   ├── Sesler/                 # Ritim ses dosyaları
│   │   ├── ankara.mp3
│   │   ├── bursa.mp3
│   │   ├── gelibolu.mp3
│   │   ├── izmir.mp3
│   │   ├── karaman.mp3
│   │   ├── terazi.mp3
│   │   └── van.mp3
│   ├── favicon.png
│   ├── icon-192.png
│   └── index.html
├── Layout/
│   ├── MainLayout.razor        # Ana sayfa düzeni
│   └── NavMenu.razor           # Navigasyon menüsü
├── Pages/
│   ├── Counter.razor
│   ├── Home.razor              # Ana sayfa
│   └── Weather.razor
├── _Imports.razor
├── App.razor
└── Program.cs
```
 
---

## Ritim Kalıpları

Uygulama aşağıdaki ritim kalıplarını içerir:

| İsim | Ritim Kalıbı |
|------|-------------|
| Van | Dörtlük |
| İzmir | 2 Sekizlik |
| Ankara | Sekizlik + 2 Onaltılık |
| Karaman | 2 Onaltılık + Sekizlik |
| Gelibolu | 4 Onaltılık |
| Terazi | 3 Sekizlik |
| Bursa | Bursa Kalıbı |

---


## 📄 Lisans

Bu proje MIT lisansı ile lisanslanmıştır.

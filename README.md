# 🌍 EkoAl — Kentsel Isı Adası ve Atık Yönetimi Uygulaması

## Neden EkoAl?

Geçen yıl bir araştırma yaparken 2022 yazında Avrupa'da 
61.000'den fazla insanın sıcak hava dalgası yüzünden 
hayatını kaybettiğini öğrendim. İlk okuduğumda yanlış 
anladım sandım ama gerçekti. Üstelik 2003'te de 70.000 
kişi aynı şekilde ölmüştü. Yani bu tek seferlik değil, 
her yaz tekrarlanan ve büyüyen bir kriz.

Daha da çarpıcı olan şu: aynı şehirde bile mahalleler 
arasında 8-10 dereceye varan sıcaklık farkı var. Parkı 
olmayan, ağacı olmayan, betonla kaplı mahalleler çok daha 
fazla ısınıyor. Buna kentsel ısı adası deniyor. Ve kimse 
kendi mahallesinin ne kadar riskli olduğunu somut olarak 
görebileceği bir araca sahip değil.

EkoAl'ı tam bu boşluğu doldurmak için geliştiriyorum.

---

## Ne Yapıyor?

###  Isı Riski Haritası
Mapbox altyapısıyla çalışan interaktif harita. 
Bulunduğun bölgenin ısı riski skorunu renk skalasıyla 
gösteriyor kırmızı yüksek risk, yeşil düşük risk.

###  Isı Hafızası
Benim en çok önem verdiğim özellik. 2010'dan bugüne 
o bölgedeki sıcaklık değişimini çizgi grafiğiyle 
gösteriyor. Ve 2035 tahmini var kullanıcı günlük 
görevleri tamamladıkça bu tahmin iyileşiyor. Yani 
kendi etkini somut olarak görüyorsun.

###  Günlük Görevler
Her gün küçük çevre görevleri: bisiklet kullan, 
balkonuna bitki dik, bir komşunu bilgilendir. 
Tamamladıkça puan kazanıyorsun, mahalle 
sıralamasında yükseliyorsun.

### Atık Haritası
Sokakta gördüğün bir atığı fotoğraflayıp haritaya 
ekleyebiliyorsun. Başka biri gidip temizliyor, 
ikisi de puan kazanıyor.

---

## Teknik Altyapı

| Teknoloji | Kullanım Amacı |
|---|---|
| Kotlin | Ana geliştirme dili |
| Mapbox SDK | Harita altyapısı |
| Room Database | Yerel veri depolama |
| MVVM | Uygulama mimarisi |
| Material Design 3 | Arayüz tasarımı |
| Jetpack Navigation | Ekranlar arası geçiş |

---

## Ekranlar

- **Ana Harita Ekranı** — Isı riski skorları ve atık noktaları
- **Isı Hafızası** — 2010-2024 sıcaklık grafiği + 2035 tahmini
- **Görev Ekranı** — Günlük çevre görevleri ve puan sistemi
- **Atık Haritası** — Bildir ve temizle döngüsü
- **Profil** — Kullanıcı puanı ve mahalle sıralaması

---

## Geliştirme Süreci

Bu proje hâlâ aktif geliştirme aşamasında. 
Sabancı Üniversitesi Liseliler Arası Duyarlıyım 
Ödül Programı kapsamında geliştiriyorum.

Sürecimi Instagram'dan takip edebilirsiniz:
[@ekoal.app](https://instagram.com/ekoal.app)

---

## Bilimsel Kaynak

> Ballester, J. et al. (2023). Heat-related mortality 
> in Europe during the summer of 2022. 
> *Nature Medicine*, 29, 1857–1866.
> https://www.nature.com/articles/s41591-023-02419-z

---

## İletişim

Proje hakkında görüş ve önerileriniz için 
Instagram üzerinden ulaşabilirsiniz.

 *Küçük adımlar büyük fark yaratır.*

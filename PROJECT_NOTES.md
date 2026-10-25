# PROJE NOTLARI — Hayatta Kalma Oyunu (POV)

> Bu dosya, yeni bir sohbette projeye devam edebilmek için yazıldı.
> **Yeni sohbete başlarken:** GitHub'dan projenin zip'ini indir, sohbete at ve şunu yaz:
> "Bu projeye devam ediyoruz. PROJECT_NOTES.md dosyasını oku, kaldığımız yerden devam edelim."
> Claude'un yapması gerekenler: önce bu dosyayı oku, sonra "Mevcut Durum" ve "Sıradaki Adım" bölümlerine göre ilerle.
> **Her adım bittiğinde bu dosya güncellenir.**

## 1. Proje Özeti
- **Tür:** Hayatta kalma (survival), birinci şahıs (POV) 3B oyun
- **Platform:** Web tarayıcı (bilgisayar), link ile oynanır
- **Hedef:** Üst düzey görsel kalite (gerçekçi ışık, gölge, sis, doku), akıcı performans
- **Dil:** Kullanıcı Türkçe konuşuyor; anlatımlar Türkçe, adım adım ve "neyi nereye yükleyeceğim" detayıyla

## 2. Teknoloji Kararları
| Konu | Seçim | Neden |
|---|---|---|
| 3B motor | Three.js | Tarayıcıda çalışır, kurulum gerektirmez, GitHub/Firebase ile uyumlu |
| Derleme aracı | Vite | Hızlı, basit |
| Kod yeri | GitHub (repo) | Sürüm geçmişi + yedek + zip ile taşınabilirlik |
| Yayın (hosting) | Firebase Hosting | Ücretsiz plan yeterli, hızlı, otomatik HTTPS |
| Giriş | Firebase Authentication | Oyuncu hesabı |
| Kayıt/veri | Firestore | Oyuncu ilerlemesi, envanter, kayıt |
| Çok oyunculu (ileride) | Firestore veya Realtime Database | İhtiyaç olursa |

## 3. Hesaplar ve Hizmetler (durum)
- [ ] GitHub hesabı
- [ ] GitHub repo oluşturuldu (isim: ______)
- [ ] Google hesabı (Firebase için)
- [ ] Firebase projesi oluşturuldu (proje adı: ______)
- [ ] Firebase Hosting etkin
- [ ] Firebase Authentication etkin
- [ ] Firestore etkin

> Not: Gizli anahtarlar (API key, şifre) bu dosyaya YAZILMAZ.

## 4. Klasör Yapısı (planlanan)
```
/
├─ PROJECT_NOTES.md      ← bu dosya
├─ index.html
├─ package.json
├─ src/
│  ├─ main.js            ← oyun girişi
│  ├─ player/            ← POV kamera, hareket
│  ├─ world/             ← arazi, ağaçlar, gökyüzü, ışık
│  ├─ survival/          ← açlık, susuzluk, sağlık, envanter
│  └─ firebase/          ← giriş ve kayıt kodu
└─ public/               ← doku, model, ses dosyaları
```

## 5. Mevcut Durum
- Aşama: **0 — Başlangıç.** Henüz kod yok, hesaplar açılacak.

## 6. Sıradaki Adım
- Adım 1: GitHub hesabı + repo, Firebase hesabı + proje açmak.

## 7. Yol Haritası
1. Hesaplar ve repo (GitHub + Firebase)
2. Proje iskeleti (Vite + Three.js), ilk ekran
3. POV kamera + yürüme/koşma/zıplama
4. Arazi, gökyüzü, güneş, gölge, sis (grafik temeli)
5. Ağaç, kaya, çimen, su (çevre)
6. Hayatta kalma sistemi: açlık, susuzluk, sağlık, enerji
7. Envanter, eşya toplama, craft
8. Gece/gündüz, hava durumu
9. Düşman/hayvan yapay zekası
10. Firebase giriş + kayıt/yükleme
11. Firebase Hosting ile yayınlama
12. Cila: ses, efektler, performans

## 8. Yapılan İşler (günlük)
- 2026-10-25: Proje başlatıldı, notlar dosyası oluşturuldu.

## 9. Bilinen Sorunlar / Yapılacaklar
- (henüz yok)

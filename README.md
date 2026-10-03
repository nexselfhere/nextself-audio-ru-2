# nextself-audio-ru-2

NextSelf uygulamasının Rusça indirilen ses paketi: B1+ ders sesleri, sözlük kelimeleri ve örnek cümleleri, okuma metinleri ve oyun sesleri
(A1–A2 ders sesleri uygulamanın içine gömülüdür) — anahtarı 8…f ile başlayan kayıtlar (dilin sesleri nextself-audio-ru · nextself-audio-ru-2 depolarına bölünmüştür). Uygulama bu dosyaları tek tek indirir
(`ru/<ilk iki hex>/<anahtar>.mp3`, mono mp3); anahtar, seslendirilen metnin
sha1 özetinin ilk 16 hanesidir.

Yayın adresi: https://nextselfhere.github.io/nextself-audio-ru-2

## Ses modeli ve lisans

- **Silero TTS** (v5_cis_base, ru_oksana) — MIT — https://github.com/snakers4/silero-models

Kayıtlar bu ses modeliyle üretilmiştir; metinler NextSelf müfredatına aittir.

## Doğrulama

`SHA256SUMS.txt` tüm dosyaların özetini taşır: `shasum -c SHA256SUMS.txt`

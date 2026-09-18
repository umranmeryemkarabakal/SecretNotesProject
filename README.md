# SecretNotesProject

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Tkinter-1F2A44?style=for-the-badge" alt="Tkinter" />
</p>

## Overview

A Tkinter app for keeping secret notes: the note is encrypted with a master key (character shift + Base64) and saved to a file, and can be decrypted back with the same key.

**Quick start:** `python main.py`

## Proje hakkında

Gizli not tutmak için Tkinter arayüzlü bir uygulama. Not, ana anahtarla (karakter kaydırma + Base64) şifrelenip `my_secret` dosyasına kaydedilir; aynı anahtarla çözülür.

## Özellikler

- Başlık, ana anahtar ve not metni girişi
- Şifreleyip dosyaya kaydetme
- Anahtarla şifre çözme
- Eksik bilgi ve dosya hatalarında uyarı penceresi

## Kurulum ve çalıştırma

Yalnızca standart kütüphane kullanılır.

```bash
python main.py
```

## Dosya yapısı

```text
SecretNotesProject/
├── img.png
└── main.py
```

## Notlar

- Şifreleme yöntemi eğitim amaçlıdır, gerçek gizli veriler için uygun değildir.

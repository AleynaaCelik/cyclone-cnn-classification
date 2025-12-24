# 🌀 Akdeniz Siklonları CNN Sınıflandırması

Akdeniz bölgesindeki yarı-durağan siklonların durağanlık seviyelerini CNN ile sınıflandırma projesi.

## 📊 Proje Özeti

- **Amaç:** Siklon trajectory verilerini görsel formata dönüştürerek CNN ile sınıflandırma
- **Veri Seti:** 2,377 siklon kaydı → 956 dengeli görsel
- **Model:** Custom CNN (3 Conv Blocks, ~1.2M parametre)
- **Sonuç:** Binary sınıflandırma %65.10 accuracy

## 🎯 Sonuçlar

| Yaklaşım | Accuracy | Durum |
|----------|----------|-------|
| 4 Sınıflı Model | %34.38 | ❌ Başarısız |
| Binary Model | %65.10 | ✅ Başarılı |
| İyileşme | +%30.72 | ⬆️ |

## 📂 Dosyalar

- `Derin_Ogrenme_Final.ipynb` - Ana kod (Jupyter Notebook)
- `requirements.txt` - Gerekli kütüphaneler
- `Cyclone_Project_Report_WITH_IMAGES.docx` - Detaylı rapor

## 🚀 Kurulum
```bash
# Kütüphaneleri yükle
pip install -r requirements.txt

# Jupyter Notebook başlat
jupyter notebook Derin_Ogrenme_Final.ipynb
```

## 📦 Gereksinimler

- Python 3.8+
- TensorFlow 2.15.0
- Pandas, NumPy, Matplotlib, Seaborn
- Pillow, scikit-learn

## 👤 Yazar

**Aleyna Çelik**
- Kırıkkale Üniversitesi - Bilgisayar Mühendisliği
- celikaleyna71@gmail.com

## 📚 Veri Seti

[Quasi-Stationary Mediterranean Cyclones Dataset](https://github.com/SofiaBGH/Quasi-Stationary-MedCyclones)

## 📄 Lisans

Bu proje Kırıkkale Üniversitesi Derin Öğrenme dersi için hazırlanmıştır.
```

---


*.pyc
.DS_Store

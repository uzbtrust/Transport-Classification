# Transport Classification

Transport turlarini (Samalyot, Kema, Avtomobil) klassifikatsiya qiluvchi AI aplikatsiya.

## Loyiha haqida

Bu loyiha deep learning yordamida transportni klassifikatsiya qiladi. Foydalanuvchi rasm yuklashi mumkin va AI qaysi turdagi transport ekani aniqlashadi.

**Klassifikatsiya turlari:**
- 🛩️ Samalyot (Airplane)
- 🚤 Qayiq (Boat)
- 🚗 Avtomobil (Car)

## Texnologiyalar

- **FastAI** - Deep learning model
- **Streamlit** - Web interfeysi
- **PyTorch** - Neural network framework
- **Plotly** - Ma'lumotlarni visualizatsiya qilish

## O'rnatish

1. Repozitoriyani klonlang:
```bash
git clone https://github.com/uzbtrust/Transport-Classification.git
cd Transport-Classification
```

2. Virtual environment yarating:
```bash
python -m venv venv
source venv/bin/activate  # Mac/Linux uchun
# yoki
venv\Scripts\activate  # Windows uchun
```

3. Kerakli paketlarni o'rnatng:
```bash
pip install -r requirements.txt
```

## Foydalanish

Streamlit ilova orqali dasturni ishga tushiring:
```bash
streamlit run app.py
```

Keyin:
1. Brauzeringiz avtomatik ochiladi
2. Rasm yuklang (PNG, JPG, JPEG formatida)
3. AI klassifikatsiya natijasini ko'ring

## Fayl tuzilishi

```
Transport-Classification/
├── app.py                 # Streamlit aplikatsiya
├── model.ipynb           # Model o'rganiŝ notebook
├── transport_model.pkl   # O'rgatilgan model
└── requirements.txt      # Bog'liq paketlar
```

## Xususiyatlar

- 🎯 Real-time klassifikatsiya
- 📊 Ehtimollik bar-chartasi
- 🖼️ Rasm preview
- 🎨 Uzbek til interfeysi

## Requirements

Python 3.8+

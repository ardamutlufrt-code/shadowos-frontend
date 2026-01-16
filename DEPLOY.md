# Deploy / Çalıştırma (En Profesyonel Ücretsiz Akış)

## 1) Frontend (Netlify)
- Bu ZIP'in kökündeki dosyaları Netlify'ye sürükle-bırak
- Site canlı olur (index.html)

## 2) AI Backend (Render / Railway / VPS)
Backend klasörü: /backend

### Lokal test
```bash
cd backend
npm install
export OPENAI_API_KEY="YOUR_KEY"
npm start
# http://localhost:8787
```

### Üretim
- Render.com (Free) veya Railway.app
- Environment variables:
  - OPENAI_API_KEY
  - (ops) OPENAI_MODEL=gpt-4.1-mini
- Start command: `npm start`

Sonra sitede Analyzer sayfasındaki “AI Sunucu Adresi” alanına backend URL'sini yaz.

> Not: Instagram, sunucu isteklerini bazen kısıtlayabilir. Bu durumda meta veri az gelir ve analiz "tahmini" olur.

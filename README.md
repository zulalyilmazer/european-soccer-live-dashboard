# ⚽ European Football Live Score & Smart Upset Analytics

Bu proje, canlı futbol verilerini API üzerinden anlık olarak çekip, Google BigQuery üzerinde modellenmiş tarihsel veri setiyle harmanlayan ve akıllı sürpriz (upset) tespiti yapan bir veri bilimi web uygulamasıdır.

## 🚀 Teknolojik Mimari
* **Veri Kaynağı:** API-Sports (Live Fixtures API)
* **Veri Ambarı & Modelleme:** Google BigQuery (Historical Soccer Dataset )
* **Arayüz Tasarımı:** Gradio UI & Streamlit (HTML/CSS Enriched)
* **Geliştirme Ortamı:** Google Colab

## 📊 Proje Görselleri
> **Not:** Canlı tünel bağlantısı (`.gradio.live` veya `localtunnel`) kesildiğinde arayüz tasarımının ve veri akışının doğrulanabilmesi için çalışma anından alınan ekran görüntüleri aşağıdadır:

### 1. Gradio Canlı Akıllı Dashboard Paneli
<img width="1470" height="743" alt="Ekran Resmi 2026-06-30 15 24 04" src="https://github.com/user-attachments/assets/02169eca-0ac4-41d2-be20-4a9ac24bd46a" />


### 2. Streamlit Alternatif Tasarım (HTML/CSS Destekli)
<img width="1379" height="304" alt="Ekran Resmi 2026-06-30 15 25 33" src="https://github.com/user-attachments/assets/218af22a-89cf-4bd8-9dc5-fd04ca0dab83" />


## 🛠️ Kurulum ve Çalıştırma
Projenin çalışabilmesi için Google Colab ortamında aşağıdaki kütüphanelerin kurulması ve BigQuery kimlik doğrulamasının yapılması gerekmektedir:

Kodun içerisindeki API_KEY alanına kendi API-Sports anahtarınızı tanımlayın.

bigquery.Client(project="...") alanına kendi Google Cloud proje ID'nizi girin.

Hücreleri sırasıyla çalıştırıp üretilen canlı link üzerinden paneli test edebilirsiniz.

```bash
pip install gradio requests pandas google-cloud-bigquery

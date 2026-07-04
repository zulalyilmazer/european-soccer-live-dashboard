## 📊 Rapor ve Web Uygulaması Görselleri

### 📱 Canlı Skor Paneli & Akıllı Sürpriz (Upset) Algoritması Arayüzü
API-Sports üzerinden çekilen canlı maç skorları ile BigQuery veri ambarından (BQ Geçmiş Gol) beslenen tarihsel verilerin harmanlandığı, Streamlit/Gradio tabanlı web uygulaması arayüzü.
<img src="live_score_panel.jpg" width="900">

### 1. Avrupa Futbol Analitiği (Ana Sayfa)
Avrupa liglerindeki genel durum, toplam maç/gol sayıları ve liglere göre sürpriz maç analizlerinin yer aldığı ana panel.
<img src="ana_sayfa.jpg" width="900">
# ⚽ European Football Live Score & Smart Upset Analytics

Bu proje, canlı futbol verilerini API üzerinden anlık olarak çekip, Google BigQuery üzerinde modellenmiş tarihsel veri setiyle harmanlayan ve akıllı sürpriz (upset) tespiti yapan bir veri bilimi web uygulamasıdır. Proje kapsamında ayrıca geniş ölçekli bir iş zekası (BI) ve scouting raporlama arayüzü geliştirilmiştir.

## 🛠️ Teknolojik Mimari

* **Veri Kaynağı:** API-Sports (Live Fixtures API)
* **Veri Ambarı & Modelleme:** Google BigQuery (Historical Soccer Dataset)
* **Arayüz Tasarımı:** Gradio UI & Streamlit (HTML/CSS Enriched)
* **Geliştirme Ortamı:** Google Colab
* **İş Zekası (BI) & Analiz:** Power BI Desktop

---

## 📊 Rapor ve Dashboard Görselleri

### 1. Avrupa Futbol Analitiği (Ana Sayfa)
Avrupa liglerindeki genel durum, toplam maç/gol sayıları ve liglere göre sürpriz maç analizlerinin yer aldığı ana panel.
<img src="ana_sayfa.jpg" width="900">

### 2. Mevki Analizi & Gelişmiş AI Etkileyiciler (Defans)
Power BI AI "Key Influencers" görseli kullanılarak oyuncuların genel reytinglerini en çok etkileyen defansif metriklerin analizi.
<img src="oyuncu_mevki_analizi_D.jpg" width="900">

### 3. Oyuncu Profili ve Yetenek Analizi
Oyuncuların şut, teknik, hız ve savunma indekslerinin karşılaştırmalı analizi, yaşa göre performans trendleri ve yatırım verimliliği.
<img src="oyuncu_analizi.jpg" width="900">

### 4. Gol Anatomisi ve Duran Top Analizi
Lig bazında gollerin nasıl atıldığı (şut, kafa, penaltı vb.), oyun kurma hızı ve pas mesafelerinin yıllara göre değişimi.
<img src="gol_analizi.jpg" width="900">

### 5. Yaş Eğrisi & Kadro Planlaması
Oyuncu sayısının ve ortalama performansın yaş gruplarına göre dağılımı ile hücuma kalkış hızına göre kadro yaş analizi.
<img src="yaş_eğrisi.jpg" width="900">

### 6. Liglere Göre Bahis ve Sürpriz Analizi
Liglerin sürpriz skor üretme eğilimleri ve kazanç/kayıp marjlarının analitik dağılımı.
<img src="bahis_analizi.jpg" width="900">

---

## 📂 Proje Yapısı
* `european_soccer_live_matches.ipynb`: Canlı veri çekme, BigQuery entegrasyonu ve modelleme süreçlerini içeren Jupyter Notebook.
* `European Soccer Analysis_02.07.2026.pbix`: Gelişmiş analitik modelleri ve yukarıdaki tüm görselleri barındıran orijinal Power BI rapor dosyası.

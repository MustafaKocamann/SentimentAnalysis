# 🛒 Amazon Yorum Verisi Üzerinden Sentiment Analizi ve Yorum Davranışları

## 📌 Proje Hakkında

Bu proje, Amazon ürün yorumları üzerinden sentiment analizi yapmayı ve müşteri davranışlarını incelemeyi amaçlamaktadır.
Başlangıçta yalnızca pozitif/negatif duygu sınıflandırması hedeflenmiş, ancak proje genişletilerek ürün, kullanıcı ve yorum özellikleri üzerine kapsamlı analizler yapılmıştır.

## 🎯 Amaçlar
* Yorumların pozitif, negatif, nötr olarak sınıflandırılması
* Ürün bazında müşteri memnuniyetinin analizi
* Kullanıcı davranışlarının incelenmesi (sadakat, tutarlılık vb.)
* Negatif yorumlarda öne çıkan sorunların tespiti
* Yorum özellikleri (uzunluk, helpfulness, keyword, topic modeling) üzerinden çıkarımlar


## 🛠 Kullanılan Kütüphaneler
* numpy,
* pandas,
* matplotlib,
* seaborn
* nltk
* WordNetLemmatizer
*  stopwords
*  wordcloud
*  scikit-learn (CountVectorizer, LDA)
*  scipy (tt-test)

## 🔍 Analiz Adımları
### 1. Sentiment Analizi
* VADER ve RoBERTa ile duygu analizi
* Summary vs Text tutarlılığı

### 2. Ürün Analizi
* En çok yorum alan ürünler
* En yüksek ve en düşük puanlı ürünler
* Tartışmalı ürünler (hem yüksek hem düşük yorum alanlar)

### 3. Kullanıcı Analizi
* En çok yorum yapan kullanıcılar
* Sadık kullanıcılar (belirli ürünlere yoğunlaşanlar)
* Zaman içindeki puan tutarlılığı

### 4. Yorum Özellikleri
* Yorum uzunluğu & puan ilişkisi
* Helpfulness oranı
* 1⭐ ve 5⭐ yorumlarda öne çıkan kelimeler
* LDA ile konu modelleme

### 5. Negatif Yorum Temaları
* Paketleme sorunları
* Ürün tazeliği ve kalite şikayetleri
* Tat, koku ve kullanım deneyimi

### 6. İstatistiksel Testler
* Kullanıcı anonimliği (isimli vs anonim) ile puan farklılıkları (t-test)

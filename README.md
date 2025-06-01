# Mobil Uygulama Yorum Analizi Problem
## İçindekiler
1. [adım adım model reposu oluşturma](#adım-adım-model-reposu-oluşturma)
2. [kütüphaneler ve kurulum](#kütüphaneler-ve-kurulum)
3. [kullanılan veri kümesi amacı](#kullanılan-veri-kümesi-amacı)
## adım adım model reposu oluşturma
---
- Gerekli Kütüphaneleri Yükle
-  İncelemeleri Ön İşlemden Geçirin: Temiz metin, Tokenleştirme ve lemmatizasyon, Durdurma kelimelerini kaldırma, Olumsuz incelemeleri filtreleme
- Word2Vec Modelini Eğitin: Temizlenmiş yorumları Word2Vec modelini eğitmek veya yüklemek için kullanın:
## kullanılan veri kümesi amacı
---
- Google Play incelemelerinden Temu uygulamasının veri kümesi, yaygın kullanıcı şikayetlerini belirlemek ve kategorize etmek için kullanılır. Olumsuz incelemeleri filtreleyerek, anlamsal kümeleme için Word2Vec uygulayarak ve sıkça bahsedilen sorunları çıkararak, veri kümesi temel sorun alanlarını ortaya çıkarmaya yardımcı olur, geliştiricilerin kullanıcı memnuniyetsizliğini anlamalarını ve uygulama iyileştirmelerine öncelik vermelerini sağlar.
## kütüphaneler ve kurulum
---
-  pandas
-  numpy
-  plotly.express
-  textblob
-  matplotlib
-  scikit-learn
-  gensim
-  google-play-scraper

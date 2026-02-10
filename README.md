📝 PROJE DETAYLARI

🧠 Mental Sağlık Geçmişi Tahminleme (2025)

Amaç: Bireylerin yaşam tarzı, demografik bilgileri ve iş durumlarına dayanarak geçmişte ruhsal bir rahatsızlık yaşayıp yaşamadıklarını (History of Mental Illness) yüksek doğrulukla tahmin etmek.

🛠️ Metodoloji ve Güncellemeler
Model Seçimi: Veri setindeki karmaşık ilişkileri ve kategorik değişkenleri en iyi şekilde işlemek için Random Forest, KNN ve Lojistik Regresyon modelleri kullanılmıştır.

İstatistiksel Analiz: Özelliklerin hedef değişken üzerindeki etkisi incelenmiş, veri ön işleme aşamasında Label Encoding ve StandardScaler uygulanmıştır.

Karşılaştırma: Modeller arası performans ölçümü için doğruluk (accuracy), hassasiyet (precision) ve F1-skoru gibi metrikler kullanılmıştır.

🏆 Sonuçlar
Yapılan testler sonucunda modellerin başarı oranları şu şekildedir:

Random Forest: %100 (Eğitim verisinde mükemmel performans ve en iyi yorumlanabilirlik)

KNN (k=5): %99 (Çok güçlü performans)

Lojistik Regresyon: %99 (Güçlü ve kararlı temel değer)

🔍 Önemli Bulgular
En Güçlü Göstergeler: Özellik önemi analizi sonucunda İş Durumu (Occupation) ve Gelir Düzeyi (Income) değişkenlerinin mental sağlık geçmişi üzerinde en belirleyici faktörler olduğu saptanmıştır.

Yaşam Tarzı Etkisi: Uyku düzeni ve fiziksel aktivite verilerinin model üzerindeki etkisi, anket tabanlı oldukları için beklenenden daha düşük çıkmıştır; bu da veri toplama yöntemi için önemli bir içgörü sağlamıştır.

🚀 Gelecek Önerileri
IoT Entegrasyonu: Modelin akıllı saat verileriyle (gerçek zamanlı uyku ve hareket) beslenmesi.

Mobil Sağlık Asistanı: Kullanıcıya özel "Mental Hava Durumu" tahmini yapan bir uygulama geliştirilmesi.

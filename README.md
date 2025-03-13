# Karaciğer Kanseri (HCC) Nüks Riskini Hesaplama Projesi

## Proje Hakkında
Bu proje, karaciğer kanseri hastalarında ameliyat sonrası nüks riskini tahmin etmek amacıyla hazırlanmıştır. Gradient Boosting, Karar Ağacı ve Yapay Sinir Ağı yöntemleri kullanılarak makine öğrenimi modelleri geliştirilmiş ve performansları karşılaştırılmıştır.

## Kullanılan Veri Seti
- 30 kişilik örnek dataset kullanılmıştır.
- Veri setindeki parametreler şunları içermektedir:
  - Yaş, cinsiyet, boy, kilo
  - Laboratuvar değerleri (Albumin, INR, Kreatinin, Bilirubin, Platelet sayısı, AST, ALT, ALP, GGT, Hb, AFP)
  - Tümör özellikleri (ana tümör boyutu ve tümör sayısı)
  - Hedef değişken: Nüks durumu

## Kullanılan Yöntemler ve Modeller
- **Gradient Boosting Classifier**
- **Karar Ağacı (Decision Tree)**
- **Yapay Sinir Ağı (ANN)**

## Ön İşleme Adımları
- Eksik veriler KNNImputer ile doldurulmuştur.
- Özellikler standardize edilmiştir (Yapay Sinir Ağı için).

## Sonuçların Değerlendirilmesi
- Modeller accuracy ve classification report (precision, recall, F1-score) kullanılarak değerlendirilmiştir.

## Gereksinimler
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- TensorFlow

## Kullanım
1. Repository'i klonlayın.
2. Gerekli kütüphaneleri yükleyin:
```bash
pip install pandas numpy scikit-learn tensorflow
```

## Bu çalışma sanal bir veri seti üzerinden yapılmıştır. Hasta gizliliği açısından orijinal veri setine yer verilmedi. Sonuç ve model başarısı paylaşılacaktır.


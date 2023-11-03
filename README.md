# Beyin MR Görüntüleri ile Transfer Learning Kullanarak Tümör Sınıflandırma

Bu projede, beyin MR görüntülerini kullanarak tümör sınıflandırma görevini ele alıyoruz. Amacımız, önceden eğitilmiş bir VGG16 modelini kullanarak, bu görüntüler üzerinde derin öğrenme uygulayarak beyin tümörlerini sınıflandırmak. Ayrıca, veri setini daha çeşitli ve sağlam hale getirmek için veri augmentasyonu kullanılacaktır.
## Veri Seti

**Veri Kaynağı**: Kullandığımız veri seti, [Brain Tumor Classification](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri) indirildi.
**Kaggle Projem** : [Bu linkten ulaşabilirsiniz.](https://www.kaggle.com/code/muhammedaydin/transfer-learning-mri)
## Adım 1: Veri Keşfi ve Analizi
Başlangıç olarak, kullanılacak veri setini inceledik. Veri setinin yapısı, boyutları ve içeriği hakkında bilgi edindik.

## Adım 2: Veri Temizliği
Eğer veri setinde eksik veya hatalı veriler varsa, bu aşamada temizledik. Temiz veri, daha güçlü bir model eğitimine olanak sağlar.

## Adım 3: Data Augmentasyonu
Veri setini daha da zenginleştirmek için veri augmentasyonu kullandık. Görüntüler üzerinde döndürme, yansıtma, kesme, vb. işlemleri uygulayarak veri çeşitliliğini artırdık.

## Adım 4: Modelin Kurulması ve Eğitilmesi
Transfer learning kullanarak VGG16 modelini kurup eğittik. Ağırlıkları dondurma veya dondurmama seçeneklerini değerlendirdik ve modeli eğitirken kullanılacak parametreleri ayarladık.

## Adım 5: Sonuçlar ve Değerlendirme
Modelimizin performansını değerlendirdik. Sonuçlar, sınıflandırma doğruluğu, hassasiyet, özgüllük gibi metriklerle sunuldu.


## Teknolojiler ve Araçlar

- Python
- TensorFlow
- Keras
- cv2

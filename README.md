# Beyin Tümörü Tespiti Derin Öğrenme Projesi

## Giriş
Bu projede, beyin MR görüntülerinden tümör tespiti amacıyla çeşitli derin öğrenme tabanlı görüntü sınıflandırma modelleri kullanılmıştır. Kullanılan başlıca modeller şunlardır:
- **MobileNet**
- **MobileNet (Fine-tune)**
- **ResNet50**
- **EfficientNetB0**

Veri seti ve kodların detaylı açıklamaları, Kaggle notebook hücrelerinde markdown olarak mevcuttur.

## Model Sonuçları

### MobileNet V1 görsel linki : https://github.com/etaspinar/beyin-tumor-tespiti/tree/main/MobileNet-v1
### MobileNet V2 görsel linki : https://github.com/etaspinar/beyin-tumor-tespiti/tree/main/MobileNet-v2
### MobileNet fine-tune görsel linki : https://github.com/etaspinar/beyin-tumor-tespiti/tree/main/MobileNet-%20fine-tune
### ResNet50 fine-tune görsel linki : https://github.com/etaspinar/beyin-tumor-tespiti/tree/main/ResNet50%20fine-tune
### EfficientNetB0 fine-tune görsel linki :https://github.com/etaspinar/beyin-tumor-tespiti/tree/main/EfficientNetB0%20fine-tune


## Sonuç ve Gelecek Çalışmalar
Bu projede, transfer learning ve fine-tuning yöntemleriyle beyin tümörü tespitinde yüksek doğruluk elde edilmiştir. Özellikle MobileNet modelinin ince ayar (fine-tune) edilmiş hali, diğer modellere göre daha iyi performans göstermiştir.

Gelecek çalışmalarda şunlar hedeflenmektedir:
- Daha geniş ve çeşitli veri setleriyle modelin genellenebilirliğinin artırılması
- Modelin gerçek zamanlı çalışan bir web arayüzüne entegre edilmesi
- Veri artırma (augmentation) ve farklı regularizasyon tekniklerinin denenmesi
- Klinik ortamlarda kullanılabilirlik için modelin validasyonunun yapılması
- Diğer modern mimariler (ör. Vision Transformer, Swin Transformer) ile karşılaştırma

## Ekler
Projede ek olarak deployment, GPU hızlandırma gibi işlemler yapılabilir. Geliştirme sürecinde yeni teknolojiler ve araçlar entegre edilebilir.

## Linkler
Projeye ve çalışmalara ait Kaggle notebook linkleri:

https://www.kaggle.com/code/enestaspinar922/beyin-tumoru 
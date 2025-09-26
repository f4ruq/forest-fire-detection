# forest-fire-detection  
# (EN)

This repository contains a deep learning project developed for **forest fire detection**.  

## Introduction  

In this project, a **Convolutional Neural Network (CNN)** model was developed to classify forest fire images into two categories: **fire** and **nonfire**.  

The training dataset was created by **combining three different public datasets**. However, since the **nonfire class was underrepresented**, the class distribution is imbalanced. It has been observed that increasing the size of the nonfire class would further improve the model’s accuracy.  

## Metrics  

- Test Accuracy: **~91%**  
- High precision, recall, and F1-score were achieved for the fire class.  
- Performance for the nonfire class was lower due to imbalance, but it can be improved with additional data.  
- Confusion matrix and classification report analyses confirmed the model’s strong performance in fire detection.  

## Extras  

Potential additional work for the project:  
- A simple demo can be built with a **Streamlit interface**.  
- The model can be converted to **TFLite** for deployment on mobile/edge devices.  
- The data collection process can be made real-time to build an end-to-end system.  

## Conclusion and Future Work  

This study presents an effective approach to detecting forest fires from image data. Possible future improvements include:  
- **Expanding the nonfire class** for more balanced results,  
- **Integrating real-time camera data** for practical deployment.  

The project can be further developed in the future with new technologies and methods to improve its quality.  

## Links  

You can access the Kaggle notebook used for training and evaluation here:  
https://www.kaggle.com/code/xubustein/forest-fire-detection  

Datasets:  

https://www.kaggle.com/datasets/mohnishsaiprasad/forest-fire-images?select=Data  

https://www.kaggle.com/datasets/kutaykutlu/forest-fire?select=test_big  

https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset  

# (TR)
Bu repo, **orman yangını tespiti** için hazırlanmış bir derin öğrenme projesini içermektedir.  

## Giriş  

Bu projede, orman yangını görüntülerini **fire** ve **nonfire** olmak üzere iki sınıfa ayıran bir **Convolutional Neural Network (CNN)** modeli geliştirilmiştir.  

Eğitim veri seti, **3 farklı açık veri setinin birleştirilmesi** ile oluşturulmuştur. Ancak, **nonfire sınıfı azınlıkta** olduğu için sınıf dağılımı dengesizdir. Veri setinde bu sınıfın artırılması halinde model doğruluğunun daha da artacağı gözlemlenmiştir.  

## Metrikler  

- Test Doğruluğu: **~91%**  
- Fire sınıfı için yüksek precision, recall ve F1-score elde edilmiştir.  
- Nonfire sınıfında dengesizlikten dolayı performans daha düşüktür, fakat artırılmış veri ile iyileştirilebilir.  
- Confusion matrix ve classification report analizleri, modelin yangın tespitinde güçlü performans gösterdiğini doğrulamaktadır.  

## Ekler  

Projeye ilişkin potansiyel ek çalışmalar:  
- **Streamlit arayüzü** ile basit bir demo hazırlanabilir.  
- Modelin mobil/edge cihazlarda kullanılabilmesi için **TFLite dönüştürme** yapılabilir.  
- Veri toplama süreci gerçek zamanlı hale getirilerek end-to-end sistem kurulabilir.  

## Sonuç ve Gelecek Çalışmalar  

Bu çalışma, orman yangınlarını görüntü verileri üzerinden tespit etmek için etkili bir yaklaşım sunmaktadır. Gelecekte yapılabilecek geliştirmeler:  
- **Nonfire sınıfının genişletilmesi** ile daha dengeli sonuçlar elde edilmesi,  
- **Gerçek zamanlı kamera verileri** ile entegrasyon sağlanması.  

Proje, ilerleyen dönemlerde yeni teknolojiler ve yöntemler ile daha kaliteli hale getirilebilir.  

## Linkler  

Eğitim ve değerlendirme süreçlerinde kullanılan Kaggle not defterine buradan ulaşabilirsiniz:  
https://www.kaggle.com/code/xubustein/forest-fire-detection

Veri setleri:

https://www.kaggle.com/datasets/mohnishsaiprasad/forest-fire-images?select=Data

https://www.kaggle.com/datasets/kutaykutlu/forest-fire?select=test_big

https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset 
 

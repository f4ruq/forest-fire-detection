# forest-fire-detection  

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
 

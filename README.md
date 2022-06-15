# Python Tensorflow.Keras ile Görüntü Sınıflandırma
Python programlama dili ve Tensorflow kütüphanesi ile görüntülerin sağ göz kırpma, sol göz kırpma ve gözlerini kapatma gibi göz hareketlerini algılayan; sağ göz kırpıldıpında yukarı, sol göz kırpıldığında aşağı, gözlerin kapalı olması durumunda ise mouse sol tuşu çalıştıran bir proje geliştirilmiştir.

Proje de VGG16 mimarisi kullanılarak imagenet veriseti ile transfer öğrenme yapılmış, daha sonra eklenen bir ara katman ve çıktı katmanı ile de model oluşturulmuştur. Modelin eğitiminde stock fotoğraflar ve kameradan çekilen fotoğraflar kullanılmıştır.

![Closed (2)](https://user-images.githubusercontent.com/55946046/173818981-70de168e-80f6-4ea0-bba7-0f74261161ae.jpg) ![Left (4)](https://user-images.githubusercontent.com/55946046/173819204-964bb7d2-4c9d-46af-b5c0-0f773ca04038.jpg) ![Right (3)](https://user-images.githubusercontent.com/55946046/173819442-6a240619-d0c2-4605-a04f-c057e737701f.jpg)

Göz kırpma durumlarında aşağı-yukarı kapanmaması için belirli bir miktar gözleri kapalı tutmak gerekiyor.

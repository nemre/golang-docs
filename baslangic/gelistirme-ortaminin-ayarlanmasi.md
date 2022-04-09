# Geliştirme Ortamının Ayarlanması

![](<../.gitbook/assets/image 1.png>)

Go öğrenme sürecinizi hızlandırabilmek için bilgisayarınızda bir takım geliştirme ortamı ayarlamaları yapılması gerekmektedir. IDE kullanımı sayesinde Go kodlarınızın anlık hata kontrolleri ve önerilerini alabilmeniz sağlanır.\
\
Bu dokümantasyonda Visual Studio Code üzerinden anlatım yapılacaktır.\
\
Size uygun olan IDE (Tümleşik Geliştirme Ortamı) seçiminizi ihtiyaçlarınıza göre yapabilirsiniz.

{% hint style="info" %}
Go için özel olarak üretilmiş JetBrains GoLand kullanımını ayrıca tercih edebilirsiniz.
{% endhint %}

### Geliştirme Ortamı Kurulumu

* Tarayıcınızdan [Visual Studio Code Download](https://code.visualstudio.com/download) adresinde giderek IDE kurulumunu işletim sistemi platformunuza göre gerçekleştiriniz.

{% hint style="info" %}
Gerekli eklentilerin yüklenebilmesi için bilgisayarınızda **Git** kurulu olması gerekmektedir.\
[Git Downloads](https://git-scm.com/downloads) adresinden kurulum dosyasını indirebilirsiniz.
{% endhint %}

* Visual Studio Code ekranında bulunan eklentiler kısmından [Go](https://marketplace.visualstudio.com/items?itemName=golang.Go) eklentisini kurunuz.&#x20;
* Editörünüzde **.go** uzantılı dosya oluşturulup, içerisinde bir değişiklik yapıp kaydedildiğinde gerekli eklentilerin kurulması için bir uyarıyla karşılaşabilirsiniz. Bu uyarıda bulunan **Install All** butonuna tıklayarak eklenti kurulumlarını gerçekleştirebilirsiniz.

{% hint style="info" %}
Canlı hata ayıklama özelliğini aktifleştirebilmek için editör ayarlarınızda **Go Live Errors** araması yaparak **enabled** değerini **true** olarak değiştirebilirsiniz.
{% endhint %}

### Önerilen Hata Ayıklama Eklentisi

Kod yazarken karşınıza çıkabilecek hataları anında görebilmek için Visual Studio Code için üretilmiş **Error Lens** eklentisi bulunmaktadır.

![](<../.gitbook/assets/image (3).png>)

Kurulum yapabilmek için eklentiler kısmından Error Lens araması yapabilirsiniz.\
Bu eklenti sayesinde her yazdığınız satırda anlık hata bildirimleriyle geliştirme sürecinizi hızlandırabilirsiniz.

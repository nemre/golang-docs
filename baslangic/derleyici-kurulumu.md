# Derleyici Kurulumu

![](<../.gitbook/assets/image (7).png>)

Go derlenmiş bir dil olduğundan dolayı kaynak kodu dosyalarınızı, kaynak kodu okuyan ve programı çalıştırmak için kullanılan ikili veya yürütülebilir bir dosya oluşturan bir derleyici aracılığıyla çalıştırmamız gerektiği anlamına gelir. Diğer popüler derlenmiş dillere örnek olarak C, C++ ve Swift verilebilir. Bu dillerde yazılan programlar makine koduna dönüştürülür ve son derece hızlı çalışabilir.

Go derleyicisi hata kontrolü, optimizasyon ve dağıtım kolaylığı gibi çözümler sunar.

Çoğu durumda, Go derleyicisi kaynak kodunuzda sorun algılayabilir ve derleme işlemi sırasında, yani programınız çalıştırılmadan önce hatalara neden olabilir. Bu, üretimde beklenmeyen hataları önleyebilir ve geliştiricilere çok sayıda hata arama süresi kazandırabilir. Derleyici, kullanılmayan değişkenler, eksik içe aktarmalar, geçersiz işlemler ve daha fazlası gibi şeyleri algılamaya yardımcı olur.

{% hint style="info" %}
Go uygulamaları geliştirebilmek ve derleyebilmek için bilgisayara Go derleyicisinin kurulması gerekmektedir.
{% endhint %}

### Windows'a Go Derleyicisini Yükleme

Go derleyicisini Windows'a yüklemek için lütfen aşağıdaki adımları izleyebilirsiniz:

1. Tarayıcınızdan [Go İndirmeleri](https://go.dev/dl/) adresine gidin ve Microsoft Windows .msi yükleyicisini indirin.
2. Go derleyicisini sisteminize kurmak için yükleyiciyi başlatın ve kurulum sihirbazındaki adımları izleyin.

Go kurulumunu onaylayabilmek için aşağıdaki adımları izleyebilirsiniz:

1. Başlat/Windows düğmesine tıklayın, **cmd** yazın ve Enter'a basın.
2. Komut İstemi penceresine aşağıdaki komutu yazın ve Enter'a basın.

```
go version
```

Go derleyicisi doğru şekilde kurulduysa, aşağıdaki çıktıya benzer bir mesaj görebilirsiniz.

```
go version go1.x.x windows/amd64
```

### &#x20;Linux/Mac OS X'e Go Derleyicisini Yükleme

### &#x20;


# Merhaba Dünya

![](../.gitbook/assets/1\_5RTOhQC0zOUqYJVKludbxA.png)

Gerekli kurulumlar yapıldıktan sonra ilk Go uygulamanızı oluşturabilirsiniz.\
Yazılım dünyasında klasikleşen **“Merhaba Dünya”** uygulamasını oluşturmak ile başlayabiliriz.\
Editörünüzde .go uzantılı dosya oluşturup aşağıdaki kodları kullanarak bir **Merhaba Dünya** çıktısı veren uygulama yaratabilirsiniz.

```go
package main

import "fmt"

func main() {
    fmt.PrintLn("Merhaba Dünya!")
}
```

**`package main` ** ile dosyamızın paket ismini belirtiyoruz. **** Bu sayede aynı paket ismine değerine sahip olan dosyalar birbirleriyle iletişim kurabilir.

**`import "fmt"`** ile terminalimize veri basabilmek biçimlendirme kütüphanemizi içeri aktardık.

**`func main()`** ile uygulamamızın ilk çalıştıracağı ana fonksiyonu tanımlıyoruz. Süslü parantez içerisine yazılan kod parçaları uygulamamızda bir takım işlevleri yerine getirecektir.

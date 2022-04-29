# Merhaba Dünya

![](../.gitbook/assets/1\_5RTOhQC0zOUqYJVKludbxA.png)

Gerekli kurulumlar yapıldıktan sonra ilk Go uygulamanızı oluşturabilirsiniz.\
Yazılım dünyasında klasikleşen **“Merhaba Dünya”** uygulamasını oluşturmak ile başlayabiliriz.\
Editörünüzde .go uzantılı dosya oluşturup aşağıdaki kodları kullanarak bir **Merhaba Dünya** çıktısı veren uygulama yaratabilirsiniz. Daha sonrasında ne yaptığımızı inceleyeceğiz.

```go
package main

import "fmt"

func main() {
    fmt.PrintLn("Merhaba Dünya!")
}
```

Uygulamamızı çalıştırdıktan sonra terminalimizde bu çıktıyla karşılaşacağız.

![](<../.gitbook/assets/image (9).png>)

`package main` **** ile dosyamızın paket ismini belirtiyoruz. **** Bu sayede aynı package değerine wsahip olan dosyalar birbirleriyle iletişim kurabilir.

`import "fmt"`

****

---
title: JavaScript'te PPSX'ı SVG'a dönüştürün
url: /tr/nodejs-net/conversion/ppsx-to-svg/
keywords: PPSX'tan SVG'a, PPSX'ı SVG'a dönüştürün, Node.js API, JavaScript Kitaplığı, PPSX, SVG
description: JavaScript'te PPSX'ı SVG'a dönüştürün. PPSX dosyalarını SVG biçimine dönüştürmek için Node.js kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="JavaScript'te PPSX'ı SVG'a dönüştürün" h2="Aspose.Slides for Node.js for .NET, PowerPoint sunumlarını JavaScript'teki çeşitli formatlara dönüştürmenize olanak tanıyan güçlü ve kullanımı kolay bir kitaplıktır. Tüm sunum öğelerini ve formatlarını destekler ve bunlara erişmek ve bunları değiştirmek için zengin bir API sağlar. Ayrıca daha fazla işlem yapmak veya paylaşmak için slaytlarınızı çeşitli formatlara aktarmanıza da olanak tanır." >}}

{{% blocks/products/pf/feature-page-section h2="Node.js'de PPSX'ı SVG'a dönüştürün" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/tr/nodejs-net/), sunum dosyalarını oluşturmaya ve düzenlemeye yönelik güçlü bir Node.js kitaplığıdır. Ayrıca, PPSX biçimini SVG biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for Node.js for Node.js**'yi kullanan herhangi bir geliştirici veya uygulama, yalnızca birkaç satır kodla PPSX dosyalarını SVG dosyalara dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for Node.js, .NET aracılığıyla PPSX dosyaları hızlı bir şekilde SVG dosya formatlarına aktarır. Aspose PowerPoint kütüphanesi, PPSX'ı SVG'lara ve diğer birçok dosya formatına dönüştürmenize olanak tanır

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="JavaScript kullanarak PPSX biçimini SVG biçimine dönüştürün" %}}
PPSX dosyasını SVG biçimine dönüştürmek için, PPSX dosyasından Sunum oluşturmanız ve bunu SVG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="PPSX biçimini SVG biçimine dönüştürmek için JavaScript kodu" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.ppsx");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slideByteArray = pres.slides.get(i).getAsSvg();
        fs.writeFile('slide" + i + ".svg', Buffer.from(slideByteArray), (err) => {
            if (err)
                console.error(err);
        });
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2=".NET API aracılığıyla Aspose.Slides for Node.js kullanarak PPSX'ı SVG'a dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aspose.Slides for Node.js'yi .NET aracılığıyla kullanarak PPSX'ı SVG'a dönüştürmek için, paketi JavaScript dosyanıza aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Node.js'yi .NET** aracılığıyla yükleyin**](https://products.aspose.com/slides/tr/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PPSX dosyalarını Node.js'de açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu SVG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPSX'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca PPSX dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-jpg/" name="PPSX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
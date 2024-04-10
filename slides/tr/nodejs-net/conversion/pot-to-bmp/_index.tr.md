---
title: JavaScript'te POT'ı BMP'a dönüştürün
url: /tr/nodejs-net/conversion/pot-to-bmp/
keywords: POT'tan BMP'a, POT'ı BMP'a dönüştürün, Node.js API, JavaScript Kitaplığı, POT, BMP
description: JavaScript'te POT'ı BMP'a dönüştürün. POT dosyalarını BMP biçimine dönüştürmek için Node.js kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="JavaScript'te POT'ı BMP'a dönüştürün" h2="Aspose.Slides for Node.js for .NET, PowerPoint sunumlarını JavaScript'teki çeşitli formatlara dönüştürmenize olanak tanıyan güçlü ve kullanımı kolay bir kitaplıktır. Tüm sunum öğelerini ve formatlarını destekler ve bunlara erişmek ve bunları değiştirmek için zengin bir API sağlar. Ayrıca daha fazla işlem yapmak veya paylaşmak için slaytlarınızı çeşitli formatlara aktarmanıza da olanak tanır." >}}

{{% blocks/products/pf/feature-page-section h2="Node.js'de POT'ı BMP'a dönüştürün" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/tr/nodejs-net/), sunum dosyalarını oluşturmaya ve düzenlemeye yönelik güçlü bir Node.js kitaplığıdır. Ayrıca, POT biçimini BMP biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for Node.js for Node.js**'yi kullanan herhangi bir geliştirici veya uygulama, yalnızca birkaç satır kodla POT dosyalarını BMP dosyalara dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for Node.js, .NET aracılığıyla POT dosyaları hızlı bir şekilde BMP dosya formatlarına aktarır. Aspose PowerPoint kütüphanesi, POT'ı BMP'lara ve diğer birçok dosya formatına dönüştürmenize olanak tanır

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="JavaScript kullanarak POT biçimini BMP biçimine dönüştürün" %}}
POT dosyasını BMP biçimine dönüştürmek için, POT dosyasından Sunum oluşturmanız ve bunu BMP olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="POT biçimini BMP biçimine dönüştürmek için JavaScript kodu" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pot");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".bmp", ImageFormat.Bmp); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2=".NET API aracılığıyla Aspose.Slides for Node.js kullanarak POT'ı BMP'a dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aspose.Slides for Node.js'yi .NET aracılığıyla kullanarak POT'ı BMP'a dönüştürmek için, paketi JavaScript dosyanıza aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Node.js'yi .NET** aracılığıyla yükleyin**](https://products.aspose.com/slides/tr/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak POT dosyalarını Node.js'de açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu BMP dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="POT'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca POT dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-jpg/" name="POT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-svg/" name="POT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-net/conversion/pot-to-tiff/" name="POT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
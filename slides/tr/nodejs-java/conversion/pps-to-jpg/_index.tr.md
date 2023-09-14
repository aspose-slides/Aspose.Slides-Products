---
title: Node.js'de PPS'ı JPG'a dönüştürün
url: /tr/nodejs-java/conversion/pps-to-jpg/
keywords: PPS'tan JPG'a, PPS'ı JPG'a dönüştürün, Node.js API'si, Node.js Kitaplığı, PPS, JPG
description: Node.js'de PPS'ı JPG'a dönüştürün. PPS dosyalarını JPG dosyalara dönüştürmek için Node.js kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Node.js'de PPS'ı JPG'a dönüştürün" h2="Aspose.Slides for Node.js Java aracılığıyla, PowerPoint sunumlarını Node.js'deki çeşitli formatlara dönüştürmenize olanak tanıyan güçlü ve kullanımı kolay bir kitaplıktır. Tüm sunum öğelerini ve formatlarını destekler ve bunlara erişmek ve bunları değiştirmek için zengin bir API sağlar. Ayrıca daha fazla işlem yapmak veya paylaşmak için slaytlarınızı çeşitli formatlara aktarmanıza da olanak tanır." >}}

{{% blocks/products/pf/feature-page-section h2="Node.js'de PPS'ı JPG'a dönüştürün" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/tr/nodejs-java/), sunum dosyalarını oluşturmaya ve düzenlemeye yönelik güçlü bir Node.js kitaplığıdır. Ayrıca, PPS biçimini JPG biçimine dönüştürmek için esnek yollar sağlar. Herhangi bir geliştirici veya uygulama **Java aracılığıyla Aspose.Slides for Node.js** kullanarak yalnızca birkaç satır kodla PPS dosyalarını JPG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olan Aspose.Slides for Node.js, PPS dosyaları hızlı bir şekilde JPG dosya formatlarına aktarır. Aspose PowerPoint kitaplığı, PPS biçimini JPG biçimine ve diğer birçok dosya biçimine dönüştürmenize olanak tanır

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Node.js'yi kullanarak PPS biçimini JPG biçimine dönüştürün" %}}
PPS dosyasını JPG biçimine dönüştürmek için, PPS dosyasından Sunum oluşturmanız ve bunu JPG olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="PPS biçimini JPG biçimine dönüştürmek için Node.js kodu" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pps");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".jpg");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "jpeg", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java API aracılığıyla Aspose.Slides for Node.js kullanarak PPS'ı JPG'a dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java aracılığıyla Aspose.Slides for Node.js kullanarak PPS dosyasını JPG biçimine dönüştürmek için, paketi JavaScript dosyanıza aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Node.js'yi Java aracılığıyla**](https://products.aspose.com/slides/tr/nodejs-java/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PPS dosyalarını Node.js'de açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu JPG dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPS'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca PPS dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-svg/" name="PPS TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
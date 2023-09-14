---
title: Node.js'de PDF'ı FODP'a dönüştürün
url: /tr/nodejs-java/conversion/pdf-to-fodp/
keywords: PDF'tan FODP'a, PDF'ı FODP'a dönüştürün, Node.js API'si, Node.js Kitaplığı, PDF, FODP
description: Node.js'de PDF'ı FODP'a dönüştürün. PDF dosyalarını FODP dosyalara dönüştürmek için Node.js kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Node.js'de PDF'ı FODP'a dönüştürün" h2="Aspose.Slides for Node.js Java aracılığıyla, PowerPoint sunumlarını Node.js'deki çeşitli formatlara dönüştürmenize olanak tanıyan güçlü ve kullanımı kolay bir kitaplıktır. Tüm sunum öğelerini ve formatlarını destekler ve bunlara erişmek ve bunları değiştirmek için zengin bir API sağlar. Ayrıca daha fazla işlem yapmak veya paylaşmak için slaytlarınızı çeşitli formatlara aktarmanıza da olanak tanır." >}}

{{% blocks/products/pf/feature-page-section h2="Node.js'de PDF'ı FODP'a dönüştürün" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/tr/nodejs-java/), sunum dosyalarını oluşturmaya ve düzenlemeye yönelik güçlü bir Node.js kitaplığıdır. Ayrıca, PDF biçimini FODP biçimine dönüştürmek için esnek yollar sağlar. Herhangi bir geliştirici veya uygulama **Java aracılığıyla Aspose.Slides for Node.js** kullanarak yalnızca birkaç satır kodla PDF dosyalarını FODP dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olan Aspose.Slides for Node.js, PDF dosyaları hızlı bir şekilde FODP dosya formatlarına aktarır. Aspose PowerPoint kitaplığı, PDF biçimini FODP biçimine ve diğer birçok dosya biçimine dönüştürmenize olanak tanır

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Node.js'yi kullanarak PDF biçimini FODP biçimine dönüştürün" %}}
PDF dosyasını FODP biçimine dönüştürmek için, PDF dosyasından Sunum oluşturmanız ve bunu FODP olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="PDF biçimini FODP biçimine dönüştürmek için Node.js kodu" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation();
try
{
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

    pres.save("output.fodp", aspose.slides.SaveFormat.Fodp);
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java API aracılığıyla Aspose.Slides for Node.js kullanarak PDF'ı FODP'a dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java aracılığıyla Aspose.Slides for Node.js kullanarak PDF dosyasını FODP biçimine dönüştürmek için, paketi JavaScript dosyanıza aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Node.js'yi Java aracılığıyla**](https://products.aspose.com/slides/tr/nodejs-java/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PDF dosyalarını Node.js'de açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu FODP dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PDF'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca PDF dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
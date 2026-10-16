---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Node.js'de PPSM'ı JPG'a dönüştürün
url: /tr/nodejs-java/conversion/ppsm-to-jpg/
keywords: PPSM'tan JPG'a, PPSM'ı JPG'a dönüştürün, Node.js API'si, Node.js Kitaplığı, PPSM, JPG
description: Node.js'de PPSM'ı JPG'a dönüştürün. PPSM dosyalarını JPG dosyalara dönüştürmek için Node.js kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Node.js'de PPSM'ı JPG'a dönüştürün" h2="Aspose.Slides for Node.js Java aracılığıyla, PowerPoint sunumlarını Node.js'deki çeşitli formatlara dönüştürmenize olanak tanıyan güçlü ve kullanımı kolay bir kitaplıktır. Tüm sunum öğelerini ve formatlarını destekler ve bunlara erişmek ve bunları değiştirmek için zengin bir API sağlar. Ayrıca daha fazla işlem yapmak veya paylaşmak için slaytlarınızı çeşitli formatlara aktarmanıza da olanak tanır." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js'yi kullanarak PPSM biçimini JPG biçimine dönüştürün" variant="code" %}}

PPSM dosyasını JPG biçimine dönüştürmek için, PPSM dosyasından Sunum oluşturmanız ve bunu JPG olarak kaydetmeniz gerekir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM biçimini JPG biçimine dönüştürmek için Node.js kodu" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppsm");
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js'de PPSM'ı JPG'a dönüştürün" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/tr/nodejs-java/), sunum dosyalarını oluşturmaya ve düzenlemeye yönelik güçlü bir Node.js kitaplığıdır. Ayrıca, PPSM biçimini JPG biçimine dönüştürmek için esnek yollar sağlar. Herhangi bir geliştirici veya uygulama **Java aracılığıyla Aspose.Slides for Node.js** kullanarak yalnızca birkaç satır kodla PPSM dosyalarını JPG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olan Aspose.Slides for Node.js, PPSM dosyaları hızlı bir şekilde JPG dosya formatlarına aktarır. Aspose PowerPoint kitaplığı, PPSM biçimini JPG biçimine ve diğer birçok dosya biçimine dönüştürmenize olanak tanır

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java API aracılığıyla Aspose.Slides for Node.js kullanarak PPSM'ı JPG'a dönüştürme" intro="Java aracılığıyla Aspose.Slides for Node.js kullanarak PPSM dosyasını JPG biçimine dönüştürmek için, paketi JavaScript dosyanıza aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Node.js'yi Java aracılığıyla**](https://products.aspose.com/slides/tr/nodejs-java/) yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kaynak PPSM dosyalarını Node.js'de açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sonucu JPG dosyası olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="PPSM'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca PPSM dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

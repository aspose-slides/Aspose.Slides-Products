---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Node.js'de POTM'ı SVG'a dönüştürün
url: /tr/nodejs-java/conversion/potm-to-svg/
keywords: POTM'tan SVG'a, POTM'ı SVG'a dönüştürün, Node.js API'si, Node.js Kitaplığı, POTM, SVG
description: Node.js'de POTM'ı SVG'a dönüştürün. POTM dosyalarını SVG dosyalara dönüştürmek için Node.js kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Node.js'de POTM'ı SVG'a dönüştürün" h2="Aspose.Slides for Node.js Java aracılığıyla, PowerPoint sunumlarını Node.js'deki çeşitli formatlara dönüştürmenize olanak tanıyan güçlü ve kullanımı kolay bir kitaplıktır. Tüm sunum öğelerini ve formatlarını destekler ve bunlara erişmek ve bunları değiştirmek için zengin bir API sağlar. Ayrıca daha fazla işlem yapmak veya paylaşmak için slaytlarınızı çeşitli formatlara aktarmanıza da olanak tanır." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js'yi kullanarak POTM biçimini SVG biçimine dönüştürün" variant="code" %}}

POTM dosyasını SVG biçimine dönüştürmek için, POTM dosyasından Sunum oluşturmanız ve bunu SVG olarak kaydetmeniz gerekir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM biçimini SVG biçimine dönüştürmek için Node.js kodu" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.potm");
try
{
    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js'de POTM'ı SVG'a dönüştürün" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/tr/nodejs-java/), sunum dosyalarını oluşturmaya ve düzenlemeye yönelik güçlü bir Node.js kitaplığıdır. Ayrıca, POTM biçimini SVG biçimine dönüştürmek için esnek yollar sağlar. Herhangi bir geliştirici veya uygulama **Java aracılığıyla Aspose.Slides for Node.js** kullanarak yalnızca birkaç satır kodla POTM dosyalarını SVG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olan Aspose.Slides for Node.js, POTM dosyaları hızlı bir şekilde SVG dosya formatlarına aktarır. Aspose PowerPoint kitaplığı, POTM biçimini SVG biçimine ve diğer birçok dosya biçimine dönüştürmenize olanak tanır

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java API aracılığıyla Aspose.Slides for Node.js kullanarak POTM'ı SVG'a dönüştürme" intro="Java aracılığıyla Aspose.Slides for Node.js kullanarak POTM dosyasını SVG biçimine dönüştürmek için, paketi JavaScript dosyanıza aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Node.js'yi Java aracılığıyla**](https://products.aspose.com/slides/tr/nodejs-java/) yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kaynak POTM dosyalarını Node.js'de açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sonucu SVG dosyası olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="POTM'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca POTM dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-pdf/" name="POTM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-html/" name="POTM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-bmp/" name="POTM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-jpg/" name="POTM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/potm-to-tiff/" name="POTM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

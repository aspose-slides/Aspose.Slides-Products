---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Node.js'de PPTX'ı SVG'a dönüştürün
url: /tr/nodejs-java/conversion/pptx-to-svg/
keywords: PPTX'tan SVG'a, PPTX'ı SVG'a dönüştürün, Node.js API'si, Node.js Kitaplığı, PPTX, SVG
description: Node.js'de PPTX'ı SVG'a dönüştürün. PPTX dosyalarını SVG dosyalara dönüştürmek için Node.js kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Node.js'de PPTX'ı SVG'a dönüştürün" h2="Aspose.Slides for Node.js Java aracılığıyla, PowerPoint sunumlarını Node.js'deki çeşitli formatlara dönüştürmenize olanak tanıyan güçlü ve kullanımı kolay bir kitaplıktır. Tüm sunum öğelerini ve formatlarını destekler ve bunlara erişmek ve bunları değiştirmek için zengin bir API sağlar. Ayrıca daha fazla işlem yapmak veya paylaşmak için slaytlarınızı çeşitli formatlara aktarmanıza da olanak tanır." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js'yi kullanarak PPTX biçimini SVG biçimine dönüştürün" variant="code" %}}

PPTX dosyasını SVG biçimine dönüştürmek için, PPTX dosyasından Sunum oluşturmanız ve bunu SVG olarak kaydetmeniz gerekir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX biçimini SVG biçimine dönüştürmek için Node.js kodu" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pptx");
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js'de PPTX'ı SVG'a dönüştürün" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/tr/nodejs-java/), sunum dosyalarını oluşturmaya ve düzenlemeye yönelik güçlü bir Node.js kitaplığıdır. Ayrıca, PPTX biçimini SVG biçimine dönüştürmek için esnek yollar sağlar. Herhangi bir geliştirici veya uygulama **Java aracılığıyla Aspose.Slides for Node.js** kullanarak yalnızca birkaç satır kodla PPTX dosyalarını SVG dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olan Aspose.Slides for Node.js, PPTX dosyaları hızlı bir şekilde SVG dosya formatlarına aktarır. Aspose PowerPoint kitaplığı, PPTX biçimini SVG biçimine ve diğer birçok dosya biçimine dönüştürmenize olanak tanır

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java API aracılığıyla Aspose.Slides for Node.js kullanarak PPTX'ı SVG'a dönüştürme" intro="Java aracılığıyla Aspose.Slides for Node.js kullanarak PPTX dosyasını SVG biçimine dönüştürmek için, paketi JavaScript dosyanıza aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Node.js'yi Java aracılığıyla**](https://products.aspose.com/slides/tr/nodejs-java/) yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kaynak PPTX dosyalarını Node.js'de açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sonucu SVG dosyası olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="PPTX'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca PPTX dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

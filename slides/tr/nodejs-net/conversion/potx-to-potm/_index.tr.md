---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: JavaScript'te POTX'ı POTM'a dönüştürün
url: /tr/nodejs-net/conversion/potx-to-potm/
keywords: POTX'tan POTM'a, POTX'ı POTM'a dönüştürün, Node.js API, JavaScript Kitaplığı, POTX, POTM
description: JavaScript'te POTX'ı POTM'a dönüştürün. POTX dosyalarını POTM biçimine dönüştürmek için Node.js kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JavaScript'te POTX'ı POTM'a dönüştürün" h2="Aspose.Slides for Node.js for .NET, PowerPoint sunumlarını JavaScript'teki çeşitli formatlara dönüştürmenize olanak tanıyan güçlü ve kullanımı kolay bir kitaplıktır. Tüm sunum öğelerini ve formatlarını destekler ve bunlara erişmek ve bunları değiştirmek için zengin bir API sağlar. Ayrıca daha fazla işlem yapmak veya paylaşmak için slaytlarınızı çeşitli formatlara aktarmanıza da olanak tanır." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JavaScript kullanarak POTX biçimini POTM biçimine dönüştürün" variant="code" %}}

POTX dosyasını POTM biçimine dönüştürmek için, POTX dosyasından Sunum oluşturmanız ve bunu POTM olarak kaydetmeniz gerekir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTX biçimini POTM biçimine dönüştürmek için JavaScript kodu" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.potx");
try
{
    pres.save("output.potm", SaveFormat.Potm);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js'de POTX'ı POTM'a dönüştürün" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/tr/nodejs-net/), sunum dosyalarını oluşturmaya ve düzenlemeye yönelik güçlü bir Node.js kitaplığıdır. Ayrıca, POTX biçimini POTM biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for Node.js for Node.js**'yi kullanan herhangi bir geliştirici veya uygulama, yalnızca birkaç satır kodla POTX dosyalarını POTM dosyalara dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for Node.js, .NET aracılığıyla POTX dosyaları hızlı bir şekilde POTM dosya formatlarına aktarır. Aspose PowerPoint kütüphanesi, POTX'ı POTM'lara ve diğer birçok dosya formatına dönüştürmenize olanak tanır

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title=".NET API aracılığıyla Aspose.Slides for Node.js kullanarak POTX'ı POTM'a dönüştürme" intro="Aspose.Slides for Node.js'yi .NET aracılığıyla kullanarak POTX'ı POTM'a dönüştürmek için, paketi JavaScript dosyanıza aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Node.js'yi .NET** aracılığıyla yükleyin**](https://products.aspose.com/slides/tr/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kaynak POTX dosyalarını Node.js'de açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sonucu POTM dosyası olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="POTX'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca POTX dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-bmp/" name="POTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

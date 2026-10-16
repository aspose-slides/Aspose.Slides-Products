---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: JavaScript'te PPSM'ı POTM'a dönüştürün
url: /tr/nodejs-net/conversion/ppsm-to-potm/
keywords: PPSM'tan POTM'a, PPSM'ı POTM'a dönüştürün, Node.js API, JavaScript Kitaplığı, PPSM, POTM
description: JavaScript'te PPSM'ı POTM'a dönüştürün. PPSM dosyalarını POTM biçimine dönüştürmek için Node.js kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JavaScript'te PPSM'ı POTM'a dönüştürün" h2="Aspose.Slides for Node.js for .NET, PowerPoint sunumlarını JavaScript'teki çeşitli formatlara dönüştürmenize olanak tanıyan güçlü ve kullanımı kolay bir kitaplıktır. Tüm sunum öğelerini ve formatlarını destekler ve bunlara erişmek ve bunları değiştirmek için zengin bir API sağlar. Ayrıca daha fazla işlem yapmak veya paylaşmak için slaytlarınızı çeşitli formatlara aktarmanıza da olanak tanır." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JavaScript kullanarak PPSM biçimini POTM biçimine dönüştürün" variant="code" %}}

PPSM dosyasını POTM biçimine dönüştürmek için, PPSM dosyasından Sunum oluşturmanız ve bunu POTM olarak kaydetmeniz gerekir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM biçimini POTM biçimine dönüştürmek için JavaScript kodu" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.ppsm");
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js'de PPSM'ı POTM'a dönüştürün" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/tr/nodejs-net/), sunum dosyalarını oluşturmaya ve düzenlemeye yönelik güçlü bir Node.js kitaplığıdır. Ayrıca, PPSM biçimini POTM biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for Node.js for Node.js**'yi kullanan herhangi bir geliştirici veya uygulama, yalnızca birkaç satır kodla PPSM dosyalarını POTM dosyalara dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for Node.js, .NET aracılığıyla PPSM dosyaları hızlı bir şekilde POTM dosya formatlarına aktarır. Aspose PowerPoint kütüphanesi, PPSM'ı POTM'lara ve diğer birçok dosya formatına dönüştürmenize olanak tanır

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title=".NET API aracılığıyla Aspose.Slides for Node.js kullanarak PPSM'ı POTM'a dönüştürme" intro="Aspose.Slides for Node.js'yi .NET aracılığıyla kullanarak PPSM'ı POTM'a dönüştürmek için, paketi JavaScript dosyanıza aktarmanız ve Sunum sınıfının bir örneğini oluşturmanız gerekir. Sunum sınıfı bir PowerPoint belgesini temsil eder ve öğelerine erişmeye ve bunları yönetmeye yönelik yöntemler sağlar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Node.js'yi .NET** aracılığıyla yükleyin**](https://products.aspose.com/slides/tr/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js projenize bir kitaplık referansı ekleyin (kitaplığı içe aktarın).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kaynak PPSM dosyalarını Node.js'de açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sonucu POTM dosyası olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="PPSM'ı Desteklenen Diğer Formatlara Dönüştürün" subTitle="Ayrıca PPSM dosyasını dönüştürebilir ve diğer dosya formatlarına kaydedebilirsiniz. Desteklenen tüm formatları aşağıda görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/nodejs-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

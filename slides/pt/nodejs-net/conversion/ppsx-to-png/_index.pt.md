---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPSX em PNG em JavaScript
url: /pt/nodejs-net/conversion/ppsx-to-png/
keywords: PPSX para PNG, converter PPSX para PNG, API Node.js, biblioteca JavaScript, PPSX, PNG
description: Converta PPSX em PNG em JavaScript. Use a API da biblioteca Node.js para converter arquivos PPSX em PNG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PPSX em PNG em JavaScript" h2="Aspose.Slides para Node.js via .NET é uma biblioteca poderosa e fácil de usar que permite converter apresentações do PowerPoint para vários formatos em JavaScript. Ele suporta todos os elementos e formatos de apresentação e fornece uma API avançada para acessá-los e modificá-los. Também permite exportar seus slides para vários formatos para processamento ou compartilhamento posterior." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converta PPSX em PNG usando JavaScript" variant="code" %}}

Para converter PPSX para PNG, você precisará criar uma apresentação a partir do arquivo PPSX e salvá-la como PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código JavaScript para converter PPSX em PNG" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.ppsx");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".png", ImageFormat.Png); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PPSX em PNG em Node.js" %}}

[**Aspose.Slides para Node.js via .NET**](https://products.aspose.com/slides/pt/nodejs-net/) é uma biblioteca Node.js poderosa para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter PPSX em PNG. Usando **Aspose.Slides para Node.js via .NET**, qualquer desenvolvedor ou aplicativo pode converter arquivos PPSX em PNG com apenas algumas linhas de código.

Como uma API moderna de processamento de documentos, Aspose.Slides para Node.js via .NET exporta arquivos PPSX para formatos de arquivo PNG rapidamente. A biblioteca Aspose PowerPoint permite converter PPSX em PNGs e muitos outros formatos de arquivo

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter PPSX para PNG usando Aspose.Slides para Node.js via .NET API" intro="Para converter PPSX para PNG usando Aspose.Slides para Node.js via .NET, você precisa importar o pacote em seu arquivo JavaScript e criar uma instância da classe Presentation. A classe Presentation representa um documento PowerPoint e fornece métodos para acessar e manipular seus elementos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [**Aspose.Slides para Node.js via .NET**](https://products.aspose.com/slides/pt/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra os arquivos de origem PPSX em Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o resultado como arquivo PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converter PPSX para outros formatos suportados" subTitle="Você também pode converter PPSX e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-jpg/" name="PPSX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/nodejs-net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

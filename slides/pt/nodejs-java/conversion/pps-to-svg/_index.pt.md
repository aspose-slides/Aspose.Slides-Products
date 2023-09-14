---
title: Converter PPS em SVG em Node.js
url: /pt/nodejs-java/conversion/pps-to-svg/
keywords: PPS para SVG, converter PPS para SVG, API Node.js, biblioteca Node.js, PPS, SVG
description: Converta PPS em SVG em Node.js. Use a API da biblioteca Node.js para converter arquivos PPS em SVGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter PPS em SVG em Node.js" h2="Aspose.Slides para Node.js via Java é uma biblioteca poderosa e fácil de usar que permite converter apresentações do PowerPoint para vários formatos em Node.js. Ele suporta todos os elementos e formatos de apresentação e fornece uma API avançada para acessá-los e modificá-los. Também permite exportar seus slides para vários formatos para processamento ou compartilhamento posterior." >}}

{{% blocks/products/pf/feature-page-section h2="Converter PPS em SVG em Node.js" %}}

[**Aspose.Slides para Node.js via Java**](https://products.aspose.com/slides/pt/nodejs-java/) é uma biblioteca Node.js poderosa para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter PPS em SVG. Usando **Aspose.Slides para Node.js via Java**, qualquer desenvolvedor ou aplicativo pode converter arquivos PPS em SVG com apenas algumas linhas de código.

Como uma API moderna de processamento de documentos, Aspose.Slides for Node.js exporta arquivos PPS para formatos de arquivo SVG rapidamente. A biblioteca Aspose PowerPoint permite converter PPS em SVGs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converta PPS para SVG usando Node.js" %}}
Para converter PPS para SVG, você precisará criar uma apresentação a partir do arquivo PPS e salvá-la como SVG.

{{% blocks/products/pf/agp/code-block title="Código Node.js para converter PPS em SVG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pps");
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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como converter PPS para SVG usando Aspose.Slides para Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Para converter PPS para SVG usando Aspose.Slides para Node.js via Java, você precisa importar o pacote em seu arquivo JavaScript e criar uma instância da classe Presentation. A classe Presentation representa um documento PowerPoint e fornece métodos para acessar e manipular seus elementos." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Node.js via Java**](https://products.aspose.com/slides/pt/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem PPS em Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter PPS para outros formatos suportados" subTitle="Você também pode converter PPS e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-jpg/" name="PPS TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
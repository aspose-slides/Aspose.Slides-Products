---
title: Converter FODP em JPG em Node.js
url: /pt/nodejs-java/conversion/fodp-to-jpg/
keywords: FODP para JPG, converter FODP para JPG, API Node.js, biblioteca Node.js, FODP, JPG
description: Converta FODP em JPG em Node.js. Use a API da biblioteca Node.js para converter arquivos FODP em JPGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter FODP em JPG em Node.js" h2="Aspose.Slides para Node.js via Java é uma biblioteca poderosa e fácil de usar que permite converter apresentações do PowerPoint para vários formatos em Node.js. Ele suporta todos os elementos e formatos de apresentação e fornece uma API avançada para acessá-los e modificá-los. Também permite exportar seus slides para vários formatos para processamento ou compartilhamento posterior." >}}

{{% blocks/products/pf/feature-page-section h2="Converter FODP em JPG em Node.js" %}}

[**Aspose.Slides para Node.js via Java**](https://products.aspose.com/slides/pt/nodejs-java/) é uma biblioteca Node.js poderosa para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter FODP em JPG. Usando **Aspose.Slides para Node.js via Java**, qualquer desenvolvedor ou aplicativo pode converter arquivos FODP em JPG com apenas algumas linhas de código.

Como uma API moderna de processamento de documentos, Aspose.Slides for Node.js exporta arquivos FODP para formatos de arquivo JPG rapidamente. A biblioteca Aspose PowerPoint permite converter FODP em JPGs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converta FODP para JPG usando Node.js" %}}
Para converter FODP para JPG, você precisará criar uma apresentação a partir do arquivo FODP e salvá-la como JPG.

{{% blocks/products/pf/agp/code-block title="Código Node.js para converter FODP em JPG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.fodp");
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

{{< blocks/products/pf/feature-page-section  h2="Como converter FODP para JPG usando Aspose.Slides para Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Para converter FODP para JPG usando Aspose.Slides para Node.js via Java, você precisa importar o pacote em seu arquivo JavaScript e criar uma instância da classe Presentation. A classe Presentation representa um documento PowerPoint e fornece métodos para acessar e manipular seus elementos." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Node.js via Java**](https://products.aspose.com/slides/pt/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem FODP em Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter FODP para outros formatos suportados" subTitle="Você também pode converter FODP e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
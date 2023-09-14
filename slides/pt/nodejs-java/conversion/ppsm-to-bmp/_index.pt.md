---
title: Converter PPSM em BMP em Node.js
url: /pt/nodejs-java/conversion/ppsm-to-bmp/
keywords: PPSM para BMP, converter PPSM para BMP, API Node.js, biblioteca Node.js, PPSM, BMP
description: Converta PPSM em BMP em Node.js. Use a API da biblioteca Node.js para converter arquivos PPSM em BMPs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter PPSM em BMP em Node.js" h2="Aspose.Slides para Node.js via Java é uma biblioteca poderosa e fácil de usar que permite converter apresentações do PowerPoint para vários formatos em Node.js. Ele suporta todos os elementos e formatos de apresentação e fornece uma API avançada para acessá-los e modificá-los. Também permite exportar seus slides para vários formatos para processamento ou compartilhamento posterior." >}}

{{% blocks/products/pf/feature-page-section h2="Converter PPSM em BMP em Node.js" %}}

[**Aspose.Slides para Node.js via Java**](https://products.aspose.com/slides/pt/nodejs-java/) é uma biblioteca Node.js poderosa para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter PPSM em BMP. Usando **Aspose.Slides para Node.js via Java**, qualquer desenvolvedor ou aplicativo pode converter arquivos PPSM em BMP com apenas algumas linhas de código.

Como uma API moderna de processamento de documentos, Aspose.Slides for Node.js exporta arquivos PPSM para formatos de arquivo BMP rapidamente. A biblioteca Aspose PowerPoint permite converter PPSM em BMPs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converta PPSM para BMP usando Node.js" %}}
Para converter PPSM para BMP, você precisará criar uma apresentação a partir do arquivo PPSM e salvá-la como BMP.

{{% blocks/products/pf/agp/code-block title="Código Node.js para converter PPSM em BMP" offSpacer="true" %}}

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
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".bmp");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "bmp", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como converter PPSM para BMP usando Aspose.Slides para Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Para converter PPSM para BMP usando Aspose.Slides para Node.js via Java, você precisa importar o pacote em seu arquivo JavaScript e criar uma instância da classe Presentation. A classe Presentation representa um documento PowerPoint e fornece métodos para acessar e manipular seus elementos." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Node.js via Java**](https://products.aspose.com/slides/pt/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem PPSM em Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter PPSM para outros formatos suportados" subTitle="Você também pode converter PPSM e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Converter PPTX em BMP em Node.js
url: /pt/nodejs-java/conversion/pptx-to-bmp/
keywords: PPTX para BMP, converter PPTX para BMP, API Node.js, biblioteca Node.js, PPTX, BMP
description: Converta PPTX em BMP em Node.js. Use a API da biblioteca Node.js para converter arquivos PPTX em BMPs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter PPTX em BMP em Node.js" h2="Aspose.Slides para Node.js via Java é uma biblioteca poderosa e fácil de usar que permite converter apresentações do PowerPoint para vários formatos em Node.js. Ele suporta todos os elementos e formatos de apresentação e fornece uma API avançada para acessá-los e modificá-los. Também permite exportar seus slides para vários formatos para processamento ou compartilhamento posterior." >}}

{{% blocks/products/pf/feature-page-section h2="Converter PPTX em BMP em Node.js" %}}

[**Aspose.Slides para Node.js via Java**](https://products.aspose.com/slides/pt/nodejs-java/) é uma biblioteca Node.js poderosa para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter PPTX em BMP. Usando **Aspose.Slides para Node.js via Java**, qualquer desenvolvedor ou aplicativo pode converter arquivos PPTX em BMP com apenas algumas linhas de código.

Como uma API moderna de processamento de documentos, Aspose.Slides for Node.js exporta arquivos PPTX para formatos de arquivo BMP rapidamente. A biblioteca Aspose PowerPoint permite converter PPTX em BMPs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converta PPTX para BMP usando Node.js" %}}
Para converter PPTX para BMP, você precisará criar uma apresentação a partir do arquivo PPTX e salvá-la como BMP.

{{% blocks/products/pf/agp/code-block title="Código Node.js para converter PPTX em BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pptx");
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

{{< blocks/products/pf/feature-page-section  h2="Como converter PPTX para BMP usando Aspose.Slides para Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Para converter PPTX para BMP usando Aspose.Slides para Node.js via Java, você precisa importar o pacote em seu arquivo JavaScript e criar uma instância da classe Presentation. A classe Presentation representa um documento PowerPoint e fornece métodos para acessar e manipular seus elementos." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Node.js via Java**](https://products.aspose.com/slides/pt/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem PPTX em Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter PPTX para outros formatos suportados" subTitle="Você também pode converter PPTX e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/nodejs-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
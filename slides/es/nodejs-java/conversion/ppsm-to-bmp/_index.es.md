---
title: Convierta PPSM a BMP en Node.js
url: /es/nodejs-java/conversion/ppsm-to-bmp/
keywords: PPSM a BMP, Convertir PPSM a BMP, API de Node.js, Biblioteca Node.js, PPSM, BMP
description: Convierta PPSM a BMP en Node.js. Utilice la API de la biblioteca Node.js para convertir archivos PPSM a BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convierta PPSM a BMP en Node.js" h2="Aspose.Slides para Node.js vía Java es una biblioteca potente y fácil de usar que le permite convertir presentaciones de PowerPoint a varios formatos en Node.js. Admite todos los elementos y formatos de presentación y proporciona una API enriquecida para acceder a ellos y modificarlos. También le permite exportar sus diapositivas a varios formatos para procesarlas o compartirlas posteriormente." >}}

{{% blocks/products/pf/feature-page-section h2="Convierta PPSM a BMP en Node.js" %}}

[**Aspose.Slides para Node.js vía Java**](https://products.aspose.com/slides/es/nodejs-java/) es una poderosa biblioteca de Node.js para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir PPSM a BMP. Al utilizar **Aspose.Slides para Node.js a través de Java**, cualquier desarrollador o aplicación puede convertir archivos PPSM a BMP con solo unas pocas líneas de código.

Como API moderna de procesamiento de documentos, Aspose.Slides para Node.js exporta archivos PPSM a formatos de archivo BMP rápidamente. La biblioteca Aspose PowerPoint le permite convertir PPSM a BMPs y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta PPSM a BMP usando Node.js" %}}
Para convertir PPSM a BMP, deberá crear una presentación a partir del archivo PPSM y guardarla como BMP.

{{% blocks/products/pf/agp/code-block title="Código Node.js para convertir PPSM en BMP" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir PPSM a BMP usando Aspose.Slides para Node.js a través de la API de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Para convertir PPSM a BMP usando Aspose.Slides para Node.js a través de Java, debe importar el paquete en su archivo JavaScript y crear una instancia de la clase Presentación. La clase Presentación representa un documento de PowerPoint y proporciona métodos para acceder y manipular sus elementos." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Node.js a través de Java**](https://products.aspose.com/slides/es/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente PPSM en Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el resultado como archivo BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PPSM a otros formatos admitidos" subTitle="También puede convertir PPSM y guardarlo en otros formatos de archivo. Vea todos los formatos compatibles a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
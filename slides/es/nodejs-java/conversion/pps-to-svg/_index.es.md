---
title: Convierta PPS a SVG en Node.js
url: /es/nodejs-java/conversion/pps-to-svg/
keywords: PPS a SVG, Convertir PPS a SVG, API de Node.js, Biblioteca Node.js, PPS, SVG
description: Convierta PPS a SVG en Node.js. Utilice la API de la biblioteca Node.js para convertir archivos PPS a SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convierta PPS a SVG en Node.js" h2="Aspose.Slides para Node.js vía Java es una biblioteca potente y fácil de usar que le permite convertir presentaciones de PowerPoint a varios formatos en Node.js. Admite todos los elementos y formatos de presentación y proporciona una API enriquecida para acceder a ellos y modificarlos. También le permite exportar sus diapositivas a varios formatos para procesarlas o compartirlas posteriormente." >}}

{{% blocks/products/pf/feature-page-section h2="Convierta PPS a SVG en Node.js" %}}

[**Aspose.Slides para Node.js vía Java**](https://products.aspose.com/slides/es/nodejs-java/) es una poderosa biblioteca de Node.js para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir PPS a SVG. Al utilizar **Aspose.Slides para Node.js a través de Java**, cualquier desarrollador o aplicación puede convertir archivos PPS a SVG con solo unas pocas líneas de código.

Como API moderna de procesamiento de documentos, Aspose.Slides para Node.js exporta archivos PPS a formatos de archivo SVG rápidamente. La biblioteca Aspose PowerPoint le permite convertir PPS a SVGs y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta PPS a SVG usando Node.js" %}}
Para convertir PPS a SVG, deberá crear una presentación a partir del archivo PPS y guardarla como SVG.

{{% blocks/products/pf/agp/code-block title="Código Node.js para convertir PPS en SVG" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir PPS a SVG usando Aspose.Slides para Node.js a través de la API de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Para convertir PPS a SVG usando Aspose.Slides para Node.js a través de Java, debe importar el paquete en su archivo JavaScript y crear una instancia de la clase Presentación. La clase Presentación representa un documento de PowerPoint y proporciona métodos para acceder y manipular sus elementos." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Node.js a través de Java**](https://products.aspose.com/slides/es/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente PPS en Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el resultado como archivo SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PPS a otros formatos admitidos" subTitle="También puede convertir PPS y guardarlo en otros formatos de archivo. Vea todos los formatos compatibles a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-jpg/" name="PPS TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/nodejs-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
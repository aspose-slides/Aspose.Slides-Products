---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PDF a POT en JavaScript
url: /es/nodejs-net/conversion/pdf-to-pot/
keywords: PDF a POT, Convertir PDF a POT, API de Node.js, Biblioteca JavaScript, PDF, POT
description: Convierta PDF a POT en JavaScript. Utilice la API de la biblioteca Node.js para convertir archivos PDF a POT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PDF a POT en JavaScript" h2="Aspose.Slides para Node.js vía .NET es una biblioteca potente y fácil de usar que le permite convertir presentaciones de PowerPoint a varios formatos en JavaScript. Admite todos los elementos y formatos de presentación y proporciona una API enriquecida para acceder a ellos y modificarlos. También le permite exportar sus diapositivas a varios formatos para procesarlas o compartirlas posteriormente." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convierta PDF a POT usando JavaScript" variant="code" %}}

Para convertir PDF a POT, deberá crear una presentación a partir del archivo PDF y guardarla como POT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código JavaScript para convertir PDF en POT" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat, ShapeType } = asposeSlides;

var pres = new Presentation();
try
{
    pres.slides.removeAt(0);
    var slides = pres.slides.addFromPdf("welcome-to-powerpoint.pdf");

    pres.save("output.pot", SaveFormat.Pot);
}
finally
{
    if (pres != null) pres.dispose();
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convierta PDF a POT en Node.js" %}}

[**Aspose.Slides para Node.js vía .NET**](https://products.aspose.com/slides/es/nodejs-net/) es una poderosa biblioteca de Node.js para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir PDF a POT. Al utilizar **Aspose.Slides para Node.js a través de .NET**, cualquier desarrollador o aplicación puede convertir archivos PDF a POT con solo unas pocas líneas de código.

Como API moderna de procesamiento de documentos, Aspose.Slides para Node.js a través de .NET exporta archivos PDF a formatos de archivo POT rápidamente. La biblioteca Aspose PowerPoint le permite convertir PDF a POTs y muchos otros formatos de archivo

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo convertir PDF a POT usando Aspose.Slides para Node.js a través de .NET API" intro="Para convertir PDF a POT usando Aspose.Slides para Node.js a través de .NET, debe importar el paquete en su archivo JavaScript y crear una instancia de la clase Presentación. La clase Presentación representa un documento de PowerPoint y proporciona métodos para acceder y manipular sus elementos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [**Aspose.Slides para Node.js a través de .NET**](https://products.aspose.com/slides/es/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra los archivos fuente PDF en Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el resultado como archivo POT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir PDF a otros formatos admitidos" subTitle="También puede convertir PDF y guardarlo en otros formatos de archivo. Vea todos los formatos compatibles a continuación" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/nodejs-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

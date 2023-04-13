---
title: Convertir PNG a PPTX en C#
url: /es/net/conversion/png-to-pptx/
keywords: Convierta PNG a PPTX, PNG a PPTX, PowerPoint, PNG, PPTX, C# API, Biblioteca .NET
description: Convierte PNG a PPTX en C#. Use la API de la biblioteca .NET para convertir imágenes PNG a PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PNG a PPTX en C#" h2="Potente API .NET multiplataforma para convertir PNG a PPTX usando código C# en plataformas NET Framework, .NET Core, Windows Azure, Mono o Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta PNG a PPTX usando Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/es/net/) es una potente biblioteca .NET que se utiliza para crear, convertir y manipular presentaciones de PowerPoint, PDF, documentos HTML, y otros archivos. Cuando convierte PNG a PPTX, básicamente está creando una presentación de PowerPoint que contiene diapositivas basadas en imágenes PNG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convertir PNG a PPTX en C#" %}}
Con [**Aspose.Slides for .NET**](https://products.aspose.com/slides/es/net/), puede convertir una imagen PNG en una presentación de PowerPoint con solo unas pocas líneas de código:

{{% blocks/products/pf/agp/code-block title="Código C# para convertir PNG a PPTX" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cómo convertir PNG a PPTX en C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para .NET**. Consulte [**Instalación**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue la biblioteca como referencia en su proyecto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea una instancia de la clase Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue la imagen PNG que desea convertir a PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el archivo resultante como una presentación PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertidor en línea gratuito" sectionDescription="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones de PowerPoint admitidas" subTitle="También puede convertir archivos en otros formatos a PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
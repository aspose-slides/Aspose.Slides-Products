---
title: Convertir PNG a JPG en C++
url: /es/cpp/conversion/png-to-jpg/
keywords: PNG a JPG, Convertir PNG a JPG, API de C++, Biblioteca de C++, PNG, JPG
description: Convierte PNG a JPG en C++. Use la API de la biblioteca C++ para convertir archivos PNG a JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PNG a JPG en C++" h2="Biblioteca C++ multiplataforma y de alta velocidad que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PNG a JPG en C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/es/cpp/) es una poderosa biblioteca de C++ para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir PNG a JPG. Con **Aspose.Slides para C++**, cualquier desarrollador o aplicación puede convertir archivos PNG a JPG con solo unas pocas líneas de código C++.

Como una API moderna de procesamiento de documentos, Aspose.Slides para C++ exporta archivos PNG a formatos de archivo JPG rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir PNG a JPGs y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta PNG a JPG usando C++" %}}
Para convertir PNG a JPG, deberá crear la presentación desde el archivo PNG y guardarlo como JPG.

{{% blocks/products/pf/agp/code-block title="Código C++ para convertir PNG en JPG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".jpg");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Jpeg());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir PNG a JPG usando Aspose.Slides para la API de C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir PNG a JPG en C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para C++**](https://products.aspose.com/slides/es/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto de C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente PNG en C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado como archivo JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertidor en línea gratuito" sectionDescription="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PNG a otros formatos admitidos" subTitle="También puede convertir PNG y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Convertir SVG a PNG en C++
url: /es/cpp/conversion/svg-to-png/
keywords: SVG a PNG, Convertir SVG a PNG, API de C++, Biblioteca de C++, SVG, PNG
description: Convierte SVG a PNG en C++. Use la API de la biblioteca C++ para convertir archivos SVG a PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir SVG a PNG en C++" h2="Biblioteca C++ multiplataforma y de alta velocidad que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir SVG a PNG en C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/es/cpp/) es una poderosa biblioteca de C++ para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir SVG a PNG. Con **Aspose.Slides para C++**, cualquier desarrollador o aplicación puede convertir archivos SVG a PNG con solo unas pocas líneas de código C++.

Como una API moderna de procesamiento de documentos, Aspose.Slides para C++ exporta archivos SVG a formatos de archivo PNG rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir SVG a PNGs y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta SVG a PNG usando C++" %}}
Para convertir SVG a PNG, deberá crear la presentación desde el archivo SVG y guardarlo como PNG.

{{% blocks/products/pf/agp/code-block title="Código C++ para convertir SVG en PNG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
System::String svgContent = System::IO::File::ReadAllText(svgPath);
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
System::SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(Aspose::Slides::ShapeType::Rectangle, 0.0f, 0.0f, 
    static_cast<float>(ppImage->get_Width()), 
    static_cast<float>(ppImage->get_Height()), ppImage);
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
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir SVG a PNG usando Aspose.Slides para la API de C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir SVG a PNG en C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para C++**](https://products.aspose.com/slides/es/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto de C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente SVG en C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado como archivo PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir SVG a otros formatos admitidos" subTitle="También puede convertir SVG y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
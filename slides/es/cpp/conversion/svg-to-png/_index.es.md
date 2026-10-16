---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir SVG a PNG en C++
url: /es/cpp/conversion/svg-to-png/
keywords: SVG a PNG, Convertir SVG a PNG, API de C++, Biblioteca de C++, SVG, PNG
description: Convierte SVG a PNG en C++. Use la API de la biblioteca C++ para convertir archivos SVG a PNG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir SVG a PNG en C++" h2="Biblioteca C++ multiplataforma y de alta velocidad que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convierta SVG a PNG usando C++" variant="code" %}}

Para convertir SVG a PNG, deberá crear la presentación desde el archivo SVG y guardarlo como PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código C++ para convertir SVG en PNG" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir SVG a PNG en C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/es/cpp/) es una poderosa biblioteca de C++ para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir SVG a PNG. Con **Aspose.Slides para C++**, cualquier desarrollador o aplicación puede convertir archivos SVG a PNG con solo unas pocas líneas de código C++.

Como una API moderna de procesamiento de documentos, Aspose.Slides para C++ exporta archivos SVG a formatos de archivo PNG rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir SVG a PNGs y muchos otros formatos de archivo

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo convertir SVG a PNG usando Aspose.Slides para la API de C++" intro="Estos son los pasos para convertir SVG a PNG en C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [**Aspose.Slides para C++**](https://products.aspose.com/slides/es/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto de C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra los archivos fuente SVG en C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guardar resultado como archivo PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertidor en línea gratuito"
  description="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir SVG a otros formatos admitidos" subTitle="También puede convertir SVG y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

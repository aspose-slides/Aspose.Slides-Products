---
title: Konvertera JPG till PNG i C++
url: /sv/cpp/conversion/jpg-to-png/
keywords: JPG till PNG, Konvertera JPG till PNG, C++ API, C++ Library, JPG, PNG
description: Konvertera JPG till PNG i C++. Använd C++ biblioteks-API för att konvertera JPG-filer till PNGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera JPG till PNG i C++" h2="Höghastighets- och plattformsoberoende C++-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera JPG till PNG i C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/sv/cpp/) är ett kraftfullt C++-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera JPG till PNG. Genom att använda **Aspose.Slides för C++** kan alla utvecklare eller appar konvertera JPG till PNG-filer med bara några rader C++-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för C++ snabbt JPG-filer till PNG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera JPG till PNG och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera JPG till PNG med C++" %}}
För att konvertera JPG till PNG måste du skapa en presentation från filen JPG och spara den som PNG.

{{% blocks/products/pf/agp/code-block title="C++-kod för att konvertera JPG till PNG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
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
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar JPG till PNG med Aspose.Slides för C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera JPG till PNG i C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for C++**](https://products.aspose.com/slides/sv/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt C++-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna JPG i C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som PNG-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera JPG till andra format som stöds" subTitle="Du kan också konvertera JPG och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
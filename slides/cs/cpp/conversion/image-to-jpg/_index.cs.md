---
title: Převeďte Image do JPG v C++
url: /cs/cpp/conversion/image-to-jpg/
keywords: Image do JPG, Převést Image do JPG, C++ API, C++ Library, Image, JPG
description: Převeďte Image do JPG v C++. Použijte API knihovny C++ k převodu souborů Image na JPGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte Image do JPG v C++" h2="Vysokorychlostní a multiplatformní knihovna C++, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte Image do JPG v C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cs/cpp/) je výkonná knihovna C++ pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu Image do JPG. Pomocí **Aspose.Slides for C++** může každý vývojář nebo aplikace převést soubory Image do JPG pomocí několika řádků kódu C++.

Aspose.Slides pro C++ jako moderní API pro zpracování dokumentů rychle exportuje soubory Image do formátů souborů JPG. Knihovna Aspose PowerPoint vám umožňuje převést Image do JPGs a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte Image do JPG pomocí C++" %}}
Chcete-li převést Image do JPG, budete muset vytvořit prezentaci ze souboru Image a uložit ji jako JPG.

{{% blocks/products/pf/agp/code-block title="C++ kód pro převod Image do JPG" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Jak převést Image do JPG pomocí Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky pro převod Image do JPG v C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides for C++**](https://products.aspose.com/slides/cs/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory Image v C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Zdarma online konvertor" sectionDescription="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést Image do jiných podporovaných formátů" subTitle="Můžete také převést Image a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
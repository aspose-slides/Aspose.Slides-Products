---
title: Konwertuj SVG na PNG w C++
url: /pl/cpp/conversion/svg-to-png/
keywords: SVG do PNG, Konwersja SVG do PNG, API C++, Biblioteka C++, SVG, PNG
description: Konwertuj SVG na PNG w C++. Użyj interfejsu API biblioteki C++, aby przekonwertować pliki SVG na pliki PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj SVG na PNG w C++" h2="Szybka i wieloplatformowa biblioteka C++, która pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj SVG na PNG w C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/pl/cpp/) to potężna biblioteka C++ do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji SVG na PNG. Korzystając z **Aspose.Slides dla C++**, każdy programista lub aplikacja może konwertować pliki SVG na PNG za pomocą zaledwie kilku wierszy kodu C++.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla C++ szybko eksportuje pliki SVG do formatów plików PNG. Biblioteka Aspose PowerPoint umożliwia konwersję SVG do PNG i wielu innych formatów plików

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj SVG na PNG przy użyciu C++" %}}
Aby przekonwertować SVG na PNG, musisz utworzyć Prezentację z pliku SVG i zapisać ją jako PNG.

{{% blocks/products/pf/agp/code-block title="Kod C++ do konwersji SVG na PNG" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować SVG na PNG przy użyciu Aspose.Slides dla C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować SVG na PNG w C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla C++**](https://products.aspose.com/slides/pl/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do projektu C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz źródłowe pliki SVG w języku C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj SVG na inne obsługiwane formaty" subTitle="Możesz także przekonwertować SVG i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
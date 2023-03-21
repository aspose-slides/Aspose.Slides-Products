---
title: Konwertuj PNG na SVG w C++
url: /pl/cpp/conversion/png-to-svg/
keywords: PNG do SVG, Konwersja PNG do SVG, API C++, Biblioteka C++, PNG, SVG
description: Konwertuj PNG na SVG w C++. Użyj interfejsu API biblioteki C++, aby przekonwertować pliki PNG na pliki SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj PNG na SVG w C++" h2="Szybka i wieloplatformowa biblioteka C++, która pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PNG na SVG w C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/pl/cpp/) to potężna biblioteka C++ do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji PNG na SVG. Korzystając z **Aspose.Slides dla C++**, każdy programista lub aplikacja może konwertować pliki PNG na SVG za pomocą zaledwie kilku wierszy kodu C++.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla C++ szybko eksportuje pliki PNG do formatów plików SVG. Biblioteka Aspose PowerPoint umożliwia konwersję PNG do SVG i wielu innych formatów plików

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PNG na SVG przy użyciu C++" %}}
Aby przekonwertować PNG na SVG, musisz utworzyć Prezentację z pliku PNG i zapisać ją jako SVG.

{{% blocks/products/pf/agp/code-block title="Kod C++ do konwersji PNG na SVG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = pres->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować PNG na SVG przy użyciu Aspose.Slides dla C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować PNG na SVG w C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla C++**](https://products.aspose.com/slides/pl/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do projektu C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz źródłowe pliki PNG w języku C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Darmowy konwerter online" sectionDescription="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj PNG na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PNG i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
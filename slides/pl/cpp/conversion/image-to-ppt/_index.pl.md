---
title: Konwertuj obraz na PPT w C++
url: /pl/cpp/conversion/image-to-ppt/
keywords: Obraz do PPT, Konwertuj obraz do PPT, C++ API, C++ Library, Image, PPT
description: Konwertuj obraz na PPT w C++. Użyj interfejsu API biblioteki C++ do konwersji plików obrazów na pliki PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj obraz na PPT w C++" h2="Szybka i wieloplatformowa biblioteka C++, która pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj obraz na PPT w C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/pl/cpp/) to potężna biblioteka C++ do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji obrazu na PPT. Korzystając z **Aspose.Slides dla C++**, każdy programista lub aplikacja może konwertować obrazy na pliki PPT za pomocą zaledwie kilku wierszy kodu C++.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla C++ szybko eksportuje pliki obrazów do formatów plików PPT. Biblioteka Aspose PowerPoint umożliwia konwersję obrazów do plików PDF i wielu innych formatów plików

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj obraz na PPT za pomocą C++" %}}
Aby przekonwertować obraz na PPT, musisz utworzyć prezentację z pliku obrazu i zapisać go jako PPT.

{{% blocks/products/pf/agp/code-block title="Kod C++ do konwersji obrazu na PPT" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);
pres->Save(u"presentation.ppt", SaveFormat::Ppt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować obraz na PPT za pomocą Aspose.Slides dla C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować obraz na PPT w C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla C++**](https://products.aspose.com/slides/pl/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do projektu C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz źródłowe pliki obrazów w języku C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj obraz na inne obsługiwane formaty" subTitle="Możesz także konwertować obraz i zapisywać go w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
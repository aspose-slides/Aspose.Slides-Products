---
title: Konwertuj PNG na PPTX w C++
url: /pl/cpp/conversion/png-to-pptx/
keywords: Konwertuj PNG na PPTX, PNG na PPTX, PowerPoint, PNG, PPTX, C++ API, C++ Library
description: Konwertuj PNG na PPTX w C++. Użyj interfejsu API biblioteki C++ do konwersji obrazów PNG do programu PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj PNG na PPTX w C++" h2="Potężny, wieloplatformowy interfejs API C++ do konwersji PNG na PPTX przy użyciu kodu C++" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PNG na PPTX za pomocą Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/pl/cpp/) to potężna biblioteka C++ używana do tworzenia, konwertowania i manipulowania prezentacjami programu PowerPoint, plikami PDF, dokumentami HTML i innymi akta. Kiedy konwertujesz PNG na PPTX, zasadniczo tworzysz prezentację PowerPoint zawierającą slajdy oparte na obrazach PNG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Konwertuj PNG na PPTX w C++" %}}
Używając [**Aspose.Slides for C++**](https://products.aspose.com/slides/pl/cpp/), możesz przekonwertować obraz PNG na prezentację PowerPoint za pomocą zaledwie kilku linijek kodu:

{{% blocks/products/pf/agp/code-block title="Kod C++ do konwersji PNG na PPTX" offSpacer="true" %}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować PNG na PPTX w C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj **Aspose.Slides dla C++**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj bibliotekę jako odniesienie w swoim projekcie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utwórz wystąpienie klasy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj obraz PNG, który chcesz przekonwertować na PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynikowy plik jako prezentację PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Darmowy konwerter online" sectionDescription="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje programu PowerPoint" subTitle="Możesz także konwertować pliki w innych formatach do programu PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
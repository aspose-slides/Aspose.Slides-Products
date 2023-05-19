---
title: Wyszukaj tekst w plikach prezentacji PPTX za pomocą C++
url: /pl/cpp/search/pptx/
keywords: wyszukaj słowa w PPTX, wyszukaj i zamień tekst w PPTX, wyszukaj tekst PPTX Prezentacja
description: Kod źródłowy C++ do wyszukiwania tekstu w prezentacji PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Wyszukaj tekst PPTX za pomocą C++" h2="Twórz własne aplikacje C++ do wyszukiwania i zastępowania tekstu w plikach prezentacji przy użyciu interfejsów API po stronie serwera. Dowiedz się, jak znaleźć wszystkie wejścia określonego słowa lub wyrażenia w dokumentach prezentacji. Wyszukuj tekst według dokładnego dopasowania danych i dopasowania wyrażenia regularnego." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Wyszukaj i zastąp tekst PPTX Prezentacja za pośrednictwem C++" %}}
Podstawowe wyszukiwanie dokumentów i zastępowanie tekstu w treści, komentarzach, notatkach slajdów lub metadanych za pomocą interfejsów API Aspose.Slides for C++ można wykonać za pomocą zaledwie kilku wierszy kodu. Użyj dopasowywania wyrażeń regularnych, dopasowuj wielkość liter, aby wyszukiwać tekst w prezentacji. Szukaj tekstu w tytułach, treści, stopce lub nagłówku.
{{% blocks/products/pf/agp/code-block title="Wyszukaj tekst PPTX Prezentacja za pomocą C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.pptx", SaveFormat::Pptx);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak wyszukiwać tekst w PPTX przez C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki wyszukiwania plików tekstowych PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPTX z instancją Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Użyj metody [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/), aby znaleźć i zamienić tekst.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Wyszukaj prezentacje na żywo" sectionDescription="Wyszukuj i zastępuj tekst w treści, komentarzach lub metadanych w dokumentach PPTX już teraz." >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty wyszukiwania" subTitle="Korzystając z C++, możesz również wyszukiwać tekst w następujących formatach:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
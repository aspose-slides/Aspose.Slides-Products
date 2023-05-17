---
title: Zredaguj pliki prezentacji ODP za pomocą C++
url: /pl/cpp/redaction/odp/
keywords: Zredaguj ODP, znajdź i zamień tekst w ODP, zaktualizuj prezentację ODP
description: Kod źródłowy C++ do znajdowania i zastępowania tekstu w prezentacji ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zredaguj ODP za pomocą C++" h2="Twórz własne aplikacje C++, aby wyszukiwać i zamieniać tekst w plikach prezentacji za pomocą interfejsów API po stronie serwera. Dowiedz się, jak wyszukiwać i zastępować tekst w treści, komentarzach lub metadanych prezentacji ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Zredaguj prezentację ODP za pośrednictwem C++" %}}
Podstawowe wyszukiwanie dokumentów i zastępowanie tekstu w treści, komentarzach, notatkach slajdów lub metadanych za pomocą interfejsów API Aspose.Slides for C++ można wykonać za pomocą zaledwie kilku wierszy kodu. Znajdź i zamień tekst w programach PowerPoint i OpenOffice. Edytuj tekst, komentarze, metadane w prezentacji za pomocą dopasowywania danych wyrażeń regularnych.
{{% blocks/products/pf/agp/code-block title="Zredaguj prezentację ODP za pomocą C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak zredagować ODP przez C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki redagowania plików ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj ODP z instancją Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Użyj metody [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/), aby znaleźć i zamienić tekst.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Redakcyjne prezentacje na żywo" sectionDescription="Wyszukuj i zastępuj tekst w treści, komentarzach lub metadanych w dokumentach ODP już teraz." >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty redakcji" subTitle="Korzystając z C++, możesz również zredagować następujące formaty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/cpp/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
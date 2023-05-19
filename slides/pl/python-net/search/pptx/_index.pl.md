---
title: Wyszukaj tekst w plikach prezentacji PPTX za pomocą Python
url: /pl/python-net/search/pptx/
keywords: wyszukaj słowa w PPTX, wyszukaj i zamień tekst w PPTX, wyszukaj tekst PPTX Prezentacja
description: Kod źródłowy Python do wyszukiwania tekstu w prezentacji PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Wyszukaj tekst PPTX za pomocą Python" h2="Twórz własne aplikacje Python do wyszukiwania i zastępowania tekstu w plikach prezentacji przy użyciu interfejsów API po stronie serwera. Dowiedz się, jak znaleźć wszystkie wejścia określonego słowa lub wyrażenia w dokumentach prezentacji. Wyszukuj tekst według dokładnego dopasowania danych i dopasowania wyrażenia regularnego." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Wyszukaj i zastąp tekst PPTX Prezentacja za pośrednictwem Python" %}}
Podstawowe wyszukiwanie dokumentów i zastępowanie tekstu w treści, komentarzach, notatkach slajdów lub metadanych za pomocą interfejsów API Aspose.Slides for Python via .NET można wykonać za pomocą zaledwie kilku wierszy kodu. Użyj dopasowywania wyrażeń regularnych, dopasowuj wielkość liter, aby wyszukiwać tekst w prezentacji. Szukaj tekstu w tytułach, treści, stopce lub nagłówku.
{{% blocks/products/pf/agp/code-block title="Wyszukaj tekst PPTX Prezentacja za pomocą Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak wyszukiwać tekst w PPTX przez Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki wyszukiwania plików tekstowych PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPTX z instancją Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Użyj metody [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/), aby znaleźć i zamienić tekst.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Wyszukaj prezentacje na żywo" sectionDescription="Wyszukuj i zastępuj tekst w treści, komentarzach lub metadanych w dokumentach PPTX już teraz." >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty wyszukiwania" subTitle="Korzystając z Python, możesz również wyszukiwać tekst w następujących formatach:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
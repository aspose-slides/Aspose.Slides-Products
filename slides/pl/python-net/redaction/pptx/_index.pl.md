---
title: Zredaguj pliki prezentacji PPTX za pomocą Python
url: /pl/python-net/redaction/pptx/
keywords: Zredaguj PPTX, znajdź i zamień tekst w PPTX, zaktualizuj prezentację PPTX
description: Kod źródłowy Python do znajdowania i zastępowania tekstu w prezentacji PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zredaguj PPTX za pomocą Python" h2="Twórz własne aplikacje Python, aby wyszukiwać i zamieniać tekst w plikach prezentacji za pomocą interfejsów API po stronie serwera. Dowiedz się, jak wyszukiwać i zastępować tekst w treści, komentarzach lub metadanych prezentacji PPTX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Zredaguj prezentację PPTX za pośrednictwem Python" %}}
Podstawowe wyszukiwanie dokumentów i zastępowanie tekstu w treści, komentarzach, notatkach slajdów lub metadanych za pomocą interfejsów API Aspose.Slides for Python via .NET można wykonać za pomocą zaledwie kilku wierszy kodu. Znajdź i zamień tekst w programach PowerPoint i OpenOffice. Edytuj tekst, komentarze, metadane w prezentacji za pomocą dopasowywania danych wyrażeń regularnych.
{{% blocks/products/pf/agp/code-block title="Zredaguj prezentację PPTX za pomocą Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak zredagować PPTX przez Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki redagowania plików PPTX." >}}

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

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redakcyjne prezentacje na żywo" sectionDescription="Wyszukuj i zastępuj tekst w treści, komentarzach lub metadanych w dokumentach PPTX już teraz." >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty redakcji" subTitle="Korzystając z Python, możesz również zredagować następujące formaty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Usuń adnotację PPT za pomocą Pythona
weight: 4380
url: /pl/python-net/annotation/ppt/ 
description: Kod źródłowy Pythona do usuwania komentarzy do prezentacji PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Usuń komentarze i autorów komentarzy z PPT w Pythonie" h2="Twórz własne skrypty w języku Python, aby manipulować komentarzami i autorami w plikach dokumentów, korzystając z interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Usuń komentarze z PPT przez Pythona" %}}
Aby usunąć adnotacje z pliku PPT, użyjemy [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/) API, które jest bogatym w funkcje, potężny i łatwy w użyciu interfejs API do manipulacji dokumentami dla platformy Python.
{{% blocks/products/pf/agp/code-block title="Usuń adnotacje z PPT — Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.ppt") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Jak usunąć komentarze z PPT przez Pythona" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPT z instancją klasy Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iteruj po wszystkich autorach załadowanego PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Usuń wszystkie komentarze autora
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Usuń wszystkich autorów na końcu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty adnotacji" subTitle="Korzystając z Pythona, można łatwo dodawać adnotacje do innych formatów, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
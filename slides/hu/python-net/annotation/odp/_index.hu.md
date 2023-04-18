---
title: Távolítsa el az ODP-jegyzeteket a Python használatával
weight: 4380
url: /hu/python-net/annotation/odp/ 
description: Python-forráskód az ODP-prezentáció megjegyzéseinek eltávolításához
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Távolítsa el a megjegyzéseket és a megjegyzés szerzőket az ODP-ből a Pythonban" h2="Készítse el saját Python-szkriptjeit, hogy manipulálja a megjegyzéseket és a szerzőket a dokumentumfájlokban szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Távolítsa el a megjegyzéseket az ODP-ből Python segítségével" %}}
A megjegyzések ODP-fájlból való eltávolításához az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hu/python-net/) API-t használjuk, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési API Python platformhoz.
{{% blocks/products/pf/agp/code-block title="Megjegyzések törlése az ODP - Pythonból" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.odp") as presentation:
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

{{< blocks/products/pf/feature-page-section  h2="Hogyan távolítsuk el a megjegyzéseket az ODP-ből Python segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for Python programot .NET-en keresztül**. Lásd: [**Telepítés**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be az ODP-t a Presentation osztály egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iteráljon a betöltött ODP összes szerzőjén
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Távolítsa el a szerző összes megjegyzését
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A végén távolítsa el az összes szerzőt
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott megjegyzésformátumok" subTitle="A Python használatával könnyen feljegyezhet más formátumokat, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
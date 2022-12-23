---
title: Upravte PDF v Pythonu
url: /cs/python-net/editor/pdf/
keywords: Upravit PDF, PDF, Python API, Python Library
description: Upravte PDF v Pythonu. K úpravě dokumentu PDF použijte rozhraní API knihovny Python
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Upravte PDF v Pythonu" h2="Vysokorychlostní a multiplatformní knihovna Python pro úpravu PDF pomocí kódu Python" >}}

{{% blocks/products/pf/feature-page-section h2="Upravte PDF pomocí Aspose.Slides" %}}

[**Aspose.Slides pro Python přes .NET**](https://products.aspose.com/slides/cs/python-net/) je výkonná knihovna Pythonu používaná k manipulaci a úpravám prezentací, dokumentů PDF a dalších souborů . Dokument PDF můžete upravit přidáním nového řádku textu. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Upravte PDF v Pythonu" %}}
Pomocí [**Aspose.Slides pro Python přes .NET**](https://products.aspose.com/slides/cs/python-net/) můžete do dokumentu PDF přidat nový řádek textu pomocí několika řádky kódu.

{{% blocks/products/pf/agp/code-block title="Python kód pro úpravu PDF" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak upravit PDF v Pythonu" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Aspose.Slides pro Python přes .NET**. Viz [**Instalace**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte knihovnu jako referenci do svého projektu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte dokument PDF, který chcete upravit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte nový řádek textu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte změněný soubor PDF.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Upravte další soubory" subTitle="Můžete také upravovat soubory v jiných formátech" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
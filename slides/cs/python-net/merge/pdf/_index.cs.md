---
title: Sloučit soubory PDF pomocí Pythonu
url: /cs/python-net/merge/pdf/
keywords: Sloučit PDF, Připojit PDF, Kombinovat PDF, PowerPoint, Prezentace, Python, Aspose
description: Sloučit více souborů PDF v Pythonu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Sloučit soubory PDF dohromady v Pythonu" h2="Vysokorychlostní a multiplatformní Python API, které pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Sloučit PDF v Pythonu" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/cs/python-net/) je výkonná knihovna Pythonu pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby, jak kombinovat více prezentací PDF. Když sloučíte jednu prezentaci do druhé, efektivně kombinujete jejich snímky do jedné prezentace, abyste získali jeden soubor. Aspose.Slides umožňuje sloučit dvě prezentace různými způsoby. Můžete sloučit prezentace se všemi jejich tvary, styly, texty, formátováním, komentáři, animacemi atd., aniž byste se museli obávat ztráty kvality nebo dat.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Sloučit soubory PDF pomocí Pythonu" %}}
Chcete-li sloučit prezentace PowerPoint, budete muset naklonovat snímky z jedné prezentace do druhé.

{{% blocks/products/pf/agp/code-block title="Python kód pro sloučení více PDF do jednoho souboru" offSpacer="true" %}}


```python

import aspose.slides as slides


with slides.Presentation() as pres1:
    pres1.slides.remove_at(0)
    pres1.slides.add_from_pdf("document1.pdf")
    with slides.Presentation() as pres2:
        pres2.slides.remove_at(0)
        pres2.slides.add_from_pdf("document2.pdf")
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pdf", slides.export.SaveFormat.PDF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak sloučit PDF pomocí Aspose.Slides pro Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky ke sloučení dvou souborů PDF a uložení výsledku jako PDF v Pythonu." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/cs/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Python.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory PDF v Pythonu.
```
pres1 = slides.Presentation('pres1.pdf')
pres2 = slides.Presentation('pres2.pdf')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zkombinujte soubory PDF pomocí metody [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte prezentaci a získejte výsledek jako jeden soubor PDF.
```
pres1.save("result.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportovat PDF do jiných podporovaných formátů" subTitle="Můžete také kombinovat PDF a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-pptx/" name="PDF TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-ppt/" name="PDF TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-html/" name="PDF TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-png/" name="PDF TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-bmp/" name="PDF TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-jpg/" name="PDF TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-fodp/" name="PDF TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-gif/" name="PDF TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-odp/" name="PDF TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-otp/" name="PDF TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-pot/" name="PDF TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-potm/" name="PDF TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-potx/" name="PDF TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-pps/" name="PDF TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-ppsm/" name="PDF TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-ppsx/" name="PDF TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-pptm/" name="PDF TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-svg/" name="PDF TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-tiff/" name="PDF TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pdf-to-xps/" name="PDF TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
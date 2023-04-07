---
title: Sloučit soubory PPTM pomocí Pythonu
url: /cs/python-net/merge/pptm/
keywords: Sloučit PPTM, Připojit PPTM, Kombinovat PPTM, PowerPoint, Prezentace, Python, Aspose
description: Sloučit více souborů PPTM v Pythonu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Sloučit soubory PPTM dohromady v Pythonu" h2="Vysokorychlostní a multiplatformní Python API, které pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Sloučit PPTM v Pythonu" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/cs/python-net/) je výkonná knihovna Pythonu pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby, jak kombinovat více prezentací PPTM. Když sloučíte jednu prezentaci do druhé, efektivně kombinujete jejich snímky do jedné prezentace, abyste získali jeden soubor. Aspose.Slides umožňuje sloučit dvě prezentace různými způsoby. Můžete sloučit prezentace se všemi jejich tvary, styly, texty, formátováním, komentáři, animacemi atd., aniž byste se museli obávat ztráty kvality nebo dat.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Sloučit soubory PPTM pomocí Pythonu" %}}
Chcete-li sloučit prezentace PowerPoint, budete muset naklonovat snímky z jedné prezentace do druhé.

{{% blocks/products/pf/agp/code-block title="Python kód pro sloučení více PPTM do jednoho souboru" offSpacer="true" %}}


```python

import aspose.slides as slides


with slides.Presentation("presentation1.pptm") as pres1:
    with slides.Presentation("presentation2.pptm") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pptm", slides.export.SaveFormat.PPTM)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak sloučit PPTM pomocí Aspose.Slides pro Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky ke sloučení dvou souborů PPTM a uložení výsledku jako PPTM v Pythonu." >}}

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
Otevřete zdrojové soubory PPTM v Pythonu.
```
pres1 = slides.Presentation('pres1.pptm')
pres2 = slides.Presentation('pres2.pptm')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zkombinujte soubory PPTM pomocí metody [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte prezentaci a získejte výsledek jako jeden soubor PPTM.
```
pres1.save("result.pptm", slides.export.SaveFormat.PPTM)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Sloučit soubory PDF online" sectionDescription="[Jak sloučit PDF v Pythonu](https://products.aspose.com/slides/cs/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportovat PPTM do jiných podporovaných formátů" subTitle="Můžete také kombinovat PPTM a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-pptx/" name="PPTM TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-ppt/" name="PPTM TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-pdf/" name="PPTM TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-html/" name="PPTM TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-png/" name="PPTM TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-bmp/" name="PPTM TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-jpg/" name="PPTM TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-fodp/" name="PPTM TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-gif/" name="PPTM TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-odp/" name="PPTM TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-otp/" name="PPTM TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-pot/" name="PPTM TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-potm/" name="PPTM TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-potx/" name="PPTM TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-pps/" name="PPTM TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-ppsm/" name="PPTM TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-ppsx/" name="PPTM TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-svg/" name="PPTM TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-tiff/" name="PPTM TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/pptm-to-xps/" name="PPTM TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
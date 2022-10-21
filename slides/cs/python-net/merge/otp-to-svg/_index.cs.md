---
title: Sloučit soubory OTP do SVG pomocí Pythonu
url: /cs/python-net/merge/otp-to-svg/
keywords: Sloučit OTP do SVG, připojit OTP do SVG, kombinovat OTP do SVG, PowerPoint, Presentation, SVG, Python, Aspose
description: Sloučit více souborů OTP v Pythonu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Sloučit soubory OTP do SVG dohromady v Pythonu" h2="Vysokorychlostní a multiplatformní Python API, které pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Sloučit OTP do SVG v Pythonu" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/cs/python-net/) je výkonná knihovna Pythonu pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby, jak kombinovat více prezentací OTP. Když sloučíte jednu prezentaci do druhé, efektivně kombinujete jejich snímky do jedné prezentace, abyste získali jeden soubor. Aspose.Slides umožňuje sloučit dvě prezentace různými způsoby. Můžete sloučit prezentace se všemi jejich tvary, styly, texty, formátováním, komentáři, animacemi atd., aniž byste se museli obávat ztráty kvality nebo dat.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Sloučit soubory OTP do SVG pomocí Pythonu" %}}
Chcete-li sloučit prezentace PowerPoint, budete muset naklonovat snímky z jedné prezentace do druhé.

{{% blocks/products/pf/agp/code-block title="Python kód pro sloučení více OTP do jednoho souboru SVG" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.otp") as pres1:
    with slides.Presentation("presentation2.otp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak sloučit OTP do SVG pomocí Aspose.Slides pro Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky ke sloučení dvou souborů OTP a uložení výsledku jako SVG v Pythonu." >}}

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
Otevřete zdrojové soubory OTP v Pythonu.
```
pres1 = slides.Presentation('pres1.otp')
pres2 = slides.Presentation('pres2.otp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zkombinujte soubory OTP pomocí metody [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte prezentaci a získejte výsledek jako jeden soubor SVG.
```
for slide in pres1.slides:
    with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
        slide.write_as_svg(file)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportovat OTP do jiných podporovaných formátů" subTitle="Můžete také kombinovat OTP a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-pptx/" name="OTP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-ppt/" name="OTP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-pdf/" name="OTP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-html/" name="OTP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-png/" name="OTP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-bmp/" name="OTP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-jpg/" name="OTP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-fodp/" name="OTP TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-gif/" name="OTP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-odp/" name="OTP TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-pot/" name="OTP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-potm/" name="OTP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-potx/" name="OTP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-pps/" name="OTP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-ppsm/" name="OTP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-ppsx/" name="OTP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-pptm/" name="OTP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-tiff/" name="OTP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/merge/otp-to-xps/" name="OTP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
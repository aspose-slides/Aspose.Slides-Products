---
title: Slå samman POT-filer till PNG med Python
url: /sv/python-net/merge/pot-to-png/
keywords: Slå samman POT till PNG, gå med POT till PNG, kombinera POT till PNG, PowerPoint, Presentation, PNG, Python, Aspose
description: Slå samman flera POT-filer i Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Slå samman POT-filer till PNG i Python" h2="Höghastighets- och plattformsoberoende Python API som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Slå samman POT till PNG i Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/sv/python-net/) är ett kraftfullt Python-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att kombinera flera POT-presentationer. När du slår samman en presentation med en annan, kombinerar du effektivt deras bilder i en enda presentation för att få en fil. Aspose.Slides låter dig slå samman två presentationer på olika sätt. Du får slå samman presentationer med alla deras former, stilar, texter, formatering, kommentarer, animationer etc. utan att behöva oroa dig för förlust av kvalitet eller data.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Slå samman POT-filer till PNG med Python" %}}
För att slå samman PowerPoint-presentationer måste du klona bilderna från en presentation till den andra.

{{% blocks/products/pf/agp/code-block title="Python-kod för att slå samman flera POT till en enda PNG-fil" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.pot") as pres1:
    with slides.Presentation("presentation2.pot") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man slår samman POT till PNG med Aspose.Slides för Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att slå samman två POT-filer och spara resultatet som PNG i Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/sv/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt Python-projekt.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna POT i Python.
```
pres1 = slides.Presentation('pres1.pot')
pres2 = slides.Presentation('pres2.pot')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinera POT-filer med metoden [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara presentationen och få resultatet som en enda PNG-fil.
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportera POT till andra format som stöds" subTitle="Du kan också kombinera POT och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-pptx/" name="POT TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-ppt/" name="POT TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-pdf/" name="POT TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-html/" name="POT TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-bmp/" name="POT TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-jpg/" name="POT TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-fodp/" name="POT TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-gif/" name="POT TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-odp/" name="POT TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-otp/" name="POT TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-potm/" name="POT TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-potx/" name="POT TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-pps/" name="POT TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-ppsm/" name="POT TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-ppsx/" name="POT TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-pptm/" name="POT TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-svg/" name="POT TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-tiff/" name="POT TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pot-to-xps/" name="POT TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
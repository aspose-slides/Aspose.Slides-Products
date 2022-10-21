---
title: Slå samman PPTM-filer till HTML med Python
url: /sv/python-net/merge/pptm-to-html/
keywords: Slå samman PPTM till HTML, gå med PPTM till HTML, kombinera PPTM till HTML, PowerPoint, Presentation, HTML, Python, Aspose
description: Slå samman flera PPTM-filer i Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Slå samman PPTM-filer till HTML i Python" h2="Höghastighets- och plattformsoberoende Python API som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Slå samman PPTM till HTML i Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/sv/python-net/) är ett kraftfullt Python-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att kombinera flera PPTM-presentationer. När du slår samman en presentation med en annan, kombinerar du effektivt deras bilder i en enda presentation för att få en fil. Aspose.Slides låter dig slå samman två presentationer på olika sätt. Du får slå samman presentationer med alla deras former, stilar, texter, formatering, kommentarer, animationer etc. utan att behöva oroa dig för förlust av kvalitet eller data.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Slå samman PPTM-filer till HTML med Python" %}}
För att slå samman PowerPoint-presentationer måste du klona bilderna från en presentation till den andra.

{{% blocks/products/pf/agp/code-block title="Python-kod för att slå samman flera PPTM till en enda HTML-fil" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.pptm") as pres1:
    with slides.Presentation("presentation2.pptm") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.html", slides.export.SaveFormat.HTML5)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man slår samman PPTM till HTML med Aspose.Slides för Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att slå samman två PPTM-filer och spara resultatet som HTML i Python." >}}

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
Öppna källfilerna PPTM i Python.
```
pres1 = slides.Presentation('pres1.pptm')
pres2 = slides.Presentation('pres2.pptm')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinera PPTM-filer med metoden [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara presentationen och få resultatet som en enda HTML-fil.
```
pres1.save("presentation.html", slides.export.SaveFormat.HTML5)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exportera PPTM till andra format som stöds" subTitle="Du kan också kombinera PPTM och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-pptx/" name="PPTM TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-ppt/" name="PPTM TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-pdf/" name="PPTM TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-png/" name="PPTM TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-bmp/" name="PPTM TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-jpg/" name="PPTM TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-fodp/" name="PPTM TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-gif/" name="PPTM TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-odp/" name="PPTM TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-otp/" name="PPTM TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-pot/" name="PPTM TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-potm/" name="PPTM TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-potx/" name="PPTM TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-pps/" name="PPTM TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-ppsm/" name="PPTM TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-ppsx/" name="PPTM TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-svg/" name="PPTM TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-tiff/" name="PPTM TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/python-net/merge/pptm-to-xps/" name="PPTM TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
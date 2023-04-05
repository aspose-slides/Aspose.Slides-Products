---
title: Scal pliki PPT do PNG za pomocą Pythona
url: /pl/python-net/merge/ppt-to-png/
keywords: Połącz {z_formatu} z {do_formatu}, Połącz {z_formatu} z {do_formatu}, Połącz {z_formatu} z {do_formatu}, PowerPoint, Prezentacja, {do_formatu}, Python, Aspose
description: Scal wiele plików PPT w Pythonie.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Scal pliki PPT do PNG razem w Pythonie" h2="Szybki i wieloplatformowy interfejs API Pythona, który pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia jakiegokolwiek oprogramowania, takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Scal PPT do PNG w Pythonie" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pl/python-net/) to potężna biblioteka Pythona do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby łączenia wielu prezentacji PPT. Scalając jedną prezentację z drugą, skutecznie łączysz ich slajdy w jedną prezentację, aby uzyskać jeden plik. Aspose.Slides umożliwia łączenie dwóch prezentacji na różne sposoby. Możesz łączyć prezentacje ze wszystkimi ich kształtami, stylami, tekstami, formatowaniem, komentarzami, animacjami itp. bez obaw o utratę jakości lub danych.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Scal pliki PPT do PNG za pomocą Pythona" %}}
Aby scalić prezentacje PowerPoint, musisz sklonować slajdy z jednej prezentacji do drugiej.

{{% blocks/products/pf/agp/code-block title="Kod Pythona do łączenia wielu plików PPT w jeden plik PNG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.ppt") as pres1:
    with slides.Presentation("presentation2.ppt") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak połączyć PPT z PNG za pomocą Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby połączyć dwa pliki PPT i zapisać wynik jako PNG w Pythonie." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pl/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu w Pythonie.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz źródłowe pliki PPT w Pythonie.
```
pres1 = slides.Presentation('pres1.ppt')
pres2 = slides.Presentation('pres2.ppt')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Połącz pliki PPT za pomocą metody [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz prezentację i uzyskaj wynik jako pojedynczy plik PNG.
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Scal pliki PDF online" sectionDescription="[Jak scalić PDF w Pythonie](https://products.aspose.com/slides/pl/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Eksportuj PPT do innych obsługiwanych formatów" subTitle="Możesz też łączyć PPT i zapisywać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-pptx/" name="PPT TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-pdf/" name="PPT TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-html/" name="PPT TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-bmp/" name="PPT TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-jpg/" name="PPT TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-fodp/" name="PPT TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-gif/" name="PPT TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-odp/" name="PPT TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-otp/" name="PPT TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-pot/" name="PPT TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-potm/" name="PPT TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-potx/" name="PPT TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-pps/" name="PPT TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-ppsm/" name="PPT TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-ppsx/" name="PPT TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-pptm/" name="PPT TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-svg/" name="PPT TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-tiff/" name="PPT TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/ppt-to-xps/" name="PPT TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
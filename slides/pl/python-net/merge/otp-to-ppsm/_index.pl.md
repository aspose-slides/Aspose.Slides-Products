---
title: Scal pliki OTP do PPSM za pomocą Pythona
url: /pl/python-net/merge/otp-to-ppsm/
keywords: Połącz {z_formatu} z {do_formatu}, Połącz {z_formatu} z {do_formatu}, Połącz {z_formatu} z {do_formatu}, PowerPoint, Prezentacja, {do_formatu}, Python, Aspose
description: Scal wiele plików OTP w Pythonie.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Scal pliki OTP do PPSM razem w Pythonie" h2="Szybki i wieloplatformowy interfejs API Pythona, który pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia jakiegokolwiek oprogramowania, takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Scal OTP do PPSM w Pythonie" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pl/python-net/) to potężna biblioteka Pythona do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby łączenia wielu prezentacji OTP. Scalając jedną prezentację z drugą, skutecznie łączysz ich slajdy w jedną prezentację, aby uzyskać jeden plik. Aspose.Slides umożliwia łączenie dwóch prezentacji na różne sposoby. Możesz łączyć prezentacje ze wszystkimi ich kształtami, stylami, tekstami, formatowaniem, komentarzami, animacjami itp. bez obaw o utratę jakości lub danych.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Scal pliki OTP do PPSM za pomocą Pythona" %}}
Aby scalić prezentacje PowerPoint, musisz sklonować slajdy z jednej prezentacji do drugiej.

{{% blocks/products/pf/agp/code-block title="Kod Pythona do łączenia wielu plików OTP w jeden plik PPSM" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.otp") as pres1:
    with slides.Presentation("presentation2.otp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.ppsm", slides.export.SaveFormat.PPSM)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak połączyć OTP z PPSM za pomocą Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby połączyć dwa pliki OTP i zapisać wynik jako PPSM w Pythonie." >}}

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
Otwórz źródłowe pliki OTP w Pythonie.
```
pres1 = slides.Presentation('pres1.otp')
pres2 = slides.Presentation('pres2.otp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Połącz pliki OTP za pomocą metody [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz prezentację i uzyskaj wynik jako pojedynczy plik PPSM.
```
pres1.save("presentation.ppsm", slides.export.SaveFormat.PPSM)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Eksportuj OTP do innych obsługiwanych formatów" subTitle="Możesz też łączyć OTP i zapisywać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-pptx/" name="OTP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-ppt/" name="OTP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-pdf/" name="OTP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-html/" name="OTP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-png/" name="OTP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-bmp/" name="OTP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-jpg/" name="OTP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-fodp/" name="OTP TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-gif/" name="OTP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-odp/" name="OTP TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-pot/" name="OTP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-potm/" name="OTP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-potx/" name="OTP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-pps/" name="OTP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-ppsx/" name="OTP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-pptm/" name="OTP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-svg/" name="OTP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-tiff/" name="OTP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/merge/otp-to-xps/" name="OTP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
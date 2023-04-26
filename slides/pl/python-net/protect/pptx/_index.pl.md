---
title: Chroń pliki prezentacji PPTX za pomocą Python
url: /pl/python-net/protect/pptx/
keywords: Ochrona przed zapisem PPTX, szyfrowanie PPTX, blokada prezentacji PPTX, ochrona PPTX
description: Kod źródłowy Python do ochrony prezentacji PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zablokuj lub zabezpiecz hasłem PPTX za pomocą Python" h2="Twórz własne aplikacje Python, aby chronić pliki prezentacji za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ochrona prezentacji PPTX za pośrednictwem Python" %}}
Korzystając z Aspose.Slides for Python via .NET, możesz zabezpieczyć swoją prezentację PPTX przed otwarciem lub modyfikacją, ustawiając hasło. Następnie, aby otworzyć lub zmodyfikować zablokowaną prezentację, użytkownik musi podać hasło.
{{% blocks/products/pf/agp/code-block title="Szyfrowanie prezentacji PPTX za pomocą Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ustawianie ochrony przed zapisem w prezentacji PPTX za pomocą Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak zabezpieczyć hasłem PPTX za pośrednictwem Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, które należy wykonać, aby chronić pliki PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPTX z instancją Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chroń prezentację za pomocą klasy ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty ochrony" subTitle="Korzystając z Python, możesz również chronić następujące formaty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
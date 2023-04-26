---
title: Chroń pliki prezentacji PPT za pomocą Python
url: /pl/python-net/protect/ppt/
keywords: Ochrona przed zapisem PPT, szyfrowanie PPT, blokada prezentacji PPT, ochrona PPT
description: Kod źródłowy Python do ochrony prezentacji PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zablokuj lub zabezpiecz hasłem PPT za pomocą Python" h2="Twórz własne aplikacje Python, aby chronić pliki prezentacji za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ochrona prezentacji PPT za pośrednictwem Python" %}}
Korzystając z Aspose.Slides for Python via .NET, możesz zabezpieczyć swoją prezentację PPT przed otwarciem lub modyfikacją, ustawiając hasło. Następnie, aby otworzyć lub zmodyfikować zablokowaną prezentację, użytkownik musi podać hasło.
{{% blocks/products/pf/agp/code-block title="Szyfrowanie prezentacji PPT za pomocą Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ustawianie ochrony przed zapisem w prezentacji PPT za pomocą Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak zabezpieczyć hasłem PPT za pośrednictwem Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, które należy wykonać, aby chronić pliki PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj PPT z instancją Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chroń prezentację za pomocą klasy ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty ochrony" subTitle="Korzystając z Python, możesz również chronić następujące formaty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
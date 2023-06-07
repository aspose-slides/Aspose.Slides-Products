---
title: Odblokuj pliki prezentacji ODP za pomocą Python
url: /pl/python-net/unlock/odp/
keywords: Usuń ochronę przed zapisem ODP, odszyfruj ODP, odblokuj prezentację ODP, usuń ochronę ODP
description: Kod źródłowy Python usuwający ochronę z prezentacji ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Odblokuj ODP za pomocą Python" h2="Twórz własne aplikacje Python, aby usuwać hasła z programu PowerPoint i odszyfrowywać pliki prezentacji za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Usuwanie szyfrowania z ODP prezentacji przez Python" %}}
Korzystając z Aspose.Slides for Python via .NET, możesz usunąć szyfrowanie lub ochronę hasłem w prezentacji ODP. W ten sposób użytkownicy mogą uzyskiwać dostęp do prezentacji ODP lub ją modyfikować bez ograniczeń.
{{% blocks/products/pf/agp/code-block title="Wyłączanie ochrony hasłem z ODP przy użyciu Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.odp", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Usuwanie ochrony przed zapisem z ODP prezentacji za pomocą Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.odp") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.odp", slides.export.SaveFormat.ODP)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak usunąć hasło z ODP przez Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, które należy wykonać, aby usunąć ochronę plików ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj ODP z instancją Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Usuń ochronę przed zapisem przy użyciu klasy ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty" subTitle="Korzystając z Python, możesz również usunąć ochronę następujących formatów:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Chroń pliki prezentacji ODP za pomocą .NET
url: /pl/net/protect/odp/
keywords: Ochrona przed zapisem ODP, szyfrowanie ODP, blokada prezentacji ODP, ochrona ODP
description: Kod źródłowy C# do ochrony prezentacji ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zablokuj lub zabezpiecz hasłem ODP za pomocą C#" h2="Twórz własne aplikacje .NET, aby chronić pliki prezentacji za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ochrona prezentacji ODP za pośrednictwem C#" %}}
Korzystając z Aspose.Slides for .NET, możesz zabezpieczyć swoją prezentację ODP przed otwarciem lub modyfikacją, ustawiając hasło. Następnie, aby otworzyć lub zmodyfikować zablokowaną prezentację, użytkownik musi podać hasło.
{{% blocks/products/pf/agp/code-block title="Szyfrowanie prezentacji ODP za pomocą C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ustawianie ochrony przed zapisem w prezentacji ODP za pomocą C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak zabezpieczyć hasłem ODP za pośrednictwem C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, które należy wykonać, aby chronić pliki ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj ODP z instancją Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chroń prezentację za pomocą klasy ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik w formacie ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty ochrony" subTitle="Korzystając z C#, możesz również chronić następujące formaty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
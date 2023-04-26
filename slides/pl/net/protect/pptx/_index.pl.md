---
title: Chroń pliki prezentacji PPTX za pomocą .NET
url: /pl/net/protect/pptx/
keywords: Ochrona przed zapisem PPTX, szyfrowanie PPTX, blokada prezentacji PPTX, ochrona PPTX
description: Kod źródłowy C# do ochrony prezentacji PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zablokuj lub zabezpiecz hasłem PPTX za pomocą C#" h2="Twórz własne aplikacje .NET, aby chronić pliki prezentacji za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ochrona prezentacji PPTX za pośrednictwem C#" %}}
Korzystając z Aspose.Slides for .NET, możesz zabezpieczyć swoją prezentację PPTX przed otwarciem lub modyfikacją, ustawiając hasło. Następnie, aby otworzyć lub zmodyfikować zablokowaną prezentację, użytkownik musi podać hasło.
{{% blocks/products/pf/agp/code-block title="Szyfrowanie prezentacji PPTX za pomocą C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ustawianie ochrony przed zapisem w prezentacji PPTX za pomocą C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak zabezpieczyć hasłem PPTX za pośrednictwem C#" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty ochrony" subTitle="Korzystając z C#, możesz również chronić następujące formaty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
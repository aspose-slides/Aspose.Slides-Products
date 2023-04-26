---
title: Bescherm presentatiebestanden van PPT met .NET
url: /nl/net/protect/ppt/
keywords: Schrijfbeveiliging PPT, een PPT coderen, PPT-presentatie vergrendelen, PPT beschermen
description: C# broncode om PPT Presentatie te beschermen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vergrendel of beveilig PPT met C#" h2="Bouw uw eigen .NET-apps om presentatiebestanden te beschermen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Een PPT-presentatie beveiligen via C#" %}}
Met Aspose.Slides for .NET kunt u uw PPT-presentatie beschermen tegen openen of wijzigen door een wachtwoord in te stellen. Om vervolgens de vergrendelde presentatie te openen of te wijzigen, moet een gebruiker het wachtwoord opgeven.
{{% blocks/products/pf/agp/code-block title="Een PPT-presentatie versleutelen met C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Schrijfbeveiliging instellen op een PPT-presentatie met C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe PPT met een wachtwoord te beveiligen via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om PPT bestanden te beschermen." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPT met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bescherm de presentatie met de klasse ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPT formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde beveiligingsindelingen" subTitle="Met C# kunt u ook de volgende indelingen beveiligen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
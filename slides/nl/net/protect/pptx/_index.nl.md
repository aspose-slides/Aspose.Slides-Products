---
title: Bescherm presentatiebestanden van PPTX met .NET
url: /nl/net/protect/pptx/
keywords: Schrijfbeveiliging PPTX, een PPTX coderen, PPTX-presentatie vergrendelen, PPTX beschermen
description: C# broncode om PPTX Presentatie te beschermen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vergrendel of beveilig PPTX met C#" h2="Bouw uw eigen .NET-apps om presentatiebestanden te beschermen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Een PPTX-presentatie beveiligen via C#" %}}
Met Aspose.Slides for .NET kunt u uw PPTX-presentatie beschermen tegen openen of wijzigen door een wachtwoord in te stellen. Om vervolgens de vergrendelde presentatie te openen of te wijzigen, moet een gebruiker het wachtwoord opgeven.
{{% blocks/products/pf/agp/code-block title="Een PPTX-presentatie versleutelen met C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Schrijfbeveiliging instellen op een PPTX-presentatie met C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe PPTX met een wachtwoord te beveiligen via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om PPTX bestanden te beschermen." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPTX met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bescherm de presentatie met de klasse ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPTX formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde beveiligingsindelingen" subTitle="Met C# kunt u ook de volgende indelingen beveiligen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
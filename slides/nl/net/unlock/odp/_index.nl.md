---
title: Ontgrendel ODP presentatiebestanden met .NET
url: /nl/net/unlock/odp/
keywords: Schrijfbeveiliging ODP verwijderen, een ODP ontsleutelen, presentatie ODP ontgrendelen, beveiliging ODP opheffen
description: C# broncode om de beveiliging van ODP Presentatie te verwijderen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ontgrendel ODP met C#" h2="Bouw uw eigen .NET-apps om wachtwoorden uit PowerPoint te verwijderen en presentatiebestanden te decoderen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Versleuteling verwijderen uit ODP-presentatie via C#" %}}
Met Aspose.Slides for .NET kunt u de codering of wachtwoordbeveiliging op de ODP-presentatie verwijderen. Op deze manier kunnen gebruikers de ODP-presentatie zonder beperkingen openen of wijzigen.
{{% blocks/products/pf/agp/code-block title="Wachtwoordbeveiliging uitschakelen van ODP met C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.odp", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Schrijfbeveiliging verwijderen uit presentatie ODP met behulp van C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Wachtwoord verwijderen uit ODP via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om de beveiliging van ODP-bestanden te verwijderen." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad ODP met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwijder schrijfbeveiliging met de klasse ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in ODP formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde formaten" subTitle="Met C# kunt u ook de beveiliging van de volgende indelingen verwijderen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
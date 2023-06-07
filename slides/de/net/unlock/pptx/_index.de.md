---
title: Schalten Sie PPTX-Präsentationsdateien mit .NET frei
url: /de/net/unlock/pptx/
keywords: Schreibschutz PPTX entfernen, PPTX entschlüsseln, PPTX-Präsentation entsperren, PPTX-Schutz aufheben
description: C#-Quellcode zum Entfernen des Schutzes aus der PPTX-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Schalten Sie PPTX mit C# frei" h2="Erstellen Sie Ihre eigenen .NET-Apps, um Passwörter aus PowerPoint zu entfernen und Präsentationsdateien mithilfe serverseitiger APIs zu entschlüsseln." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Entfernen der Verschlüsselung aus der PPTX-Präsentation über C#" %}}
Mit Aspose.Slides for .NET können Sie die Verschlüsselung oder den Passwortschutz für die Präsentation PPTX entfernen. Auf diese Weise können Benutzer ohne Einschränkungen auf die PPTX-Präsentation zugreifen oder diese ändern.
{{% blocks/products/pf/agp/code-block title="Deaktivieren des Passwortschutzes von PPTX mit C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.pptx", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Schreibschutz aus der PPTX-Präsentation mit C# entfernen" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So entfernen Sie das Passwort aus PPTX über C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Entfernen des Schutzes von PPTX-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPTX mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Entfernen Sie den Schreibschutz mithilfe der ProtectionManager-Klasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format PPTX speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Formate" subTitle="Mit C# können Sie den Schutz auch von den folgenden Formaten entfernen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
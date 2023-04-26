---
title: ODP-Präsentationsdateien mit C++ schützen
url: /de/cpp/protect/odp/
keywords: Schreibschutz ODP, Verschlüsseln einer ODP, Sperren von ODP Präsentation, Schützen von ODP
description: C++-Quellcode zum Schutz der ODP-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ODP mit C++ sperren oder mit Passwort schützen" h2="Erstellen Sie Ihre eigenen C++-Apps, um Präsentationsdateien mit serverseitigen APIs zu schützen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Schützen einer ODP-Präsentation über C++" %}}
Mit Aspose.Slides for C++ können Sie Ihre ODP-Präsentation vor dem Öffnen oder Ändern schützen, indem Sie ein Passwort festlegen. Um die gesperrte Präsentation zu öffnen oder zu ändern, muss ein Benutzer dann das Kennwort eingeben.
{{% blocks/products/pf/agp/code-block title="Verschlüsseln einer ODP-Präsentation mit C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Festlegen des Schreibschutzes für eine ODP-Präsentation mit C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So schützen Sie ODP über C++ mit einem Passwort" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Schützen von ODP-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie ODP mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Schützen Sie die Präsentation mit der ProtectionManager-Klasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format ODP speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte geschützte Formate" subTitle="Mit C++ können Sie auch die folgenden Formate schützen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
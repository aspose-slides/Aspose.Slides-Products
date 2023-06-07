---
title: Schalten Sie ODP-Präsentationsdateien mit C++ frei
url: /de/cpp/unlock/odp/
keywords: Schreibschutz ODP entfernen, ODP entschlüsseln, ODP-Präsentation entsperren, ODP-Schutz aufheben
description: C++-Quellcode zum Entfernen des Schutzes aus der ODP-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Schalten Sie ODP mit C++ frei" h2="Erstellen Sie Ihre eigenen C++-Apps, um Passwörter aus PowerPoint zu entfernen und Präsentationsdateien mithilfe serverseitiger APIs zu entschlüsseln." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Entfernen der Verschlüsselung aus der ODP-Präsentation über C++" %}}
Mit Aspose.Slides for C++ können Sie die Verschlüsselung oder den Passwortschutz für die Präsentation ODP entfernen. Auf diese Weise können Benutzer ohne Einschränkungen auf die ODP-Präsentation zugreifen oder diese ändern.
{{% blocks/products/pf/agp/code-block title="Deaktivieren des Passwortschutzes von ODP mit C++" offSpacer="true" %}}

```cpp

auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"123123");
    
auto presentation = System::MakeObject<Presentation>(u"pres.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"encryption-removed.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Schreibschutz aus der ODP-Präsentation mit C++ entfernen" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So entfernen Sie das Passwort aus ODP über C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Entfernen des Schutzes von ODP-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie ODP mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Entfernen Sie den Schreibschutz mithilfe der ProtectionManager-Klasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format ODP speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Formate" subTitle="Mit C++ können Sie den Schutz auch von den folgenden Formaten entfernen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
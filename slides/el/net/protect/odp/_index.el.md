---
title: Προστασία αρχείων παρουσίασης ODP χρησιμοποιώντας .NET
url: /el/net/protect/odp/
keywords: Προστασία εγγραφής ODP, Κρυπτογράφηση παρουσίασης ODP, Κλείδωμα ODP, Προστασία ODP
description: Πηγαίος κώδικας C# για προστασία της παρουσίασης ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Κλείδωμα ή προστασία με κωδικό πρόσβασης ODP χρησιμοποιώντας C#" h2="Δημιουργήστε τις δικές σας εφαρμογές .NET για την προστασία των αρχείων παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Προστασία παρουσίασης ODP μέσω C#" %}}
Χρησιμοποιώντας το Aspose.Slides for .NET, μπορείτε να προστατέψετε την παρουσίασή σας ODP από άνοιγμα ή τροποποίηση ορίζοντας έναν κωδικό πρόσβασης. Στη συνέχεια, για να ανοίξει ή να τροποποιήσει την κλειδωμένη παρουσίαση, ο χρήστης πρέπει να δώσει τον κωδικό πρόσβασης.
{{% blocks/products/pf/agp/code-block title="Κρυπτογράφηση παρουσίασης ODP χρησιμοποιώντας C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ρύθμιση της προστασίας εγγραφής σε μια παρουσίαση ODP χρησιμοποιώντας C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος προστασίας με κωδικό πρόσβασης ODP μέσω C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την προστασία των αρχείων ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του ODP με μια παρουσία παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προστατέψτε την παρουσίαση χρησιμοποιώντας την κλάση ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές προστασίας" subTitle="Χρησιμοποιώντας το C#, μπορείτε επίσης να προστατεύσετε τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
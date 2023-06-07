---
title: Ξεκλείδωμα αρχείων παρουσίασης ODP χρησιμοποιώντας .NET
url: /el/net/unlock/odp/
keywords: Κατάργηση Προστασίας εγγραφής ODP, Αποκρυπτογράφηση μιας παρουσίασης ODP, Ξεκλείδωμα ODP Παρουσίασης, Κατάργηση προστασίας ODP
description: Πηγαίος κώδικας C# για κατάργηση προστασίας από την παρουσίαση ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ξεκλείδωμα ODP χρησιμοποιώντας C#" h2="Δημιουργήστε τις δικές σας εφαρμογές .NET για να καταργήσετε κωδικούς πρόσβασης από το PowerPoint και να αποκρυπτογραφήσετε τα αρχεία παρουσιάσεων χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Κατάργηση κρυπτογράφησης από την παρουσίαση ODP μέσω C#" %}}
Χρησιμοποιώντας το Aspose.Slides for .NET, μπορείτε να καταργήσετε την προστασία κρυπτογράφησης ή κωδικού πρόσβασης στην παρουσίαση ODP. Με αυτόν τον τρόπο, οι χρήστες μπορούν να έχουν πρόσβαση ή να τροποποιούν την παρουσίαση ODP χωρίς περιορισμούς.
{{% blocks/products/pf/agp/code-block title="Απενεργοποίηση προστασίας κωδικού πρόσβασης από ODP χρησιμοποιώντας C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.odp", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Κατάργηση προστασίας εγγραφής από την παρουσίαση ODP χρησιμοποιώντας C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να αφαιρέσετε τον κωδικό πρόσβασης από το ODP μέσω του C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την κατάργηση προστασίας από αρχεία ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του ODP με μια παρουσία παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Καταργήστε την προστασία εγγραφής χρησιμοποιώντας την κλάση ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές" subTitle="Χρησιμοποιώντας το C#, μπορείτε επίσης να καταργήσετε την προστασία από τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
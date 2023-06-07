---
title: Ξεκλείδωμα αρχείων παρουσίασης PPT χρησιμοποιώντας .NET
url: /el/net/unlock/ppt/
keywords: Κατάργηση Προστασίας εγγραφής PPT, Αποκρυπτογράφηση μιας παρουσίασης PPT, Ξεκλείδωμα PPT Παρουσίασης, Κατάργηση προστασίας PPT
description: Πηγαίος κώδικας C# για κατάργηση προστασίας από την παρουσίαση PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ξεκλείδωμα PPT χρησιμοποιώντας C#" h2="Δημιουργήστε τις δικές σας εφαρμογές .NET για να καταργήσετε κωδικούς πρόσβασης από το PowerPoint και να αποκρυπτογραφήσετε τα αρχεία παρουσιάσεων χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Κατάργηση κρυπτογράφησης από την παρουσίαση PPT μέσω C#" %}}
Χρησιμοποιώντας το Aspose.Slides for .NET, μπορείτε να καταργήσετε την προστασία κρυπτογράφησης ή κωδικού πρόσβασης στην παρουσίαση PPT. Με αυτόν τον τρόπο, οι χρήστες μπορούν να έχουν πρόσβαση ή να τροποποιούν την παρουσίαση PPT χωρίς περιορισμούς.
{{% blocks/products/pf/agp/code-block title="Απενεργοποίηση προστασίας κωδικού πρόσβασης από PPT χρησιμοποιώντας C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.ppt", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Κατάργηση προστασίας εγγραφής από την παρουσίαση PPT χρησιμοποιώντας C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να αφαιρέσετε τον κωδικό πρόσβασης από το PPT μέσω του C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την κατάργηση προστασίας από αρχεία PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του PPT με μια παρουσία παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Καταργήστε την προστασία εγγραφής χρησιμοποιώντας την κλάση ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές" subTitle="Χρησιμοποιώντας το C#, μπορείτε επίσης να καταργήσετε την προστασία από τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
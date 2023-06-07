---
title: Ξεκλείδωμα αρχείων παρουσίασης PPT χρησιμοποιώντας Java
url: /el/java/unlock/ppt/
keywords: Κατάργηση Προστασίας εγγραφής PPT, Αποκρυπτογράφηση μιας παρουσίασης PPT, Ξεκλείδωμα PPT Παρουσίασης, Κατάργηση προστασίας PPT
description: Πηγαίος κώδικας Java για κατάργηση προστασίας από την παρουσίαση PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ξεκλείδωμα PPT χρησιμοποιώντας Java" h2="Δημιουργήστε τις δικές σας εφαρμογές Java για να καταργήσετε κωδικούς πρόσβασης από το PowerPoint και να αποκρυπτογραφήσετε τα αρχεία παρουσιάσεων χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Κατάργηση κρυπτογράφησης από την παρουσίαση PPT μέσω Java" %}}
Χρησιμοποιώντας το Aspose.Slides for Java, μπορείτε να καταργήσετε την προστασία κρυπτογράφησης ή κωδικού πρόσβασης στην παρουσίαση PPT. Με αυτόν τον τρόπο, οι χρήστες μπορούν να έχουν πρόσβαση ή να τροποποιούν την παρουσίαση PPT χωρίς περιορισμούς.
{{% blocks/products/pf/agp/code-block title="Απενεργοποίηση προστασίας κωδικού πρόσβασης από PPT χρησιμοποιώντας Java" offSpacer="true" %}}

```java

LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");
Presentation presentation = new Presentation("pres.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Κατάργηση προστασίας εγγραφής από την παρουσίαση PPT χρησιμοποιώντας Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να αφαιρέσετε τον κωδικό πρόσβασης από το PPT μέσω του Java" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές" subTitle="Χρησιμοποιώντας το Java, μπορείτε επίσης να καταργήσετε την προστασία από τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
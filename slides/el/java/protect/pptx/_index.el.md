---
title: Προστασία αρχείων παρουσίασης PPTX χρησιμοποιώντας Java
url: /el/java/protect/pptx/
keywords: Προστασία εγγραφής PPTX, Κρυπτογράφηση παρουσίασης PPTX, Κλείδωμα PPTX, Προστασία PPTX
description: Πηγαίος κώδικας Java για προστασία της παρουσίασης PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Κλείδωμα ή προστασία με κωδικό πρόσβασης PPTX χρησιμοποιώντας Java" h2="Δημιουργήστε τις δικές σας εφαρμογές Java για την προστασία των αρχείων παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Προστασία παρουσίασης PPTX μέσω Java" %}}
Χρησιμοποιώντας το Aspose.Slides for Java, μπορείτε να προστατέψετε την παρουσίασή σας PPTX από άνοιγμα ή τροποποίηση ορίζοντας έναν κωδικό πρόσβασης. Στη συνέχεια, για να ανοίξει ή να τροποποιήσει την κλειδωμένη παρουσίαση, ο χρήστης πρέπει να δώσει τον κωδικό πρόσβασης.
{{% blocks/products/pf/agp/code-block title="Κρυπτογράφηση παρουσίασης PPTX χρησιμοποιώντας Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ρύθμιση της προστασίας εγγραφής σε μια παρουσίαση PPTX χρησιμοποιώντας Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος προστασίας με κωδικό πρόσβασης PPTX μέσω Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την προστασία των αρχείων PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του PPTX με μια παρουσία παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προστατέψτε την παρουσίαση χρησιμοποιώντας την κλάση ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές προστασίας" subTitle="Χρησιμοποιώντας το Java, μπορείτε επίσης να προστατεύσετε τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
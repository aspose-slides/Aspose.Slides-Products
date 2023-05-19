---
title: Αναζήτηση κειμένου σε PPT Αρχεία παρουσίασης χρησιμοποιώντας Java
url: /el/java/search/ppt/
keywords: αναζήτηση λέξεων σε PPT, αναζήτηση και αντικατάσταση κειμένου σε PPT, κείμενο αναζήτησης PPT Παρουσίαση
description: Πηγαίος κώδικας Java για αναζήτηση κειμένου στην παρουσίαση PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Αναζήτηση κειμένου PPT χρησιμοποιώντας Java" h2="Δημιουργήστε τις δικές σας εφαρμογές Java για αναζήτηση και αντικατάσταση κειμένου σε αρχεία παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή. Μάθετε πώς να βρίσκετε όλες τις εισόδους μιας συγκεκριμένης λέξης ή φράσης σε έγγραφα παρουσίασης. Αναζήτηση κειμένου με ακριβή αντιστοίχιση δεδομένων και αντιστοίχιση τυπικών εκφράσεων." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Αναζήτηση και αντικατάσταση κειμένου PPT Παρουσίαση μέσω Java" %}}
Μια βασική αναζήτηση εγγράφων και αντικατάσταση κειμένου σε περιεχόμενα, σχόλια, σημειώσεις διαφανειών ή μεταδεδομένα με API του Aspose.Slides for Java μπορεί να γίνει με λίγες μόνο γραμμές κώδικα. Χρησιμοποιήστε αντιστοίχιση τυπικών εκφράσεων, αντιστοίχιση πεζών-κεφαλαίων για αναζήτηση κειμένου στην παρουσίαση. Αναζήτηση κειμένου σε τίτλους, περιεχόμενο, υποσέλιδο ή κεφαλίδα.
{{% blocks/products/pf/agp/code-block title="Κείμενο αναζήτησης PPT Παρουσίαση με χρήση Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος αναζήτησης κειμένου σε PPT μέσω Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την αναζήτηση αρχείων κειμένου PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του PPT με μια παρουσία παρουσίασης.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Χρησιμοποιήστε τη μέθοδο [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) για να βρείτε και να αντικαταστήσετε κείμενο.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Διαδικτυακή αναζήτηση σε ζωντανές επιδείξεις PPT" sectionDescription="Αναζητήστε και αντικαταστήστε κείμενο σε περιεχόμενα, σχόλια ή μεταδεδομένα σε έγγραφα PPT αυτήν τη στιγμή." >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές αναζήτησης" subTitle="Χρησιμοποιώντας το Java, μπορείτε επίσης να αναζητήσετε κείμενο στις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
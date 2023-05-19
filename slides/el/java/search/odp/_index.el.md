---
title: Αναζήτηση κειμένου σε ODP Αρχεία παρουσίασης χρησιμοποιώντας Java
url: /el/java/search/odp/
keywords: αναζήτηση λέξεων σε ODP, αναζήτηση και αντικατάσταση κειμένου σε ODP, κείμενο αναζήτησης ODP Παρουσίαση
description: Πηγαίος κώδικας Java για αναζήτηση κειμένου στην παρουσίαση ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Αναζήτηση κειμένου ODP χρησιμοποιώντας Java" h2="Δημιουργήστε τις δικές σας εφαρμογές Java για αναζήτηση και αντικατάσταση κειμένου σε αρχεία παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή. Μάθετε πώς να βρίσκετε όλες τις εισόδους μιας συγκεκριμένης λέξης ή φράσης σε έγγραφα παρουσίασης. Αναζήτηση κειμένου με ακριβή αντιστοίχιση δεδομένων και αντιστοίχιση τυπικών εκφράσεων." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Αναζήτηση και αντικατάσταση κειμένου ODP Παρουσίαση μέσω Java" %}}
Μια βασική αναζήτηση εγγράφων και αντικατάσταση κειμένου σε περιεχόμενα, σχόλια, σημειώσεις διαφανειών ή μεταδεδομένα με API του Aspose.Slides for Java μπορεί να γίνει με λίγες μόνο γραμμές κώδικα. Χρησιμοποιήστε αντιστοίχιση τυπικών εκφράσεων, αντιστοίχιση πεζών-κεφαλαίων για αναζήτηση κειμένου στην παρουσίαση. Αναζήτηση κειμένου σε τίτλους, περιεχόμενο, υποσέλιδο ή κεφαλίδα.
{{% blocks/products/pf/agp/code-block title="Κείμενο αναζήτησης ODP Παρουσίαση με χρήση Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος αναζήτησης κειμένου σε ODP μέσω Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την αναζήτηση αρχείων κειμένου ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του ODP με μια παρουσία παρουσίασης.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Χρησιμοποιήστε τη μέθοδο [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) για να βρείτε και να αντικαταστήσετε κείμενο.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Διαδικτυακή αναζήτηση σε ζωντανές επιδείξεις ODP" sectionDescription="Αναζητήστε και αντικαταστήστε κείμενο σε περιεχόμενα, σχόλια ή μεταδεδομένα σε έγγραφα ODP αυτήν τη στιγμή." >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές αναζήτησης" subTitle="Χρησιμοποιώντας το Java, μπορείτε επίσης να αναζητήσετε κείμενο στις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
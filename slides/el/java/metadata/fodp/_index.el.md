---
title: Προβολή ή επεξεργασία μεταδεδομένων αρχείων FODP χρησιμοποιώντας Java
url: /el/java/metadata/fodp/
keywords: Επεξεργασία μεταδεδομένων FODP, Προβολή μεταδεδομένων FODP, Επεξεργασία ιδιοτήτων FODP, Προβολή ιδιοτήτων FODP
description: Πηγαίος κώδικας Java για επεξεργασία ή προβολή μεταδεδομένων μορφής FODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Επεξεργασία ιδιοτήτων FODP χρησιμοποιώντας Java" h2="Δημιουργήστε τις δικές σας εφαρμογές Java για να τροποποιήσετε τις Ενσωματωμένες και Προσαρμοσμένες ιδιότητες σε αρχεία παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="FODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Τροποποίηση ιδιοτήτων FODP μέσω Java" %}}
Χρησιμοποιώντας το Aspose.Slides for Java, οι προγραμματιστές μπορούν να έχουν πρόσβαση και να τροποποιούν τις τιμές των ενσωματωμένων ιδιοτήτων καθώς και των προσαρμοσμένων ιδιοτήτων. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν την ιδιότητα [DocumentProperties](https://reference.aspose.com/slides/java/com.aspose.slides/documentproperties/) που εκτίθεται από το αντικείμενο Παρουσίασης για να αποκτήσουν πρόσβαση στις ιδιότητες του εγγράφου του αρχείου παρουσίασης.
{{% blocks/products/pf/agp/code-block title="Τροποποίηση ενσωματωμένων ιδιοτήτων FODP - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation("Presentation.fodp");
try {
    // Create a reference to IDocumentProperties object associated with Presentation
    IDocumentProperties dp = pres.getDocumentProperties();
    
    // Set the built-in properties
    dp.setAuthor("Aspose.Slides for Java");
    dp.setTitle("Modifying Presentation Properties");
    dp.setSubject("Aspose Subject");
    dp.setComments("Aspose Description");
    dp.setManager("Aspose Manager");
    
    // Save your presentation to a file
    pres.save("DocProps.fodp", SaveFormat.Fodp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Προσθήκη προσαρμοσμένων ιδιοτήτων στο FODP - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    // Getting Document Properties
    IDocumentProperties dProps = pres.getDocumentProperties();
    
    // Adding Custom properties
    dProps.set_Item("New Custom", 12);
    dProps.set_Item("My Name", "Aspose Metadata Editor");
    dProps.set_Item("Custom", 124);
    
    // Getting property name at particular index
    String getPropertyName = dProps.getCustomPropertyName(2);
    
    // Removing selected property
    dProps.removeCustomProperty(getPropertyName);
    
    // Saving presentation
    pres.save("CustomDemo.fodp", SaveFormat.Fodp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος εξαγωγής μεταδεδομένων του FODP μέσω του Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την εξαγωγή μεταδεδομένων από αρχεία FODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε την κλάση Presentation με διαδρομή προς το αρχείο FODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Λήψη αντικειμένου DocumentProperties που σχετίζεται με την Παρουσίαση
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κάντε βρόχο πάνω από τα στοιχεία στο αντικείμενο DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Πρόσβαση και τροποποίηση προσαρμοσμένων ιδιοτήτων
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές μεταδεδομένων" subTitle="Χρησιμοποιώντας το Java, μπορείτε επίσης να χειριστείτε μεταδεδομένα πολλών άλλων μορφών, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
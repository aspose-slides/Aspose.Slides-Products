---
title: Καταργήστε το ODP Annotation χρησιμοποιώντας Java
weight: 1790
url: /el/java/annotation/odp/ 
description: Δείγμα κώδικα Java για τη διαγραφή σχολιασμών μορφής ODP στο Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Καταργήστε τα σχόλια και τους συντάκτες σχολίων από το ODP σε Java" h2="Δημιουργήστε τις δικές σας εφαρμογές Java για να χειρίζεστε σχόλια και συγγραφείς σε αρχεία εγγράφων χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Κατάργηση σχολίων από το ODP μέσω Java" %}}
Για να καταργήσουμε τους σχολιασμούς από το αρχείο ODP, θα χρησιμοποιήσουμε το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/) API που είναι πλούσιο σε χαρακτηριστικά, ισχυρό και εύκολο στη χρήση API χειρισμού εγγράφων για πλατφόρμα Java.
{{% blocks/products/pf/agp/code-block title="Διαγραφή σχολιασμών από ODP - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.odp");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να αφαιρέσετε σχόλια από το ODP μέσω Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για Java**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε το ODP με μια παρουσία της κλάσης παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Επανάληψη σε όλους τους Συντάκτες του φορτωμένου ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κατάργηση όλων των σχολίων ενός συγγραφέα
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κατάργηση όλων των Συντακτών στο τέλος
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές σχολιασμού" subTitle="Χρησιμοποιώντας Java, μπορεί κανείς εύκολα να σχολιάσει άλλες μορφές, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
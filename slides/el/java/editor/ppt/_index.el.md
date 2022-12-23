---
title: Επεξεργασία PPT σε Java
url: /el/java/editor/ppt/
keywords: Επεξεργασία PPT, Επεξεργασία PowerPoint, PPT, PowerPoint, Java API, Βιβλιοθήκη Java
description: Επεξεργασία PPT σε Java. Χρησιμοποιήστε το Java Library API για να επεξεργαστείτε την παρουσίαση του PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Επεξεργασία PPT σε Java" h2="Βιβλιοθήκη Java υψηλής ταχύτητας και πολλαπλών πλατφορμών για επεξεργασία PPT με χρήση κώδικα Java" >}}

{{% blocks/products/pf/feature-page-section h2="Επεξεργαστείτε το PPT χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for Java**](https://products.aspose.com/slides/el/java/) είναι μια ισχυρή βιβλιοθήκη Java που χρησιμοποιείται για το χειρισμό και την επεξεργασία παρουσιάσεων. Μπορείτε να επεξεργαστείτε μια παρουσίαση PPT προσθέτοντας μια νέα γραμμή κειμένου σε αυτήν. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Επεξεργασία PPT σε Java" %}}
Χρησιμοποιώντας το [**Aspose.Slides for Java**](https://products.aspose.com/slides/el/java/), μπορείτε να προσθέσετε μια νέα γραμμή κειμένου σε ένα έγγραφο PPT με λίγες μόνο γραμμές κώδικα.

{{% blocks/products/pf/agp/code-block title="Κώδικας Java για επεξεργασία PPT" offSpacer="true" %}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να επεξεργαστείτε το PPT σε Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για Java**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε την παρουσίαση PPT που θέλετε να επεξεργαστείτε.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια νέα γραμμή κειμένου.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αλλαγμένο αρχείο PowerPoint.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Επεξεργαστείτε άλλα αρχεία" subTitle="Μπορείτε επίσης να επεξεργαστείτε αρχεία σε άλλες μορφές" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
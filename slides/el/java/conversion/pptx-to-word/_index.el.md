---
title: Μετατροπή PPTX σε Word σε Java
url: /el/java/conversion/pptx-to-word/
keywords: Μετατροπή PPTX σε Word, PPTX σε Word, PPTX σε DOC, PowerPoint σε Word, Java API, Java Library
description: Μετατροπή PPTX σε Word σε Java. Χρησιμοποιήστε το Java Library API για να μετατρέψετε το PowerPoint σε Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατροπή PPTX σε Word σε Java" h2="Ισχυρό cross-platform Java API για μετατροπή PowerPoint σε Word χρησιμοποιώντας κώδικα Java χωρίς Microsoft PowerPoint ή Office" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή PowerPoint σε Word χρησιμοποιώντας Aspose.Slides και Aspose.Words" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/el/java/) και [**Aspose.Words for Java**](https://products.aspose.com/ words/java/) είναι ισχυρές βιβλιοθήκες Java που χρησιμοποιούνται για το χειρισμό και τη μετατροπή παρουσιάσεων PowerPoint, εγγράφων του Word και άλλων αρχείων. Όταν μετατρέπετε το PowerPoint σε Word, ουσιαστικά μετακινείτε τα περιεχόμενα των διαφανειών μιας παρουσίασης σε σελίδες ενός εγγράφου του Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PowerPoint σε Word σε Java" %}}
Μπορείτε να μετατρέψετε το PPTX σε Word γρήγορα με λίγες μόνο γραμμές κώδικα

{{% blocks/products/pf/agp/code-block title="Κώδικας Java για τη μετατροπή του PowerPoint σε Word" offSpacer="true" %}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να μετατρέψετε το PPTX σε Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε τα **Aspose.Slides για Java** και **Aspose.Words για Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε μια παρουσία της κλάσης Presentation και της τάξης Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε την παρουσίαση PPTX που θέλετε να μετατρέψετε σε Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε εικόνες και κείμενα με βάση το περιεχόμενο των διαφανειών.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το έγγραφο του Word που προκύπτει.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Δωρεάν Online Μετατροπέας" sectionDescription="[Πώς να μετατρέψετε το PPT σε HTML στην Python](https://products.aspose.com/slides/el/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το PowerPoint σε αρχεία σε άλλες μορφές" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Μετατροπή HTML σε JPG σε Java
url: /el/java/conversion/html-to-jpg/
keywords: HTML σε JPG, Convert HTML σε JPG, Java API, Java Library, HTML, JPG
description: Μετατροπή HTML σε JPG σε Java. Χρησιμοποιήστε το Java Library API για να μετατρέψετε αρχεία HTML σε JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατροπή HTML σε JPG σε Java" h2="Βιβλιοθήκη Java υψηλής ταχύτητας και πολλαπλών πλατφορμών που βοηθά στην ανάπτυξη εφαρμογών με δυνατότητα δημιουργίας, συγχώνευσης, επιθεώρησης ή μετατροπής αρχείων παρουσίασης Microsoft PowerPoint και OpenOffice χωρίς τη χρήση λογισμικού όπως Microsoft ή Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή HTML σε JPG σε Java" %}}

Το [**Aspose.Slides for Java**](https://products.aspose.com/slides/el/java/) είναι μια ισχυρή βιβλιοθήκη Java για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του HTML σε JPG. Χρησιμοποιώντας το **Aspose.Slides για Java**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία HTML σε JPG με λίγες μόνο γραμμές κώδικα Java.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides για Java εξάγει αρχεία HTML σε μορφές αρχείων JPG γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το HTML σε JPG και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε το HTML σε JPG χρησιμοποιώντας Java" %}}
Για να μετατρέψετε το HTML σε JPG, θα χρειαστεί να δημιουργήσετε Παρουσίαση από το αρχείο HTML και να το αποθηκεύσετε ως JPG.

{{% blocks/products/pf/agp/code-block title="Κώδικας Java για μετατροπή HTML σε JPG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να μετατρέψετε το HTML σε JPG χρησιμοποιώντας το Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για τη μετατροπή του HTML σε JPG σε Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το [**Aspose.Slides για Java**](https://products.aspose.com/slides/el/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο σας Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ανοίξτε τα αρχεία πηγής HTML σε Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αποτέλεσμα ως αρχείο JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Δωρεάν Online Μετατροπέας" sectionDescription="[Πώς να μετατρέψετε το PPT σε HTML στην Python](https://products.aspose.com/slides/el/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Μετατροπή HTML σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το HTML και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
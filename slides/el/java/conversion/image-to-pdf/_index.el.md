---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή Image σε PDF σε Java
url: /el/java/conversion/image-to-pdf/
keywords: Image σε PDF, Convert Image σε PDF, Java API, Java Library, Image, PDF
description: Μετατροπή Image σε PDF σε Java. Χρησιμοποιήστε το Java Library API για να μετατρέψετε αρχεία Image σε PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή Image σε PDF σε Java" h2="Βιβλιοθήκη Java υψηλής ταχύτητας και πολλαπλών πλατφορμών που βοηθά στην ανάπτυξη εφαρμογών με δυνατότητα δημιουργίας, συγχώνευσης, επιθεώρησης ή μετατροπής αρχείων παρουσίασης Microsoft PowerPoint και OpenOffice χωρίς τη χρήση λογισμικού όπως Microsoft ή Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατρέψτε το Image σε PDF χρησιμοποιώντας Java" variant="code" %}}

Για να μετατρέψετε το Image σε PDF, θα χρειαστεί να δημιουργήσετε Παρουσίαση από το αρχείο Image και να το αποθηκεύσετε ως PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας Java για μετατροπή Image σε PDF" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή Image σε PDF σε Java" %}}

Το [**Aspose.Slides for Java**](https://products.aspose.com/slides/el/java/) είναι μια ισχυρή βιβλιοθήκη Java για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του Image σε PDF. Χρησιμοποιώντας το **Aspose.Slides για Java**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία Image σε PDF με λίγες μόνο γραμμές κώδικα Java.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides για Java εξάγει αρχεία Image σε μορφές αρχείων PDF γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το Image σε PDF και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το Image σε PDF χρησιμοποιώντας το Aspose.Slides for Java API" intro="Αυτά είναι τα βήματα για τη μετατροπή του Image σε PDF σε Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το [**Aspose.Slides για Java**](https://products.aspose.com/slides/el/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο σας Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε τα αρχεία πηγής Image σε Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αποτέλεσμα ως αρχείο PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Δημιουργήθηκε με το Aspose.Slides" title="Μετατροπή Εικόνα σε PDF online" description="Η δωρεάν εφαρμογή Aspose.Slides Conversion έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία Εικόνα." button="Άνοιγμα Aspose.Slides Conversion" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" upload="Σύρετε ή ανεβάστε το αρχείο σας" saveAs="Αποθήκευση ως" convert="Μετατροπή" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides μετατρέπει αρχεία πριν γράψετε κώδικα.
- Ανεβάστε αρχεία Εικόνα και αποθηκεύστε τα ως PDF.
- Κατεβάστε το αποτέλεσμα ή μετατρέψτε περισσότερα αρχεία.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Μετατροπή Image σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το Image και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

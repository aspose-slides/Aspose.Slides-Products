---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή Image σε PDF σε PHP
url: /el/php-java/conversion/image-to-pdf/
keywords: Image σε PDF, Convert Image σε PDF, PHP API, PHP Library, Image, PDF
description: Μετατροπή Image σε PDF σε PHP. Χρησιμοποιήστε το PowerPoint PHP API για να μετατρέψετε αρχεία Image σε PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή Image σε PDF σε PHP" h2="Ισχυρή βιβλιοθήκη PowerPoint PHP που βοηθά στην ανάπτυξη εφαρμογών με τη δυνατότητα δημιουργίας, συγχώνευσης, επιθεώρησης ή μετατροπής αρχείων παρουσίασης Microsoft PowerPoint και OpenOffice χωρίς τη χρήση λογισμικού όπως Microsoft ή Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή Image σε PDF χρησιμοποιώντας PHP" variant="code" %}}

Για να μετατρέψετε το Image σε PDF, θα χρειαστεί να δημιουργήσετε Παρουσίαση από το αρχείο Image και να το αποθηκεύσετε ως PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας PHP για μετατροπή Image σε PDF" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή Image σε PDF σε PHP" %}}

Το [**Aspose.Slides για PHP μέσω Java**](https://products.aspose.com/slides/el/php-java/) είναι μια ισχυρή βιβλιοθήκη PHP για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του Image σε PDF. Χρησιμοποιώντας το **Aspose.Slides για PHP μέσω Java**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία Image σε PDF με λίγες μόνο γραμμές κώδικα PHP.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides για PHP εξάγει αρχεία Image σε μορφές αρχείων PDF γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το Image σε PDF και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το Image σε PDF χρησιμοποιώντας το Aspose.Slides for PHP API" intro="Αυτά είναι τα βήματα για τη μετατροπή του Image σε PDF στην PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το [**Aspose.Slides για PHP μέσω Java**](https://products.aspose.com/slides/el/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο PHP σας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε τα αρχεία πηγής Image στην PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αποτέλεσμα ως αρχείο PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Δωρεάν Online Μετατροπέας"
  description="[Πώς να μετατρέψετε το PPT σε HTML στην Python](https://products.aspose.com/slides/el/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Μετατροπή Image σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το Image και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

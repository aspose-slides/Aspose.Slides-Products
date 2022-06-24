---
title: Μετατροπή παρουσίασης Microsoft PowerPoint σε PDF σε PHP
url: /el/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API για μετατροπή PPT σε PDF. Μετατροπή Παρουσιάσεων σε JPG, PNG και άλλες μορφές σε PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή Microsoft<sup>®</sup> PowerPoint σε PDF σε PHP" h2="Πηγαίοι κώδικες PHP για διαφορετικές περιπτώσεις μετατροπής για μετατροπή PPT σε PDF, PNG, HTML, JPEG, PPTX και άλλες μορφές." >}}

{{% blocks/products/pf/feature-page-summary %}}

Το [Aspose.Slides για PHP μέσω Java](https://products.aspose.com/slides/el/php-java/) είναι μια ισχυρή βιβλιοθήκη κλάσης εσωτερικής εγκατάστασης που χρησιμοποιείται για επεξεργασία και εργασία με παρουσιάσεις. Είναι εύκολο για τους προγραμματιστές να μετατρέψουν το PowerPoint σε PDF με ταχύτητα και ακρίβεια. Λάβετε τα αποτελέσματα σε χρόνο μηδέν για την αυτοματοποίηση των επιχειρηματικών διαδικασιών. Εδώ συζητάμε μερικές περιπτώσεις για ανάγνωση ή φόρτωση οποιασδήποτε εισόδου [υποστηριζόμενες μορφές PowerPoint](https://docs.aspose.com/slides/php-java/supported-file-formats/) και εγγραφή ή αποθήκευση σε οποιαδήποτε υποστηριζόμενη μορφή εξόδου . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PowerPoint σε PDF σε PHP" %}}
Το [Aspose.Slides](https://products.aspose.com/slides/el/php-java/) σάς επιτρέπει να μετατρέπετε αρχεία σε μορφές PowerPoint PPT, PPTX και OpenOffice ODP σε PDF. Για να μετατρέψετε μια παρουσίαση σε PDF, απλώς περάστε το όνομα του αρχείου και αποθηκεύστε τη μορφή στη μέθοδο «Presentation.save». Η κλάση «Παρουσίαση» εκθέτει τη μέθοδο «αποθήκευση» που μπορεί να κληθεί για να μετατρέψει ολόκληρη την παρουσίαση PPT, PPTX ή ODP σε έγγραφο PDF.

{{% blocks/products/pf/feature-page-code h3="Μετατροπή PHP PowerPoint σε PDF" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.pdf", SaveFormat::Pdf); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf potm-to-pdf potx-to-pdf ppsm-to-pdf odp-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PDF σε PPT σε PHP" %}}
Το [Aspose.Slides](https://products.aspose.com/slides/el/php-java/) σάς επιτρέπει να εισάγετε παρουσιάσεις από αρχεία PDF. Ουσιαστικά, μπορείτε να μετατρέψετε ένα PDF σε παρουσίαση PowerPoint. Για να μετατρέψετε PDF σε Powerpoint, ακολουθήστε αυτά τα βήματα:
- Δημιουργήστε ένα αντικείμενο της κλάσης «Presentation».
- Καλέστε τη μέθοδο «addFromPdf» και περάστε το αρχείο PDF.
- Χρησιμοποιήστε τη μέθοδο «αποθήκευση» για να αποθηκεύσετε το αρχείο σε μορφή PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Μετατροπή PHP PDF σε Powerpoint" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    $pres->save("output.pptx", SaveFormat::Pptx); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-ppt pdf-to-pptx pdf-to-odp pdf-to-png pdf-to-jpg pdf-to-html" >}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PPT σε PDF με προσαρμοσμένες επιλογές σε PHP" %}}

Για τη μετατροπή των διαφανειών του PowerPoint σε PDF με ακρίβεια, οι προγραμματιστές μπορούν να φορτώσουν το έγγραφο χρησιμοποιώντας την κλάση «Presentation» και να χρησιμοποιήσουν την κατηγορία «PdfOptions» για όλες τις συγκεκριμένες και προσαρμοσμένες επιλογές όπως το επίπεδο συμπίεσης κειμένου, η ποιότητα Jpeg, η συμπεριφορά των μετα-αρχείων, η μετατροπή κρυφών διαφανειών καθώς και η επιλογή συγκεκριμένες διαφάνειες και άλλα. Ακόμη και υπάρχει η επιλογή προστασίας του αρχείου PDF που έχει μετατραπεί με κωδικό πρόσβασης.
{{% blocks/products/pf/feature-page-code h3="Μετατροπή PHP PowerPoint σε PDF με προσαρμοσμένες ρυθμίσεις" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\PdfOptions;
use aspose\slides\PdfTextCompression;
use aspose\slides\PdfCompliance;
 
$pres = new Presentation("input.pptx");
try
{
    $pdfOptions = new PdfOptions();
    $pdfOptions->setJpegQuality(90);
    $pdfOptions->setSaveMetafilesAsPng(true);
    $pdfOptions->setTextCompression(PdfTextCompression::Flate);
    $pdfOptions->setCompliance(PdfCompliance::Pdf15);
    $pres->save("output.pdf", SaveFormat::Pdf, $pdfOptions);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή Microsoft PowerPoint σε HTML σε PHP" %}}
Όταν χρειάζεται να ενσωματωθούν παρουσιάσεις σε ιστοσελίδες, τότε χρειάζεται να μετατραπούν οι διαφάνειες σε HTML. 
{{% blocks/products/pf/feature-page-code h3="Κώδικας PHP για μετατροπή PowerPoint σε HTML" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\Html5Options;
 
$pres = new Presentation("input.pptx");
try
{
    $html5Options = new Html5Options();
    $html5Options->setAnimateShapes(false);
    $html5Options->setAnimateTransitions(false);
    $pres->save("output.html", SaveFormat::Html5, $html5Options);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PowerPoint σε JPG" %}}
Η μετατροπή μορφών Microsoft<sup>®</sup> PowerPoint σε εικόνες JPEG, PNG, TIFF κ.λπ. είναι μια άλλη συνηθισμένη περίπτωση χρήσης που χρησιμοποιείται κυρίως για τη δημιουργία μικρογραφιών διαφανειών. 
{{% blocks/products/pf/feature-page-code h3="Κώδικας μετατροπέα PHP PPT σε JPG" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
 
$pres = new Presentation("input.pptx");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(1, 1);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPEG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>  
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-jpg pptx-to-jpg ppt-to-png pptx-to-png ppt-to-gif pptx-to-gif" >}}
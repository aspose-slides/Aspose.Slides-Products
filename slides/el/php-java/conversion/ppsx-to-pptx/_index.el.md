---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή PPSX σε PPTX σε PHP
weight: 2060
url: /el/php-java/conversion/ppsx-to-pptx/ 
keywords: "Convert, PowerPoint, PPSX, PPTX, Presentation, PHP"
description: Δείγμα κώδικα για μετατροπή PHP από PPSX σε PPTX. Χρησιμοποιήστε το PowerPoint PHP API για ομαδική μετατροπή αρχείων PPSX σε αρχεία PPTX.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή PPSX σε PPTX σε PHP" h2="Ισχυρή βιβλιοθήκη PHP PowerPoint για μετατροπή PPSX σε PPTX"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή PPSX σε PPTX σε PHP" %}}

Θέλετε να μετατρέψετε αρχεία PPSX σε PPTX μέσω προγραμματισμού; Χρησιμοποιώντας το [*Aspose.Slides για PHP μέσω Java*](https://products.aspose.com/slides/el/php-java/) οποιοσδήποτε προγραμματιστής μπορεί να μετατρέψει τη μορφή PPSX σε PPTX με λίγες μόνο γραμμές κώδικα PHP .

Ως σύγχρονο API επεξεργασίας παρουσιάσεων, το Aspose.Slides για PHP δημιουργεί γρήγορα το PPTX από το PPSX. Δοκιμάστε την ποιότητα της μετατροπής PPSX σε PPTX απευθείας στο [browser] σας (https://products.aspose.app/slides/conversion). Η βιβλιοθήκη Aspose PowerPoint PPTX σάς επιτρέπει να μετατρέπετε αρχεία PPSX σε πολλές δημοφιλείς μορφές.

Μπορείτε να εγκαταστήσετε τη βιβλιοθήκη από το [Composer](https://packagist.org/packages/aspose/slides) χρησιμοποιώντας την ακόλουθη εντολή:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Κονσόλα/Τερματικό" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Αποθηκεύστε το PPSX ως PPTX στην PHP" %}}

Χρησιμοποιήστε τη δωρεάν εφαρμογή για να δείτε μια επίδειξη της διαδικασίας μετατροπής PPSX σε PPTX.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή PHP PPSX σε PPTX" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsx");
try
{
    $pres->save("output.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το PPSX σε PPTX στην PHP" intro="Αυτά είναι τα βήματα για να μετατρέψετε ένα αρχείο PPSX σε PPTX χρησιμοποιώντας PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φόρτωση αρχείου PPSX με μια παρουσία της κλάσης Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο «αποθήκευση» καθορίζοντας τη διαδρομή του αρχείου εξόδου και το SaveFormat.PPTX ως παραμέτρους.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Το αρχείο PPSX θα αποθηκευτεί στην καθορισμένη διαδρομή{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Απαιτήσεις συστήματος" intro="Πριν εκτελέσετε το δείγμα πηγαίου κώδικα μετατροπής PHP, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε την PHP 7, προσθέστε διαδρομή προς την PHP στη μεταβλητή «PATH» του συστήματος και ορίστε το «allow_url_include» σε «On» στο αρχείο «php.ini».{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το JRE 8. Ορίστε τη μεταβλητή περιβάλλοντος «JAVA_HOME» ως διαδρομή προς την εγκατεστημένη θέση JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το Apache Tomcat 8.0 (δείτε [περισσότερα](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Δημιουργήθηκε με το Aspose.Slides" title="Μετατροπή PPSX σε PPTX online" description="Η δωρεάν εφαρμογή Aspose.Slides Conversion έχει δημιουργηθεί με το [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/el/php-java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPSX." button="Άνοιγμα Aspose.Slides Conversion" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" upload="Σύρετε ή ανεβάστε το αρχείο σας" saveAs="Αποθήκευση ως" convert="Μετατροπή" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides μετατρέπει αρχεία πριν γράψετε κώδικα.
- Ανεβάστε αρχεία PPSX και αποθηκεύστε τα ως PPTX.
- Κατεβάστε το αποτέλεσμα ή μετατρέψτε περισσότερα αρχεία.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το PPSX σε πολλές άλλες μορφές αρχείων. Δείτε άλλες υποστηριζόμενες μετατροπές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Εικόνα Bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="Επίπεδη παρουσίαση XML OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="Εικόνα JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Μορφή παρουσίασης OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Τυπική μορφή OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Μορφή φορητού εγγράφου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Φορητά γραφικά δικτύου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="Μορφή SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Προδιαγραφές χαρτιού XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

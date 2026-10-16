---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή PPTM σε POTX σε PHP
weight: 2430
url: /el/php-java/conversion/pptm-to-potx/ 
keywords: "Convert, PowerPoint, PPTM, POTX, Presentation, PHP"
description: Δείγμα κώδικα για μετατροπή PHP από PPTM σε POTX. Χρησιμοποιήστε το PowerPoint PHP API για ομαδική μετατροπή αρχείων PPTM σε αρχεία POTX.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή PPTM σε POTX σε PHP" h2="Ισχυρή βιβλιοθήκη PHP PowerPoint για μετατροπή PPTM σε POTX"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή PPTM σε POTX σε PHP" %}}

Θέλετε να μετατρέψετε αρχεία PPTM σε POTX μέσω προγραμματισμού; Χρησιμοποιώντας το [*Aspose.Slides για PHP μέσω Java*](https://products.aspose.com/slides/el/php-java/) οποιοσδήποτε προγραμματιστής μπορεί να μετατρέψει τη μορφή PPTM σε POTX με λίγες μόνο γραμμές κώδικα PHP .

Ως σύγχρονο API επεξεργασίας παρουσιάσεων, το Aspose.Slides για PHP δημιουργεί γρήγορα το POTX από το PPTM. Δοκιμάστε την ποιότητα της μετατροπής PPTM σε POTX απευθείας στο [browser] σας (https://products.aspose.app/slides/conversion). Η βιβλιοθήκη Aspose PowerPoint PPTX σάς επιτρέπει να μετατρέπετε αρχεία PPTM σε πολλές δημοφιλείς μορφές.

Μπορείτε να εγκαταστήσετε τη βιβλιοθήκη από το [Composer](https://packagist.org/packages/aspose/slides) χρησιμοποιώντας την ακόλουθη εντολή:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Κονσόλα/Τερματικό" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Αποθηκεύστε το PPTM ως POTX στην PHP" %}}

Χρησιμοποιήστε τη δωρεάν εφαρμογή για να δείτε μια επίδειξη της διαδικασίας μετατροπής PPTM σε POTX.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή PHP PPTM σε POTX" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    $pres->save("output.potx", SaveFormat::Potx);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το PPTM σε POTX στην PHP" intro="Αυτά είναι τα βήματα για να μετατρέψετε ένα αρχείο PPTM σε POTX χρησιμοποιώντας PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φόρτωση αρχείου PPTM με μια παρουσία της κλάσης Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο «αποθήκευση» καθορίζοντας τη διαδρομή του αρχείου εξόδου και το SaveFormat.POTX ως παραμέτρους.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Το αρχείο PPTM θα αποθηκευτεί στην καθορισμένη διαδρομή{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Απαιτήσεις συστήματος" intro="Πριν εκτελέσετε το δείγμα πηγαίου κώδικα μετατροπής PHP, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε την PHP 7, προσθέστε διαδρομή προς την PHP στη μεταβλητή «PATH» του συστήματος και ορίστε το «allow_url_include» σε «On» στο αρχείο «php.ini».{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το JRE 8. Ορίστε τη μεταβλητή περιβάλλοντος «JAVA_HOME» ως διαδρομή προς την εγκατεστημένη θέση JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το Apache Tomcat 8.0 (δείτε [περισσότερα](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTM to POTX"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το PPTM σε πολλές άλλες μορφές αρχείων. Δείτε άλλες υποστηριζόμενες μετατροπές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Εικόνα Bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="Επίπεδη παρουσίαση XML OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="Εικόνα JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Μορφή παρουσίασης OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Τυπική μορφή OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Μορφή φορητού εγγράφου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Φορητά γραφικά δικτύου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Μορφή SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Προδιαγραφές χαρτιού XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

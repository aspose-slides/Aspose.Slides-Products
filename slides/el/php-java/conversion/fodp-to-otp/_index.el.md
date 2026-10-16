---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή FODP σε OTP σε PHP
weight: 60
url: /el/php-java/conversion/fodp-to-otp/ 
keywords: "Convert, PowerPoint, FODP, OTP, Presentation, PHP"
description: Δείγμα κώδικα για μετατροπή PHP από FODP σε OTP. Χρησιμοποιήστε το PowerPoint PHP API για ομαδική μετατροπή αρχείων FODP σε αρχεία OTP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή FODP σε OTP σε PHP" h2="Ισχυρή βιβλιοθήκη PHP PowerPoint για μετατροπή FODP σε OTP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή FODP σε OTP σε PHP" %}}

Θέλετε να μετατρέψετε αρχεία FODP σε OTP μέσω προγραμματισμού; Χρησιμοποιώντας το [*Aspose.Slides για PHP μέσω Java*](https://products.aspose.com/slides/el/php-java/) οποιοσδήποτε προγραμματιστής μπορεί να μετατρέψει τη μορφή FODP σε OTP με λίγες μόνο γραμμές κώδικα PHP .

Ως σύγχρονο API επεξεργασίας παρουσιάσεων, το Aspose.Slides για PHP δημιουργεί γρήγορα το OTP από το FODP. Δοκιμάστε την ποιότητα της μετατροπής FODP σε OTP απευθείας στο [browser] σας (https://products.aspose.app/slides/conversion). Η βιβλιοθήκη Aspose PowerPoint PPTX σάς επιτρέπει να μετατρέπετε αρχεία FODP σε πολλές δημοφιλείς μορφές.

Μπορείτε να εγκαταστήσετε τη βιβλιοθήκη από το [Composer](https://packagist.org/packages/aspose/slides) χρησιμοποιώντας την ακόλουθη εντολή:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Κονσόλα/Τερματικό" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Αποθηκεύστε το FODP ως OTP στην PHP" %}}

Χρησιμοποιήστε τη δωρεάν εφαρμογή για να δείτε μια επίδειξη της διαδικασίας μετατροπής FODP σε OTP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή PHP FODP σε OTP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    $pres->save("output.otp", SaveFormat::Otp);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το FODP σε OTP στην PHP" intro="Αυτά είναι τα βήματα για να μετατρέψετε ένα αρχείο FODP σε OTP χρησιμοποιώντας PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φόρτωση αρχείου FODP με μια παρουσία της κλάσης Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο «αποθήκευση» καθορίζοντας τη διαδρομή του αρχείου εξόδου και το SaveFormat.OTP ως παραμέτρους.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Το αρχείο FODP θα αποθηκευτεί στην καθορισμένη διαδρομή{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Απαιτήσεις συστήματος" intro="Πριν εκτελέσετε το δείγμα πηγαίου κώδικα μετατροπής PHP, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε την PHP 7, προσθέστε διαδρομή προς την PHP στη μεταβλητή «PATH» του συστήματος και ορίστε το «allow_url_include» σε «On» στο αρχείο «php.ini».{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το JRE 8. Ορίστε τη μεταβλητή περιβάλλοντος «JAVA_HOME» ως διαδρομή προς την εγκατεστημένη θέση JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το Apache Tomcat 8.0 (δείτε [περισσότερα](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert FODP to OTP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το FODP σε πολλές άλλες μορφές αρχείων. Δείτε άλλες υποστηριζόμενες μετατροπές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Εικόνα Bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="Εικόνα JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-odp/" name="FODP TO ODP" description="Μορφή παρουσίασης OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Μορφή φορητού εγγράφου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="Φορητά γραφικά δικτύου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-pot/" name="FODP TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-pps/" name="FODP TO PPS" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-svg/" name="FODP TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="Μορφή SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/php-java/conversion/fodp-to-xps/" name="FODP TO XPS" description="Προδιαγραφές χαρτιού XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

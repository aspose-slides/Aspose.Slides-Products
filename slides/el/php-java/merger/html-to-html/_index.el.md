---
title: Συγχώνευση αρχείων HTML σε PHP
url: /el/php-java/merger/html-to-html/
keywords: Συγχώνευση HTML, HTML σε HTML, Συμμετοχή σε HTML, Συνδυασμός HTML, PHP API, Βιβλιοθήκη PHP
description: Συγχώνευση HTML σε HTML στην PHP. Χρησιμοποιήστε το API βιβλιοθήκης PHP για να συνδυάσετε αρχεία HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Συγχώνευση HTML σε PHP" h2="Βιβλιοθήκη PHP υψηλής ταχύτητας και πολλαπλών πλατφορμών για συγχώνευση αρχείων HTML με χρήση κώδικα PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση HTML σε HTML χρησιμοποιώντας το Aspose.Slides" %}}

[**Aspose.Slides για PHP μέσω Java**](https://products.aspose.com/slides/el/php-java/) είναι μια ισχυρή βιβλιοθήκη PHP που χρησιμοποιείται για τη δημιουργία, μετατροπή, συγχώνευση και χειρισμό παρουσιάσεων, αρχείων HTML και άλλα έγγραφα. Όταν συγχωνεύετε HTML σε HTML, συνδυάζετε αποτελεσματικά τα περιεχόμενα από 2 έγγραφα για να αποκτήσετε ένα αρχείο HTML. Το Aspose.Slides σάς επιτρέπει να συγχωνεύετε έγγραφα HTML με διαφορετικούς τρόπους. Μπορείτε να συγχωνεύσετε το HTML με όλα τα κείμενα, τη μορφοποίηση, τα στυλ κ.λπ.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Συγχώνευση HTML σε HTML στην PHP" %}}
Χρησιμοποιώντας το [**Aspose.Slides για PHP μέσω Java**](https://products.aspose.com/slides/el/php-java/), μπορείτε να συγχωνεύσετε γρήγορα αρχεία HTML με λίγες μόνο γραμμές κώδικα

{{% blocks/products/pf/agp/code-block title="Κώδικας PHP για συγχώνευση HTML σε HTML" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename1 = 'file1.html';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }
    
    $pres->getSlides()->addFromHtml($contents1);
    
    $filename2 = 'file2.html';
    $f2 = fopen($filename2, 'r');
    if ($f2) {
        $contents2 = fread($f2, filesize($filename2));
        fclose($f2);
    }
    
    $pres->getSlides()->addFromHtml($contents2);

    $pres->save("merged-html.html", SaveFormat::Html5);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να συγχωνεύσετε HTML σε PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για PHP μέσω Java**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε τα αρχεία HTML που θέλετε να συγχωνεύσετε.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το έγγραφο HTML που προκύπτει.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Συγχώνευση αρχείων PDF στο Διαδίκτυο" sectionDescription="[Πώς να συγχωνεύσετε το PDF στην Python](https://products.aspose.com/slides/el/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Συγχώνευση άλλων αρχείων" subTitle="Μπορείτε επίσης να συνδυάσετε αρχεία σε άλλες μορφές για να αποκτήσετε ένα μόνο αρχείο" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
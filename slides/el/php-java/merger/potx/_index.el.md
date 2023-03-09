---
title: Συγχώνευση αρχείων POTX με χρήση PHP
url: /el/php-java/merger/potx/
keywords: Συγχώνευση POTX, Join POTX, Combine POTX, PowerPoint, Presentation, PHP, Aspose
description: Συγχώνευση πολλών αρχείων POTX στην PHP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Συγχώνευση αρχείων POTX μαζί στην PHP" h2="API PHP υψηλής ταχύτητας και πολλαπλών πλατφορμών που βοηθά στην ανάπτυξη εφαρμογών με δυνατότητα δημιουργίας, συγχώνευσης, επιθεώρησης ή μετατροπής αρχείων παρουσίασης Microsoft PowerPoint και OpenOffice χωρίς τη χρήση λογισμικού όπως Microsoft ή Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση POTX σε PHP" %}}

Το [**Aspose.Slides για PHP μέσω Java**](https://products.aspose.com/slides/el/php-java/) είναι μια ισχυρή βιβλιοθήκη PHP για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους συνδυασμού πολλαπλών παρουσιάσεων POTX. Όταν συγχωνεύετε μια παρουσίαση με μια άλλη, συνδυάζετε αποτελεσματικά τις διαφάνειές τους σε μια παρουσίαση για να αποκτήσετε ένα αρχείο. Το Aspose.Slides σάς επιτρέπει να συγχωνεύσετε δύο παρουσιάσεις με διαφορετικούς τρόπους. Μπορείτε να συγχωνεύσετε παρουσιάσεις με όλα τα σχήματα, στυλ, κείμενα, μορφοποίηση, σχόλια, κινούμενα σχέδια κ.λπ. χωρίς να χρειάζεται να ανησυχείτε για απώλεια ποιότητας ή δεδομένων.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Συγχώνευση αρχείων POTX χρησιμοποιώντας PHP" %}}
Για να συγχωνεύσετε τις παρουσιάσεις του PowerPoint, θα χρειαστεί να κλωνοποιήσετε τις διαφάνειες από τη μία παρουσίαση στην άλλη.

{{% blocks/products/pf/agp/code-block title="Κώδικας PHP για συγχώνευση πολλαπλών POTX σε μεμονωμένο αρχείο" offSpacer="true" %}}


```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres1 = new Presentation("document1.potx");
$pres2 = new Presentation("document2.potx");
try
{
    for ($i = 0; $i < java_values($pres2->getSlides()->size()); $i++) 
    {
        $pres1->getSlides()->addClone($pres2->getSlides()->get_Item($i));
    }

    $pres1->save("merged.potx", SaveFormat::Potx);
}
finally
{
    if ($pres1 != null) $pres1->dispose();
    if ($pres2 != null) $pres2->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να συγχωνεύσετε το POTX χρησιμοποιώντας το Aspose.Slides για PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για να συγχωνεύσετε δύο αρχεία POTX και να αποθηκεύσετε το αποτέλεσμα ως POTX στην PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για PHP μέσω Java**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε τα αρχεία POTX που θέλετε να συγχωνεύσετε.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το έγγραφο POTX που προκύπτει.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Εξαγωγή POTX σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να συνδυάσετε το POTX και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/php-java/merger/fodp/" name="FODP" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
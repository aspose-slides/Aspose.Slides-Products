---
title: Μετατροπή PPTM σε SVG στο Node.js
url: /el/nodejs-java/conversion/pptm-to-svg/
keywords: PPTM σε SVG, Convert PPTM σε SVG, Node.js API, Node.js Library, PPTM, SVG
description: Μετατροπή PPTM σε SVG στο Node.js. Χρησιμοποιήστε το API βιβλιοθήκης Node.js για να μετατρέψετε αρχεία PPTM σε SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατροπή PPTM σε SVG στο Node.js" h2="Το Aspose.Slides for Node.js μέσω Java είναι μια ισχυρή και εύχρηστη βιβλιοθήκη που σας επιτρέπει να μετατρέψετε παρουσιάσεις PowerPoint σε διάφορες μορφές στο Node.js. Υποστηρίζει όλα τα στοιχεία και τις μορφές παρουσίασης και παρέχει ένα πλούσιο API για πρόσβαση και τροποποίηση τους. Σας επιτρέπει επίσης να εξάγετε τις διαφάνειές σας σε διάφορες μορφές για περαιτέρω επεξεργασία ή κοινή χρήση." >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή PPTM σε SVG στο Node.js" %}}

Το [**Aspose.Slides for Node.js μέσω Java**](https://products.aspose.com/slides/el/nodejs-java/) είναι μια ισχυρή βιβλιοθήκη Node.js για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του PPTM σε SVG. Χρησιμοποιώντας το **Aspose.Slides για Node.js μέσω Java**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία PPTM σε SVG με λίγες μόνο γραμμές κώδικα.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides for Node.js εξάγει αρχεία PPTM σε μορφές αρχείων SVG γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το PPTM σε SVG και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε το PPTM σε SVG χρησιμοποιώντας το Node.js" %}}
Για να μετατρέψετε το PPTM σε SVG, θα χρειαστεί να δημιουργήσετε την Παρουσίαση από το αρχείο PPTM και να την αποθηκεύσετε ως SVG.

{{% blocks/products/pf/agp/code-block title="Κώδικας Node.js για μετατροπή PPTM σε SVG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pptm");
try
{
    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να μετατρέψετε το PPTM σε SVG χρησιμοποιώντας το Aspose.Slides για Node.js μέσω Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Για να μετατρέψετε το PPTM σε SVG χρησιμοποιώντας το Aspose.Slides για Node.js μέσω Java, πρέπει να εισαγάγετε το πακέτο στο αρχείο JavaScript και να δημιουργήσετε ένα στιγμιότυπο της κλάσης Presentation. Η κλάση Presentation αντιπροσωπεύει ένα έγγραφο PowerPoint και παρέχει μεθόδους πρόσβασης και χειρισμού των στοιχείων του." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το [**Aspose.Slides για Node.js μέσω Java**](https://products.aspose.com/slides/el/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο σας Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ανοίξτε τα αρχεία πηγής PPTM στο Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αποτέλεσμα ως αρχείο SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Μετατροπή PPTM σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το PPTM και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-html/" name="PPTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-png/" name="PPTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-gif/" name="PPTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-odp/" name="PPTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-otp/" name="PPTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-pot/" name="PPTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
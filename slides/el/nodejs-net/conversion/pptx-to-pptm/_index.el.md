---
title: Μετατροπή PPTX σε PPTM σε JavaScript
url: /el/nodejs-net/conversion/pptx-to-pptm/
keywords: PPTX σε PPTM, Μετατροπή PPTX σε PPTM, Node.js API, JavaScript Library, PPTX, PPTM
description: Μετατροπή PPTX σε PPTM σε JavaScript. Χρησιμοποιήστε το API βιβλιοθήκης Node.js για να μετατρέψετε αρχεία PPTX σε PPTM
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατροπή PPTX σε PPTM σε JavaScript" h2="Το Aspose.Slides for Node.js μέσω .NET είναι μια ισχυρή και εύχρηστη βιβλιοθήκη που σας επιτρέπει να μετατρέπετε παρουσιάσεις PowerPoint σε διάφορες μορφές σε JavaScript. Υποστηρίζει όλα τα στοιχεία και τις μορφές παρουσίασης και παρέχει ένα πλούσιο API για πρόσβαση και τροποποίηση σε αυτά. Σας επιτρέπει επίσης να εξάγετε τις διαφάνειές σας σε διάφορες μορφές για περαιτέρω επεξεργασία ή κοινή χρήση." >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή PPTX σε PPTM στο Node.js" %}}

Το [**Aspose.Slides for Node.js μέσω .NET**](https://products.aspose.com/slides/el/nodejs-net/) είναι μια ισχυρή βιβλιοθήκη Node.js για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του PPTX σε PPTM. Χρησιμοποιώντας το **Aspose.Slides για Node.js μέσω .NET**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία PPTX σε PPTM με λίγες μόνο γραμμές κώδικα.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides για Node.js μέσω .NET εξάγει αρχεία PPTX σε μορφές αρχείων PPTM γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το PPTX σε PPTM και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε το PPTX σε PPTM χρησιμοποιώντας JavaScript" %}}
Για να μετατρέψετε το PPTX σε PPTM, θα χρειαστεί να δημιουργήσετε την Παρουσίαση από το αρχείο PPTX και να την αποθηκεύσετε ως PPTM.

{{% blocks/products/pf/agp/code-block title="Κώδικας JavaScript για μετατροπή PPTX σε PPTM" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pptx");
try
{
    pres.save("output.pptm", SaveFormat.Pptm);
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να μετατρέψετε το PPTX σε PPTM χρησιμοποιώντας το Aspose.Slides για Node.js μέσω .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Για να μετατρέψετε το PPTX σε PPTM χρησιμοποιώντας το Aspose.Slides για Node.js μέσω .NET, πρέπει να εισαγάγετε το πακέτο στο αρχείο JavaScript και να δημιουργήσετε ένα στιγμιότυπο της κλάσης Presentation. Η κλάση Presentation αντιπροσωπεύει ένα έγγραφο PowerPoint και παρέχει μεθόδους πρόσβασης και χειρισμού των στοιχείων του." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το [**Aspose.Slides για Node.js μέσω .NET**](https://products.aspose.com/slides/el/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο σας Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ανοίξτε τα αρχεία πηγής PPTX στο Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αποτέλεσμα ως αρχείο PPTM.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Μετατροπή PPTX σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το PPTX και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
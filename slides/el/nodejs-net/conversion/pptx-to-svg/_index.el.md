---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή PPTX σε SVG σε JavaScript
url: /el/nodejs-net/conversion/pptx-to-svg/
keywords: PPTX σε SVG, Μετατροπή PPTX σε SVG, Node.js API, JavaScript Library, PPTX, SVG
description: Μετατροπή PPTX σε SVG σε JavaScript. Χρησιμοποιήστε το API βιβλιοθήκης Node.js για να μετατρέψετε αρχεία PPTX σε SVG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή PPTX σε SVG σε JavaScript" h2="Το Aspose.Slides for Node.js μέσω .NET είναι μια ισχυρή και εύχρηστη βιβλιοθήκη που σας επιτρέπει να μετατρέπετε παρουσιάσεις PowerPoint σε διάφορες μορφές σε JavaScript. Υποστηρίζει όλα τα στοιχεία και τις μορφές παρουσίασης και παρέχει ένα πλούσιο API για πρόσβαση και τροποποίηση σε αυτά. Σας επιτρέπει επίσης να εξάγετε τις διαφάνειές σας σε διάφορες μορφές για περαιτέρω επεξεργασία ή κοινή χρήση." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατρέψτε το PPTX σε SVG χρησιμοποιώντας JavaScript" variant="code" %}}

Για να μετατρέψετε το PPTX σε SVG, θα χρειαστεί να δημιουργήσετε την Παρουσίαση από το αρχείο PPTX και να την αποθηκεύσετε ως SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας JavaScript για μετατροπή PPTX σε SVG" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pptx");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slideByteArray = pres.slides.get(i).getAsSvg();
        fs.writeFile('slide" + i + ".svg', Buffer.from(slideByteArray), (err) => {
            if (err)
                console.error(err);
        });
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή PPTX σε SVG στο Node.js" %}}

Το [**Aspose.Slides for Node.js μέσω .NET**](https://products.aspose.com/slides/el/nodejs-net/) είναι μια ισχυρή βιβλιοθήκη Node.js για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του PPTX σε SVG. Χρησιμοποιώντας το **Aspose.Slides για Node.js μέσω .NET**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία PPTX σε SVG με λίγες μόνο γραμμές κώδικα.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides για Node.js μέσω .NET εξάγει αρχεία PPTX σε μορφές αρχείων SVG γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το PPTX σε SVG και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το PPTX σε SVG χρησιμοποιώντας το Aspose.Slides για Node.js μέσω .NET API" intro="Για να μετατρέψετε το PPTX σε SVG χρησιμοποιώντας το Aspose.Slides για Node.js μέσω .NET, πρέπει να εισαγάγετε το πακέτο στο αρχείο JavaScript και να δημιουργήσετε ένα στιγμιότυπο της κλάσης Presentation. Η κλάση Presentation αντιπροσωπεύει ένα έγγραφο PowerPoint και παρέχει μεθόδους πρόσβασης και χειρισμού των στοιχείων του." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το [**Aspose.Slides για Node.js μέσω .NET**](https://products.aspose.com/slides/el/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο σας Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε τα αρχεία πηγής PPTX στο Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αποτέλεσμα ως αρχείο SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Μετατροπή PPTX σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το PPTX και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

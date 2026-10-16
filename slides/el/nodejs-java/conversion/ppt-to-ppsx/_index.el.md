---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή PPT σε PPSX στο Node.js
url: /el/nodejs-java/conversion/ppt-to-ppsx/
keywords: PPT σε PPSX, Convert PPT σε PPSX, Node.js API, Node.js Library, PPT, PPSX
description: Μετατροπή PPT σε PPSX στο Node.js. Χρησιμοποιήστε το API βιβλιοθήκης Node.js για να μετατρέψετε αρχεία PPT σε PPSX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή PPT σε PPSX στο Node.js" h2="Το Aspose.Slides for Node.js μέσω Java είναι μια ισχυρή και εύχρηστη βιβλιοθήκη που σας επιτρέπει να μετατρέψετε παρουσιάσεις PowerPoint σε διάφορες μορφές στο Node.js. Υποστηρίζει όλα τα στοιχεία και τις μορφές παρουσίασης και παρέχει ένα πλούσιο API για πρόσβαση και τροποποίηση τους. Σας επιτρέπει επίσης να εξάγετε τις διαφάνειές σας σε διάφορες μορφές για περαιτέρω επεξεργασία ή κοινή χρήση." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατρέψτε το PPT σε PPSX χρησιμοποιώντας το Node.js" variant="code" %}}

Για να μετατρέψετε το PPT σε PPSX, θα χρειαστεί να δημιουργήσετε την Παρουσίαση από το αρχείο PPT και να την αποθηκεύσετε ως PPSX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας Node.js για μετατροπή PPT σε PPSX" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppt");
try
{
    pres.save("output.ppsx", aspose.slides.SaveFormat.Ppsx);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή PPT σε PPSX στο Node.js" %}}

Το [**Aspose.Slides for Node.js μέσω Java**](https://products.aspose.com/slides/el/nodejs-java/) είναι μια ισχυρή βιβλιοθήκη Node.js για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του PPT σε PPSX. Χρησιμοποιώντας το **Aspose.Slides για Node.js μέσω Java**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία PPT σε PPSX με λίγες μόνο γραμμές κώδικα.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides for Node.js εξάγει αρχεία PPT σε μορφές αρχείων PPSX γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το PPT σε PPSX και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το PPT σε PPSX χρησιμοποιώντας το Aspose.Slides για Node.js μέσω Java API" intro="Για να μετατρέψετε το PPT σε PPSX χρησιμοποιώντας το Aspose.Slides για Node.js μέσω Java, πρέπει να εισαγάγετε το πακέτο στο αρχείο JavaScript και να δημιουργήσετε ένα στιγμιότυπο της κλάσης Presentation. Η κλάση Presentation αντιπροσωπεύει ένα έγγραφο PowerPoint και παρέχει μεθόδους πρόσβασης και χειρισμού των στοιχείων του." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το [**Aspose.Slides για Node.js μέσω Java**](https://products.aspose.com/slides/el/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο σας Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε τα αρχεία πηγής PPT στο Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αποτέλεσμα ως αρχείο PPSX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Μετατροπή PPT σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το PPT και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-jpg/" name="PPT TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

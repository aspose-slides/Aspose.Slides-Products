---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή ODP σε POTX στο Node.js
url: /el/nodejs-java/conversion/odp-to-potx/
keywords: ODP σε POTX, Convert ODP σε POTX, Node.js API, Node.js Library, ODP, POTX
description: Μετατροπή ODP σε POTX στο Node.js. Χρησιμοποιήστε το API βιβλιοθήκης Node.js για να μετατρέψετε αρχεία ODP σε POTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή ODP σε POTX στο Node.js" h2="Το Aspose.Slides for Node.js μέσω Java είναι μια ισχυρή και εύχρηστη βιβλιοθήκη που σας επιτρέπει να μετατρέψετε παρουσιάσεις PowerPoint σε διάφορες μορφές στο Node.js. Υποστηρίζει όλα τα στοιχεία και τις μορφές παρουσίασης και παρέχει ένα πλούσιο API για πρόσβαση και τροποποίηση τους. Σας επιτρέπει επίσης να εξάγετε τις διαφάνειές σας σε διάφορες μορφές για περαιτέρω επεξεργασία ή κοινή χρήση." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατρέψτε το ODP σε POTX χρησιμοποιώντας το Node.js" variant="code" %}}

Για να μετατρέψετε το ODP σε POTX, θα χρειαστεί να δημιουργήσετε την Παρουσίαση από το αρχείο ODP και να την αποθηκεύσετε ως POTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας Node.js για μετατροπή ODP σε POTX" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.odp");
try
{
    pres.save("output.potx", aspose.slides.SaveFormat.Potx);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή ODP σε POTX στο Node.js" %}}

Το [**Aspose.Slides for Node.js μέσω Java**](https://products.aspose.com/slides/el/nodejs-java/) είναι μια ισχυρή βιβλιοθήκη Node.js για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του ODP σε POTX. Χρησιμοποιώντας το **Aspose.Slides για Node.js μέσω Java**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία ODP σε POTX με λίγες μόνο γραμμές κώδικα.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides for Node.js εξάγει αρχεία ODP σε μορφές αρχείων POTX γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το ODP σε POTX και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το ODP σε POTX χρησιμοποιώντας το Aspose.Slides για Node.js μέσω Java API" intro="Για να μετατρέψετε το ODP σε POTX χρησιμοποιώντας το Aspose.Slides για Node.js μέσω Java, πρέπει να εισαγάγετε το πακέτο στο αρχείο JavaScript και να δημιουργήσετε ένα στιγμιότυπο της κλάσης Presentation. Η κλάση Presentation αντιπροσωπεύει ένα έγγραφο PowerPoint και παρέχει μεθόδους πρόσβασης και χειρισμού των στοιχείων του." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το [**Aspose.Slides για Node.js μέσω Java**](https://products.aspose.com/slides/el/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο σας Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε τα αρχεία πηγής ODP στο Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αποτέλεσμα ως αρχείο POTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Μετατροπή ODP σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το ODP και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-png/" name="ODP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-bmp/" name="ODP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/nodejs-java/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

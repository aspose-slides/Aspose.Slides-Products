---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή ODP σε PDF μέσω Java
weight: 450
url: /el/java/conversion/odp-to-pdf/ 
description: Δείγμα κώδικα μετατροπής Java για μορφή ODP σε αρχείο PDF. Χρησιμοποιήστε αυτό το παράδειγμα κώδικα για να εξαγάγετε παρουσιάσεις PowerPoint & OpenOffice σε PDF μέσα σε οποιαδήποτε εφαρμογή που βασίζεται σε Web ή Desktop Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή ODP σε PDF μέσω Java" h2="ODP σε PDF Μετατροπή Java για μετατροπή μεμονωμένων ή πολλαπλών σελίδων σε PDF χρησιμοποιώντας βιβλιοθήκη Java On-premise."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Πώς να μετατρέψετε το ODP σε PDF χρησιμοποιώντας Java" %}}

Για να αποδώσουμε το ODP σε PDF, θα χρησιμοποιήσουμε
 [Aspose.Slides για Java](https://products.aspose.com/slides/el/java/)
 API που είναι ένα πλούσιο σε χαρακτηριστικά, ισχυρό και εύχρηστο API μετατροπής για πλατφόρμα Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 και εγκαταστήστε το στο έργο σας που βασίζεται στο Maven προσθέτοντας τις ακόλουθες διαμορφώσεις στο pom.xml.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Αποθήκη" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εξάρτηση" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Πηγαίος κώδικας μετατροπής ODP σε PDF Java" >}}
```cs
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("template.odp");
// save the presentation as PDF
presentation.save("output.pdf", SaveFormat.Pdf);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Βήματα για τη μετατροπή του ODP σε PDF μέσω Java" intro="Οι προγραμματιστές Java μπορούν εύκολα να μετατρέψουν το αρχείο ODP σε PDF σε λίγες μόνο γραμμές κώδικα." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο ODP με μια παρουσία της κλάσης Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο Presentation.save καθορίζοντας τη διαδρομή του αρχείου εξόδου και το SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Το αρχείο PDF θα αποθηκευτεί στην καθορισμένη διαδρομή{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Πριν εκτελέσετε το δείγμα κώδικα μετατροπής Java, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις." %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
- Λάβετε την τελευταία έκδοση του Aspose.Slides για Java απευθείας από τη Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Δημιουργήθηκε με το Aspose.Slides" title="Μετατροπή ODP σε PDF online" description="Η δωρεάν εφαρμογή Aspose.Slides Conversion έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία ODP." button="Άνοιγμα Aspose.Slides Conversion" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" upload="Σύρετε ή ανεβάστε το αρχείο σας" saveAs="Αποθήκευση ως" convert="Μετατροπή" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides μετατρέπει αρχεία πριν γράψετε κώδικα.
- Ανεβάστε αρχεία ODP και αποθηκεύστε τα ως PDF.
- Κατεβάστε το αποτέλεσμα ή μετατρέψτε περισσότερα αρχεία.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το ODP σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Εικόνα Bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-gif/" name="ODP TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-html/" name="ODP TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="Εικόνα JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-otp/" name="ODP TO OTP" description="Τυπική μορφή OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-png/" name="ODP TO PNG" description="Φορητά γραφικά δικτύου" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-pot/" name="ODP TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-potm/" name="ODP TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-potx/" name="ODP TO POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-pps/" name="ODP TO PPS" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-svg/" name="ODP TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-swf/" name="ODP TO SWF" description="Μορφή SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/conversion/odp-to-xps/" name="ODP TO XPS" description="Προδιαγραφές χαρτιού XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

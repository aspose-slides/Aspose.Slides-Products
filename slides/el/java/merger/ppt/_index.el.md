---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Συγχώνευση αρχείων PPT μέσω Java
weight: 730
url: /el/java/merger/ppt/ 
description: Δείγμα κώδικα Java για συνδυασμό εγγράφων PPT σε Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Συγχώνευση μορφών PPT σε Java" h2="Συγχώνευση εγγενών εγγράφων PPT με χρήση API Java από την πλευρά του διακομιστή."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Πώς να συγχωνεύσετε αρχεία PPT χρησιμοποιώντας Java" %}}

Για να συγχωνεύσουμε το αρχείο PPT, θα χρησιμοποιήσουμε
 [Aspose.Slides για Java](https://products.aspose.com/slides/el/java/)
 API που είναι ένα πλούσιο σε χαρακτηριστικά, ισχυρό και εύχρηστο API συγχώνευσης για πλατφόρμα Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Συγχώνευση αρχείων PPT - Java" >}}
```cs
// Load first PPT File
Presentation prest1 = new Presentation("prest1.ppt");

// Load second PPT File
Presentation prest2 = new Presentation("prest2.ppt");

// Merge
for (ISlide slide : prest2.getSlides()) {
	// Merge from source to target
	prest1.getSlides().addClone(slide);
}

// Save the File
prest1.save("merged-presentation.ppt", SaveFormat.Ppt);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Βήματα για τη συγχώνευση αρχείων PPT σε Java" intro="Ένα βασικό έγγραφο που συγχωνεύεται και συνδέεται με τα API [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/) μπορεί να γίνει με λίγες μόνο γραμμές κώδικα." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το πρώτο αρχείο PPT με μια παρουσία της κλάσης Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το δεύτερο έγγραφο PPT με μια παρουσία της κλάσης Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Κάντε βρόχο σε κάθε διαφάνεια του δεύτερου αρχείου PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Με κάθε επανάληψη, χρησιμοποιώντας την addClone() για να προσθέσετε διαφάνειες με το πρώτο αρχείο .{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε τη μέθοδο save() για αποθήκευση σε καθορισμένη διαδρομή{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Το Aspose.Slides for Java υποστηρίζει όλες τις μεγάλες πλατφόρμες και τα λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις." %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
- Λάβετε την τελευταία έκδοση του Aspose.Slides για Java απευθείας από [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides) .

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Συγχώνευση αρχείων PDF στο Διαδίκτυο"
  description="[Πώς να συγχωνεύσετε το PDF στην Python](https://products.aspose.com/slides/el/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Τα αρχεία με επέκταση `.PPT` είναι αρχεία παρουσιάσεων Microsoft PowerPoint 97-2003. Ένα αρχείο `PPT` μπορεί να περιέχει διαφάνειες με κείμενο, εικόνες, πολυμέσα και άλλα ενσωματωμένα αντικείμενα.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές συγχώνευσης" subTitle="Χρησιμοποιώντας Java, το One μπορεί επίσης να συγχωνεύσει πολλές άλλες μορφές αρχείων, όπως.." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/odp/" name="ODP" description="Μορφή παρουσίασης OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/otp/" name="OTP" description="Τυπική μορφή OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/pot/" name="POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/potm/" name="POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/potx/" name="POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/pps/" name="PPS" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/ppsm/" name="PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/ppsx/" name="PPSX" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/pptm/" name="PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/merger/pptx/" name="PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

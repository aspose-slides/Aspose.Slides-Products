---
title: Μετατροπή POTX σε SVG μέσω Java
weight: 5280
url: /el/java/conversion/potx-to-svg/ 
description: Δείγμα κώδικα μετατροπής Java για μορφή POTX σε αρχείο SVG. Χρησιμοποιήστε αυτό το παράδειγμα κώδικα για να εξαγάγετε παρουσιάσεις PowerPoint & OpenOffice σε SVG σε οποιαδήποτε εφαρμογή που βασίζεται σε Web ή Desktop Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή POTX σε SVG μέσω Java" h2="Μετατροπή POTX σε SVG Java για μετατροπή μεμονωμένων ή πολλαπλών σελίδων σε SVG χρησιμοποιώντας βιβλιοθήκη Java εσωτερικής εγκατάστασης." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το POTX σε SVG χρησιμοποιώντας Java" %}}

 Για να αποδώσουμε το POTX σε SVG, θα χρησιμοποιήσουμε
 [Aspose.Slides για Java](https://products.aspose.com/slides/el/java)
 API που είναι ένα πλούσιο σε χαρακτηριστικά, ισχυρό και εύχρηστο API μετατροπής για πλατφόρμα Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 και εγκαταστήστε το στο έργο σας που βασίζεται στο Maven προσθέτοντας τις ακόλουθες διαμορφώσεις στο pom.xml.

{{% blocks/products/pf/agp/code-block title="Αποθήκη" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Εξάρτηση" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή POTX σε SVG μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές Java μπορούν εύκολα να μετατρέψουν το αρχείο POTX σε SVG σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φορτώστε το αρχείο POTX με μια παρουσία της κλάσης Presentation
1. Καλέστε τη μέθοδο Presentation.save καθορίζοντας τη διαδρομή του αρχείου εξόδου και το SaveFormat
1. Το αρχείο SVG θα αποθηκευτεί στην καθορισμένη διαδρομή

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε το δείγμα κώδικα μετατροπής Java, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
- Λάβετε την τελευταία έκδοση του Aspose.Slides για Java απευθείας από τη Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής Java POTX σε SVG" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a POTX file
Presentation pres = new Presentation("template.potx");
try {
    // Access the first slide
    ISlide sld = pres.getSlides().get_Item(0);

    // Create a memory stream object
    FileOutputStream svgStream = new FileOutputStream("output.svg");

    // Create SVG image of slide and save in memory stream
    sld.writeAsSvg(svgStream);

    svgStream.close();
} catch (IOException e) {
} finally {
    pres.dispose();
}   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Δωρεάν εφαρμογή για μετατροπή POTX σε SVG" 
        sectionDescription="[Δοκιμάστε τη δωρεάν εφαρμογή Editor](https://products.aspose.app/slides/editor/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το POTX σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-bmp/" name="POTX TO BMP" description="Εικόνα Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-gif/" name="POTX TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-html/" name="POTX TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="Εικόνα JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-odp/" name="POTX TO ODP" description="Μορφή παρουσίασης OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-otp/" name="POTX TO OTP" description="Τυπική μορφή OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-pdf/" name="POTX TO PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-png/" name="POTX TO PNG" description="Φορητά γραφικά δικτύου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-pot/" name="POTX TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-potm/" name="POTX TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-pps/" name="POTX TO PPS" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-swf/" name="POTX TO SWF" description="Μορφή SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/conversion/potx-to-xps/" name="POTX TO XPS" description="Προδιαγραφές χαρτιού XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
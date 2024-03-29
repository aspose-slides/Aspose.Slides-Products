---
title: Μετατροπή PPSM σε PDF μέσω εφαρμογής C++
weight: 6930
url: /el/cpp/conversion/ppsm-to-pdf/ 
description: Δείγμα κώδικα μετατροπής C++ για έγγραφο PPSM σε μορφή PDF. Χρησιμοποιήστε παράδειγμα κώδικα για ομαδική μετατροπή PPSM σε PDF σε οποιαδήποτε εφαρμογή C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή PPSM σε PDF μέσω C++" h2="Μετατροπή PPSM σε PDF υψηλής απόδοσης με χρήση βιβλιοθήκης C++ χωρίς την ανάγκη εγκατάστασης του Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το PPSM σε PDF χρησιμοποιώντας C++" %}}

 Για να μετατρέψουμε το PPSM σε PDF, θα χρησιμοποιήσουμε
 [Aspose.Slides για C++](https://products.aspose.com/slides/cpp/)
 API που είναι ένα πλούσιο σε χαρακτηριστικά, ισχυρό και εύχρηστο API χειρισμού εγγράφων και μετατροπής για πλατφόρμα C++. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας, απλά ανοίξτε
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 διαχειριστής πακέτων, αναζητήστε
 Aspose.Slides.Cpp
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή PPSM σε PDF μέσω C++" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές C++ μπορούν εύκολα να μετατρέψουν το αρχείο PPSM σε PDF σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φορτώστε το αρχείο PPSM με το Aspose.Slides για Αντικείμενο παρουσίασης C++.
1. Καλέστε τη μέθοδο Save().
1. Περάστε τη διαδρομή του αρχείου εξόδου με επέκταση αρχείου (PDF).
1. Το αρχείο PDF θα αποθηκευτεί στην καθορισμένη διαδρομή.
1. Ανοίξτε το αρχείο PDF σε συμβατό πρόγραμμα.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε τον κώδικα παραδείγματος μετατροπής C++, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.
- Aspose.Slides για C++ DLL που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής PPSM σε PDF C++" offSpacer="" %}}

```cs
// Load the PPSM.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppsm");
// Save in PDF format.
prs->Save(u"convertedFile.pdf", Aspose::Slides::Export::SaveFormat::Pdf);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Δωρεάν εφαρμογή για μετατροπή PPSM σε PDF" 
        sectionDescription="[Δοκιμάστε την δωρεάν εφαρμογή μας για να μετατρέψετε PPT σε PDF](https://products.aspose.app/slides/conversion/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το PPSM σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Εικόνα Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="Εικόνα JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Μορφή παρουσίασης OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Τυπική μορφή OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Φορητά γραφικά δικτύου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-xml/" name="PPSM TO XML" description="Επεκτάσιμη γλώσσα σήμανσης" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Προδιαγραφές χαρτιού XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
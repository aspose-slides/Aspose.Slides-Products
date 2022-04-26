---
title: Επεξεργασία ή προβολή μεταδεδομένων εγγράφου POT μέσω C++
weight: 5800
url: /el/cpp/metadata/pot/ 
description: Παράδειγμα κώδικα C++ για επεξεργασία ή προβολή μεταδεδομένων αρχείου POT στο περιβάλλον χρόνου εκτέλεσης C++ για Windows 32 bit, Windows 64 bit και Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Εξαγωγή μεταδεδομένων POT μέσω C++" h2="Δημιουργήστε τις δικές σας εφαρμογές C++ για να προσθέσετε, να επεξεργαστείτε, να αφαιρέσετε ή να εξαγάγετε μεταδεδομένα από αρχεία POT χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να αποκτήσετε μεταδεδομένα POT χρησιμοποιώντας C++" %}}

 Για να εξαγάγουμε μεταδεδομένα POT, θα χρησιμοποιήσουμε
 [Aspose.Slides για C++](https://products.aspose.com/slides/cpp)
 API που είναι ένα πλούσιο σε χαρακτηριστικά, ισχυρό και εύκολο στη χρήση API εξαγωγής μεταδεδομένων εγγράφων για πλατφόρμα C++. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας, απλά ανοίξτε
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 διαχειριστής πακέτων, αναζητήστε
 **Aspose.Slides.Cpp**
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Βήματα για την εξαγωγή μεταδεδομένων του POT μέσω C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Η κλάση IDocumentProperties αντιπροσωπεύει τις ιδιότητες του εγγράφου που σχετίζονται με ένα αρχείο παρουσίασης. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν αυτήν την ιδιότητα για πρόσβαση στα μεταδεδομένα όπως περιγράφεται παρακάτω." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση αρχείου POT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Λάβετε ιδιότητες εγγράφου χρησιμοποιώντας το get\_DocumentProperties()
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
επανάληψη για όλες τις ιδιότητες χρησιμοποιώντας βρόχο
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εκτυπώστε ιδιότητες με κάθε επανάληψη.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Το Aspose.Slides for C++ υποστηρίζει όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.
- Aspose.Slides για C++ DLL που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Εξαγωγή Μεταδεδομένων του POT - C++" offSpacer="" %}}

```cs

const String templatePath = u"../templates/AccessModifyingProperties.pot";

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(templatePath);

// Create a reference to DocumentProperties object associated with Prsentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

for (int32_t i = 0; i get_CountOfCustomProperties(); i++){
	System::Console::WriteLine(u"Custom Property Name : {0}", documentProperties->GetCustomPropertyName(i));
	System::Console::WriteLine(u"Custom Property Vlaue : {0}", documentProperties->idx_get(documentProperties->GetCustomPropertyName(i)));
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με το Aspose.Slides for C++ API" %}}

 Το Aspose.Slides API μπορεί να χρησιμοποιηθεί για ανάγνωση, εγγραφή, χειρισμό και μετατροπή εγγράφων του Microsoft PowerPoint σε PDF, XPS, HTML, TIFF, ODP και διάφορες άλλες μορφές. Κάποιος μπορεί να δημιουργήσει νέα αρχεία από την αρχή και να τα αποθηκεύσει στις σχετικές υποστηριζόμενες μορφές. Το Aspose.Slides είναι ένα αυτόνομο API για δημιουργία, ανάλυση ή χειρισμό παρουσιάσεων, διαφανειών και στοιχείων και δεν εξαρτάται από κανένα λογισμικό όπως το Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of POT via Online App" sectionDescription="View & edit Metadata to POT documents by using our [Live Demos](https://products.aspose.app/slides/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your POT file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" >}}
Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Files created with these versions of Microsoft PowerPoint are in binary format as compared to those created in Office OpenXML file formats using the higher versions of PowerPoint. The files, hence, generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές μεταδεδομένων" subTitle="Χρησιμοποιώντας C++, μπορεί κανείς να χειριστεί μεταδεδομένα πολλών άλλων μορφών, συμπεριλαμβανομένων" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/odp/" name="ODP" description="Μορφή παρουσίασης OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/otp/" name="OTP" description="Τυπική μορφή OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/potm/" name="POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/potx/" name="POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pps/" name="PPS" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/ppsm/" name="PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/ppsx/" name="PPSX" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pptm/" name="PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pptx/" name="PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
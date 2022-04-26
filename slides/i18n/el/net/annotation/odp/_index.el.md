---
title: Καταργήστε τον σχολιασμό ODP μέσω .NET
weight: 1370
url: /el/net/annotation/odp/ 
description: Πηγαίος κώδικας C# για διαγραφή σχολιασμών μορφής ODP σε πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Κατάργηση σχολίων και συντακτών σχολίων από το ODP μέσω C#" h2="Δημιουργήστε τις δικές σας εφαρμογές .NET για να χειρίζεστε σχόλια και συντάκτες σε αρχεία εγγράφων χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να σχολιάσετε αρχείο ODP χρησιμοποιώντας C#" %}}

 Για να σχολιάσουμε το αρχείο ODP, θα χρησιμοποιήσουμε
 [Aspose.Slides για .NET](https://products.aspose.com/slides/net)
 API που είναι ένα πλούσιο σε χαρακτηριστικά, ισχυρό και εύκολο στη χρήση API χειρισμού εγγράφων για πλατφόρμα C#. Ανοιξε
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 διαχειριστής πακέτων, αναζητήστε
 **Aspose.Slides**
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Κατάργηση σχολίων από το ODP μέσω C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Χρειάζεστε [aspose.slides.dll](https://downloads.aspose.com/slides/net) για να δοκιμάσετε τον κώδικα στο περιβάλλον σας." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε το ODP με μια παρουσία της κλάσης Παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Επανάληψη σε όλους τους Συντάκτες του φορτωμένου ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κάντε βρόχο και ελέγξτε όλα τα σχόλια κάθε συγγραφέα
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κατάργηση όλων των σχολίων ενός συγγραφέα
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αφαιρέστε τον συγγραφέα στο τέλος
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Το Aspose.Slides για .NET υποστηρίζεται σε όλα τα κύρια λειτουργικά συστήματα. Απλώς βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin.
- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.
- Aspose.Slides για .NET DLL που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Διαγραφή σχολιασμών από ODP - C#" offSpacer="" %}}

```cs
// load ODP with a new instance of Presentation class
var presentation = new Aspose.Slides.Presentation("template.odp");
// iterate over comment authors
foreach (var author in presentation.CommentAuthors)
{
    // iterate over author comments
    foreach (var comment in author.Comments)
    {
        // remove comments
        author.Comments.Remove(comment);
    }
    // remove author
    author.Remove();
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με το Aspose.Slides για .NET API" %}}

 Το Aspose.Slides API μπορεί να χρησιμοποιηθεί για ανάγνωση, εγγραφή, χειρισμό και μετατροπή εγγράφων του Microsoft PowerPoint σε PDF, XPS, HTML, TIFF, ODP και διάφορες άλλες μορφές. Κάποιος μπορεί να δημιουργήσει νέα αρχεία από την αρχή και να τα αποθηκεύσει στις σχετικές υποστηριζόμενες μορφές. Το Aspose.Slides είναι ένα αυτόνομο API για δημιουργία, ανάλυση ή χειρισμό παρουσιάσεων, διαφανειών και στοιχείων και δεν εξαρτάται από κανένα λογισμικό όπως το Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Remove Annotation from ODP via Online App" sectionDescription="Delete ODP document annotations right now by visiting our [Live Demos website](https://products.aspose.app/slides/annotation). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP file and hit the \"Remove\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές σχολιασμού" subTitle="Χρησιμοποιώντας C#, μπορεί κανείς εύκολα να σχολιάσει άλλες μορφές, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/annotation/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/annotation/pptx/" name="PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
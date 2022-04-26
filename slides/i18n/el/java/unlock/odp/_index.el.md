---
title: Ξεκλειδώστε το έγγραφο ODP μέσω Java
weight: 3650
url: /el/java/unlock/odp/ 
description: Δείγμα κώδικα Java για να ξεκλειδώσετε το προστατευμένο με κωδικό πρόσβασης αρχείο ODP στο Java Runtime Environment για JSP/JSF Application και Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Ξεκλείδωμα αρχείων ODP μέσω Java" h2="Καταργήστε την προστασία από παρουσιάσεις PowerPoint συμπεριλαμβανομένου του αρχείου ODP χρησιμοποιώντας τη Βιβλιοθήκη Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Πώς να αφαιρέσετε το αρχείο ODP προστασίας χρησιμοποιώντας Java" %}}

 Για να ξεκλειδώσετε το αρχείο ODP, θα χρησιμοποιήσουμε
 [Aspose.Slides για Java](https://products.aspose.com/slides/java)
 API που είναι ένα πλούσιο σε χαρακτηριστικά, ισχυρό και εύχρηστο API προστασίας για πλατφόρμα Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
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


{{< blocks/products/pf/agp/feature-section-col title="Βήματα για να ξεκλειδώσετε το ODP μέσω Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε το κλειδωμένο ODP με μια παρουσία παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ελέγξτε την προστασία χρησιμοποιώντας την ιδιότητα boolean type isWriteProtected
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Καταργήστε την προστασία χρησιμοποιώντας τη μέθοδο removeWriteProtection().
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Το Aspose.Slides for Java υποστηρίζει όλες τις μεγάλες πλατφόρμες και τα λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ξεκλείδωμα αρχείων ODP μέσω C#" offSpacer="" %}}

```cs

// Open the ODP file
Presentation pres = new Presentation("WriteProtectedFile.odp");

// Checking if presentation is write protected
if (pres.getProtectionManager().isWriteProtected())
	// Removing Write protection
	pres.getProtectionManager().removeWriteProtection();

// Saving presentation
pres.save("output.odp", com.aspose.slides.SaveFormat.Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με το Aspose.Slides for Java API" %}}

 Το Aspose.Slides API μπορεί να χρησιμοποιηθεί για ανάγνωση, εγγραφή, χειρισμό και μετατροπή εγγράφων του Microsoft PowerPoint σε PDF, XPS, HTML, TIFF, ODP και διάφορες άλλες μορφές. Κάποιος μπορεί να δημιουργήσει νέα αρχεία από την αρχή και να τα αποθηκεύσει στις σχετικές υποστηριζόμενες μορφές. Το Aspose.Slides είναι ένα αυτόνομο API για δημιουργία, ανάλυση ή χειρισμό παρουσιάσεων, διαφανειών και στοιχείων και δεν εξαρτάται από κανένα λογισμικό όπως το Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Unlock ODP" sectionDescription="Check our live demos to [unlock ODP files](https://products.aspose.app/slides/unlock/odp) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload ODP file and hit the \"Unlock\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant ODP file from the link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές ξεκλειδώματος" subTitle="Χρησιμοποιώντας Java, μπορεί κανείς εύκολα να αφαιρέσει την προστασία / ξεκλείδωμα διαφορετικών μορφών, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/unlock/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/unlock/pptx/" name="PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
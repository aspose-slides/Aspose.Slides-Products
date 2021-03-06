---
title: Μετατροπή PPSX σε PNG μέσω C#
weight: 120
url: /el/net/conversion/ppsx-to-png/ 
description: Δείγμα κώδικα για μετατροπή PPSX σε PNG C#. Χρησιμοποιήστε παράδειγμα κώδικα API για ομαδική μετατροπή αρχείων PPSX σε PNG εντός VB.NET, Asp.NET ή οποιασδήποτε εφαρμογής που βασίζεται σε .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή PPSX σε PNG μέσω C#" h2="Εξαγωγή αρχείων PowerPoint® PPSX σε PNG σε πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε PPSX σε PNG χρησιμοποιώντας C#" %}}

 Για να μετατρέψουμε το PPSX σε PNG, θα χρησιμοποιήσουμε
 [Aspose.Slides για .NET](https://products.aspose.com/slides/el/net)
 API που είναι ένα πλούσιο σε χαρακτηριστικά, ισχυρό και εύκολο στη χρήση API χειρισμού εγγράφων και μετατροπής για πλατφόρμα C#. Ανοιξε
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 διαχειριστής πακέτων, αναζητήστε
 Aspose.Διαφάνειες
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή κονσόλας διαχείρισης πακέτων" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή PPSX σε PNG μέσω C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Οι προγραμματιστές .NET μπορούν εύκολα να φορτώσουν και να μετατρέψουν αρχεία PPSX σε PNG σε λίγες μόνο γραμμές κώδικα." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε το αρχείο PPSX με μια παρουσία της κλάσης Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Επαναλάβετε σε κάθε Διαφάνεια στην Παρουσίαση
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε μια εικόνα πλήρους κλίμακας ως Bitmap με κάθε επανάληψη
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Καλέστε τη μέθοδο Bitmap.Save με επέκταση αρχείου PNG & ImageFormat.Png ως παραμέτρους
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε το δείγμα πηγαίου κώδικα μετατροπής .NET, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin.
- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.
- Aspose.Slides για .NET DLL που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή PPSX σε PNG C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.ppsx"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in PNG format
        bitmap.Save(string.Format("Slide_{0}.png", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Png);
    }
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
        sectionTitle="Δωρεάν εφαρμογή για μετατροπή PPSX σε PNG" 
        sectionDescription="[Δοκιμάστε την δωρεάν εφαρμογή μας για να μετατρέψετε PPT σε PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το PPSX σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Εικόνα Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="Εικόνα JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Μορφή παρουσίασης OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Τυπική μορφή OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="Μορφή SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Προδιαγραφές χαρτιού XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
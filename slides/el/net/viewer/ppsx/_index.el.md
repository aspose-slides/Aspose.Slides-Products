---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προβολή PPSX σε C#
keywords: Προβολή PPSX, Άνοιγμα PPSX, Πρόγραμμα προβολής PPSX, PPSX, PowerPoint, C# API, Βιβλιοθήκη .NET
weight: 2370
url: /el/net/viewer/ppsx/ 
description: Προβάλετε αρχεία PPSX σε C#. Χρησιμοποιήστε το Aspose.Slides for .NET για να ανοίξετε αρχεία παρουσιάσεων και να τα αποθηκεύσετε ως HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Προβολή PPSX σε C#" h2="C# API για άνοιγμα αρχείων PPSX και αποθήκευσή τους ως responsive HTML."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προβολή PPSX με το Aspose.Slides" %}}

Για να προβάλετε αρχεία PPSX, χρησιμοποιήστε το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), ένα ισχυρό και εύχρηστο API για C# με πλούσιες δυνατότητες. Ανοίξτε τη διαχείριση πακέτων [NuGet](https://www.nuget.org/packages/aspose.slides.net), αναζητήστε το **Aspose.Slides** και εγκαταστήστε το. Μπορείτε επίσης να εκτελέσετε την παρακάτω εντολή στην κονσόλα Package Manager.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εντολή κονσόλας Package Manager" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Με το [**Aspose.Slides for .NET**](/slides/el/net/) μπορείτε να φορτώσετε ένα αρχείο PPSX και να το αποθηκεύσετε ως responsive HTML με λίγες γραμμές κώδικα.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας C# για προβολή PPSX" >}}
```cs
using var presentation = new Presentation("presentation.ppsx");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προβάλετε PPSX σε C#" intro="Το Aspose.Slides επιτρέπει στους προγραμματιστές να προβάλλουν αρχεία PPSX με λίγες μόνο γραμμές κώδικα." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το **Aspose.Slides for .NET**. Δείτε την [**Εγκατάσταση**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο `PPSX` με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα αντικείμενο `ResponsiveHtmlController` για responsive έξοδο HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα αντικείμενο `HtmlOptions` και ορίστε την ιδιότητα `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αρχείο PPSX ως HTML με `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Το Aspose.Slides for .NET υποστηρίζει όλα τα κύρια λειτουργικά συστήματα. Βεβαιωθείτε ότι πληροίτε τις παρακάτω προϋποθέσεις." %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin
- Ένα περιβάλλον ανάπτυξης, όπως το Microsoft Visual Studio
- Αναφορά στο Aspose.Slides for .NET στο έργο σας

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Δημιουργήθηκε με το Aspose.Slides" title="Προβολή αρχείων PPSX online" description="Η δωρεάν εφαρμογή Aspose.Slides Viewer έχει δημιουργηθεί με το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPSX." button="Άνοιγμα Aspose.Slides Viewer" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς αποδίδει το Aspose.Slides τα αρχεία σας πριν γράψετε κώδικα.
- Ανεβάστε το αρχείο PPSX και δείτε αμέσως τις διαφάνειές του.
- Λειτουργεί σε υπολογιστή και κινητό, χωρίς PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. When a PPSX file is shared with another user and opened, it starts as PowerPoint show unlike PPTX file that opens in editable mode. The sequence of slide show is the same as in the original presentation. All the slides accompany the images, sounds and other embedded media accompany the presentation slides to the PPSX during the slideshow.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Προβολή άλλων αρχείων" subTitle="Μπορείτε επίσης να ανοίξετε και να προβάλετε παρουσιάσεις σε άλλες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/odp/" name="ODP" description="Παρουσίαση OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/otp/" name="OTP" description="Πρότυπο παρουσίασης OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/pot/" name="POT" description="Πρότυπο PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/potm/" name="POTM" description="Πρότυπο PowerPoint με μακροεντολές" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/potx/" name="POTX" description="Πρότυπο PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/pps/" name="PPS" description="Προβολή παρουσίασης PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/ppsm/" name="PPSM" description="Προβολή παρουσίασης PowerPoint με μακροεντολές" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/ppt/" name="PPT" description="Παρουσίαση PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/pptm/" name="PPTM" description="Παρουσίαση PowerPoint με μακροεντολές" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/viewer/pptx/" name="PPTX" description="Παρουσίαση PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

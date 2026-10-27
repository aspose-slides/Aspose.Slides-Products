---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 70
title: Εξαγωγή κειμένου από αρχεία PPT με .NET
url: /el/net/parser/ppt/ 
description: Πηγαίος κώδικας C# για εξαγωγή κειμένου από αρχεία PPT με .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ανάλυση αρχείων PPT με C#" h2="Εξαγάγετε κείμενο και εξετάστε τη μορφοποίηση κειμένου σε αρχεία PPT με API .NET από την πλευρά του διακομιστή."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ανάλυση αρχείου PPT με C#" %}}

Χρησιμοποιήστε το [Aspose.Slides for .NET](/slides/el/net/) για να εξαγάγετε κείμενο από παρουσιάσεις PPT. Εγκαταστήστε το πακέτο από το [NuGet](https://www.nuget.org/packages/aspose.slides.net) ή εκτελέστε την παρακάτω εντολή στην κονσόλα Package Manager.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εντολή" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ανάλυση αρχείων PPT – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αναλύσετε αρχεία PPT σε C#" intro="Η βασική ανάλυση εγγράφων με το API [Aspose.Slides for .NET](/slides/el/net/) απαιτεί μόνο λίγες γραμμές κώδικα." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPT με την `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανακτήστε τα πλαίσια κειμένου με τη `SlideUtil.GetAllTextFrames`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τα πλαίσια κειμένου, τις παραγράφους και τα τμήματα κειμένου.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε τις ιδιότητες `Text`, `FontHeight` και `LatinFont.FontName` όπως χρειάζεται.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Απαιτούνται ένα υποστηριζόμενο περιβάλλον εκτέλεσης .NET και αναφορά στο πακέτο Aspose.Slides for .NET. Μπορείτε να χρησιμοποιήσετε το Visual Studio ή άλλο συμβατό περιβάλλον ανάπτυξης C#." %}}

- Περιβάλλον συμβατό με .NET Framework, .NET, Mono ή Xamarin
- Ένα περιβάλλον ανάπτυξης C#, όπως το Visual Studio
- Το Aspose.Slides for .NET εγκατεστημένο από το NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Δημιουργήθηκε με το Aspose.Slides" title="Εξαγωγή κειμένου και εικόνων online" description="Η δωρεάν εφαρμογή Aspose.Slides Parser έχει δημιουργηθεί με το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPT." button="Άνοιγμα Aspose.Slides Parser" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς διαβάζει το Aspose.Slides τα αρχεία σας πριν γράψετε κώδικα.
- Ανεβάστε ένα αρχείο PPT και λάβετε το κείμενο και τις εικόνες του.
- Κατεβάστε τα πάντα σε ένα αρχείο ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Ένα αρχείο PPT είναι παρουσίαση Microsoft PowerPoint 97-2003 σε δυαδική μορφή αρχείων. Περιέχει διαφάνειες με κείμενο, λίστες με κουκκίδες, εικόνες, πολυμέσα και ενσωματωμένα αντικείμενα OLE. Οι νεότερες εκδόσεις του PowerPoint χρησιμοποιούν τη μορφή PPTX, που βασίζεται στο Office Open XML. Αρχεία PPT μπορούν να δημιουργήσουν και εφαρμογές όπως το OpenOffice Impress και το Apple Keynote.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για ανάλυση" subTitle="Με C# μπορείτε επίσης να αναλύσετε τις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/parser/odp/" name="ODP" description="Παρουσίαση OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/parser/pptx/" name="PPTX" description="Παρουσίαση PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

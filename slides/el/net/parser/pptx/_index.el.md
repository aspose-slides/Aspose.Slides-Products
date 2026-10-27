---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1480
title: Εξαγωγή κειμένου από αρχεία PPTX με .NET
url: /el/net/parser/pptx/ 
description: Πηγαίος κώδικας C# για εξαγωγή κειμένου από αρχεία PPTX με .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ανάλυση αρχείων PPTX με C#" h2="Εξαγάγετε κείμενο και εξετάστε τη μορφοποίηση κειμένου σε αρχεία PPTX με API .NET από την πλευρά του διακομιστή."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ανάλυση αρχείου PPTX με C#" %}}

Χρησιμοποιήστε το [Aspose.Slides for .NET](/slides/el/net/) για να εξαγάγετε κείμενο από παρουσιάσεις PPTX. Εγκαταστήστε το πακέτο από το [NuGet](https://www.nuget.org/packages/aspose.slides.net) ή εκτελέστε την παρακάτω εντολή στην κονσόλα Package Manager.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εντολή" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ανάλυση αρχείων PPTX – C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αναλύσετε αρχεία PPTX σε C#" intro="Η βασική ανάλυση εγγράφων με το API [Aspose.Slides for .NET](/slides/el/net/) απαιτεί μόνο λίγες γραμμές κώδικα." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPTX με την `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Δημιουργήθηκε με το Aspose.Slides" title="Εξαγωγή κειμένου και εικόνων online" description="Η δωρεάν εφαρμογή Aspose.Slides Parser έχει δημιουργηθεί με το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Parser" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς διαβάζει το Aspose.Slides τα αρχεία σας πριν γράψετε κώδικα.
- Ανεβάστε ένα αρχείο PPTX και λάβετε το κείμενο και τις εικόνες του.
- Κατεβάστε τα πάντα σε ένα αρχείο ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Τα αρχεία PPTX είναι παρουσιάσεις που δημιουργούνται με το Microsoft PowerPoint. Σε αντίθεση με τη δυαδική μορφή PPT, το PPTX χρησιμοποιεί τη μορφή Office Open XML. Μια παρουσίαση περιέχει διαφάνειες με κείμενο, εικόνες, μορφοποίηση, κινούμενα εφέ και άλλα πολυμέσα που προβάλλονται ως προβολή διαφανειών.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για ανάλυση" subTitle="Με C# μπορείτε επίσης να αναλύσετε τις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/parser/odp/" name="ODP" description="Παρουσίαση OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/parser/ppt/" name="PPT" description="Παρουσίαση PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

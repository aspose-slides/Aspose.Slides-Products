---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 460
title: Εξαγωγή κειμένου από παρουσιάσεις ODP με C++
url: /el/cpp/parser/odp/ 
description: Εξαγάγετε κείμενο από παρουσιάσεις ODP σε C++. Χρησιμοποιήστε το Aspose.Slides for C++ για ανάλυση διαφανειών, πλαισίων κειμένου, παραγράφων και τμημάτων κειμένου.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ανάλυση παρουσιάσεων ODP σε C++" h2="Χρησιμοποιήστε το Aspose.Slides for C++ για να εξαγάγετε κείμενο από διαφάνειες χωρίς το Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ανάλυση αρχείου ODP με C++" %}}

Χρησιμοποιήστε το Aspose.Slides for C++ για να αναλύσετε αρχεία παρουσιάσεων ODP και να εξαγάγετε κείμενο από διαφάνειες. Το API παρέχει το κείμενο των διαφανειών μέσω των `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` και `IPortion`, ώστε να διαβάζετε το περιεχόμενο χωρίς αυτοματοποίηση του Microsoft PowerPoint. Εγκαταστήστε το πακέτο [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) από το NuGet ή χρησιμοποιήστε την παρακάτω εντολή στην κονσόλα Package Manager.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εντολή" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ανάλυση αρχείων ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αναλύσετε αρχεία ODP σε C++" intro="Εξαγάγετε κείμενο από αρχεία ODP με το Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο ODP με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Λάβετε τα αντικείμενα `ITextFrame` της πρώτης διαφάνειας με τη `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τα αντικείμενα `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τα αντικείμενα `IParagraph` σε κάθε `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τα αντικείμενα `IPortion` σε κάθε `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε το κείμενο με τη `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Το Aspose.Slides for C++ υποστηρίζει τις κύριες πλατφόρμες επιφάνειας εργασίας και διακομιστή. Βεβαιωθείτε ότι το έργο σας πληροί τις παρακάτω προϋποθέσεις." %}}

-  Microsoft Windows, Linux, macOS ή άλλο συμβατό λειτουργικό σύστημα με το υποστηριζόμενο περιβάλλον εκτέλεσης C++.
-  Η βιβλιοθήκη Aspose.Slides for C++ με αναφορά στο έργο σας.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Δημιουργήθηκε με το Aspose.Slides" title="Εξαγωγή κειμένου και εικόνων online" description="Η δωρεάν εφαρμογή Aspose.Slides Parser έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία ODP." button="Άνοιγμα Aspose.Slides Parser" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς διαβάζει το Aspose.Slides τα αρχεία σας πριν γράψετε κώδικα.
- Ανεβάστε ένα αρχείο ODP και λάβετε το κείμενο και τις εικόνες του.
- Κατεβάστε τα πάντα σε ένα αρχείο ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

Ένα αρχείο ODP είναι αρχείο παρουσίασης OpenDocument που χρησιμοποιούν εφαρμογές όπως το OpenOffice Impress και το LibreOffice Impress. Αποθηκεύει διαφάνειες, κείμενο, εικόνες, μορφοποίηση, κινούμενα εφέ και άλλο περιεχόμενο παρουσίασης σε ένα ανοιχτό πακέτο βασισμένο σε XML.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για ανάλυση" subTitle="Με C++ μπορείτε επίσης να αναλύσετε άλλες μορφές παρουσιάσεων." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/parser/ppt/" name="PPT" description="Παρουσίαση PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/parser/pptx/" name="PPTX" description="Παρουσίαση PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

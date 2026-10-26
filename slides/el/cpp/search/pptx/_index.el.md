---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Αναζήτηση κειμένου σε παρουσιάσεις PPTX με C++
url: /el/cpp/search/pptx/
description: Αναζητήστε κείμενο σε παρουσιάσεις PPTX σε C++. Χρησιμοποιήστε το Aspose.Slides for C++ για να βρείτε κείμενο σε αρχεία παρουσιάσεων.
keywords: αναζήτηση λέξεων σε PPTX, εύρεση κειμένου σε PPTX, αναζήτηση κειμένου παρουσίασης PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Αναζήτηση κειμένου σε PPTX με C++" h2="Χρησιμοποιήστε το Aspose.Slides for C++ για να βρείτε κείμενο σε αρχεία παρουσιάσεων χωρίς το Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Αναζήτηση κειμένου σε παρουσίαση PPTX μέσω C++" variant="code" %}}

Το Aspose.Slides for C++ σάς επιτρέπει να αναζητάτε κείμενο σε παρουσιάσεις PPTX. Χρησιμοποιήστε το `SlideUtil::GetAllTextBoxes` για να συλλέξετε τα πλαίσια κειμένου μιας διαφάνειας και, στη συνέχεια, ελέγξτε αν το κείμενό τους περιέχει την απαιτούμενη φράση.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Αναζήτηση κειμένου σε παρουσίαση PPTX με C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αναζητήσετε κείμενο σε PPTX μέσω C++" intro="Ακολουθήστε αυτά τα βήματα για να αναζητήσετε κείμενο σε μια παρουσίαση PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPTX με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Λάβετε την απαιτούμενη διαφάνεια με το `Presentation::get_Slides` και τα πλαίσια κειμένου της με το [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ελέγξτε αν το κείμενο κάθε πλαισίου περιέχει την απαιτούμενη φράση.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή αναζήτηση κειμένου σε αρχεία PPTX" description="Η δωρεάν εφαρμογή Aspose.Slides Search έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Search" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides βρίσκει κείμενο πριν γράψετε κώδικα.
- Αναζητήστε απλό κείμενο ή κανονικές εκφράσεις στο αρχείο PPTX.
- Κατεβάστε τα αποτελέσματα ως αρχείο κειμένου.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για αναζήτηση" subTitle="Με C++, μπορείτε επίσης να αναζητήσετε κείμενο στις ακόλουθες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

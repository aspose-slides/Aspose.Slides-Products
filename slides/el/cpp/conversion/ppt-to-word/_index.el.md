---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή PPT σε Word σε C++
url: /el/cpp/conversion/ppt-to-word/
keywords: Μετατροπή PPT σε Word, PPT σε Word, PPT σε DOC, PowerPoint σε Word, C++ API, Βιβλιοθήκη C++, CPP
description: Μετατροπή PPT σε Word σε C++. Χρησιμοποιήστε το API βιβλιοθήκης C++ για να μετατρέψετε το PowerPoint σε Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή PPT σε Word σε C++" h2="Ισχυρό cross-platform C++ API για μετατροπή PowerPoint σε Word χρησιμοποιώντας κώδικα C++ χωρίς Microsoft PowerPoint ή Office" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή PowerPoint σε Word σε C++" variant="code" %}}

Μπορείτε να μετατρέψετε το PPT σε Word γρήγορα με λίγες μόνο γραμμές κώδικα

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας C++ για τη μετατροπή του PowerPoint σε Word" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή PowerPoint σε Word χρησιμοποιώντας Aspose.Slides και Aspose.Words" %}}

[**Aspose.Slides για C++**](https://products.aspose.com/slides/el/cpp/) και [**Aspose.Words για C++**](https://products.aspose.com/ words/cpp/) είναι ισχυρές βιβλιοθήκες C++ που χρησιμοποιούνται για το χειρισμό και τη μετατροπή παρουσιάσεων PowerPoint, εγγράφων του Word και άλλων αρχείων. Όταν μετατρέπετε το PowerPoint σε Word, ουσιαστικά μετακινείτε τα περιεχόμενα των διαφανειών μιας παρουσίασης σε σελίδες ενός εγγράφου του Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το PPT σε Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε τα **Aspose.Slides για C++** και **Aspose.Words για C++**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε μια παρουσία της κλάσης Presentation και της τάξης Doc.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε την παρουσίαση PPT που θέλετε να μετατρέψετε σε Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε εικόνες και κείμενα με βάση το περιεχόμενο των διαφανειών.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το έγγραφο του Word που προκύπτει.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Δωρεάν Online Μετατροπέας"
  description="[Πώς να μετατρέψετε το PPT σε HTML στην Python](https://products.aspose.com/slides/el/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το PowerPoint σε αρχεία σε άλλες μορφές" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Εξαγωγή κειμένου από αρχεία PPTX με Python
url: /el/python-net/parser/pptx/
description: Εξαγάγετε κείμενο και λεπτομέρειες μορφοποίησης κειμένου από παρουσιάσεις PPTX με Python.
keywords: ανάλυση PPTX με Python, αναλυτής PPTX Python, εξαγωγή δεδομένων από PPTX σε Python, εξαγωγή κειμένου από PPTX με Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Εξαγωγή κειμένου από παρουσιάσεις PPTX με Python" h2="Δημιουργήστε εφαρμογές Python που εξάγουν κείμενο και λεπτομέρειες μορφοποίησης από παρουσιάσεις PowerPoint με το Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Εξαγωγή κειμένου από παρουσίαση PPTX με Python" variant="code" %}}

Το [**Aspose.Slides for Python via .NET**](/slides/el/python-net/) παρέχει τη στατική μέθοδο [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) της `SlideUtil`. Επιστρέφει τα αντικείμενα `TextFrame` ολόκληρης της παρουσίασης και μπορεί να περιλαμβάνει κείμενο από τις κύριες διαφάνειες. Το παρακάτω παράδειγμα εξάγει κείμενο και σχετικές λεπτομέρειες γραμματοσειράς από μια παρουσίαση PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Εξαγωγή κειμένου από παρουσίαση PPTX – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.pptx") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να εξαγάγετε κείμενο από PPTX με Python" intro="Ακολουθήστε αυτά τα βήματα για να εξαγάγετε κείμενο από ένα αρχείο PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε το αρχείο PPTX με την `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη `SlideUtil.get_all_text_frames` και ορίστε αν θα περιλαμβάνονται οι κύριες διαφάνειες.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τα αντικείμενα `TextFrame` που επιστρέφονται.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τη συλλογή `paragraphs` κάθε πλαισίου κειμένου.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε τη συλλογή `portions` κάθε παραγράφου.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε το `text` και τις ιδιότητες μορφοποίησης του τρέχοντος τμήματος.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Δημιουργήθηκε με το Aspose.Slides" title="Εξαγωγή κειμένου και εικόνων online" description="Η δωρεάν εφαρμογή Aspose.Slides Parser έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Parser" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς διαβάζει το Aspose.Slides τα αρχεία σας πριν γράψετε κώδικα.
- Ανεβάστε ένα αρχείο PPTX και λάβετε το κείμενο και τις εικόνες του.
- Κατεβάστε τα πάντα σε ένα αρχείο ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για ανάλυση" subTitle="Με Python μπορείτε επίσης να εξαγάγετε κείμενο από άλλες υποστηριζόμενες μορφές παρουσιάσεων." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/parser/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

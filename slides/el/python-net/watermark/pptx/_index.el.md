---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προσθήκη υδατογραφημάτων σε παρουσιάσεις PPTX με Python
url: /el/python-net/watermark/pptx/
description: Προσθέστε υδατογραφήματα κειμένου και εικόνας σε παρουσιάσεις PPTX με Python και Aspose.Slides.
keywords: προσθήκη υδατογραφήματος σε PPTX, προσθήκη υδατογραφήματος κειμένου σε PPTX, προσθήκη υδατογραφήματος εικόνας σε PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Προσθήκη υδατογραφημάτων σε παρουσιάσεις PPTX με Python" h2="Δημιουργήστε εφαρμογές Python που προσθέτουν υδατογραφήματα κειμένου ή εικόνας σε παρουσιάσεις PPTX με το Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προσθήκη υδατογραφήματος σε παρουσίαση PPTX με Python" variant="code" %}}

Με το [Aspose.Slides for Python via .NET](/slides/el/python-net/) μπορείτε να προσθέσετε υδατογράφημα κειμένου ή εικόνας σε μια παρουσίαση PPTX χωρίς το Microsoft PowerPoint. Ένα υδατογράφημα μπορεί να δηλώνει τον κάτοχο, να επισημαίνει μια παρουσίαση ως εμπιστευτική ή ως πρόχειρη ή να εξασφαλίζει ενιαία εταιρική ταυτότητα. Τα παρακάτω παραδείγματα τοποθετούν το υδατογράφημα στην πρώτη κύρια διαφάνεια, ώστε να εμφανίζεται στις διαφάνειες που τη χρησιμοποιούν.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη υδατογραφήματος κειμένου σε παρουσίαση PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 100, 100, 400, 50)
    watermark_text_frame = watermark_shape.add_text_frame("CONFIDENTIAL")

    watermark_shape.fill_format.fill_type = slides.FillType.NO_FILL
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    watermark_portion = watermark_text_frame.paragraphs[0].portions[0]
    watermark_portion.portion_format.font_height = 32

    watermark_shape.auto_shape_lock.select_locked = True
    watermark_shape.auto_shape_lock.size_locked = True
    watermark_shape.auto_shape_lock.text_locked = True
    watermark_shape.auto_shape_lock.position_locked = True
    watermark_shape.auto_shape_lock.grouping_locked = True

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη υδατογραφήματος εικόνας σε παρουσίαση PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προσθέσετε υδατογράφημα σε PPTX με Python" intro="Ακολουθήστε αυτά τα βήματα για να προσθέσετε υδατογράφημα κειμένου σε παρουσίαση PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ανοίξτε το αρχείο PPTX με την `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Λάβετε την πρώτη κύρια διαφάνεια από τη συλλογή `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε την `add_auto_shape` για να προσθέσετε ένα ορθογώνιο στην κύρια διαφάνεια.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε την `add_text_frame` για να προσθέσετε το κείμενο του υδατογραφήματος και, στη συνέχεια, μορφοποιήστε και κλειδώστε το σχήμα.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε την `save` με `SaveFormat.PPTX` για να αποθηκεύσετε την παρουσίαση με το υδατογράφημα.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Δημιουργήθηκε με το Aspose.Slides" title="Προσθήκη υδατογραφημάτων σε αρχεία PPTX online" description="Η δωρεάν εφαρμογή Aspose.Slides Watermark έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Watermark" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς προσθέτει υδατογραφήματα το Aspose.Slides πριν γράψετε κώδικα.
- Προσθέστε υδατογράφημα κειμένου ή εικόνας στο αρχείο PPTX.
- Κατεβάστε το αρχείο με το υδατογράφημα.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες μορφές που υποστηρίζουν υδατογραφήματα" subTitle="Με Python μπορείτε επίσης να προσθέσετε υδατογραφήματα σε άλλες υποστηριζόμενες μορφές παρουσιάσεων." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

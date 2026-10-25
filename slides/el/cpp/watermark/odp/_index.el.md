---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προσθήκη υδατογραφήματος σε παρουσιάσεις ODP με C++
url: /el/cpp/watermark/odp/
description: Προσθέστε υδατογραφήματα κειμένου ή εικόνας σε παρουσιάσεις ODP σε C++. Χρησιμοποιήστε το Aspose.Slides for C++ για να τοποθετήσετε υδατογραφήματα σε διαφάνειες.
keywords: προσθήκη υδατογραφήματος σε ODP, προσθήκη υδατογραφήματος κειμένου σε ODP, προσθήκη υδατογραφήματος εικόνας σε ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Προσθήκη υδατογραφήματος σε παρουσίαση ODP με C++" h2="Χρησιμοποιήστε το Aspose.Slides for C++ για να προσθέσετε υδατογραφήματα κειμένου ή εικόνας σε αρχεία παρουσιάσεων χωρίς το Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προσθήκη υδατογραφήματος σε παρουσίαση ODP μέσω C++" variant="code" %}}

Το Aspose.Slides for C++ σας επιτρέπει να προσθέτετε υδατογραφήματα κειμένου ή εικόνας σε παρουσιάσεις ODP. Προσθέστε ένα σχήμα υδατογραφήματος στην κύρια διαφάνεια με `AddAutoShape`, προσθέστε κείμενο με `AddTextFrame` ή γεμίστε το σχήμα με μια εικόνα που φορτώνεται μέσω `File::ReadAllBytes` και `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη υδατογραφήματος κειμένου σε ODP με C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη υδατογραφήματος εικόνας σε παρουσίαση ODP με C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προσθέσετε υδατογράφημα σε ODP με C++" intro="Ακολουθήστε αυτά τα βήματα για να προσθέσετε υδατογράφημα κειμένου ή εικόνας σε αρχεία ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο ODP με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Επιλέξτε την κύρια διαφάνεια από τη συλλογή `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε ένα σχήμα υδατογραφήματος με τη μέθοδο `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε κείμενο υδατογραφήματος με τη μέθοδο `AddTextFrame` ή ορίστε γέμισμα εικόνας με `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αρχείο με το υδατογράφημα με `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Δημιουργήθηκε με το Aspose.Slides" title="Προσθήκη υδατογραφημάτων σε αρχεία ODP online" description="Η δωρεάν εφαρμογή Aspose.Slides Watermark έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία ODP." button="Άνοιγμα Aspose.Slides Watermark" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς προσθέτει υδατογραφήματα το Aspose.Slides πριν γράψετε κώδικα.
- Προσθέστε υδατογράφημα κειμένου ή εικόνας στο αρχείο ODP.
- Κατεβάστε το αρχείο με το υδατογράφημα.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες μορφές που υποστηρίζουν υδατογραφήματα" subTitle="Με C++ μπορείτε επίσης να προσθέσετε υδατογραφήματα στις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

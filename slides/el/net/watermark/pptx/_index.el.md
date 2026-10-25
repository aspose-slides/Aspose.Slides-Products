---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προσθήκη υδατογραφήματος σε παρουσιάσεις PPTX με C#
url: /el/net/watermark/pptx/
description: Προσθέστε υδατογραφήματα κειμένου και εικόνας σε παρουσιάσεις PPTX σε C# με το Aspose.Slides for .NET.
keywords: προσθήκη υδατογραφήματος σε PPTX, προσθήκη υδατογραφήματος κειμένου σε PPTX, προσθήκη υδατογραφήματος εικόνας σε PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Προσθήκη υδατογραφήματος σε παρουσίαση PPTX με C#" h2="Δημιουργήστε εφαρμογές .NET που εισάγουν υδατογραφήματα κειμένου ή εικόνας σε αρχεία παρουσιάσεων." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προσθήκη υδατογραφήματος σε παρουσίαση PPTX μέσω C#" variant="code" %}}

Με το [Aspose.Slides for .NET](/slides/el/net/) μπορείτε να προσθέσετε υδατογραφήματα κειμένου και εικόνας σε παρουσιάσεις PPTX. Προσθέστε ένα σχήμα υδατογραφήματος σε μια κύρια διαφάνεια, ώστε το υδατογράφημα να εμφανίζεται στις διαφάνειες που τη χρησιμοποιούν.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη υδατογραφήματος κειμένου σε PPTX με C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη υδατογραφήματος εικόνας σε παρουσίαση PPTX με C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προσθέσετε υδατογράφημα σε PPTX με C#" intro="Ακολουθήστε αυτά τα βήματα για να προσθέσετε υδατογράφημα κειμένου ή εικόνας σε αρχεία PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο `PPTX` με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Επιλέξτε μια κύρια διαφάνεια από τη συλλογή `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `AddAutoShape` για να προσθέσετε ένα σχήμα υδατογραφήματος.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `AddTextFrame` για να προσθέσετε κείμενο υδατογραφήματος ή χρησιμοποιήστε την `AddImage` για υδατογράφημα εικόνας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αρχείο με το υδατογράφημα με `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Δημιουργήθηκε με το Aspose.Slides" title="Προσθήκη υδατογραφημάτων σε αρχεία PPTX online" description="Η δωρεάν εφαρμογή Aspose.Slides Watermark έχει δημιουργηθεί με το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Watermark" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς προσθέτει υδατογραφήματα το Aspose.Slides πριν γράψετε κώδικα.
- Προσθέστε υδατογράφημα κειμένου ή εικόνας στο αρχείο PPTX.
- Κατεβάστε το αρχείο με το υδατογράφημα.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες μορφές που υποστηρίζουν υδατογραφήματα" subTitle="Με C# μπορείτε επίσης να προσθέσετε υδατογραφήματα στις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

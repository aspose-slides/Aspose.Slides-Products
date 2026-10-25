---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προσθήκη υδατογραφήματος σε αρχεία παρουσιάσεων PPTX με Java
url: /el/java/watermark/pptx/
description: Προσθέστε υδατογραφήματα κειμένου και εικόνας σε παρουσιάσεις PPTX σε Java με το Aspose.Slides for Java.
keywords: προσθήκη υδατογραφήματος σε PPTX, προσθήκη υδατογραφήματος κειμένου σε PPTX, προσθήκη υδατογραφήματος εικόνας σε PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Προσθήκη υδατογραφήματος σε παρουσίαση PPTX με Java" h2="Δημιουργήστε εφαρμογές Java που εισάγουν υδατογραφήματα κειμένου ή εικόνας σε αρχεία παρουσιάσεων με API διακομιστή." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Προσθήκη υδατογραφήματος σε παρουσίαση PPTX μέσω Java" variant="code" %}}

Με το [Aspose.Slides for Java](/slides/el/java/) μπορείτε να προσθέσετε υδατογραφήματα κειμένου και εικόνας σε παρουσιάσεις PPTX. Προσθέστε ένα σχήμα υδατογραφήματος σε μια κύρια διαφάνεια, ώστε το υδατογράφημα να εμφανίζεται στις διαφάνειες που τη χρησιμοποιούν.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη υδατογραφήματος κειμένου σε PPTX με Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη υδατογραφήματος εικόνας σε παρουσίαση PPTX με Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προσθέσετε υδατογράφημα σε PPTX με Java" intro="Ακολουθήστε αυτά τα βήματα για να προσθέσετε υδατογράφημα κειμένου ή εικόνας σε αρχεία PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο `PPTX` με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Επιλέξτε μια κύρια διαφάνεια με τη μέθοδο `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `addAutoShape` για να προσθέσετε ένα σχήμα υδατογραφήματος.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `addTextFrame` για να προσθέσετε κείμενο υδατογραφήματος ή χρησιμοποιήστε την `addImage` για υδατογράφημα εικόνας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την παρουσίαση με το υδατογράφημα σε μορφή PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Δημιουργήθηκε με το Aspose.Slides" title="Προσθήκη υδατογραφημάτων σε αρχεία PPTX online" description="Η δωρεάν εφαρμογή Aspose.Slides Watermark έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Watermark" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς προσθέτει υδατογραφήματα το Aspose.Slides πριν γράψετε κώδικα.
- Προσθέστε υδατογράφημα κειμένου ή εικόνας στο αρχείο PPTX.
- Κατεβάστε το αρχείο με το υδατογράφημα.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες μορφές που υποστηρίζουν υδατογραφήματα" subTitle="Με Java μπορείτε επίσης να προσθέσετε υδατογραφήματα στις παρακάτω μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

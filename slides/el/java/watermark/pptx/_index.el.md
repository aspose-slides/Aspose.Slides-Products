---
title: Προσθήκη υδατογραφήματος σε αρχεία παρουσίασης PPTX χρησιμοποιώντας Java
url: /el/java/watermark/pptx/
keywords: Προσθήκη υδατογραφήματος PPTX, προσθήκη υδατογραφήματος κειμένου PPTX, προσθήκη υδατογραφήματος εικόνας PPTX
description: Πηγαίος κώδικας Java για την προσθήκη υδατογραφήματος στην παρουσίαση PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Προσθήκη υδατογραφήματος στην παρουσίαση PPTX χρησιμοποιώντας Java" h2="Δημιουργήστε τις δικές σας εφαρμογές Java για να εισαγάγετε υδατογράφημα κειμένου ή εικόνας σε παρουσίαση PPT, PPTX ή ODP χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Προσθήκη υδατογραφήματος στην παρουσίαση PPTX μέσω Java" %}}
Χρησιμοποιώντας το Aspose.Slides for Java, μπορείτε να προσθέσετε υδατογράφημα στην παρουσίαση PPTX. Τα υδατογραφήματα αποτελούν ουσιαστικό μέρος κάθε παρουσίασης. Χρησιμοποιούνται για την προστασία του περιεχομένου της παρουσίασης από αντιγραφή ή χρήση χωρίς άδεια. Το υδατογράφημα είναι μια ορατή ή αόρατη εικόνα ή κείμενο που τοποθετείται στην κορυφή της παρουσίασης. Μπορεί να χρησιμοποιηθεί για την αναγνώριση του κατόχου της παρουσίασης και για την αποτροπή μη εξουσιοδοτημένης χρήσης. Τα υδατογραφήματα μπορούν επίσης να χρησιμοποιηθούν για να προσθέσουν μια επαγγελματική πινελιά στην παρουσίαση και να την κάνουν να φαίνεται πιο εκλεπτυσμένη. 
{{% blocks/products/pf/agp/code-block title="Προσθήκη υδατογραφήματος κειμένου στο PPTX χρησιμοποιώντας το Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Προσθήκη υδατογραφήματος εικόνας στην παρουσίαση PPTX χρησιμοποιώντας Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.pptx", SaveFormat.Pptx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος προσθήκης υδατογραφήματος στο PPTX μέσω του Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την προσθήκη υδατογραφήματος κειμένου σε αρχεία PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του PPTX με μια παρουσία παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Επιλέξτε την κύρια παρουσίαση
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε τύπο σχήματος χρησιμοποιώντας τη μέθοδο AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε κείμενο υδατογραφήματος χρησιμοποιώντας τη μέθοδο AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές" subTitle="Χρησιμοποιώντας το Java, μπορείτε επίσης να προσθέσετε υδατογράφημα στις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
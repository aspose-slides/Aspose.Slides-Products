---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Επεξεργασία HTML σε Java
url: /el/java/editor/html/
keywords: Επεξεργασία HTML, HTML, Java API, Java Library
description: Επεξεργασία HTML σε Java. Χρησιμοποιήστε το Java Library API για να επεξεργαστείτε το αρχείο HTML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Επεξεργασία HTML σε Java" h2="Βιβλιοθήκη Java υψηλής ταχύτητας και πολλαπλών πλατφορμών για επεξεργασία HTML με χρήση κώδικα Java" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Επεξεργασία HTML σε Java" variant="code" %}}

Χρησιμοποιώντας το [**Aspose.Slides for Java**](https://products.aspose.com/slides/el/java/), μπορείτε να προσθέσετε μια νέα γραμμή κειμένου σε ένα έγγραφο HTML με λίγες μόνο γραμμές κώδικα.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κώδικας Java για επεξεργασία HTML" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        pres.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("page.html", SaveFormat.Html5);
} catch(IOException e) {
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Επεξεργαστείτε HTML χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for Java**](https://products.aspose.com/slides/el/java/) είναι μια ισχυρή βιβλιοθήκη Java που χρησιμοποιείται για το χειρισμό και την επεξεργασία παρουσιάσεων, εγγράφων HTML και άλλων αρχείων. Μπορείτε να επεξεργαστείτε ένα έγγραφο HTML προσθέτοντας μια νέα γραμμή κειμένου σε αυτό.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να επεξεργαστείτε HTML σε Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το **Aspose.Slides για Java**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το έγγραφο HTML που θέλετε να επεξεργαστείτε.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια νέα γραμμή κειμένου.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αλλαγμένο αρχείο HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Επεξεργαστείτε άλλα αρχεία" subTitle="Μπορείτε επίσης να επεξεργαστείτε αρχεία σε άλλες μορφές" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/java/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

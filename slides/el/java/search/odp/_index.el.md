---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Αναζήτηση κειμένου σε αρχεία παρουσιάσεων ODP με Java
url: /el/java/search/odp/
description: Αναζητήστε κείμενο σε παρουσιάσεις ODP σε Java με το Aspose.Slides for Java.
keywords: αναζήτηση λέξεων σε ODP, αναζήτηση κειμένου σε ODP, αναζήτηση κειμένου παρουσίασης ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Αναζήτηση κειμένου σε ODP με Java" h2="Δημιουργήστε εφαρμογές Java που αναζητούν κείμενο σε αρχεία παρουσιάσεων με API διακομιστή." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Αναζήτηση κειμένου σε παρουσίαση ODP μέσω Java" variant="code" %}}

Με το [Aspose.Slides for Java](/slides/el/java/), μπορείτε να αναζητήσετε κείμενο σε παρουσιάσεις ODP. Χρησιμοποιήστε τη μέθοδο `SlideUtil.getAllTextBoxes` για να συλλέξετε τα πλαίσια κειμένου και, στη συνέχεια, εξετάστε τα αντικείμενα `ITextFrame`, `IParagraph` και `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Αναζήτηση κειμένου σε παρουσίαση ODP με Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αναζητήσετε κείμενο σε ODP μέσω Java" intro="Ακολουθήστε αυτά τα βήματα για να αναζητήσετε κείμενο σε μια παρουσίαση ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο ODP με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `SlideUtil.getAllTextBoxes` για να συλλέξετε τα πλαίσια κειμένου κάθε διαφάνειας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εξετάστε τα αντικείμενα `ITextFrame`, `IParagraph` και `IPortion` για να βρείτε το κείμενο που ταιριάζει.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή αναζήτηση κειμένου σε αρχεία ODP" description="Η δωρεάν εφαρμογή Aspose.Slides Search έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία ODP." button="Άνοιγμα Aspose.Slides Search" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides βρίσκει κείμενο πριν γράψετε κώδικα.
- Αναζητήστε απλό κείμενο ή κανονικές εκφράσεις στο αρχείο ODP.
- Κατεβάστε τα αποτελέσματα ως αρχείο κειμένου.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για αναζήτηση" subTitle="Με Java, μπορείτε επίσης να αναζητήσετε κείμενο στις ακόλουθες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

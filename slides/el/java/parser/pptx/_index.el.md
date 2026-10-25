---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1000
title: Εξαγωγή κειμένου από έγγραφα PPTX με Java
url: /el/java/parser/pptx/ 
description: Εξαγάγετε κείμενο από αρχεία PPTX σε Java με το Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ανάλυση αρχείων PPTX σε Java" h2="Εξαγάγετε κείμενο και περιεχόμενο παρουσιάσεων από έγγραφα PPTX με τα API διακομιστή του Aspose.Slides for Java."
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ανάλυση αρχείου PPTX με Java" %}}

Χρησιμοποιήστε το [Aspose.Slides for Java](/slides/el/java/) για να αναλύσετε παρουσιάσεις PPTX και να εξαγάγετε κείμενο από διαφάνειες. Προσθέστε τη βιβλιοθήκη σε ένα έργο Maven με την παρακάτω ρύθμιση αποθετηρίου και εξάρτησης στο αρχείο `pom.xml`.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Αποθετήριο" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εξάρτηση" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ανάλυση αρχείων PPTX – Java" >}}
```java
Presentation presentation = new Presentation("demo.pptx");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αναλύσετε αρχεία PPTX σε Java" intro="Εξαγάγετε κείμενο από μια παρουσίαση PPTX με το Aspose.Slides for Java σε λίγες γραμμές κώδικα." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο `PPTX` με την κλάση `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο `SlideUtil.getAllTextBoxes` για να λάβετε τα πλαίσια κειμένου της πρώτης διαφάνειας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διατρέξτε κάθε αντικείμενο `ITextFrame`, `IParagraph` και `IPortion`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε το κείμενο, το μέγεθος και το όνομα της γραμματοσειράς από κάθε αντικείμενο `IPortion`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Το Aspose.Slides for Java υποστηρίζει τις κύριες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι το περιβάλλον σας πληροί τις παρακάτω προϋποθέσεις." %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
- Η πιο πρόσφατη έκδοση του Aspose.Slides for Java από το [Maven](https://releases.aspose.com/java/repo/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Δημιουργήθηκε με το Aspose.Slides" title="Εξαγωγή κειμένου και εικόνων online" description="Η δωρεάν εφαρμογή Aspose.Slides Parser έχει δημιουργηθεί με το [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Parser" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς διαβάζει το Aspose.Slides τα αρχεία σας πριν γράψετε κώδικα.
- Ανεβάστε ένα αρχείο PPTX και λάβετε το κείμενο και τις εικόνες του.
- Κατεβάστε τα πάντα σε ένα αρχείο ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Files with the PPTX extension use the Office Open XML presentation format. A PPTX file stores slides that can contain text, images, formatting, animations, and other presentation content.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για ανάλυση" subTitle="Με Java μπορείτε επίσης να αναλύσετε άλλες μορφές παρουσιάσεων." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/parser/odp/" name="ODP" description="Παρουσίαση OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/java/parser/ppt/" name="PPT" description="Παρουσίαση PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

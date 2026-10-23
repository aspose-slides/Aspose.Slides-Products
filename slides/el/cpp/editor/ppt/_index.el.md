---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Επεξεργαστείτε το PPT σε C++
url: /el/cpp/editor/ppt/
keywords: Επεξεργασία PPT, Επεξεργασία PowerPoint, PPT, PowerPoint, C++ API, Βιβλιοθήκη C++
description: Επεξεργαστείτε το PPT σε C++. Χρησιμοποιήστε το API βιβλιοθήκης C++ για να επεξεργαστείτε την παρουσίαση του PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Επεξεργαστείτε το PPT σε C++" h2="Βιβλιοθήκη C++ υψηλής ταχύτητας και πολλαπλών πλατφορμών για επεξεργασία PPT με χρήση κώδικα C++" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Επεξεργαστείτε το PPT σε C++" variant="code" %}}

Χρησιμοποιώντας το [**Aspose.Slides για C++**](https://products.aspose.com/slides/el/cpp/), μπορείτε να προσθέσετε μια νέα γραμμή κειμένου σε ένα έγγραφο PPT με λίγες μόνο γραμμές κώδικα.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κωδικός C++ για επεξεργασία PPT" >}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Επεξεργαστείτε το PPT χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for C++**](https://products.aspose.com/slides/el/cpp/) είναι μια ισχυρή βιβλιοθήκη C++ που χρησιμοποιείται για το χειρισμό και την επεξεργασία παρουσιάσεων. Μπορείτε να επεξεργαστείτε μια παρουσίαση PPT προσθέτοντας μια νέα γραμμή κειμένου σε αυτήν.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να επεξεργαστείτε το PPT σε C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το **Aspose.Slides για C++**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε την παρουσίαση PPT που θέλετε να επεξεργαστείτε.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε μια νέα γραμμή κειμένου.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το αλλαγμένο αρχείο PowerPoint.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Δημιουργήθηκε με το Aspose.Slides" title="Επεξεργασία αρχείων PPTX online" description="Η δωρεάν εφαρμογή Aspose.Slides Editor έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Editor" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς χειρίζεται το Aspose.Slides τα αρχεία σας πριν γράψετε κώδικα.
- Ανεβάστε τα αρχεία PPTX και επεξεργαστείτε τα αμέσως.
- Αποθηκεύστε και κατεβάστε το επεξεργασμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Επεξεργαστείτε άλλα αρχεία" subTitle="Μπορείτε επίσης να επεξεργαστείτε αρχεία σε άλλες μορφές" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

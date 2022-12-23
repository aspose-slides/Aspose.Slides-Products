---
title: Επεξεργαστείτε το PDF σε C++
url: /el/cpp/editor/pdf/
keywords: Επεξεργασία PDF, PDF, C++ API, C++ Library
description: Επεξεργαστείτε το PDF σε C++. Χρησιμοποιήστε το API βιβλιοθήκης C++ για να επεξεργαστείτε έγγραφο PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Επεξεργαστείτε το PDF σε C++" h2="Βιβλιοθήκη C++ υψηλής ταχύτητας και πολλαπλών πλατφορμών για επεξεργασία PDF με χρήση κώδικα C++" >}}

{{% blocks/products/pf/feature-page-section h2="Επεξεργαστείτε το PDF χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for C++**](https://products.aspose.com/slides/el/cpp/) είναι μια ισχυρή βιβλιοθήκη C++ που χρησιμοποιείται για το χειρισμό και την επεξεργασία παρουσιάσεων, εγγράφων PDF και άλλων αρχείων. Μπορείτε να επεξεργαστείτε ένα έγγραφο PDF προσθέτοντας μια νέα γραμμή κειμένου σε αυτό. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Επεξεργαστείτε το PDF σε C++" %}}
Χρησιμοποιώντας το [**Aspose.Slides για C++**](https://products.aspose.com/slides/el/cpp/), μπορείτε να προσθέσετε μια νέα γραμμή κειμένου σε ένα έγγραφο PDF με λίγες μόνο γραμμές κώδικα.

{{% blocks/products/pf/agp/code-block title="Κωδικός C++ για επεξεργασία PDF" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να επεξεργαστείτε το PDF σε C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για C++**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε το έγγραφο PDF που θέλετε να επεξεργαστείτε.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια νέα γραμμή κειμένου.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αλλαγμένο αρχείο PDF.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Επεξεργαστείτε άλλα αρχεία" subTitle="Μπορείτε επίσης να επεξεργαστείτε αρχεία σε άλλες μορφές" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
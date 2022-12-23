---
title: Επεξεργασία HTML σε Python
url: /el/python-net/editor/html/
keywords: Επεξεργασία HTML, HTML, Python API, Python Library
description: Επεξεργασία HTML σε Python. Χρησιμοποιήστε το API βιβλιοθήκης Python για να επεξεργαστείτε το αρχείο HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Επεξεργασία HTML σε Python" h2="Βιβλιοθήκη Python υψηλής ταχύτητας και πολλαπλών πλατφορμών για επεξεργασία HTML με χρήση κώδικα Python" >}}

{{% blocks/products/pf/feature-page-section h2="Επεξεργαστείτε HTML χρησιμοποιώντας το Aspose.Slides" %}}

[**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/) είναι μια ισχυρή βιβλιοθήκη Python που χρησιμοποιείται για το χειρισμό και την επεξεργασία παρουσιάσεων, εγγράφων HTML και άλλων αρχείων . Μπορείτε να επεξεργαστείτε ένα έγγραφο HTML προσθέτοντας μια νέα γραμμή κειμένου σε αυτό. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Επεξεργασία HTML σε Python" %}}
Χρησιμοποιώντας το [**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/), μπορείτε να προσθέσετε μια νέα γραμμή κειμένου σε ένα έγγραφο HTML με λίγα μόνο γραμμές κώδικα.

{{% blocks/products/pf/agp/code-block title="Κώδικας Python για επεξεργασία HTML" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("page.html", slides.export.SaveFormat.HTML5)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να επεξεργαστείτε HTML στην Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για Python μέσω .NET**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε το έγγραφο HTML που θέλετε να επεξεργαστείτε.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια νέα γραμμή κειμένου.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αλλαγμένο αρχείο HTML.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Επεξεργαστείτε άλλα αρχεία" subTitle="Μπορείτε επίσης να επεξεργαστείτε αρχεία σε άλλες μορφές" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
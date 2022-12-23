---
title: Επεξεργασία HTML σε C#
url: /el/net/editor/html/
keywords: Επεξεργασία HTML, HTML, C# API, .NET Library
description: Επεξεργασία HTML σε C#. Χρησιμοποιήστε το API βιβλιοθήκης .NET για να επεξεργαστείτε το αρχείο HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Επεξεργασία HTML σε C#" h2="Ισχυρό cross-platform .NET API για επεξεργασία HTML με χρήση κώδικα C# σε πλατφόρμες NET Framework, .NET Core, Windows Azure, Mono ή Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Επεξεργαστείτε HTML χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for .NET**](https://products.aspose.com/slides/el/net/) είναι μια ισχυρή βιβλιοθήκη .NET που χρησιμοποιείται για το χειρισμό και την επεξεργασία παρουσιάσεων, εγγράφων HTML και άλλων αρχείων. Μπορείτε να επεξεργαστείτε ένα έγγραφο HTML προσθέτοντας μια νέα γραμμή κειμένου σε αυτό. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Επεξεργασία HTML σε C#" %}}
Χρησιμοποιώντας το [**Aspose.Slides για .NET**](https://products.aspose.com/slides/el/net/), μπορείτε να προσθέσετε μια νέα γραμμή κειμένου σε ένα έγγραφο HTML με λίγες μόνο γραμμές κώδικα.

{{% blocks/products/pf/agp/code-block title="Κωδικός C# για επεξεργασία HTML" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide
    pres.Slides.AddFromHtml("page.html");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("page.html", SaveFormat.Html);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να επεξεργαστείτε HTML σε C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για .NET**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/net/installation/).
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Συγχώνευση εικόνας σε PDF σε C#
url: /el/net/merger/image-to-pdf/
keywords: Εικόνα σε PDF, Συγχώνευση εικόνας σε PDF, Σύνδεση εικόνας σε PDF, PDF, Εικόνα, C# API, Βιβλιοθήκη .NET
description: Συγχώνευση εικόνας σε PDF σε C#. Χρησιμοποιήστε το API βιβλιοθήκης .NET για να συνδυάσετε εικόνα και PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Συγχώνευση εικόνας σε PDF σε C#" h2="Ισχυρό cross-platform .NET API για συγχώνευση εικόνας σε αρχεία PDF με χρήση κώδικα C# σε πλατφόρμες NET Framework, .NET Core, Windows Azure, Mono ή Xamarin" related="JPG,PNG,HTML,IMAGE,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Συγχώνευση εικόνας σε PDF σε C#" variant="code" %}}

Χρησιμοποιώντας το [**Aspose.Slides για .NET**](https://products.aspose.com/slides/el/net/), μπορείτε να συγχωνεύσετε γρήγορα την εικόνα σε PDF με λίγες μόνο γραμμές κώδικα

{{< blocks/products/pf/slides-design-update-10-2026/code title="Κωδικός C# για τη συγχώνευση εικόνας σε PDF" >}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image1.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image);

    IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("image2.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    pres.Save("MergedFile.pdf", SaveFormat.Pdf);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Συγχώνευση εικόνας σε PDF χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for .NET**](https://products.aspose.com/slides/el/net/) είναι μια ισχυρή βιβλιοθήκη .NET που χρησιμοποιείται για τη δημιουργία, μετατροπή, συγχώνευση και χειρισμό παρουσιάσεων, αρχείων PDF, εικόνων, και άλλα αρχεία. Όταν συγχωνεύετε εικόνα σε PDF, συνδυάζετε αποτελεσματικά εικόνες για να αποκτήσετε ένα μόνο αρχείο PDF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να συγχωνεύσετε εικόνα σε PDF σε C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Εγκαταστήστε το **Aspose.Slides για .NET**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε τις εικόνες που θέλετε να συγχωνεύσετε ως κορνίζες.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε το PDF που προκύπτει.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Δημιουργήθηκε με το Aspose.Slides" title="Συγχώνευση Εικόνα σε PDF online" description="Η δωρεάν εφαρμογή Aspose.Slides Merger έχει δημιουργηθεί με το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία Εικόνα." button="Άνοιγμα Aspose.Slides Merger" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides συγχωνεύει αρχεία πριν γράψετε κώδικα.
- Ανεβάστε πολλά αρχεία Εικόνα και συνδυάστε τα σε ένα αρχείο PDF.
- Κατεβάστε το συγχωνευμένο αποτέλεσμα ως ένα αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Συγχώνευση άλλων αρχείων" subTitle="Μπορείτε επίσης να συνδυάσετε αρχεία σε άλλες μορφές για να αποκτήσετε ένα μόνο αρχείο" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
title: Συγχώνευση SVG σε PNG σε C#
url: /el/net/merger/svg-to-png/
keywords: Συγχώνευση SVG σε PNG, SVG σε PNG, Σύνδεση SVG σε PNG, Συνδυασμός SVG σε PNG, C# API, Βιβλιοθήκη .NET
description: Συγχώνευση SVG σε PNG σε C#. Χρησιμοποιήστε το API βιβλιοθήκης .NET για να συνδυάσετε αρχεία SVG και PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Συγχώνευση SVG σε PNG σε C#" h2="Ισχυρό cross-platform .NET API για συγχώνευση εικόνων SVG σε PNG χρησιμοποιώντας κώδικα C# σε πλατφόρμες NET Framework, .NET Core, Windows Azure, Mono ή Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση SVG σε PNG χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for .NET**](https://products.aspose.com/slides/el/net/) είναι μια ισχυρή βιβλιοθήκη .NET που χρησιμοποιείται για τη συγχώνευση και το χειρισμό παρουσιάσεων, εικόνων και άλλων αρχείων. Όταν συγχωνεύετε SVG σε PNG, συνδυάζετε αποτελεσματικά εικόνες SVG για να λάβετε μια εικόνα PNG.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Συγχώνευση SVG σε PNG σε C#" %}}
Χρησιμοποιώντας το [**Aspose.Slides για .NET**](https://products.aspose.com/slides/el/net/), μπορείτε να συγχωνεύσετε γρήγορα αρχεία SVG σε PNG με λίγες μόνο γραμμές κώδικα

{{% blocks/products/pf/agp/code-block title="Κωδικός C# για τη συγχώνευση SVG σε PNG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    ISvgImage svgImage = new SvgImage("doc.svg");
    IPPImage image = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    ISvgImage svgImage2 = new SvgImage("doc.svg");
    IPPImage image2 = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να συγχωνεύσετε SVG σε PNG σε C#" >}}


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
Φορτώστε τα αρχεία SVG που θέλετε να συγχωνεύσετε.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε την εικόνα PNG που προκύπτει.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Συγχώνευση άλλων αρχείων" subTitle="Μπορείτε επίσης να συνδυάσετε αρχεία σε άλλες μορφές για να αποκτήσετε ένα μόνο αρχείο" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
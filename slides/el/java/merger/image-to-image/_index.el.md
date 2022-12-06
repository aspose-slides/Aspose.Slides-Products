---
title: Συγχώνευση εικόνων σε Java
url: /el/java/merger/image-to-image/
keywords: Συγχώνευση εικόνας, εικόνας σε εικόνα, Σύνδεση εικόνων, Συνδυασμός εικόνων, Java API, Βιβλιοθήκη Java
description: Συγχώνευση εικόνας σε εικόνα σε Java. Χρησιμοποιήστε το Java Library API για να συνδυάσετε εικόνες
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge image in Java" h2="Βιβλιοθήκη Java υψηλής ταχύτητας και πολλαπλών πλατφορμών για συγχώνευση εικόνων με χρήση κώδικα Java" >}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση εικόνας με εικόνα χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for Java**](https://products.aspose.com/slides/el/java/) είναι μια ισχυρή βιβλιοθήκη Java που χρησιμοποιείται για τη συγχώνευση και το χειρισμό παρουσιάσεων, εικόνων και άλλων αρχείων. Όταν συγχωνεύετε εικόνα με εικόνα, συνδυάζετε αποτελεσματικά δύο εικόνες για να λάβετε μία εικόνα.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Συγχώνευση εικόνας σε εικόνα σε Java" %}}
Using [**Aspose.Slides for Java**](https://products.aspose.com/slides/el/java/), you can merge image files quickly with just a few lines of code

{{% blocks/products/pf/agp/code-block title="Κώδικας Java για τη συγχώνευση εικόνας με εικόνα" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να συγχωνεύσετε εικόνες σε Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για Java**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε τη βιβλιοθήκη ως αναφορά στο έργο σας.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε τις εικόνες που θέλετε να συγχωνεύσετε ως κορνίζες.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε την εικόνα που προκύπτει.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Συγχώνευση άλλων αρχείων" subTitle="Μπορείτε επίσης να συνδυάσετε αρχεία σε άλλες μορφές για να αποκτήσετε ένα μόνο αρχείο" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/java/merger/html-to-image/" name="HTML TO IMAGE" >}}    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
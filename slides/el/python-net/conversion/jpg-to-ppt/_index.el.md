---
title: Μετατροπή JPG σε PPT στην Python
url: /el/python-net/conversion/jpg-to-ppt/
keywords: Μετατροπή JPG σε PPT, JPG σε PPT, PowerPoint, JPG, PPT, Python API, Python Library
description: Μετατροπή JPG σε PPT στην Python. Χρησιμοποιήστε το API βιβλιοθήκης Python για να μετατρέψετε εικόνες JPG σε PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατροπή JPG σε PPT στην Python" h2="Ισχυρό API Python σε πολλές πλατφόρμες για μετατροπή JPG σε PPT χρησιμοποιώντας κώδικα Python" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το JPG σε PPT χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/) είναι μια ισχυρή βιβλιοθήκη Python που χρησιμοποιείται για τη δημιουργία, τη μετατροπή και το χειρισμό παρουσιάσεων PowerPoint, PDF, Έγγραφα HTML και άλλα αρχεία. Όταν μετατρέπετε JPG σε PPT, ουσιαστικά δημιουργείτε μια παρουσίαση PowerPoint που περιέχει διαφάνειες που βασίζονται σε εικόνες JPG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή JPG σε PPT στην Python" %}}
Χρησιμοποιώντας το [**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/), μπορείτε να μετατρέψετε εικόνα JPG σε παρουσίαση PowerPoint με λίγες μόνο γραμμές κώδικα:

{{% blocks/products/pf/agp/code-block title="Κώδικας Python για τη μετατροπή JPG σε PPT" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.jpg", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να μετατρέψετε JPG σε PPT στην Python" >}}


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
Φορτώστε την εικόνα JPG που θέλετε να μετατρέψετε σε PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αρχείο που προκύπτει ως παρουσίαση PPT.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Δωρεάν Online Μετατροπέας" sectionDescription="[Πώς να μετατρέψετε το PPT σε HTML στην Python](https://products.aspose.com/slides/el/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές PowerPoint" subTitle="Μπορείτε επίσης να μετατρέψετε αρχεία σε άλλες μορφές σε PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
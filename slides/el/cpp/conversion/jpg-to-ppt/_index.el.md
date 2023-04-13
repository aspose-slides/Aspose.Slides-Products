---
title: Μετατροπή JPG σε PPT σε C++
url: /el/cpp/conversion/jpg-to-ppt/
keywords: Μετατροπή JPG σε PPT, JPG σε PPT, PowerPoint, JPG, PPT, C++ API, Βιβλιοθήκη C++
description: Μετατροπή JPG σε PPT σε C++. Χρησιμοποιήστε το API βιβλιοθήκης C++ για να μετατρέψετε εικόνες JPG σε PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατροπή JPG σε PPT σε C++" h2="Ισχυρό cross-platform C++ API για μετατροπή JPG σε PPT χρησιμοποιώντας κώδικα C++" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το JPG σε PPT χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for C++**](https://products.aspose.com/slides/el/cpp/) είναι μια ισχυρή βιβλιοθήκη C++ που χρησιμοποιείται για τη δημιουργία, μετατροπή και χειρισμό παρουσιάσεων PowerPoint, PDF, εγγράφων HTML και άλλων αρχεία. Όταν μετατρέπετε JPG σε PPT, ουσιαστικά δημιουργείτε μια παρουσίαση PowerPoint που περιέχει διαφάνειες που βασίζονται σε εικόνες JPG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή JPG σε PPT σε C++" %}}
Χρησιμοποιώντας το [**Aspose.Slides για C++**](https://products.aspose.com/slides/el/cpp/), μπορείτε να μετατρέψετε εικόνα JPG σε παρουσίαση PowerPoint με λίγες μόνο γραμμές κώδικα:

{{% blocks/products/pf/agp/code-block title="Κωδικός C++ για μετατροπή JPG σε PPT" offSpacer="true" %}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να μετατρέψετε JPG σε PPT σε C++" >}}


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
Φορτώστε την εικόνα JPG που θέλετε να μετατρέψετε σε PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αρχείο που προκύπτει ως παρουσίαση PPT.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Δωρεάν Online Μετατροπέας" sectionDescription="[Πώς να μετατρέψετε το PPT σε HTML στην Python](https://products.aspose.com/slides/el/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές PowerPoint" subTitle="Μπορείτε επίσης να μετατρέψετε αρχεία σε άλλες μορφές σε PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
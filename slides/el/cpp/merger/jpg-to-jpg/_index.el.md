---
title: Συγχώνευση εικόνων JPG σε C++
url: /el/cpp/merger/jpg-to-jpg/
keywords: Συγχώνευση JPG, JPEG σε JPG, Συμμετοχή σε JPG, Συνδυασμός JPG, C++ API, Βιβλιοθήκη C++
description: Συγχώνευση JPG σε JPG σε C++. Χρησιμοποιήστε το API βιβλιοθήκης C++ για να συνδυάσετε αρχεία JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Συγχώνευση JPG σε C++" h2="Βιβλιοθήκη C++ υψηλής ταχύτητας και πολλαπλών πλατφορμών για συγχώνευση εικόνων JPG με χρήση κώδικα C++" >}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση JPG σε JPG χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides για C++**](https://products.aspose.com/slides/el/cpp/) είναι μια ισχυρή βιβλιοθήκη C++ που χρησιμοποιείται για τη συγχώνευση και το χειρισμό παρουσιάσεων, εικόνων και άλλων αρχείων. Όταν συγχωνεύετε JPG σε JPG, συνδυάζετε αποτελεσματικά δύο εικόνες για να λάβετε μία εικόνα.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Συγχώνευση JPG σε JPEG σε C++" %}}
Χρησιμοποιώντας το [**Aspose.Slides for C++**](https://products.aspose.com/slides/el/cpp/), μπορείτε να συγχωνεύσετε γρήγορα αρχεία JPG με λίγες μόνο γραμμές κώδικα

{{% blocks/products/pf/agp/code-block title="Κωδικός C++ για συγχώνευση JPG σε JPG" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
        
auto image1 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image1.jpg"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 100.0f, 100.0f, image1);
auto image2 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image2.jpg"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 200.0f, 100.0f, 100.0f, image2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.jpg", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Jpeg());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να συγχωνεύσετε το JPG σε C++" >}}


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
Φορτώστε τα αρχεία JPG που θέλετε να συγχωνεύσετε ως κορνίζες.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε την εικόνα JPG που προκύπτει.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Συγχώνευση αρχείων PDF στο Διαδίκτυο" sectionDescription="[Πώς να συγχωνεύσετε το PDF στην Python](https://products.aspose.com/slides/el/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Συγχώνευση άλλων αρχείων" subTitle="Μπορείτε επίσης να συνδυάσετε αρχεία σε άλλες μορφές για να αποκτήσετε ένα μόνο αρχείο" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Συγχώνευση HTML με Εικόνα σε C++
url: /el/cpp/merger/html-to-image/
keywords: Συγχώνευση HTML σε εικόνα, HTML σε εικόνα, Συμμετοχή σε HTML, Συνδυασμός HTML, Εικόνα, C++ API, Βιβλιοθήκη C++
description: Συγχώνευση HTML σε εικόνα σε C++. Χρησιμοποιήστε το API βιβλιοθήκης C++ για να συνδυάσετε HTML με εικόνα
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Συγχώνευση εικόνας σε C++" h2="Βιβλιοθήκη C++ υψηλής ταχύτητας και πολλαπλών πλατφορμών για συγχώνευση HTML με εικόνα χρησιμοποιώντας κώδικα C++" >}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση HTML σε εικόνα χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for C++**](https://products.aspose.com/slides/el/cpp/) είναι μια ισχυρή βιβλιοθήκη C++ που χρησιμοποιείται για τη συγχώνευση και το χειρισμό παρουσιάσεων, εγγράφων HTML και άλλων αρχείων. Όταν συγχωνεύετε HTML με εικόνα, συνδυάζετε αποτελεσματικά τα περιεχόμενα σε έγγραφα HTML για να αποκτήσετε μια ενιαία εικόνα. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Συγχώνευση HTML σε εικόνα σε C++" %}}
Χρησιμοποιώντας το [**Aspose.Slides for C++**](https://products.aspose.com/slides/el/cpp/), μπορείτε να συγχωνεύσετε γρήγορα αρχεία εικόνας με λίγες μόνο γραμμές κώδικα

{{% blocks/products/pf/agp/code-block title="Κώδικας C++ για συγχώνευση HTML με εικόνα" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromHtml(htmlText1);
pres->get_Slides()->AddFromHtml(htmlText2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.png", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Png());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Πώς να συγχωνεύσετε το HTML με την εικόνα στη C++" >}}


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
Φορτώστε τα έγγραφα HTML που θέλετε να συγχωνεύσετε.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε την εικόνα που προκύπτει.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Συγχώνευση άλλων αρχείων" subTitle="Μπορείτε επίσης να συνδυάσετε αρχεία σε άλλες μορφές για να αποκτήσετε ένα μόνο αρχείο" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
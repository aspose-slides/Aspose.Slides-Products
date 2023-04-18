---
title: Καταργήστε τον σχολιασμό PPT χρησιμοποιώντας C++
weight: 4380
url: /el/cpp/annotation/ppt/ 
description: Πηγαίος κώδικας C++ για διαγραφή σχολιασμών από PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Καταργήστε τα σχόλια και τους συντάκτες σχολίων από το PPT στη C++" h2="Δημιουργήστε τις δικές σας εφαρμογές C++ για να χειρίζεστε σχόλια και συντάκτες σε αρχεία εγγράφων χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Καταργήστε τα σχόλια από το PPT μέσω C++" %}}
Για να καταργήσουμε τους σχολιασμούς από το αρχείο PPT, θα χρησιμοποιήσουμε το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/) API που είναι πλούσιο σε χαρακτηριστικά, ισχυρό και εύκολο στη χρήση API χειρισμού εγγράφων για πλατφόρμα C++.
{{% blocks/products/pf/agp/code-block title="Διαγραφή σχολιασμών από το PPT - C++" offSpacer="true" %}}

```cpp

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System::Drawing;

auto presentation = System::MakeObject<Presentation>(u"example.ppt");

// Deletes all comments from the presentation
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}
        
// Deletes all authors
presentation->get_CommentAuthors()->Clear();
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να αφαιρέσετε σχόλια από το PPT μέσω C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για C++**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε το PPT με μια παρουσία της κλάσης παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Επανάληψη σε όλους τους Συντάκτες του φορτωμένου PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κατάργηση όλων των σχολίων ενός συγγραφέα
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κατάργηση όλων των Συντακτών στο τέλος
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές σχολιασμού" subTitle="Χρησιμοποιώντας C++, μπορεί κανείς εύκολα να σχολιάσει άλλες μορφές, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
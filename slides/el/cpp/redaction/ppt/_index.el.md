---
title: Διορθώστε τα αρχεία παρουσίασης PPT χρησιμοποιώντας το C++
url: /el/cpp/redaction/ppt/
keywords: Διορθώστε το PPT, βρείτε και αντικαταστήστε κείμενο στο PPT, ενημερώστε την παρουσίαση PPT
description: Πηγαίος κώδικας C++ για εύρεση και αντικατάσταση κειμένου στην παρουσίαση PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Διορθώστε το PPT χρησιμοποιώντας το C++" h2="Δημιουργήστε τις δικές σας εφαρμογές C++ για να βρείτε και να αντικαταστήσετε κείμενο σε αρχεία παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή. Μάθετε πώς να αναζητάτε και να αντικαθιστάτε κείμενο σε περιεχόμενο, σχόλια ή μεταδεδομένα των παρουσιάσεων PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Διόρθωση PPT παρουσίασης μέσω C++" %}}
Μια βασική αναζήτηση εγγράφων και αντικατάσταση κειμένου σε περιεχόμενα, σχόλια, σημειώσεις διαφανειών ή μεταδεδομένα με API του Aspose.Slides for C++ μπορεί να γίνει με λίγες μόνο γραμμές κώδικα. Εύρεση και αντικατάσταση κειμένου στο PowerPoint και το OpenOffice. Επεξεργασία κειμένου, σχολίων, μεταδεδομένων στην παρουσίαση μέσω αντιστοίχισης δεδομένων regexp.
{{% blocks/products/pf/agp/code-block title="Διορθώστε την παρουσίαση PPT χρησιμοποιώντας C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.ppt", SaveFormat::Ppt);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος επεξεργασίας του PPT μέσω του C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για να επεξεργαστείτε αρχεία PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του PPT με μια παρουσία παρουσίασης.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Χρησιμοποιήστε τη μέθοδο [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) για να βρείτε και να αντικαταστήσετε κείμενο.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Διαδικτυακές Ζωντανές επιδείξεις επεξεργασίας PPT" sectionDescription="Αναζητήστε και αντικαταστήστε κείμενο σε περιεχόμενα, σχόλια ή μεταδεδομένα σε έγγραφα PPT αυτήν τη στιγμή." >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές Redact" subTitle="Χρησιμοποιώντας το C++, μπορείτε επίσης να επεξεργαστείτε τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
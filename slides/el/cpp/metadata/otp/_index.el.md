---
title: Προβολή ή επεξεργασία μεταδεδομένων αρχείων OTP χρησιμοποιώντας C++
url: /el/cpp/metadata/otp/
keywords: Επεξεργασία μεταδεδομένων OTP, Προβολή μεταδεδομένων OTP, Επεξεργασία ιδιοτήτων OTP, Προβολή ιδιοτήτων OTP
description: Πηγαίος κώδικας C++ για επεξεργασία ή προβολή μεταδεδομένων μορφής OTP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Επεξεργασία ιδιοτήτων OTP χρησιμοποιώντας C++" h2="Δημιουργήστε τις δικές σας εφαρμογές C++ για να τροποποιήσετε τις Ενσωματωμένες και Προσαρμοσμένες ιδιότητες σε αρχεία παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="OTP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Τροποποίηση ιδιοτήτων OTP μέσω C++" %}}
Χρησιμοποιώντας το Aspose.Slides for C++, οι προγραμματιστές μπορούν να έχουν πρόσβαση και να τροποποιούν τις τιμές των ενσωματωμένων ιδιοτήτων καθώς και των προσαρμοσμένων ιδιοτήτων. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν την ιδιότητα [DocumentProperties](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) που εκτίθεται από το αντικείμενο Παρουσίασης για να αποκτήσουν πρόσβαση στις ιδιότητες του εγγράφου του αρχείου παρουσίασης.
{{% blocks/products/pf/agp/code-block title="Τροποποίηση ενσωματωμένων ιδιοτήτων OTP - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class that represents the Presentation
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"presentation.otp");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

// Set the builtin properties
documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.otp", SaveFormat::Otp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Προσθήκη προσαρμοσμένων ιδιοτήτων στο OTP - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class
auto presentation = System::MakeObject<Presentation>();

// Getting Document Properties
auto documentProperties = presentation->get_DocumentProperties();

// Adding Custom properties
documentProperties->idx_set(u"New Custom", ObjectExt::Box<int32_t>(12));
documentProperties->idx_set(u"My Name", ObjectExt::Box<String>(u"Aspose Metadata Editor"));
documentProperties->idx_set(u"Custom", ObjectExt::Box<int32_t>(124));

// Getting property name at particular index
String getPropertyName = documentProperties->GetCustomPropertyName(2);

// Removing selected property
documentProperties->RemoveCustomProperty(getPropertyName);

// Saving presentation
presentation->Save(u"CustomDocumentProperties_out.otp", SaveFormat::Otp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος εξαγωγής μεταδεδομένων του OTP μέσω του C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την εξαγωγή μεταδεδομένων από αρχεία OTP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε την κλάση Presentation με διαδρομή προς το αρχείο OTP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Λήψη αντικειμένου DocumentProperties που σχετίζεται με την Παρουσίαση
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κάντε βρόχο πάνω από τα στοιχεία στο αντικείμενο DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Πρόσβαση και τροποποίηση προσαρμοσμένων ιδιοτήτων
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές μεταδεδομένων" subTitle="Χρησιμοποιώντας το C++, μπορείτε επίσης να χειριστείτε μεταδεδομένα πολλών άλλων μορφών, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
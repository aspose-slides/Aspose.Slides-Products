---
title: Προβολή ή επεξεργασία μεταδεδομένων αρχείων PPSX χρησιμοποιώντας Python
url: /el/python-net/metadata/ppsx/
keywords: Επεξεργασία μεταδεδομένων PPSX, Προβολή μεταδεδομένων PPSX, Επεξεργασία ιδιοτήτων PPSX, Προβολή ιδιοτήτων PPSX
description: Πηγαίος κώδικας Python για επεξεργασία ή προβολή μεταδεδομένων μορφής PPSX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Επεξεργασία ιδιοτήτων PPSX χρησιμοποιώντας Python" h2="Δημιουργήστε τις δικές σας εφαρμογές Python για να τροποποιήσετε τις Ενσωματωμένες και Προσαρμοσμένες ιδιότητες σε αρχεία παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Τροποποίηση ιδιοτήτων PPSX μέσω Python" %}}
Χρησιμοποιώντας το Aspose.Slides for Python via .NET, οι προγραμματιστές μπορούν να έχουν πρόσβαση και να τροποποιούν τις τιμές των ενσωματωμένων ιδιοτήτων καθώς και των προσαρμοσμένων ιδιοτήτων. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν την ιδιότητα [DocumentProperties](https://reference.aspose.com/slides/python-net/aspose.slides/documentproperties/) που εκτίθεται από το αντικείμενο Παρουσίασης για να αποκτήσουν πρόσβαση στις ιδιότητες του εγγράφου του αρχείου παρουσίασης.
{{% blocks/products/pf/agp/code-block title="Τροποποίηση ενσωματωμένων ιδιοτήτων PPSX - Python" offSpacer="true" %}}

```py

import aspose.slides as slides

# Instantiate the Presentation class that represents the Presentation
with slides.Presentation(path + "ModifyBuiltinProperties.ppsx") as presentation:
    # Create a reference to object associated with Presentation
    documentProperties = presentation.document_properties

    # Set the builtin properties
    documentProperties.author = "Aspose.Slides for Python"
    documentProperties.title = "Modifying Presentation Properties"
    documentProperties.subject = "Aspose Subject"
    documentProperties.comments = "Aspose Description"
    documentProperties.manager = "Aspose Manager"

    # save your presentation to a file
    presentation.save("DocumentProperties_out.ppsx", slides.export.SaveFormat.PPSX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Προσθήκη προσαρμοσμένων ιδιοτήτων στο PPSX - Python" offSpacer="true" %}}

```py

import aspose.slides as slides

# Instantiate the Presentation class
with slides.Presentation() as presentation:
    # Getting Document Properties
    documentProperties = presentation.document_properties

    # Adding Custom properties
    documentProperties.set_custom_property_value("New Custom", 12)
    documentProperties.set_custom_property_value("My Nam", "Aspose Metadata Editor")
    documentProperties.set_custom_property_value("Custom", 124)

    # Getting property name at particular index
    getPropertyName = documentProperties.get_custom_property_name(2)

    # Removing selected property
    documentProperties.remove_custom_property(getPropertyName)

    # Saving presentation
    presentation.save("CustomDocumentProperties_out.ppsx", slides.export.SaveFormat.PPSX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος εξαγωγής μεταδεδομένων του PPSX μέσω του Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την εξαγωγή μεταδεδομένων από αρχεία PPSX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Δημιουργήστε την κλάση Presentation με διαδρομή προς το αρχείο PPSX
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

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές μεταδεδομένων" subTitle="Χρησιμοποιώντας το Python, μπορείτε επίσης να χειριστείτε μεταδεδομένα πολλών άλλων μορφών, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
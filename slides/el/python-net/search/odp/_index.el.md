---
title: Αναζήτηση κειμένου σε ODP Αρχεία παρουσίασης χρησιμοποιώντας Python
url: /el/python-net/search/odp/
keywords: αναζήτηση λέξεων σε ODP, αναζήτηση και αντικατάσταση κειμένου σε ODP, κείμενο αναζήτησης ODP Παρουσίαση
description: Πηγαίος κώδικας Python για αναζήτηση κειμένου στην παρουσίαση ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Αναζήτηση κειμένου ODP χρησιμοποιώντας Python" h2="Δημιουργήστε τις δικές σας εφαρμογές Python για αναζήτηση και αντικατάσταση κειμένου σε αρχεία παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή. Μάθετε πώς να βρίσκετε όλες τις εισόδους μιας συγκεκριμένης λέξης ή φράσης σε έγγραφα παρουσίασης. Αναζήτηση κειμένου με ακριβή αντιστοίχιση δεδομένων και αντιστοίχιση τυπικών εκφράσεων." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Αναζήτηση και αντικατάσταση κειμένου ODP Παρουσίαση μέσω Python" %}}
Μια βασική αναζήτηση εγγράφων και αντικατάσταση κειμένου σε περιεχόμενα, σχόλια, σημειώσεις διαφανειών ή μεταδεδομένα με API του Aspose.Slides for Python via .NET μπορεί να γίνει με λίγες μόνο γραμμές κώδικα. Χρησιμοποιήστε αντιστοίχιση τυπικών εκφράσεων, αντιστοίχιση πεζών-κεφαλαίων για αναζήτηση κειμένου στην παρουσίαση. Αναζήτηση κειμένου σε τίτλους, περιεχόμενο, υποσέλιδο ή κεφαλίδα.
{{% blocks/products/pf/agp/code-block title="Κείμενο αναζήτησης ODP Παρουσίαση με χρήση Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.odp") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος αναζήτησης κειμένου σε ODP μέσω Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την αναζήτηση αρχείων κειμένου ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του ODP με μια παρουσία παρουσίασης.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Χρησιμοποιήστε τη μέθοδο [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) για να βρείτε και να αντικαταστήσετε κείμενο.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Διαδικτυακή αναζήτηση σε ζωντανές επιδείξεις ODP" sectionDescription="Αναζητήστε και αντικαταστήστε κείμενο σε περιεχόμενα, σχόλια ή μεταδεδομένα σε έγγραφα ODP αυτήν τη στιγμή." >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές αναζήτησης" subTitle="Χρησιμοποιώντας το Python, μπορείτε επίσης να αναζητήσετε κείμενο στις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
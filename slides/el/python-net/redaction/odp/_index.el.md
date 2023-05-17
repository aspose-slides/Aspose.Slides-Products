---
title: Διορθώστε τα αρχεία παρουσίασης ODP χρησιμοποιώντας το Python
url: /el/python-net/redaction/odp/
keywords: Διορθώστε το ODP, βρείτε και αντικαταστήστε κείμενο στο ODP, ενημερώστε την παρουσίαση ODP
description: Πηγαίος κώδικας Python για εύρεση και αντικατάσταση κειμένου στην παρουσίαση ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Διορθώστε το ODP χρησιμοποιώντας το Python" h2="Δημιουργήστε τις δικές σας εφαρμογές Python για να βρείτε και να αντικαταστήσετε κείμενο σε αρχεία παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή. Μάθετε πώς να αναζητάτε και να αντικαθιστάτε κείμενο σε περιεχόμενο, σχόλια ή μεταδεδομένα των παρουσιάσεων ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Διόρθωση ODP παρουσίασης μέσω Python" %}}
Μια βασική αναζήτηση εγγράφων και αντικατάσταση κειμένου σε περιεχόμενα, σχόλια, σημειώσεις διαφανειών ή μεταδεδομένα με API του Aspose.Slides for Python via .NET μπορεί να γίνει με λίγες μόνο γραμμές κώδικα. Εύρεση και αντικατάσταση κειμένου στο PowerPoint και το OpenOffice. Επεξεργασία κειμένου, σχολίων, μεταδεδομένων στην παρουσίαση μέσω αντιστοίχισης δεδομένων regexp.
{{% blocks/products/pf/agp/code-block title="Διορθώστε την παρουσίαση ODP χρησιμοποιώντας Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.odp") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος επεξεργασίας του ODP μέσω του Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για να επεξεργαστείτε αρχεία ODP." >}}

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

{{< blocks/products/pf/agp/demobox sectionTitle="Διαδικτυακές Ζωντανές επιδείξεις επεξεργασίας ODP" sectionDescription="Αναζητήστε και αντικαταστήστε κείμενο σε περιεχόμενα, σχόλια ή μεταδεδομένα σε έγγραφα ODP αυτήν τη στιγμή." >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές Redact" subTitle="Χρησιμοποιώντας το Python, μπορείτε επίσης να επεξεργαστείτε τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
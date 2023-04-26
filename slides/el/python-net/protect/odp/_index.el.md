---
title: Προστασία αρχείων παρουσίασης ODP χρησιμοποιώντας Python
url: /el/python-net/protect/odp/
keywords: Προστασία εγγραφής ODP, Κρυπτογράφηση παρουσίασης ODP, Κλείδωμα ODP, Προστασία ODP
description: Πηγαίος κώδικας Python για προστασία της παρουσίασης ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Κλείδωμα ή προστασία με κωδικό πρόσβασης ODP χρησιμοποιώντας Python" h2="Δημιουργήστε τις δικές σας εφαρμογές Python για την προστασία των αρχείων παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Προστασία παρουσίασης ODP μέσω Python" %}}
Χρησιμοποιώντας το Aspose.Slides for Python via .NET, μπορείτε να προστατέψετε την παρουσίασή σας ODP από άνοιγμα ή τροποποίηση ορίζοντας έναν κωδικό πρόσβασης. Στη συνέχεια, για να ανοίξει ή να τροποποιήσει την κλειδωμένη παρουσίαση, ο χρήστης πρέπει να δώσει τον κωδικό πρόσβασης.
{{% blocks/products/pf/agp/code-block title="Κρυπτογράφηση παρουσίασης ODP χρησιμοποιώντας Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ρύθμιση της προστασίας εγγραφής σε μια παρουσίαση ODP χρησιμοποιώντας Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος προστασίας με κωδικό πρόσβασης ODP μέσω Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την προστασία των αρχείων ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του ODP με μια παρουσία παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προστατέψτε την παρουσίαση χρησιμοποιώντας την κλάση ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές προστασίας" subTitle="Χρησιμοποιώντας το Python, μπορείτε επίσης να προστατεύσετε τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
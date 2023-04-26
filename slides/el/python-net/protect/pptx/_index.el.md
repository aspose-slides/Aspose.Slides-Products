---
title: Προστασία αρχείων παρουσίασης PPTX χρησιμοποιώντας Python
url: /el/python-net/protect/pptx/
keywords: Προστασία εγγραφής PPTX, Κρυπτογράφηση παρουσίασης PPTX, Κλείδωμα PPTX, Προστασία PPTX
description: Πηγαίος κώδικας Python για προστασία της παρουσίασης PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Κλείδωμα ή προστασία με κωδικό πρόσβασης PPTX χρησιμοποιώντας Python" h2="Δημιουργήστε τις δικές σας εφαρμογές Python για την προστασία των αρχείων παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Προστασία παρουσίασης PPTX μέσω Python" %}}
Χρησιμοποιώντας το Aspose.Slides for Python via .NET, μπορείτε να προστατέψετε την παρουσίασή σας PPTX από άνοιγμα ή τροποποίηση ορίζοντας έναν κωδικό πρόσβασης. Στη συνέχεια, για να ανοίξει ή να τροποποιήσει την κλειδωμένη παρουσίαση, ο χρήστης πρέπει να δώσει τον κωδικό πρόσβασης.
{{% blocks/products/pf/agp/code-block title="Κρυπτογράφηση παρουσίασης PPTX χρησιμοποιώντας Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ρύθμιση της προστασίας εγγραφής σε μια παρουσίαση PPTX χρησιμοποιώντας Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος προστασίας με κωδικό πρόσβασης PPTX μέσω Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την προστασία των αρχείων PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του PPTX με μια παρουσία παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προστατέψτε την παρουσίαση χρησιμοποιώντας την κλάση ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές προστασίας" subTitle="Χρησιμοποιώντας το Python, μπορείτε επίσης να προστατεύσετε τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
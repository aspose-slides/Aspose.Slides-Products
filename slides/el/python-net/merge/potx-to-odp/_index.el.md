---
title: Συγχώνευση αρχείων POTX σε ODP χρησιμοποιώντας Python
url: /el/python-net/merge/potx-to-odp/
keywords: Συγχώνευση POTX σε ODP, Join POTX σε ODP, Combine POTX σε ODP, PowerPoint, Presentation, ODP, Python, Aspose
description: Συγχώνευση πολλαπλών αρχείων POTX στην Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Συγχώνευση αρχείων POTX σε ODP μαζί στην Python" h2="API Python υψηλής ταχύτητας και πολλαπλών πλατφορμών που βοηθά στην ανάπτυξη εφαρμογών με δυνατότητα δημιουργίας, συγχώνευσης, επιθεώρησης ή μετατροπής αρχείων παρουσίασης Microsoft PowerPoint και OpenOffice χωρίς τη χρήση λογισμικού όπως Microsoft ή Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση POTX σε ODP στην Python" %}}

Η [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/el/python-net/) είναι μια ισχυρή βιβλιοθήκη Python για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους συνδυασμού πολλαπλών παρουσιάσεων POTX. Όταν συγχωνεύετε μια παρουσίαση με μια άλλη, συνδυάζετε αποτελεσματικά τις διαφάνειές τους σε μια παρουσίαση για να αποκτήσετε ένα αρχείο. Το Aspose.Slides σάς επιτρέπει να συγχωνεύσετε δύο παρουσιάσεις με διαφορετικούς τρόπους. Μπορείτε να συγχωνεύσετε παρουσιάσεις με όλα τα σχήματα, στυλ, κείμενα, μορφοποίηση, σχόλια, κινούμενα σχέδια κ.λπ. χωρίς να χρειάζεται να ανησυχείτε για απώλεια ποιότητας ή δεδομένων.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Συγχώνευση αρχείων POTX σε ODP χρησιμοποιώντας Python" %}}
Για να συγχωνεύσετε τις παρουσιάσεις του PowerPoint, θα χρειαστεί να κλωνοποιήσετε τις διαφάνειες από τη μία παρουσίαση στην άλλη.

{{% blocks/products/pf/agp/code-block title="Κώδικας Python για συγχώνευση πολλαπλών POTX σε ένα αρχείο ODP" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.potx") as pres1:
    with slides.Presentation("presentation2.potx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να συγχωνεύσετε το POTX στο ODP χρησιμοποιώντας το Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για να συγχωνεύσετε δύο αρχεία POTX και να αποθηκεύσετε το αποτέλεσμα ως ODP στην Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/el/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο Python σας.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ανοίξτε τα αρχεία πηγής POTX στην Python.
```
pres1 = slides.Presentation('pres1.potx')
pres2 = slides.Presentation('pres2.potx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Συνδυάστε αρχεία POTX χρησιμοποιώντας τη μέθοδο [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε την παρουσίαση και λάβετε αποτέλεσμα ως μεμονωμένο αρχείο ODP.
```
pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Εξαγωγή POTX σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να συνδυάσετε το POTX και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-pptx/" name="POTX TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-ppt/" name="POTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-pdf/" name="POTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-html/" name="POTX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-png/" name="POTX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-bmp/" name="POTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-jpg/" name="POTX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-fodp/" name="POTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-gif/" name="POTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-otp/" name="POTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-pot/" name="POTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-potm/" name="POTX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-pps/" name="POTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-ppsm/" name="POTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-ppsx/" name="POTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-pptm/" name="POTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-svg/" name="POTX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-tiff/" name="POTX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/merge/potx-to-xps/" name="POTX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
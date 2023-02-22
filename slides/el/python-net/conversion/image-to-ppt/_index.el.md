---
title: Μετατροπή εικόνας σε PPT στην Python
url: /el/python-net/conversion/image-to-ppt/
keywords: Εικόνα σε PPT, Μετατροπή εικόνας σε PPT, Python API, Python Library, Εικόνα, PPT
description: Μετατροπή εικόνας σε PPT στην Python. Χρησιμοποιήστε το API βιβλιοθήκης Python για να μετατρέψετε αρχεία εικόνας σε PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατροπή εικόνας σε PPT στην Python" h2="Βιβλιοθήκη Python υψηλής ταχύτητας και πολλαπλών πλατφορμών που βοηθά στην ανάπτυξη εφαρμογών με δυνατότητα δημιουργίας, συγχώνευσης, επιθεώρησης ή μετατροπής αρχείων παρουσίασης Microsoft PowerPoint και OpenOffice χωρίς τη χρήση λογισμικού όπως Microsoft ή Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή εικόνας σε PPT στην Python" %}}

Η [**Aspose.Slides for Python μέσω .NET**](https://products.aspose.com/slides/el/python-net/) είναι μια ισχυρή βιβλιοθήκη Python για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής της εικόνας σε PPT. Χρησιμοποιώντας το **Aspose.Slides για Python μέσω .NET**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει την εικόνα σε αρχεία PPT με λίγες μόνο γραμμές κώδικα Python.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides for Python εξάγει αρχεία εικόνας σε μορφές αρχείων PPT γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέπετε εικόνα σε PDF και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή εικόνας σε PPT χρησιμοποιώντας Python" %}}
Για να μετατρέψετε την εικόνα σε PPT, θα χρειαστεί να δημιουργήσετε την Παρουσίαση από το αρχείο εικόνας και να την αποθηκεύσετε ως PPT.

{{% blocks/products/pf/agp/code-block title="Κώδικας Python για τη μετατροπή εικόνας σε PPT" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.ppt", slides.export.SaveFormat.PPT)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να μετατρέψετε την εικόνα σε PPT χρησιμοποιώντας το Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για τη μετατροπή της εικόνας σε PPT στην Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/el/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο Python σας.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ανοίξτε τα αρχεία εικόνας πηγής στην Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αποτέλεσμα ως αρχείο PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Μετατροπή εικόνας σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε την εικόνα και να την αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
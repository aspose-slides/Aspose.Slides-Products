---
title: Μετατροπή POT σε SVG στην Python
weight: 1070
url: /el/python-net/conversion/pot-to-svg/ 
keywords: "Convert, PowerPoint, POT, SVG, Presentation, Python"
description: Δείγμα κώδικα για μετατροπή POT σε SVG Python. Χρησιμοποιήστε το PowerPoint Python API για ομαδική μετατροπή αρχείων POT σε αρχεία SVG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή POT σε SVG στην Python" h2="Ισχυρή βιβλιοθήκη PowerPoint Python για μετατροπή POT σε SVG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Μετατροπή POT σε SVG στην Python" %}}

Θέλετε να μετατρέψετε αρχεία POT σε SVG μέσω προγραμματισμού; Χρησιμοποιώντας το [*Aspose.Slides for Python μέσω .NET*](https://products.aspose.com/slides/el/python-net/) οποιοσδήποτε προγραμματιστής μπορεί να μετατρέψει το POT σε μορφή SVG με λίγες μόνο γραμμές κώδικα Python.

Ως σύγχρονο API επεξεργασίας παρουσιάσεων, το Aspose.Slides for Python δημιουργεί γρήγορα SVG από το POT. Δοκιμάστε την ποιότητα της μετατροπής POT σε SVG απευθείας στο [browser] σας (https://products.aspose.app/slides/conversion). Η βιβλιοθήκη Aspose PowerPoint PPTX σάς επιτρέπει να μετατρέπετε αρχεία POT σε πολλές δημοφιλείς μορφές.

Μπορείτε να εγκαταστήσετε τη βιβλιοθήκη από το [PyPI](https://pypi.org/project/Aspose.Slides/) χρησιμοποιώντας την ακόλουθη εντολή pip:

{{% blocks/products/pf/agp/code-block title="Κονσόλα/Τερματικό" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το POT σε SVG στην Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για να μετατρέψετε ένα αρχείο POT σε SVG χρησιμοποιώντας Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση αρχείου POT με μια παρουσία της κλάσης Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Καλέστε τη μέθοδο «αποθήκευση» ενώ προσδιορίζετε τη διαδρομή αρχείου εξόδου και το SaveFormat.SVG ως παραμέτρους
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Το αρχείο POT θα αποθηκευτεί στην καθορισμένη διαδρομή
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε το δείγμα πηγαίου κώδικα μετατροπής Python, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Λειτουργικό σύστημα που βασίζεται σε Microsoft Windows ή Linux (δείτε [περισσότερα](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 ή νεότερη έκδοση
- Aspose.Slides για Python που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή POT σε SVG Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pot") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Αποθήκευση POT ως SVG στην Python" %}}
Χρησιμοποιήστε τη δωρεάν εφαρμογή για να δείτε μια επίδειξη της διαδικασίας μετατροπής POT σε SVG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Δωρεάν εφαρμογή για μετατροπή POT σε SVG" 
        sectionDescription="[Δοκιμάστε τη δωρεάν εφαρμογή MP4 To MP3](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το POT σε πολλές άλλες μορφές αρχείων. Δείτε άλλες υποστηριζόμενες μετατροπές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-bmp/" name="POT TO BMP" description="Εικόνα Bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-emf/" name="POT TO EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-fodp/" name="POT TO FODP" description="Επίπεδη παρουσίαση XML OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-gif/" name="POT TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-html/" name="POT TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-jpg/" name="POT TO JPG" description="Εικόνα JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-odp/" name="POT TO ODP" description="Μορφή παρουσίασης OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-otp/" name="POT TO OTP" description="Τυπική μορφή OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-pdf/" name="POT TO PDF" description="Μορφή φορητού εγγράφου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-png/" name="POT TO PNG" description="Φορητά γραφικά δικτύου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-potm/" name="POT TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-potx/" name="POT TO POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-pps/" name="POT TO PPS" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-ppsx/" name="POT TO PPSX" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-pptm/" name="POT TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-pptx/" name="POT TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-swf/" name="POT TO SWF" description="Μορφή SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-tiff/" name="POT TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pot-to-xps/" name="POT TO XPS" description="Προδιαγραφές χαρτιού XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Μετατροπή PDF σε PPS στην Python
weight: 790
url: /el/python-net/conversion/pdf-to-pps/ 
keywords: "Convert, PowerPoint, PDF, PPS, Presentation, Python"
description: Δείγμα κώδικα για μετατροπή PDF σε PPS Python. Χρησιμοποιήστε το PowerPoint Python API για ομαδική μετατροπή αρχείων PDF σε αρχεία PPS.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή PDF σε PPS στην Python" h2="Ισχυρή βιβλιοθήκη PowerPoint Python για μετατροπή PDF σε PPS" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Μετατροπή PDF σε PPS στην Python" %}}

Θέλετε να μετατρέψετε αρχεία PDF σε PPS μέσω προγραμματισμού; Χρησιμοποιώντας το [*Aspose.Slides for Python μέσω .NET*](https://products.aspose.com/slides/el/python-net/) οποιοσδήποτε προγραμματιστής μπορεί να μετατρέψει το PDF σε μορφή PPS με λίγες μόνο γραμμές κώδικα Python.

Ως σύγχρονο API επεξεργασίας παρουσιάσεων, το Aspose.Slides for Python δημιουργεί γρήγορα PPS από PDF. Δοκιμάστε την ποιότητα της μετατροπής PDF σε PPS απευθείας στο [browser] σας (https://products.aspose.app/slides/conversion). Η βιβλιοθήκη Aspose PowerPoint PPTX σάς επιτρέπει να μετατρέπετε αρχεία PDF σε πολλές δημοφιλείς μορφές.

Μπορείτε να εγκαταστήσετε τη βιβλιοθήκη από το [PyPI](https://pypi.org/project/Aspose.Slides/) χρησιμοποιώντας την ακόλουθη εντολή pip:

{{% blocks/products/pf/agp/code-block title="Κονσόλα/Τερματικό" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε PDF σε PPS στην Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για να μετατρέψετε ένα αρχείο PDF σε PPS χρησιμοποιώντας Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση αρχείου PDF με μια παρουσία της κλάσης Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Καλέστε τη μέθοδο "αποθήκευση" καθορίζοντας τη διαδρομή αρχείου εξόδου και το SaveFormat.PPS ως παραμέτρους
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Το αρχείο PDF θα αποθηκευτεί στην καθορισμένη διαδρομή
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

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή PDF σε PPS Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.pps", slides.export.SaveFormat.PPS)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Αποθηκεύστε το PDF ως PPS στην Python" %}}
Χρησιμοποιήστε τη δωρεάν εφαρμογή για να δείτε μια επίδειξη της διαδικασίας μετατροπής PDF σε PPS. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Δωρεάν εφαρμογή για μετατροπή PDF σε PPS" 
        sectionDescription="[Δοκιμάστε την δωρεάν εφαρμογή μας για να μετατρέψετε PDF σε PPS](https://products.aspose.app/slides/import/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε PDF σε πολλές άλλες μορφές αρχείων. Δείτε άλλες υποστηριζόμενες μετατροπές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Εικόνα Bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-emf/" name="PDF TO EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-fodp/" name="PDF TO FODP" description="Επίπεδη παρουσίαση XML OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-gif/" name="PDF TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-html/" name="PDF TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" description="Εικόνα JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-odp/" name="PDF TO ODP" description="Μορφή παρουσίασης OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-otp/" name="PDF TO OTP" description="Τυπική μορφή OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-png/" name="PDF TO PNG" description="Φορητά γραφικά δικτύου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-pot/" name="PDF TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-potm/" name="PDF TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-potx/" name="PDF TO POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-swf/" name="PDF TO SWF" description="Μορφή SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-xps/" name="PDF TO XPS" description="Προδιαγραφές χαρτιού XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
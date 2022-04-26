---
title: Μετατροπή ODP σε POTX στην Python
weight: 340
url: /el/python-net/conversion/odp-to-potx/ 
keywords: "Convert, PowerPoint, ODP, POTX, Presentation, Python"
description: Δείγμα κώδικα για μετατροπή ODP σε POTX Python. Χρησιμοποιήστε το PowerPoint Python API για ομαδική μετατροπή αρχείων ODP σε αρχεία POTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή ODP σε POTX στην Python" h2="Ισχυρή βιβλιοθήκη PowerPoint Python για μετατροπή ODP σε POTX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Μετατροπή ODP σε POTX στην Python" %}}

Θέλετε να μετατρέψετε αρχεία ODP σε POTX μέσω προγραμματισμού; Χρησιμοποιώντας το [*Aspose.Slides for Python μέσω .NET*](https://products.aspose.com/slides/python-net/) οποιοσδήποτε προγραμματιστής μπορεί να μετατρέψει το ODP σε μορφή POTX με λίγες μόνο γραμμές κώδικα Python.

Ως σύγχρονο API επεξεργασίας παρουσιάσεων, το Aspose.Slides for Python δημιουργεί γρήγορα POTX από το ODP. Δοκιμάστε την ποιότητα της μετατροπής ODP σε POTX απευθείας στο [browser] σας (https://products.aspose.app/slides/conversion). Η βιβλιοθήκη Aspose PowerPoint PPTX σάς επιτρέπει να μετατρέπετε αρχεία ODP σε πολλές δημοφιλείς μορφές.

Μπορείτε να εγκαταστήσετε τη βιβλιοθήκη από το [PyPI](https://pypi.org/project/Aspose.Slides/) χρησιμοποιώντας την ακόλουθη εντολή pip:

{{% blocks/products/pf/agp/code-block title="Κονσόλα/Τερματικό" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το ODP σε POTX στην Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για να μετατρέψετε ένα αρχείο ODP σε POTX χρησιμοποιώντας Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση αρχείου ODP με μια παρουσία της κλάσης Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Καλέστε τη μέθοδο «αποθήκευση» καθορίζοντας τη διαδρομή αρχείου εξόδου και το SaveFormat.POTX ως παραμέτρους
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Το αρχείο ODP θα αποθηκευτεί στην καθορισμένη διαδρομή
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

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή ODP σε POTX Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.odp") as presentation:
    presentation.save("presentation.potx", slides.export.SaveFormat.POTX)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Αποθηκεύστε το ODP ως POTX στην Python" %}}
Χρησιμοποιήστε τη δωρεάν εφαρμογή για να δείτε μια επίδειξη της διαδικασίας μετατροπής ODP σε POTX. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="odp-to-potx"
        sectionTitle="Δωρεάν εφαρμογή για μετατροπή ODP σε POTX" 
        sectionDescription="[Δοκιμάστε τη δωρεάν εφαρμογή Video](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το ODP σε πολλές άλλες μορφές αρχείων. Δείτε άλλες υποστηριζόμενες μετατροπές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-bmp/" name="ODP TO BMP" description="Εικόνα Bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-emf/" name="ODP TO EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-fodp/" name="ODP TO FODP" description="Επίπεδη παρουσίαση XML OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-gif/" name="ODP TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-html/" name="ODP TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-jpg/" name="ODP TO JPG" description="Εικόνα JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-otp/" name="ODP TO OTP" description="Τυπική μορφή OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pdf/" name="ODP TO PDF" description="Μορφή φορητού εγγράφου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-png/" name="ODP TO PNG" description="Φορητά γραφικά δικτύου" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pot/" name="ODP TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-potm/" name="ODP TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pps/" name="ODP TO PPS" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-svg/" name="ODP TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-swf/" name="ODP TO SWF" description="Μορφή SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-xps/" name="ODP TO XPS" description="Προδιαγραφές χαρτιού XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
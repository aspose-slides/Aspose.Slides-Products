---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατροπή PDF σε PPSX στην Python
weight: 810
url: /el/python-net/conversion/pdf-to-ppsx/ 
keywords: "Convert, PowerPoint, PDF, PPSX, Presentation, Python"
description: Δείγμα κώδικα για μετατροπή PDF σε PPSX Python. Χρησιμοποιήστε το PowerPoint Python API για ομαδική μετατροπή αρχείων PDF σε αρχεία PPSX.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατροπή PDF σε PPSX στην Python" h2="Ισχυρή βιβλιοθήκη PowerPoint Python για μετατροπή PDF σε PPSX"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατροπή PDF σε PPSX στην Python" %}}

Θέλετε να μετατρέψετε αρχεία PDF σε PPSX μέσω προγραμματισμού; Χρησιμοποιώντας το [*Aspose.Slides for Python μέσω .NET*](https://products.aspose.com/slides/el/python-net/) οποιοσδήποτε προγραμματιστής μπορεί να μετατρέψει το PDF σε μορφή PPSX με λίγες μόνο γραμμές κώδικα Python.

Ως σύγχρονο API επεξεργασίας παρουσιάσεων, το Aspose.Slides for Python δημιουργεί γρήγορα PPSX από PDF. Δοκιμάστε την ποιότητα της μετατροπής PDF σε PPSX απευθείας στο [browser] σας (https://products.aspose.app/slides/conversion). Η βιβλιοθήκη Aspose PowerPoint PPTX σάς επιτρέπει να μετατρέπετε αρχεία PDF σε πολλές δημοφιλείς μορφές.

Μπορείτε να εγκαταστήσετε τη βιβλιοθήκη από το [PyPI](https://pypi.org/project/Aspose.Slides/) χρησιμοποιώντας την ακόλουθη εντολή pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Κονσόλα/Τερματικό" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Αποθηκεύστε το PDF ως PPSX στην Python" %}}

Χρησιμοποιήστε τη δωρεάν εφαρμογή για να δείτε μια επίδειξη της διαδικασίας μετατροπής PDF σε PPSX.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή PDF σε PPSX Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.ppsx", slides.export.SaveFormat.PPSX)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε PDF σε PPSX στην Python" intro="Αυτά είναι τα βήματα για να μετατρέψετε ένα αρχείο PDF σε PPSX χρησιμοποιώντας Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φόρτωση αρχείου PDF με μια παρουσία της κλάσης Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο «αποθήκευση» καθορίζοντας τη διαδρομή αρχείου εξόδου και το SaveFormat.PPSX ως παραμέτρους{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Το αρχείο PDF θα αποθηκευτεί στην καθορισμένη διαδρομή{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Πριν εκτελέσετε το δείγμα πηγαίου κώδικα μετατροπής Python, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις." %}}

- Λειτουργικό σύστημα που βασίζεται σε Microsoft Windows ή Linux (δείτε [περισσότερα](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 ή νεότερη έκδοση
- Aspose.Slides για Python που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Δημιουργήθηκε με το Aspose.Slides" title="Μετατροπή PDF σε PPSX online" description="Η δωρεάν εφαρμογή Aspose.Slides Conversion έχει δημιουργηθεί με το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/el/python-net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PDF." button="Άνοιγμα Aspose.Slides Conversion" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" upload="Σύρετε ή ανεβάστε το αρχείο σας" saveAs="Αποθήκευση ως" convert="Μετατροπή" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides μετατρέπει αρχεία πριν γράψετε κώδικα.
- Ανεβάστε αρχεία PDF και αποθηκεύστε τα ως PPSX.
- Κατεβάστε το αποτέλεσμα ή μετατρέψτε περισσότερα αρχεία.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε PDF σε πολλές άλλες μορφές αρχείων. Δείτε άλλες υποστηριζόμενες μετατροπές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Εικόνα Bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-emf/" name="PDF TO EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-fodp/" name="PDF TO FODP" description="Επίπεδη παρουσίαση XML OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-gif/" name="PDF TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-html/" name="PDF TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" description="Εικόνα JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-odp/" name="PDF TO ODP" description="Μορφή παρουσίασης OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-otp/" name="PDF TO OTP" description="Τυπική μορφή OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-png/" name="PDF TO PNG" description="Φορητά γραφικά δικτύου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-pot/" name="PDF TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-potm/" name="PDF TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-potx/" name="PDF TO POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-pps/" name="PDF TO PPS" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-swf/" name="PDF TO SWF" description="Μορφή SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/pdf-to-xps/" name="PDF TO XPS" description="Προδιαγραφές χαρτιού XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

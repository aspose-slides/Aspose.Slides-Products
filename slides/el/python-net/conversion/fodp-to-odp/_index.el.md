---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Μετατρέψτε το FODP σε ODP στην Python
weight: 60
url: /el/python-net/conversion/fodp-to-odp/ 
keywords: "Convert, PowerPoint, FODP, ODP, Presentation, Python"
description: Δείγμα κώδικα για μετατροπή FODP σε ODP Python. Χρησιμοποιήστε το PowerPoint Python API για ομαδική μετατροπή αρχείων FODP σε αρχεία ODP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Μετατρέψτε το FODP σε ODP στην Python" h2="Ισχυρή βιβλιοθήκη PowerPoint Python για μετατροπή FODP σε ODP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Μετατρέψτε το FODP σε ODP στην Python" %}}

Θέλετε να μετατρέψετε αρχεία FODP σε ODP μέσω προγραμματισμού; Χρησιμοποιώντας το [*Aspose.Slides for Python μέσω .NET*](https://products.aspose.com/slides/el/python-net/) οποιοσδήποτε προγραμματιστής μπορεί να μετατρέψει το FODP σε μορφή ODP με λίγες μόνο γραμμές κώδικα Python.

Ως σύγχρονο API επεξεργασίας παρουσιάσεων, το Aspose.Slides for Python δημιουργεί γρήγορα ODP από το FODP. Δοκιμάστε την ποιότητα της μετατροπής FODP σε ODP απευθείας στο [browser] σας (https://products.aspose.app/slides/conversion). Η βιβλιοθήκη Aspose PowerPoint PPTX σάς επιτρέπει να μετατρέπετε αρχεία FODP σε πολλές δημοφιλείς μορφές.

Μπορείτε να εγκαταστήσετε τη βιβλιοθήκη από το [PyPI](https://pypi.org/project/Aspose.Slides/) χρησιμοποιώντας την ακόλουθη εντολή pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Κονσόλα/Τερματικό" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Αποθηκεύστε το FODP ως ODP στην Python" %}}

Χρησιμοποιήστε τη δωρεάν εφαρμογή για να δείτε μια επίδειξη της διαδικασίας μετατροπής FODP σε ODP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή Python FODP σε ODP" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.fodp") as presentation:
    presentation.save("presentation.odp", slides.export.SaveFormat.ODP)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να μετατρέψετε το FODP σε ODP στην Python" intro="Αυτά είναι τα βήματα για να μετατρέψετε ένα αρχείο FODP σε ODP χρησιμοποιώντας Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο FODP με μια παρουσία της κλάσης Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Καλέστε τη μέθοδο «αποθήκευση» καθορίζοντας τη διαδρομή αρχείου εξόδου και το SaveFormat.ODP ως παραμέτρους{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Το αρχείο FODP θα αποθηκευτεί στην καθορισμένη διαδρομή{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Πριν εκτελέσετε το δείγμα πηγαίου κώδικα μετατροπής Python, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις." %}}

- Λειτουργικό σύστημα που βασίζεται σε Microsoft Windows ή Linux (δείτε [περισσότερα](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 ή νεότερη έκδοση
- Aspose.Slides για Python που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Δωρεάν εφαρμογή για μετατροπή FODP σε ODP"
  description="[Δοκιμάστε τη δωρεάν εφαρμογή Editor](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το FODP σε πολλές άλλες μορφές αρχείων. Δείτε άλλες υποστηριζόμενες μετατροπές παρακάτω" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Εικόνα Bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-emf/" name="FODP TO EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-gif/" name="FODP TO GIF" description="Μορφή γραφικής ανταλλαγής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-html/" name="FODP TO HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-jpg/" name="FODP TO JPG" description="Εικόνα JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-otp/" name="FODP TO OTP" description="Τυπική μορφή OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Μορφή φορητού εγγράφου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-png/" name="FODP TO PNG" description="Φορητά γραφικά δικτύου" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-pot/" name="FODP TO POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-potm/" name="FODP TO POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-potx/" name="FODP TO POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-pps/" name="FODP TO PPS" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="Παρουσίαση PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-svg/" name="FODP TO SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-swf/" name="FODP TO SWF" description="Μορφή SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/python-net/conversion/fodp-to-xps/" name="FODP TO XPS" description="Προδιαγραφές χαρτιού XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

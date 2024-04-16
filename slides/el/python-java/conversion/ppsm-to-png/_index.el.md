---
title: Μετατροπή PPSM σε PNG στην Python
url: /el/python-java/conversion/ppsm-to-png/
keywords: Μετατροπή παρουσίασης Python, μετατροπή παρουσιάσεων σε Python, Python για παρουσιάσεις, Aspose.Slides Python, μετατροπή PPSM σε PNG, βιβλιοθήκη παρουσιάσεων Python
description: Μετατροπή PPSM σε PNG στην Python. Χρησιμοποιήστε το API βιβλιοθήκης Python για να μετατρέψετε αρχεία PPSM σε PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατρέψτε εύκολα το PPSM σε PNG με την Python: Aspose.Slides to the Rescue!" h2="Δώστε νέα πνοή στις παρουσιάσεις σας με την Python. Ο οδηγός μας σας καθοδηγεί στη μετατροπή των υπαρχουσών διαφανειών του PowerPoint σε ελκυστικές παρουσιάσεις Python." >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή PPSM σε PNG στην Python" %}}

Κουραστήκατε να παλεύετε με πολύπλοκο λογισμικό παρουσίασης; Μην ψάχνετε πέρα ​​από το [**Aspose.Slides για Python μέσω Java**](https://products.aspose.com/slides/el/python-java/)! Αυτή η ισχυρή βιβλιοθήκη σάς δίνει τη δυνατότητα να δημιουργείτε, να επεξεργάζεστε και να μετατρέπετε παρουσιάσεις μεταξύ διαφόρων μορφών με ευκολία. Θέλετε να αλλάξετε από PPSM σε PNG; Το Aspose.Slides το κάνει παιχνιδάκι, απαιτώντας μόνο λίγες γραμμές κώδικα Python.

Ως πρωτοποριακό API επεξεργασίας εγγράφων, το **Aspose.Slides για Python μέσω Java** διαθέτει αστραπιαίες ταχύτητες μετατροπής, εξασφαλίζοντας γρήγορο μετασχηματισμό των παρουσιάσεών σας PPSM σε μορφή PNG. Ξεφορτωθείτε τους περιορισμούς των παραδοσιακών εργαλείων - Το Aspose.Slides σάς παρέχει την ευελιξία να μετατρέπετε παρουσιάσεις από PPSM όχι μόνο σε PNG αλλά και σε ένα ευρύ φάσμα άλλων μορφών, δίνοντάς σας τη δυνατότητα να προσαρμόζετε άψογα τις παρουσιάσεις σας για κάθε περίσταση.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PPSM σε PNG χρησιμοποιώντας Python" %}}
Για να μετατρέψετε το PPSM σε PNG, θα χρειαστεί να δημιουργήσετε την Παρουσίαση από το αρχείο PPSM και να την αποθηκεύσετε ως PNG.

{{% blocks/products/pf/agp/code-block title="Οδηγός Python για τη μετατροπή του PPSM σε PNG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppsm");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Εκμάθηση Python. Πώς να μετατρέψετε το PPSM σε PNG χρησιμοποιώντας το Aspose.Slides για Python μέσω Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Για να μετατρέψετε το PPSM σε PNG χρησιμοποιώντας το Aspose.Slides για Python μέσω Java, πρέπει να εισαγάγετε το πακέτο στο σενάριο Python και να δημιουργήσετε ένα στιγμιότυπο της κλάσης Presentation. Η κλάση Presentation αντιπροσωπεύει ένα έγγραφο PowerPoint και παρέχει μεθόδους πρόσβασης και χειρισμού των στοιχείων του." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το [**Aspose.Slides για Python μέσω Java**](https://products.aspose.com/slides/el/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο Python σας.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ανοίξτε τα αρχεία πηγής PPSM στην Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αποτέλεσμα ως αρχείο PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Μετατροπή PPSM σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το PPSM και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
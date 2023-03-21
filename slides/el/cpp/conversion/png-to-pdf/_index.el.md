---
title: Μετατροπή PNG σε PDF σε C++
url: /el/cpp/conversion/png-to-pdf/
keywords: PNG σε PDF, Convert PNG σε PDF, C++ API, C++ Library, PNG, PDF
description: Μετατροπή PNG σε PDF σε C++. Χρησιμοποιήστε το API βιβλιοθήκης C++ για να μετατρέψετε αρχεία PNG σε PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατροπή PNG σε PDF σε C++" h2="Βιβλιοθήκη C++ υψηλής ταχύτητας και πολλαπλών πλατφορμών που βοηθά στην ανάπτυξη εφαρμογών με δυνατότητα δημιουργίας, συγχώνευσης, επιθεώρησης ή μετατροπής αρχείων παρουσίασης Microsoft PowerPoint και OpenOffice χωρίς τη χρήση λογισμικού όπως Microsoft ή Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή PNG σε PDF σε C++" %}}

Το [**Aspose.Slides for C++**](https://products.aspose.com/slides/el/cpp/) είναι μια ισχυρή βιβλιοθήκη C++ για τη δημιουργία και τον χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους μετατροπής του PNG σε PDF. Χρησιμοποιώντας το **Aspose.Slides για C++**, οποιοσδήποτε προγραμματιστής ή εφαρμογή μπορεί να μετατρέψει αρχεία PNG σε PDF με λίγες μόνο γραμμές κώδικα C++.

Ως σύγχρονο API επεξεργασίας εγγράφων, το Aspose.Slides για C++ εξάγει αρχεία PNG σε μορφές αρχείων PDF γρήγορα. Η βιβλιοθήκη Aspose PowerPoint σάς επιτρέπει να μετατρέψετε το PNG σε PDF και πολλές άλλες μορφές αρχείων

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε το PNG σε PDF χρησιμοποιώντας C++" %}}
Για να μετατρέψετε το PNG σε PDF, θα χρειαστεί να δημιουργήσετε Παρουσίαση από το αρχείο PNG και να το αποθηκεύσετε ως PDF.

{{% blocks/products/pf/agp/code-block title="Κώδικας C++ για μετατροπή PNG σε PDF" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να μετατρέψετε το PNG σε PDF χρησιμοποιώντας το Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για τη μετατροπή του PNG σε PDF στη C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το [**Aspose.Slides για C++**](https://products.aspose.com/slides/el/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο σας C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ανοίξτε τα αρχεία πηγής PNG στη C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε το αποτέλεσμα ως αρχείο PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Δωρεάν Online Μετατροπέας" sectionDescription="[Πώς να μετατρέψετε το PPT σε HTML στην Python](https://products.aspose.com/slides/el/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Μετατροπή PNG σε άλλες υποστηριζόμενες μορφές" subTitle="Μπορείτε επίσης να μετατρέψετε το PNG και να το αποθηκεύσετε σε άλλες μορφές αρχείων. Δείτε όλες τις υποστηριζόμενες μορφές παρακάτω" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/cpp/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
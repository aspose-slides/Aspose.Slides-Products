---
title: Μετατροπή παρουσίασης Microsoft PowerPoint σε διάφορες μορφές χρησιμοποιώντας C++
url: /el/cpp/conversion/
description: Μετατρέψτε τις διαφάνειες Microsoft PowerPoint σε πολλαπλά αρχεία, συμπεριλαμβανομένων μορφών HTML, PDF και εικόνας σε εφαρμογές που βασίζονται στη C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή παρουσίασης Microsoft<sup>®</sup> PowerPoint μέσω C++" h2="Παραδείγματα κωδικών C++ για διαφορετικά σενάρια μετατροπής για μετατροπή διαφανειών σε Εικόνες, HTML, PDF και άλλες μορφές." >}}

{{% blocks/products/pf/feature-page-summary %}}

Η διαδικασία μετατροπής των μορφών Microsoft<sup>®</sup> PowerPoint είναι απλή και εύκολη στην αυτοματοποίηση των διαδικασιών χρησιμοποιώντας τη βιβλιοθήκη του PowerPoint C++. Οι προγραμματιστές μπορούν να βελτιώσουν τον σχετικό πηγαίο κώδικα και να τον ενσωματώσουν στις εφαρμογές τους. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Ενδιάμεση μετατροπή μορφών Microsoft PowerPoint" %}}
Η διαμετατροπή εγγράφων Microsoft<sup>®</sup> PowerPoint, συμπεριλαμβανομένων των PPT, PPTX μέσω προγραμματισμού, είναι απλώς ένας κώδικας δύο γραμμών. Φορτώστε το αρχείο χρησιμοποιώντας [Τάξη παρουσίασης](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) και καλώντας τη [μέθοδος αποθήκευσης](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) με παραμέτρους το αρχείο εξόδου και SaveFormat.OutputFormats.

{{% blocks/products/pf/feature-page-code h3="Κωδικός μετατροπής C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείων PowerPoint σε PDF" %}}

Η μετατροπή του Microsoft<sup>®</sup> PowerPoint σε PDF είναι ένα συνηθισμένο σενάριο λόγω της τεράστιας κοινής χρήσης εγγράφων PDF. Οι προγραμματιστές μπορούν να το αυτοματοποιήσουν και να ορίσουν τις σχετικές ρυθμίσεις μετατροπής PDF χρησιμοποιώντας το [PdfOptions class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Λίγες από τις συγκεκριμένες ρυθμίσεις, όπως επίπεδο συμπίεσης κειμένου, ποιότητα JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e31d184liance), PDF (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), μετατροπή κρυφών διαφανειών [ShowHiddenSlides.com/asslides/ShowHiddenSlides. /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), επιλεγμένες διαφάνειες και δημιουργία κλειδωμένων αρχείων [Password](https://apireference.aspose.com/slides/cpp/class.class.class.bbb94.ablides.com/class. .

{{% blocks/products/pf/feature-page-code h3="Κώδικας μετατροπής C++ PowerPoint σε PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Αποθηκεύστε τις διαφάνειες του Microsoft PowerPoint ως εικόνες" %}}
όποτε υπάρχει η περίπτωση να εμφανιστεί το περιεχόμενο της παρουσίασης στον ιστό, τότε υπάρχει ανάγκη απόδοσης αρχείων ως HTML ή εικόνων JPG, TIFF, PNG κ.λπ. Η διαδικασία μετατροπής των διαφανειών σε εικόνες είναι απλή. Λάβετε όλες τις διαφάνειες χρησιμοποιώντας το [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) και επαναλάβετε μία προς μία κάθε slide. Κατά τη διάρκεια κάθε επανάληψης χρησιμοποιήστε το [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) για να διαμορφώσετε την εικόνα που απαιτείται. 

{{% blocks/products/pf/feature-page-code h3="Μετατροπή C++ PowerPoint σε εικόνα" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}
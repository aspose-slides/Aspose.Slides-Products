---
title: Conversione di presentazioni di Microsoft PowerPoint in vari formati utilizzando C++
url: /it/cpp/conversion/
description: Converti le diapositive di Microsoft PowerPoint in più file inclusi HTML, PDF e formati immagine all'interno di applicazioni basate su C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> Conversione presentazione PowerPoint tramite C++" h2="Codici di esempio C++ per diversi scenari di conversione per convertire diapositive in immagini, HTML, PDF e altri formati." >}}

{{% blocks/products/pf/feature-page-summary %}}

Il processo di conversione dei formati Microsoft<sup>®</sup> PowerPoint è semplice e consente di automatizzare facilmente i processi utilizzando la libreria C++ PowerPoint. Gli sviluppatori possono migliorare il codice sorgente pertinente e integrarlo nelle loro applicazioni. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversione tra formati Microsoft PowerPoint" %}}
L'interconversione di documenti Microsoft<sup>®</sup> PowerPoint inclusi PPT e PPTX a livello di codice è solo un codice di due righe. Carica il file utilizzando [Presentation class](https://apiference.aspose.com/slides/cpp/class/aspose.slides.presentation) e chiamando il [Save method](https://apiference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) con il file di output e SaveFormat.OutputFormats come parametri.

{{% blocks/products/pf/feature-page-code h3="Codice di conversione C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Converti file PowerPoint in PDF" %}}

La conversione di Microsoft<sup>®</sup> PowerPoint in PDF è uno scenario comune a causa dell'enorme condivisione di documenti PDF. I programmatori possono automatizzarlo e impostare le relative impostazioni di conversione PDF utilizzando [classe PdfOptions](https://apiference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Poche impostazioni specifiche come il livello di compressione del testo, la qualità JPEG [JpegQuality](https://apiference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), il livello di conformità PDF [Compliance](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), conversione di diapositive nascoste [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), diapositive selezionate e generazione di file PDF protetti [Password](https://apiference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7) .

{{% blocks/products/pf/feature-page-code h3="Codice di conversione da PowerPoint a PDF C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Salva le diapositive di Microsoft PowerPoint come immagini" %}}
ogni volta che è necessario visualizzare il contenuto della presentazione sul Web, è necessario eseguire il rendering di file come HTML o immagini JPG, TIFF, PNG, ecc. Il processo di conversione delle diapositive in immagini è semplice. Ottieni tutte le diapositive utilizzando [get_Slides()](https://apiference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) e scorrere ciascuna diapositiva una per una. Durante ogni iterazione, usa [ISlide->GetThumbnail](https://apiference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) per l'immagine della diapositiva, quindi salva nel formato immagine richiesto. 

{{% blocks/products/pf/feature-page-code h3="Conversione da PowerPoint a C++ in immagini" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}
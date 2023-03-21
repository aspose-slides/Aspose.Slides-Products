---
title: Conversion de présentations Microsoft PowerPoint en divers formats à l'aide de C++
url: /fr/cpp/conversion/
description: Convertissez les diapositives Microsoft PowerPoint en plusieurs fichiers, y compris les formats HTML, PDF et image dans les applications basées sur C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversion de présentation PowerPoint Microsoft<sup>®</sup> via C++" h2="Codes d'exemple C++ pour différents scénarios de conversion pour convertir des diapositives en images, HTML, PDF et autres formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

Le processus de conversion des formats Microsoft<sup>®</sup> PowerPoint est simple et facile à automatiser à l'aide de la bibliothèque C++ PowerPoint. Les développeurs peuvent améliorer le code source pertinent et l'intégrer dans leurs applications. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter-conversion des formats Microsoft PowerPoint" %}}
L'interconversion de documents Microsoft<sup>®</sup> PowerPoint, y compris PPT, PPTX, par programmation, n'est qu'un code de deux lignes. Chargez le fichier à l'aide de [Classe de présentation](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) et en appelant la [Méthode Save](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) ayant le fichier de sortie et SaveFormat.OutputFormats comme paramètres.

{{% blocks/products/pf/feature-page-code h3="Code de conversion C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Convertir des fichiers PowerPoint en PDF" %}}

La conversion de Microsoft<sup>®</sup> PowerPoint en PDF est un scénario courant en raison de l'énorme partage de documents PDF. Les programmeurs peuvent l'automatiser et définir les paramètres de conversion PDF pertinents à l'aide de [classe PdfOptions](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Peu de paramètres spécifiques tels que le niveau de compression du texte, la qualité JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), le niveau de conformité PDF [Conformité](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), conversion de diapositives masquées [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), les diapositives sélectionnées et la génération de fichiers PDF protégés verrouillés [Mot de passe](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7) .

{{% blocks/products/pf/feature-page-code h3="Code de conversion PowerPoint en PDF C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Enregistrer les diapositives Microsoft PowerPoint en tant qu'images" %}}
chaque fois qu'il est nécessaire d'afficher le contenu d'une présentation sur le Web, il est nécessaire de rendre les fichiers au format HTML ou images JPG, TIFF, PNG, etc. Le processus de conversion des diapositives en images est simple. Obtenez toutes les diapositives à l'aide de [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) et parcourez chaque diapositive une par une. Au cours de chaque itération, utilisez [ISlide-> GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) pour l'image de la diapositive, puis enregistrez-la dans le format d'image requis. 

{{% blocks/products/pf/feature-page-code h3="Conversion de PowerPoint en image C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}
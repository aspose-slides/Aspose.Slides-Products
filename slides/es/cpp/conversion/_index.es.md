---
title: Conversión de presentaciones de Microsoft PowerPoint a varios formatos usando C++
url: /es/cpp/conversion/
description: Convierta diapositivas de Microsoft PowerPoint en múltiples archivos, incluidos HTML, PDF y formatos de imagen dentro de aplicaciones basadas en C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversión de presentaciones de Microsoft<sup>®</sup> PowerPoint a través de C++" h2="Códigos de ejemplo de C++ para diferentes escenarios de conversión para convertir diapositivas a imágenes, HTML, PDF y otros formatos." >}}

{{% blocks/products/pf/feature-page-summary %}}

El proceso de conversión de los formatos de Microsoft<sup>®</sup> PowerPoint es simple y fácil de automatizar mediante la biblioteca C++ de PowerPoint. Los desarrolladores pueden mejorar el código fuente relevante e integrarlo dentro de sus aplicaciones. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter conversión de formatos de Microsoft PowerPoint" %}}
La interconversión de documentos de Microsoft<sup>®</sup> PowerPoint, incluidos PPT, PPTX mediante programación, es solo un código de dos líneas. Cargue el archivo usando [Clase de presentación](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) y llame al [Método Guardar](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) con el archivo de salida y SaveFormat.OutputFormats como parámetros.

{{% blocks/products/pf/feature-page-code h3="Código de conversión de C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Convertir archivos de PowerPoint a PDF" %}}

La conversión de Microsoft<sup>®</sup> PowerPoint a PDF es un escenario común debido a la gran cantidad de documentos PDF que se comparten. Los programadores pueden automatizarlo y establecer la configuración de conversión de PDF relevante utilizando [clase PdfOptions](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Algunas de las configuraciones específicas, como el nivel de compresión de texto, calidad JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), nivel de cumplimiento de PDF [Cumplimiento](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), convertir diapositivas ocultas [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), diapositivas seleccionadas y generación de archivos PDF protegidos [Contraseña](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7) protegidos .

{{% blocks/products/pf/feature-page-code h3="C++ Código de conversión de PowerPoint a PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Guardar diapositivas de Microsoft PowerPoint como imágenes" %}}
siempre que se presente el caso de mostrar el contenido de la presentación en la web, entonces es necesario representar archivos como HTML o imágenes JPG, TIFF, PNG, etc. El proceso de conversión de diapositivas como imágenes es simple. Obtenga todas las diapositivas usando [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) y repita cada diapositiva una por una. Durante cada iteración, use [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) para la imagen de la diapositiva y luego guárdela en el formato de imagen requerido. 

{{% blocks/products/pf/feature-page-code h3="Conversión de PowerPoint a imagen de C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}
---
title: Microsoft PowerPoint Presentation Conversion to Various Formats using C++ 
url: /cpp/conversion/
description: Convert Microsoft PowerPoint Slides to multiple files including HTML, PDF and image formats within C++ based applications.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> PowerPoint Presentation Conversion via C++" h2="C++ example codes for different conversion scenarios to convert slides to Images, HTML, PDF and other formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

Conversion process of Microsoft<sup>&reg;</sup> PowerPoint formats is simple and easy to automate processes using C++ PowerPoint library. Developers can enhance relevant source code and integrate it within their applications. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter Conversion Of Microsoft PowerPoint Formats" %}}
Interconversion of Microsoft<sup>&reg;</sup> PowerPoint documents including PPT, PPTX programmatically is just a two lines code. Load the file using [Presentation class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) and calling the [Save method](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) having the output file and SaveFormat.OutputFormats as parameters.

{{% blocks/products/pf/feature-page-code h3="C++ Conversion Code" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint Files to PDF" %}}

Converting Microsoft<sup>&reg;</sup> PowerPoint to PDF is a common scenario due the huge sharing of PDF documents. Programmers can automate it and set the relevant PDF conversion settings using [PdfOptions class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Few of the specific settings such as text compression level, JPEG quality [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), PDF compliance level [Compliance](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), converting hidden slides [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), selected slides and generating locked [Password](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7) protected PDF files.

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint to PDF Conversion Code" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Save Microsoft PowerPoint Slides As Images" %}}
when ever there is the case to display presentation content on web, then there is need to render files as HTML or images JPG, TIFF, PNG, etc. Process of converting slides as images is simple. Get all the slides using [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c)  and iterate through each slide one by one. During each iteration use [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) for the slide image and then save into the required image format. 

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint to Image Conversion" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}
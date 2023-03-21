---
title: Microsoft PowerPoint-presentationskonvertering till olika format med C++
url: /sv/cpp/conversion/
description: Konvertera Microsoft PowerPoint Slides till flera filer inklusive HTML, PDF och bildformat i C++-baserade applikationer.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-presentationskonvertering via C++" h2="C++ exempelkoder för olika konverteringsscenarier för att konvertera bilder till bilder, HTML, PDF och andra format." >}}

{{% blocks/products/pf/feature-page-summary %}}

Konverteringsprocessen för Microsoft<sup>®</sup> PowerPoint-format är enkel och lätt att automatisera processer med hjälp av C++ PowerPoint-biblioteket. Utvecklare kan förbättra relevant källkod och integrera den i sina applikationer. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Interkonvertering av Microsoft PowerPoint-format" %}}
Interkonvertering av Microsoft<sup>®</sup> PowerPoint-dokument inklusive PPT, PPTX programmatiskt är bara två raders kod. Ladda filen med [Presentation class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) och anropa [Save method](https://apireference.aspose.com/slides) /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) med utdatafilen och SaveFormat.OutputFormats som parametrar.

{{% blocks/products/pf/feature-page-code h3="C++ konverteringskod" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Konvertera PowerPoint-filer till PDF" %}}

Att konvertera Microsoft<sup>®</sup> PowerPoint till PDF är ett vanligt scenario på grund av den enorma delningen av PDF-dokument. Programmerare kan automatisera det och ställa in relevanta PDF-konverteringsinställningar med [PdfOptions class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Ett fåtal av de specifika inställningarna som textkomprimeringsnivå, JPEG-kvalitet [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), överensstämmelsenivå för PDF [Comp PDF](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), konvertera dolda bilder [ShowHiddenSlides](https://apireference/classlides.aspose/apireference.aspose/ /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), valda bilder och generera låsta [Lösenord](https://apireference.aspose.com/slides/cpp/class/aspose.slides.exporttions.pdf32050000000000000000000000000000000001) protecta42305800000000000000000000000000000 .

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint till PDF-konverteringskod" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Spara Microsoft PowerPoint-bilder som bilder" %}}
när det någonsin är fallet att visa presentationsinnehåll på webben, då finns det behov av att rendera filer som HTML eller bilder JPG, TIFF, PNG, etc. Processen att konvertera bilder som bilder är enkel. Hämta alla bilder med [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) och iterera genom varje bild en efter en. Under varje iteration använd [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) för den önskade bildbilden och spara sedan i önskat bildformat. 

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint till bildkonvertering" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}
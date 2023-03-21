---
title: Преобразование презентаций Microsoft PowerPoint в различные форматы с использованием C++
url: /ru/cpp/conversion/
description: Преобразование слайдов Microsoft PowerPoint в несколько файлов, включая форматы HTML, PDF и изображений, в приложениях на основе C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование презентаций Microsoft<sup>®</sup> PowerPoint с помощью C++" h2="Примеры кода C++ для различных сценариев преобразования слайдов в изображения, HTML, PDF и другие форматы." >}}

{{% blocks/products/pf/feature-page-summary %}}

Процесс преобразования форматов Microsoft<sup>®</sup> PowerPoint прост и легко автоматизируется с помощью библиотеки C++ PowerPoint. Разработчики могут улучшать соответствующий исходный код и интегрировать его в свои приложения. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Межконверсионное преобразование форматов Microsoft PowerPoint" %}}
Взаимное преобразование документов Microsoft<sup>®</sup> PowerPoint, включая PPT, PPTX, программным путем — это всего лишь двухстрочный код. Загрузите файл, используя [класс презентации](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) и вызвав [метод сохранения](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) с выходным файлом и SaveFormat.OutputFormats в качестве параметров.

{{% blocks/products/pf/feature-page-code h3="Код преобразования С++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Преобразование файлов PowerPoint в PDF" %}}

Преобразование Microsoft<sup>®</sup> PowerPoint в PDF является распространенным сценарием из-за большого количества совместно используемых PDF-документов. Программисты могут автоматизировать его и установить соответствующие параметры преобразования PDF с помощью [класса PdfOptions](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Несколько конкретных настроек, таких как уровень сжатия текста, качество JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), уровень соответствия PDF [Compliance](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), преобразование скрытых слайдов [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), выбранные слайды и создание заблокированных [паролем](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7) защищенных PDF-файлов .

{{% blocks/products/pf/feature-page-code h3="Код преобразования C++ PowerPoint в PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Сохранить слайды Microsoft PowerPoint как изображения" %}}
когда когда-либо возникает необходимость отображать содержимое презентации в Интернете, необходимо отображать файлы в виде HTML или изображений JPG, TIFF, PNG и т. д. Процесс преобразования слайдов в изображения прост. Получите все слайды с помощью [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) и перебирайте каждый слайд один за другим. Во время каждой итерации используйте [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) для изображения слайда, а затем сохраняйте изображение в требуемом формате. 

{{% blocks/products/pf/feature-page-code h3="Преобразование C++ PowerPoint в изображение" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}
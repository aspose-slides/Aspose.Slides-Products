---
title: 使用 C++ 將 Microsoft PowerPoint 演示文稿轉換為各種格式
url: /zh-hant/cpp/conversion/
description: 在基於 C++ 的應用程序中將 Microsoft PowerPoint 幻燈片轉換為多個文件，包括 HTML、PDF 和圖像格式。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> 通過 C++ 轉換 PowerPoint 演示文稿" h2="用於不同轉換場景的C++示例代碼，將幻燈片轉換為圖像、HTML、PDF等格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

Microsoft<sup>®</sup> PowerPoint 格式的轉換過程簡單且易於使用 C++ PowerPoint 庫自動化過程。開發人員可以增強相關源代碼並將其集成到他們的應用程序中。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 格式的相互轉換" %}}
Microsoft<sup>®</sup> PowerPoint 文檔（包括 PPT、PPTX）以編程方式相互轉換只是兩行代碼。使用 [Presentation 類](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) 加載文件並調用 [Save 方法](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 具有輸出文件和 SaveFormat.OutputFormats 作為參數。

{{% blocks/products/pf/feature-page-code h3="C++ 轉換代碼" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="將 PowerPoint 文件轉換為 PDF" %}}

由於 PDF 文檔的大量共享，將 Microsoft<sup>®</sup> PowerPoint 轉換為 PDF 是一種常見情況。程序員可以使用 [PdfOptions 類](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options) 將其自動化並設​​置相關的 PDF 轉換設置。一些具體設置，例如文本壓縮級別、JPEG 質量 [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861)、PDF 合規級別 [Compliance] (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f)，轉換隱藏幻燈片[ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23），選定的幻燈片並生成鎖定的[密碼]（https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7）受保護的PDF文件.

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint 到 PDF 轉換代碼" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="將 Microsoft PowerPoint 幻燈片另存為圖像" %}}
每當需要在 Web 上顯示演示內容時，就需要將文件呈現為 HTML 或圖像 JPG、TIFF、PNG 等。將幻燈片轉換為圖像的過程很簡單。使用 [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) 獲取所有幻燈片並一張一張地遍歷每張幻燈片。在每次迭代期間，對幻燈片圖像使用 [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783)，然後保存為所需的圖像格式。 

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint 到圖像轉換" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}
---
title: Sắp xếp lại các tệp bản trình bày PPT bằng Python
url: /vi/python-net/redaction/ppt/
keywords: Viết lại PPT, tìm và thay thế văn bản trong PPT, cập nhật Bản trình bày PPT
description: Mã nguồn Python để tìm và thay thế văn bản trong Bản trình bày PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Sắp xếp lại PPT bằng Python" h2="Xây dựng ứng dụng Python của riêng bạn để tìm và thay thế văn bản trong tệp bản trình bày bằng API phía máy chủ. Tìm hiểu cách tìm kiếm và thay thế văn bản trong nội dung, nhận xét hoặc siêu dữ liệu của bản trình bày PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Chỉnh sửa bản trình bày PPT qua Python" %}}
Có thể thực hiện tìm kiếm tài liệu cơ bản và thay thế văn bản trong nội dung, nhận xét, ghi chú trang trình bày hoặc siêu dữ liệu bằng API Aspose.Slides for Python via .NET chỉ với vài dòng mã. Tìm và thay thế văn bản trong PowerPoint và OpenOffice. Chỉnh sửa văn bản, nhận xét, siêu dữ liệu trong bản trình bày thông qua kết hợp dữ liệu regexp.
{{% blocks/products/pf/agp/code-block title="Chỉnh sửa bản trình bày PPT bằng Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.ppt") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách biên tập lại PPT qua Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để Sắp xếp lại các tệp PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPT với phiên bản Trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sử dụng phương thức [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) để tìm và thay thế văn bản.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Trình diễn Trực tiếp Biên tập PPT trực tuyến" sectionDescription="Tìm kiếm và thay thế văn bản trong nội dung, nhận xét hoặc siêu dữ liệu trong tài liệu PPT ngay bây giờ." >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng Redact được hỗ trợ khác" subTitle="Sử dụng Python, Bạn cũng có thể sắp xếp lại các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
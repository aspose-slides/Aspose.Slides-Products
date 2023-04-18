---
title: Xóa chú thích PPTX bằng Python
weight: 4380
url: /vi/python-net/annotation/pptx/ 
description: Mã nguồn Python để xóa nhận xét bản trình bày PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Xóa Nhận xét và Tác giả Nhận xét khỏi PPTX trong Python" h2="Xây dựng tập lệnh Python của riêng bạn để thao tác nhận xét và tác giả trong tệp tài liệu bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa Nhận xét khỏi PPTX bằng Python" %}}
Để xóa chú thích khỏi tệp PPTX, chúng tôi sẽ sử dụng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/) API có nhiều tính năng, API thao tác tài liệu mạnh mẽ và dễ sử dụng cho nền tảng Python.
{{% blocks/products/pf/agp/code-block title="Xóa chú thích khỏi PPTX - Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.pptx") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Cách xóa nhận xét khỏi PPTX bằng Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho Python qua .NET**. Xem [**Cài đặt**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPTX với một phiên bản của lớp Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lặp lại tất cả các Tác giả của PPTX đã tải
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Xóa tất cả Nhận xét của một tác giả
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Xóa tất cả Tác giả ở cuối
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng chú thích được hỗ trợ khác" subTitle="Sử dụng Python, người ta có thể dễ dàng chú thích các định dạng khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
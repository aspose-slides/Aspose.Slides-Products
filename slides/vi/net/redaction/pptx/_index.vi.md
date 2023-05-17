---
title: Sắp xếp lại các tệp bản trình bày PPTX bằng .NET
url: /vi/net/redaction/pptx/
keywords: Viết lại PPTX, tìm và thay thế văn bản trong PPTX, cập nhật Bản trình bày PPTX
description: Mã nguồn C# để tìm và thay thế văn bản trong Bản trình bày PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Sắp xếp lại PPTX bằng C#" h2="Xây dựng ứng dụng .NET của riêng bạn để tìm và thay thế văn bản trong tệp bản trình bày bằng API phía máy chủ. Tìm hiểu cách tìm kiếm và thay thế văn bản trong nội dung, nhận xét hoặc siêu dữ liệu của bản trình bày PPTX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Chỉnh sửa bản trình bày PPTX qua C#" %}}
Có thể thực hiện tìm kiếm tài liệu cơ bản và thay thế văn bản trong nội dung, nhận xét, ghi chú trang trình bày hoặc siêu dữ liệu bằng API Aspose.Slides for .NET chỉ với vài dòng mã. Tìm và thay thế văn bản trong PowerPoint và OpenOffice. Chỉnh sửa văn bản, nhận xét, siêu dữ liệu trong bản trình bày thông qua kết hợp dữ liệu regexp.
{{% blocks/products/pf/agp/code-block title="Chỉnh sửa bản trình bày PPTX bằng C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.pptx"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách biên tập lại PPTX qua C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để Sắp xếp lại các tệp PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPTX với phiên bản Trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sử dụng phương thức [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) để tìm và thay thế văn bản.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Trình diễn Trực tiếp Biên tập PPTX trực tuyến" sectionDescription="Tìm kiếm và thay thế văn bản trong nội dung, nhận xét hoặc siêu dữ liệu trong tài liệu PPTX ngay bây giờ." >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng Redact được hỗ trợ khác" subTitle="Sử dụng C#, Bạn cũng có thể sắp xếp lại các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
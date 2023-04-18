---
title: Xóa chú thích ODP bằng .NET
weight: 4380
url: /vi/net/annotation/odp/ 
description: Mã nguồn C# để xóa chú thích định dạng ODP trên Nền tảng .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Xóa Nhận xét và Tác giả Nhận xét khỏi ODP trong C#" h2="Xây dựng ứng dụng .NET của riêng bạn để thao tác nhận xét và tác giả trong tệp tài liệu bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa Nhận xét khỏi ODP qua C#" %}}
Để xóa chú thích khỏi tệp ODP, chúng tôi sẽ sử dụng API [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net) API có nhiều tính năng, mạnh mẽ và dễ sử dụng API thao tác tài liệu cho nền tảng C#.
{{% blocks/products/pf/agp/code-block title="Xóa chú thích khỏi ODP - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.odp"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Cách xóa Nhận xét khỏi ODP qua C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho .NET**. Xem [**Cài đặt**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải ODP với một thể hiện của lớp Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lặp lại tất cả các Tác giả của ODP đã tải
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

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng chú thích được hỗ trợ khác" subTitle="Sử dụng C#, người ta có thể dễ dàng chú thích các định dạng khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
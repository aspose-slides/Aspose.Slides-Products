---
title: Xóa chú thích PPT bằng C++
weight: 4380
url: /vi/cpp/annotation/ppt/ 
description: Mã nguồn C++ để xóa chú thích khỏi PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Xóa Nhận xét và Tác giả Nhận xét khỏi PPT trong C++" h2="Xây dựng ứng dụng C++ của riêng bạn để thao tác nhận xét và tác giả trong tệp tài liệu bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa Nhận xét khỏi PPT qua C++" %}}
Để xóa chú thích khỏi tệp PPT, chúng tôi sẽ sử dụng API [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/) API có nhiều tính năng, mạnh mẽ và dễ sử dụng API thao tác tài liệu cho nền tảng C++.
{{% blocks/products/pf/agp/code-block title="Xóa chú thích khỏi PPT - C++" offSpacer="true" %}}

```cpp

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System::Drawing;

auto presentation = System::MakeObject<Presentation>(u"example.ppt");

// Deletes all comments from the presentation
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}
        
// Deletes all authors
presentation->get_CommentAuthors()->Clear();
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Cách xóa Nhận xét khỏi PPT qua C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho C++**. Xem [**Cài đặt**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPT với một thể hiện của lớp Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lặp lại tất cả các Tác giả của PPT đã tải
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

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng chú thích được hỗ trợ khác" subTitle="Sử dụng C++, người ta có thể dễ dàng chú thích các định dạng khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
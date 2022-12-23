---
title: Chỉnh sửa PDF trong C#
url: /vi/net/editor/pdf/
keywords: Chỉnh sửa PDF, PDF, C# API, Thư viện .NET
description: Chỉnh sửa PDF trong C#. Sử dụng API thư viện .NET để chỉnh sửa tài liệu PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chỉnh sửa PDF trong C#" h2="API .NET đa nền tảng mạnh mẽ để chỉnh sửa PDF bằng mã C# trên Nền tảng NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Chỉnh sửa PDF bằng Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/vi/net/) là một thư viện .NET mạnh mẽ được sử dụng để thao tác và chỉnh sửa bản trình bày, tài liệu PDF và các tệp khác. Bạn có thể chỉnh sửa tài liệu PDF bằng cách thêm một dòng văn bản mới vào đó. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Chỉnh sửa PDF trong C#" %}}
Sử dụng [**Aspose.Slides for .NET**](https://products.aspose.com/slides/vi/net/), bạn có thể thêm một dòng văn bản mới vào tài liệu PDF chỉ bằng một vài dòng mã.

{{% blocks/products/pf/agp/code-block title="Mã C# để chỉnh sửa PDF" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách chỉnh sửa PDF trong C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho .NET**. Xem [**Cài đặt**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm thư viện làm tài liệu tham khảo trong dự án của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tạo một thể hiện của lớp Trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải tài liệu PDF bạn muốn chỉnh sửa.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm một dòng văn bản mới.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tệp PDF đã thay đổi.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Chỉnh sửa các tệp khác" subTitle="Bạn cũng có thể chỉnh sửa tệp ở các định dạng khác" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
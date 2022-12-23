---
title: Chỉnh sửa HTML trong C#
url: /vi/net/editor/html/
keywords: Chỉnh sửa thư viện HTML, HTML, C# API, .NET
description: Chỉnh sửa HTML trong C#. Sử dụng API thư viện .NET để chỉnh sửa tệp HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chỉnh sửa HTML trong C#" h2="API .NET đa nền tảng mạnh mẽ để chỉnh sửa HTML bằng mã C# trên Nền tảng NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Chỉnh sửa HTML bằng Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/vi/net/) là một thư viện .NET mạnh mẽ được sử dụng để thao tác và chỉnh sửa bản trình bày, tài liệu HTML và các tệp khác. Bạn có thể chỉnh sửa tài liệu HTML bằng cách thêm một dòng văn bản mới vào đó. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Chỉnh sửa HTML trong C#" %}}
Sử dụng [**Aspose.Slides for .NET**](https://products.aspose.com/slides/vi/net/), bạn có thể thêm một dòng văn bản mới vào tài liệu HTML chỉ bằng một vài dòng mã.

{{% blocks/products/pf/agp/code-block title="Mã C# để chỉnh sửa HTML" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide
    pres.Slides.AddFromHtml("page.html");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("page.html", SaveFormat.Html);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách chỉnh sửa HTML trong C#" >}}


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
Tải tài liệu HTML mà bạn muốn chỉnh sửa.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm một dòng văn bản mới.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tệp HTML đã thay đổi.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Chỉnh sửa các tệp khác" subTitle="Bạn cũng có thể chỉnh sửa tệp ở các định dạng khác" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
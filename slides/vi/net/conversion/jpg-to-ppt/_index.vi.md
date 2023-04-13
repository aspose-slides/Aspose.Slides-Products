---
title: Chuyển đổi JPG sang PPT trong C#
url: /vi/net/conversion/jpg-to-ppt/
keywords: Chuyển đổi JPG sang PPT, JPG sang PPT, PowerPoint, JPG, PPT, C# API, Thư viện .NET
description: Chuyển đổi JPG sang PPT trong C#. Sử dụng API thư viện .NET để chuyển ảnh JPG sang PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi JPG sang PPT trong C#" h2="API .NET đa nền tảng mạnh mẽ để chuyển đổi JPG sang PPT bằng mã C# trên Nền tảng NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi JPG sang PPT bằng Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/vi/net/) là một thư viện .NET mạnh mẽ được sử dụng để tạo, chuyển đổi và thao tác với các bản trình bày PowerPoint, PDF, tài liệu HTML, và các tập tin khác. Khi bạn chuyển đổi JPG sang PPT, về cơ bản, bạn đang tạo bản trình bày PowerPoint có chứa các trang chiếu dựa trên hình ảnh JPG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi JPG sang PPT trong C#" %}}
Sử dụng [**Aspose.Slides for .NET**](https://products.aspose.com/slides/vi/net/), bạn có thể chuyển đổi hình ảnh JPG sang bản trình bày PowerPoint chỉ bằng một vài dòng mã:

{{% blocks/products/pf/agp/code-block title="Mã C# để chuyển đổi JPG sang PPT" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách chuyển đổi JPG sang PPT trong C#" >}}


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
Tải hình ảnh JPG mà bạn muốn chuyển đổi sang PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tệp kết quả dưới dạng bản trình bày PPT.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Chuyển đổi trực tuyến miễn phí" sectionDescription="[Cách chuyển đổi PPT sang HTML bằng Python](https://products.aspose.com/slides/vi/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi PowerPoint được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi các tệp ở các định dạng khác sang PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
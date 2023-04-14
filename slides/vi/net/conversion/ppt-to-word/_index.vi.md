---
title: Chuyển đổi PPT sang Word trong C#
url: /vi/net/conversion/ppt-to-word/
keywords: Chuyển đổi PPT sang Word, PPT sang Word, PPT sang DOC, PowerPoint sang Word, C# API, Thư viện .NET
description: Chuyển đổi PPT sang Word trong C#. Sử dụng API thư viện .NET để chuyển PowerPoint sang Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi PPT sang Word trong C#" h2="API .NET đa nền tảng mạnh mẽ để chuyển đổi PowerPoint sang Word bằng mã C# trên Nền tảng NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi PowerPoint sang Word bằng Aspose.Slides và Aspose.Words" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/vi/net/) và [**Aspose.Words for .NET**](https://products.aspose. com/words/net/) là các thư viện .NET mạnh mẽ được sử dụng để thao tác và chuyển đổi bản trình bày PowerPoint, tài liệu Word và các tệp khác. Khi bạn chuyển đổi PowerPoint sang Word, về cơ bản, bạn đang di chuyển nội dung của các trang chiếu của bản trình bày sang các trang trong tài liệu Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Chuyển PowerPoint sang Word trong C#" %}}
Bạn có thể chuyển PPT sang Word nhanh chóng chỉ với vài dòng mã

{{% blocks/products/pf/agp/code-block title="Mã C# để chuyển đổi PowerPoint sang Word" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách chuyển PPT sang Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho .NET** và **Aspose.Words cho .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm hai thư viện làm tài liệu tham khảo trong dự án của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tạo một thể hiện của lớp Trình bày và lớp Tài liệu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải bản trình bày PPT mà bạn muốn chuyển đổi sang Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tạo hình ảnh và văn bản dựa trên nội dung của trang trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tài liệu Word kết quả.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Chuyển đổi trực tuyến miễn phí" sectionDescription="[Cách chuyển đổi PPT sang HTML bằng Python](https://products.aspose.com/slides/vi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PowerPoint sang các tệp ở các định dạng khác" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
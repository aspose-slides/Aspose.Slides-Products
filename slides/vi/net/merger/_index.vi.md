---
title: Hợp nhất PDF, PPT, PPTX và nhiều định dạng tệp khác bằng C #
url: /vi/net/merger/
keywords: Merge, Join, PowerPoint, Presentation, C #, .NET, Aspose
description: Hợp nhất nhiều tệp trong C # PPT, PPTX, ODP, PDF, PNG, JPG và nhiều tệp khác.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Hợp nhất Powerpoint, PDF, PPT hoặc các tài liệu khác với nhau trong C #" h2="Thư viện C # tốc độ cao để hợp nhất PPT, PPTX, PDF, PNG, JPEG và các định dạng khác." >}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất PPT, PPTX, PDF bằng C #" %}}

[** Aspose.Slides for .NET **](https://products.aspose.com/slides/vi/net/) là một thư viện C # mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để kết hợp nhiều bài thuyết trình PPT / PPTX. Khi bạn hợp nhất một bản trình bày với một bản trình bày khác, bạn đang kết hợp hiệu quả các trang trình bày của chúng trong một bản trình bày duy nhất để có được một tệp. Aspose.Slides cho phép bạn hợp nhất hai bản trình bày theo những cách khác nhau. Bạn có thể hợp nhất các bản trình bày với tất cả các hình dạng, phong cách, văn bản, định dạng, nhận xét, hoạt ảnh, v.v. của chúng mà không phải lo lắng về việc mất chất lượng hoặc dữ liệu.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hợp nhất các bản trình bày PowerPoint trong C #" %}}
Để hợp nhất các bản trình bày PowerPoint, bạn sẽ cần sao chép các trang chiếu từ bản trình bày này sang bản trình bày khác.

{{% blocks/products/pf/agp/code-block title="Hợp nhất các tệp PPTX bằng C #" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hợp nhất các bản trình bày với Slide Master bằng C #" %}}
Mã C # này trình bày cách hợp nhất một số bản trình bày thành một và áp dụng các kiểu từ mẫu bản trình bày chính của trang chiếu. Vì vậy, bản trình bày kết quả sẽ giữ nguyên định dạng nguồn và sẽ chứa định dạng từ trang chiếu chính của bản trình bày khác.

{{% blocks/products/pf/agp/code-block title="Hợp nhất nhiều PPT thành một trong C #" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách hợp nhất các bản trình bày bằng cách sử dụng Aspose.Slides cho .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để hợp nhất hai tệp PPTX và lưu kết quả dưới dạng PDF trong .NET." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [** Aspose.Slides cho .NET **](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án C # của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở các tệp PPTX nguồn trong C #.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kết hợp các tệp PPTX bằng phương pháp ** AddClone **.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu bản trình bày và nhận kết quả dưới dạng tệp PDF duy nhất.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng được hỗ trợ khác để hợp nhất" subTitle="Bạn cũng có thể kết hợp các định dạng tệp khác. Xem các định dạng được hỗ trợ khác bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
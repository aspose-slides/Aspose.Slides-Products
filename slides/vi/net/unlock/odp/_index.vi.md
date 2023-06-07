---
title: Mở khóa tệp bản trình bày ODP bằng .NET
url: /vi/net/unlock/odp/
keywords: Xóa bảo vệ ghi ODP, giải mã ODP, mở khóa bản trình bày ODP, bỏ bảo vệ ODP
description: mã nguồn C# để xóa bảo vệ khỏi Bản trình bày ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Mở khóa ODP bằng C#" h2="Xây dựng ứng dụng .NET của riêng bạn để xóa mật khẩu khỏi PowerPoint và giải mã tệp bản trình bày bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa Mã hóa khỏi Bản trình bày ODP qua C#" %}}
Sử dụng Aspose.Slides for .NET, bạn có thể xóa mã hóa hoặc bảo vệ bằng mật khẩu trên bản trình bày ODP. Bằng cách này, người dùng có thể truy cập hoặc sửa đổi bản trình bày ODP mà không bị hạn chế.
{{% blocks/products/pf/agp/code-block title="Vô hiệu hóa bảo vệ bằng mật khẩu từ ODP bằng C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.odp", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Xóa tính năng chống ghi khỏi bản trình bày ODP bằng C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách xóa mật khẩu khỏi ODP qua C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để xóa bảo vệ khỏi các tệp ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải ODP với phiên bản Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Xóa Bảo vệ ghi bằng lớp ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng được hỗ trợ khác" subTitle="Sử dụng C#, Bạn cũng có thể xóa bảo vệ khỏi các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Mở khóa tệp bản trình bày PPT bằng Python
url: /vi/python-net/unlock/ppt/
keywords: Xóa bảo vệ ghi PPT, giải mã PPT, mở khóa bản trình bày PPT, bỏ bảo vệ PPT
description: mã nguồn Python để xóa bảo vệ khỏi Bản trình bày PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Mở khóa PPT bằng Python" h2="Xây dựng ứng dụng Python của riêng bạn để xóa mật khẩu khỏi PowerPoint và giải mã tệp bản trình bày bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa Mã hóa khỏi Bản trình bày PPT qua Python" %}}
Sử dụng Aspose.Slides for Python via .NET, bạn có thể xóa mã hóa hoặc bảo vệ bằng mật khẩu trên bản trình bày PPT. Bằng cách này, người dùng có thể truy cập hoặc sửa đổi bản trình bày PPT mà không bị hạn chế.
{{% blocks/products/pf/agp/code-block title="Vô hiệu hóa bảo vệ bằng mật khẩu từ PPT bằng Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.ppt", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Xóa tính năng chống ghi khỏi bản trình bày PPT bằng Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.ppt") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.ppt", slides.export.SaveFormat.PPT)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách xóa mật khẩu khỏi PPT qua Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để xóa bảo vệ khỏi các tệp PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPT với phiên bản Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Xóa Bảo vệ ghi bằng lớp ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng được hỗ trợ khác" subTitle="Sử dụng Python, Bạn cũng có thể xóa bảo vệ khỏi các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
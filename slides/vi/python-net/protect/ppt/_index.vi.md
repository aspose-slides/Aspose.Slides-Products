---
title: Bảo vệ tệp bản trình bày PPT bằng Python
url: /vi/python-net/protect/ppt/
keywords: Bảo vệ ghi PPT, Mã hóa PPT, Khóa bản trình bày PPT, Bảo vệ PPT
description: Mã nguồn Python để bảo vệ Bản trình bày PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Khóa hoặc bảo vệ bằng mật khẩu PPT bằng Python" h2="Xây dựng ứng dụng Python của riêng bạn để bảo vệ tệp bản trình bày bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Bảo vệ Bản trình bày PPT qua Python" %}}
Sử dụng Aspose.Slides for Python via .NET, bạn có thể bảo vệ bản trình bày PPT của mình khỏi bị mở hoặc sửa đổi bằng cách đặt mật khẩu. Sau đó, để mở hoặc sửa đổi bản trình bày bị khóa, người dùng phải cung cấp mật khẩu.
{{% blocks/products/pf/agp/code-block title="Mã hóa Bản trình bày PPT bằng Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Đặt tính năng Chống ghi cho Bản trình bày PPT bằng Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách bảo vệ bằng mật khẩu PPT qua Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để Bảo vệ tệp PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPT với phiên bản Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bảo vệ bài thuyết trình bằng lớp ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng bảo vệ được hỗ trợ khác" subTitle="Sử dụng Python, Bạn cũng có thể bảo vệ các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
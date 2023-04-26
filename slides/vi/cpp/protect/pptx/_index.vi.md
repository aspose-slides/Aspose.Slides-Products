---
title: Bảo vệ tệp bản trình bày PPTX bằng C++
url: /vi/cpp/protect/pptx/
keywords: Bảo vệ ghi PPTX, Mã hóa PPTX, Khóa bản trình bày PPTX, Bảo vệ PPTX
description: Mã nguồn C++ để bảo vệ Bản trình bày PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Khóa hoặc bảo vệ bằng mật khẩu PPTX bằng C++" h2="Xây dựng ứng dụng C++ của riêng bạn để bảo vệ tệp bản trình bày bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Bảo vệ Bản trình bày PPTX qua C++" %}}
Sử dụng Aspose.Slides for C++, bạn có thể bảo vệ bản trình bày PPTX của mình khỏi bị mở hoặc sửa đổi bằng cách đặt mật khẩu. Sau đó, để mở hoặc sửa đổi bản trình bày bị khóa, người dùng phải cung cấp mật khẩu.
{{% blocks/products/pf/agp/code-block title="Mã hóa Bản trình bày PPTX bằng C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Đặt tính năng Chống ghi cho Bản trình bày PPTX bằng C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách bảo vệ bằng mật khẩu PPTX qua C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để Bảo vệ tệp PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPTX với phiên bản Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bảo vệ bài thuyết trình bằng lớp ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng bảo vệ được hỗ trợ khác" subTitle="Sử dụng C++, Bạn cũng có thể bảo vệ các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
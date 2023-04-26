---
title: Bảo vệ tệp bản trình bày ODP bằng C++
url: /vi/cpp/protect/odp/
keywords: Bảo vệ ghi ODP, Mã hóa ODP, Khóa bản trình bày ODP, Bảo vệ ODP
description: Mã nguồn C++ để bảo vệ Bản trình bày ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Khóa hoặc bảo vệ bằng mật khẩu ODP bằng C++" h2="Xây dựng ứng dụng C++ của riêng bạn để bảo vệ tệp bản trình bày bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Bảo vệ Bản trình bày ODP qua C++" %}}
Sử dụng Aspose.Slides for C++, bạn có thể bảo vệ bản trình bày ODP của mình khỏi bị mở hoặc sửa đổi bằng cách đặt mật khẩu. Sau đó, để mở hoặc sửa đổi bản trình bày bị khóa, người dùng phải cung cấp mật khẩu.
{{% blocks/products/pf/agp/code-block title="Mã hóa Bản trình bày ODP bằng C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Đặt tính năng Chống ghi cho Bản trình bày ODP bằng C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách bảo vệ bằng mật khẩu ODP qua C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để Bảo vệ tệp ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải ODP với phiên bản Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bảo vệ bài thuyết trình bằng lớp ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng bảo vệ được hỗ trợ khác" subTitle="Sử dụng C++, Bạn cũng có thể bảo vệ các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
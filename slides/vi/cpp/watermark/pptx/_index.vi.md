---
title: Thêm Hình mờ vào Tệp Bản trình bày PPTX bằng C++
url: /vi/cpp/watermark/pptx/
keywords: Thêm Hình mờ PPTX, Thêm Hình mờ Văn bản PPTX, Thêm Hình mờ Hình ảnh PPTX
description: Mã nguồn C++ để thêm Hình mờ vào Bản trình bày PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Thêm Hình mờ vào Bản trình bày PPTX bằng C++" h2="Xây dựng các ứng dụng C++ của riêng bạn để chèn hình mờ văn bản hoặc hình ảnh vào bản trình bày PPT, PPTX hoặc ODP bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Thêm Hình mờ vào Bản trình bày PPTX qua C++" %}}
Sử dụng Aspose.Slides for C++, bạn có thể thêm hình mờ vào bản trình bày PPTX. Hình mờ là một phần thiết yếu của bất kỳ bài thuyết trình nào. Chúng được sử dụng để bảo vệ nội dung của bài thuyết trình không bị sao chép hoặc sử dụng trái phép. Hình mờ là một hình ảnh hoặc văn bản hiển thị hoặc không nhìn thấy được đặt ở trên cùng của bản trình bày. Nó có thể được sử dụng để xác định chủ sở hữu của bài thuyết trình và để ngăn chặn việc sử dụng trái phép. Hình nền mờ cũng có thể được sử dụng để thêm nét chuyên nghiệp cho bản trình bày và làm cho bản trình bày trông bóng bẩy hơn. 
{{% blocks/products/pf/agp/code-block title="Thêm Hình mờ văn bản vào PPTX bằng C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Thêm hình mờ vào bản trình bày PPTX bằng C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách thêm Hình mờ vào PPTX qua C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để thêm hình mờ văn bản vào tệp PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPTX với phiên bản Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chọn bản trình bày chính
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm loại hình bằng phương pháp AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm văn bản hình mờ bằng phương pháp AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng được hỗ trợ khác" subTitle="Sử dụng C++, Bạn cũng có thể thêm Hình mờ vào các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
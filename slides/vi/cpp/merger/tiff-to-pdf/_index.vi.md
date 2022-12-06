---
title: Hợp nhất TIFF thành PDF trong C++
url: /vi/cpp/merger/tiff-to-pdf/
keywords: TIFF sang PDF, Hợp nhất TIFF sang PDF, Nối TIFF sang PDF, PDF, TIFF, API C++, Thư viện C++
description: Hợp nhất TIFF thành PDF trong C++. Sử dụng API thư viện C++ để kết hợp TIFF và PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Hợp nhất TIFF thành PDF trong C++" h2="Thư viện C++ tốc độ cao và đa nền tảng để hợp nhất các tệp TIFF thành PDF bằng mã C++" >}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất TIFF thành PDF bằng Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/vi/cpp/) là một thư viện C++ mạnh mẽ được sử dụng để tạo, chuyển đổi, hợp nhất và thao tác với các bản trình bày, PDF, hình ảnh và các nội dung khác các tập tin. Khi bạn hợp nhất TIFF thành PDF, bạn đang kết hợp các hình ảnh một cách hiệu quả để thu được một tệp PDF duy nhất.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Hợp nhất TIFF thành PDF trong C++" %}}
Sử dụng [**Aspose.Slides for C++**](https://products.aspose.com/slides/vi/cpp/), bạn có thể hợp nhất TIFF thành PDF một cách nhanh chóng chỉ với một vài dòng mã

{{% blocks/products/pf/agp/code-block title="Mã C++ để hợp nhất TIFF thành PDF" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
        
auto image1 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image1.tiff"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 100.0f, 100.0f, image1);
auto image2 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image2.tiff"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 200.0f, 100.0f, 100.0f, image2);

pres->Save(u"pres.pdf", SaveFormat::Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách hợp nhất TIFF thành PDF trong C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho C++**. Xem [**Cài đặt**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm thư viện làm tài liệu tham khảo trong dự án của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tạo một thể hiện của lớp Trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải các tệp TIFF mà bạn muốn hợp nhất dưới dạng khung ảnh.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tệp PDF kết quả.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Hợp nhất các tệp khác" subTitle="Bạn cũng có thể kết hợp các tệp ở các định dạng khác để có được một tệp duy nhất" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
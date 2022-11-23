---
title: Chuyển đổi JPG thành PDF trong C++
url: /vi/cpp/conversion/jpg-to-pdf/
keywords: JPG sang PDF, Chuyển đổi JPG sang PDF, API C++, Thư viện C++, JPG, PDF
description: Chuyển đổi JPG thành PDF trong C++. Sử dụng API thư viện C++ để chuyển đổi tệp JPG thành tệp PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi JPG thành PDF trong C++" h2="Thư viện C++ tốc độ cao và đa nền tảng giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp trình chiếu Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi JPG thành PDF trong C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/vi/cpp/) là một thư viện C++ mạnh mẽ để tạo và thao tác với các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi JPG thành PDF. Sử dụng **Aspose.Slides for C++**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp JPG thành PDF chỉ bằng một vài dòng mã C++.

Là một API xử lý tài liệu hiện đại, Aspose.Slides for C++ xuất các tệp JPG sang các định dạng tệp PDF một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi JPG thành PDFs và nhiều định dạng tệp khác

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi JPG sang PDF bằng C++" %}}
Để chuyển đổi JPG sang PDF, bạn cần tạo Bản trình bày từ tệp JPG và lưu dưới dạng PDF.

{{% blocks/products/pf/agp/code-block title="Mã C++ để chuyển đổi JPG thành PDF" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách chuyển đổi JPG thành PDF bằng Aspose.Slides cho API C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để chuyển đổi JPG thành PDF trong C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides cho C++**](https://products.aspose.com/slides/vi/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án C ++ của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp nguồn JPG bằng C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi JPG sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi JPG và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/conversion/jpg-to-png/" name="JPG TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
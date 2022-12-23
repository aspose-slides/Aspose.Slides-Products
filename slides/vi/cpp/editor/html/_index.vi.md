---
title: Chỉnh sửa HTML trong C++
url: /vi/cpp/editor/html/
keywords: Chỉnh sửa HTML, HTML, API C++, Thư viện C++
description: Chỉnh sửa HTML trong C++. Sử dụng API thư viện C++ để chỉnh sửa tệp HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chỉnh sửa HTML trong C++" h2="Thư viện C++ tốc độ cao và đa nền tảng để chỉnh sửa HTML bằng mã C++" >}}

{{% blocks/products/pf/feature-page-section h2="Chỉnh sửa HTML bằng Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/vi/cpp/) là một thư viện C++ mạnh mẽ được sử dụng để thao tác và chỉnh sửa bản trình bày, tài liệu HTML và các tệp khác. Bạn có thể chỉnh sửa tài liệu HTML bằng cách thêm một dòng văn bản mới vào đó. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Chỉnh sửa HTML trong C++" %}}
Sử dụng [**Aspose.Slides for C++**](https://products.aspose.com/slides/vi/cpp/), bạn có thể thêm một dòng văn bản mới vào tài liệu HTML chỉ bằng một vài dòng mã.

{{% blocks/products/pf/agp/code-block title="Mã C++ để chỉnh sửa HTML" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromHtml(htmlText1);

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"page.html", SaveFormat::Html5);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách chỉnh sửa HTML trong C++" >}}


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
Tải tài liệu HTML mà bạn muốn chỉnh sửa.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm một dòng văn bản mới.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tệp HTML đã thay đổi.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Chỉnh sửa các tệp khác" subTitle="Bạn cũng có thể chỉnh sửa tệp ở các định dạng khác" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chỉnh sửa PPT trong C++
url: /vi/cpp/editor/ppt/
keywords: Chỉnh sửa PPT, Chỉnh sửa PowerPoint, PPT, PowerPoint, API C++, Thư viện C++
description: Chỉnh sửa PPT trong C++. Sử dụng API thư viện C++ để chỉnh sửa bản trình bày PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chỉnh sửa PPT trong C++" h2="Thư viện C++ tốc độ cao và đa nền tảng để chỉnh sửa PPT bằng mã C++" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chỉnh sửa PPT trong C++" variant="code" %}}

Sử dụng [**Aspose.Slides for C++**](https://products.aspose.com/slides/vi/cpp/), bạn có thể thêm một dòng văn bản mới vào tài liệu PPT chỉ bằng một vài dòng mã.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã C++ để chỉnh sửa PPT" >}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chỉnh sửa PPT bằng Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/vi/cpp/) là một thư viện C++ mạnh mẽ được sử dụng để thao tác và chỉnh sửa bản trình bày. Bạn có thể chỉnh sửa bản trình bày PPT bằng cách thêm một dòng văn bản mới vào đó.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chỉnh sửa PPT trong C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt **Aspose.Slides cho C++**. Xem [**Cài đặt**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm thư viện làm tài liệu tham khảo trong dự án của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo một thể hiện của lớp Trình bày.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải bản trình bày PPT mà bạn muốn chỉnh sửa.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm một dòng văn bản mới.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp PowerPoint đã thay đổi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Được xây dựng bằng Aspose.Slides" title="Chỉnh sửa tệp PPTX trực tuyến" description="Ứng dụng Aspose.Slides Editor miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Editor" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides xử lý tệp của bạn như thế nào trước khi viết mã.
- Tải lên tệp PPTX và chỉnh sửa ngay lập tức.
- Lưu và tải xuống tệp đã chỉnh sửa.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chỉnh sửa các tệp khác" subTitle="Bạn cũng có thể chỉnh sửa tệp ở các định dạng khác" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

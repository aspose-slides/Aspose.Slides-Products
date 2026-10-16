---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển PPT sang Word trong C++
url: /vi/cpp/conversion/ppt-to-word/
keywords: Chuyển đổi PPT sang Word, PPT sang Word, PPT sang DOC, PowerPoint sang Word, API C++, Thư viện C++, CPP
description: Chuyển đổi PPT sang Word trong C++. Sử dụng API thư viện C++ để chuyển PowerPoint sang Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển PPT sang Word trong C++" h2="API C++ đa nền tảng mạnh mẽ để chuyển đổi PowerPoint sang Word bằng mã C++ mà không cần Microsoft PowerPoint hoặc Office" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển PowerPoint sang Word trong C++" variant="code" %}}

Bạn có thể chuyển PPT sang Word nhanh chóng chỉ với vài dòng mã

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã C++ để chuyển đổi PowerPoint sang Word" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PowerPoint sang Word bằng Aspose.Slides và Aspose.Words" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/vi/cpp/) và [**Aspose.Words for C+***](https://products.aspose.com/ words/cpp/) là các thư viện C++ mạnh mẽ được sử dụng để thao tác và chuyển đổi bản trình bày PowerPoint, tài liệu Word và các tệp khác. Khi bạn chuyển đổi PowerPoint sang Word, về cơ bản, bạn đang di chuyển nội dung của các trang chiếu của bản trình bày sang các trang trong tài liệu Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển PPT sang Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt **Aspose.Slides for C++** và **Aspose.Words for C++**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo một thể hiện của lớp Trình bày và lớp Tài liệu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải bản trình bày PPT mà bạn muốn chuyển đổi sang Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo hình ảnh và văn bản dựa trên nội dung của trang trình bày.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tài liệu Word kết quả.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Chuyển đổi trực tuyến miễn phí"
  description="[Cách chuyển đổi PPT sang HTML bằng Python](https://products.aspose.com/slides/vi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PowerPoint sang các tệp ở các định dạng khác" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

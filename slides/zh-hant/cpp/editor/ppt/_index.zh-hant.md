---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 用C++編輯PPT
url: /zh-hant/cpp/editor/ppt/
keywords: 編輯 PPT, 編輯 PowerPoint, PPT, PowerPoint, C++ API, C++ Library
description: 用C++編輯PPT。使用 C++ 庫 API 編輯 PowerPoint 演示文稿
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="用C++編輯PPT" h2="使用C++代碼編輯PPT的高速跨平台C++庫" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="用C++編輯PPT" variant="code" %}}

使用 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/)，您只需幾行代碼即可向 PPT 文檔添加新的文本行。

{{< blocks/products/pf/slides-design-update-10-2026/code title="編輯PPT的C++代碼" >}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 編輯 PPT" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/) 是一個功能強大的 C++ 庫，用於操作和編輯演示文稿。您可以通過向其中添加新的文本行來編輯 PPT 演示文稿。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何用C++編輯PPT" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝**Aspose.Slides for C++**。請參閱 [**安裝**](https://docs.aspose.com/slides/cpp/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加庫作為項目中的引用。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}創建一個 Presentation 類的實例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加載要編輯的 PPT 演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加新的文本行。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}保存更改後的 PowerPoint 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="編輯其他文件" subTitle="您還可以編輯其他格式的文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

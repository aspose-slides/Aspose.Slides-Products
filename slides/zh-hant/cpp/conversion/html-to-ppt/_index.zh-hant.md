---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 C++ 中將 HTML 轉換為 PPT
url: /zh-hant/cpp/conversion/html-to-ppt/
keywords: 將 HTML 轉換為 PPT、將 HTML 轉換為 PPT、PowerPoint、HTML、PPT、C++ API、C++ 庫
description: 在 C++ 中將 HTML 轉換為 PPT。使用 C++ 庫 API 將 HTML 轉換為 PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C++ 中將 HTML 轉換為 PPT" h2="強大的跨平台 C++ API，用於使用 C++ 代碼將 HTML 轉換為 PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 C++ 中將 HTML 轉換為 PPT" variant="code" %}}

使用 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/)，只需幾行代碼即可將 HTML 文檔轉換為 PowerPoint 演示文稿：

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML轉PPT的C++代碼" >}}
```cpp
auto presentation = System::MakeObject<Presentation>();
presentation->get_Slides()->RemoveAt(0);

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

presentation->Save(u"MyPresentation.ppt", SaveFormat::Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 將 HTML 轉換為 PPT" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/) 是一個強大的 C++ 庫，用於創建、轉換和操作 PowerPoint 演示文稿、PDF、HTML 文檔和其他文件。將 HTML 轉換為 PPT 時，實際上是將 HTML 文檔中的內容移動到 PowerPoint 演示文稿中的幻燈片。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在C++中將HTML轉換為PPT" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝**Aspose.Slides for C++**。請參閱 [**安裝**](https://docs.aspose.com/slides/cpp/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加庫作為項目中的引用。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}創建一個 Presentation 類的實例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加載要轉換為 PPT 的 HTML 文檔。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將生成的文件另存為 PPT 演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="免費在線轉換器"
  description="[如何在 Python 中將 PPT 轉換為 HTML](https://products.aspose.com/slides/zh-hant/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的 PowerPoint 轉換" subTitle="您還可以將其他格式的文件轉換為 PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

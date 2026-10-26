---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 在 PPTX 簡報中搜尋文字
url: /zh-hant/cpp/search/pptx/
description: 在 C++ 中搜尋 PPTX 簡報中的文字。使用 Aspose.Slides for C++ 尋找簡報檔案中的文字。
keywords: 在 PPTX 中搜尋單字，在 PPTX 中尋找文字，搜尋 PPTX 簡報文字
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 在 PPTX 中搜尋文字" h2="使用 Aspose.Slides for C++ 尋找簡報檔案中的文字，無需 Microsoft PowerPoint。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 C++ 在 PPTX 簡報中搜尋文字" variant="code" %}}

Aspose.Slides for C++ 可用於在 PPTX 簡報中搜尋文字。使用 `SlideUtil::GetAllTextBoxes` 收集投影片的文字框架，然後檢查其文字是否包含所需片語。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 在單一 PPTX 簡報中搜尋文字" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 C++ 在 PPTX 中搜尋文字" intro="依照下列步驟在 PPTX 簡報中搜尋文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 PPTX 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation::get_Slides` 取得所需投影片，並使用 [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/) 取得其文字框架。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}檢查每個框架的文字是否包含所需片語。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="以 Aspose.Slides 建置" title="線上搜尋 PPTX 檔案中的文字" description="免費的 Aspose.Slides Search 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTX 檔案。" button="開啟 Aspose.Slides Search" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，了解 Aspose.Slides 如何尋找文字。
- 在您的 PPTX 檔案中搜尋純文字或規則運算式。
- 將相符結果下載為文字檔。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援搜尋的格式" subTitle="使用 C++，您也可以在下列格式中搜尋文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

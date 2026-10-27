---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: 使用 C++ 移除 PPTX 註解
url: /zh-hant/cpp/annotation/pptx/ 
description: 用於從 PPTX 簡報移除註解的 C++ 原始碼。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 從 PPTX 移除註解和註解作者" h2="建置 C++ 應用程式，使用伺服器端 API 處理簡報檔案中的註解和作者。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 C++ 從 PPTX 移除註解" variant="code" %}}

使用 [Aspose.Slides for C++](/slides/zh-hant/cpp/) 從 PPTX 簡報中移除註解和註解作者。下列範例會先清除 `get_CommentAuthors` 中每位作者的註解，再清空註解作者集合。

{{< blocks/products/pf/slides-design-update-10-2026/code title="從 PPTX 刪除註解 – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.pptx");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 C++ 從 PPTX 移除註解" intro="依照下列步驟，從 PPTX 簡報中移除註解和註解作者。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 Aspose.Slides for C++。請參閱[安裝](https://docs.aspose.com/slides/cpp/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 PPTX 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理 `get_CommentAuthors` 中的註解作者。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `get_Comments()->Clear()` 清除每位作者的註解。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}清空註解作者集合。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat::Pptx` 儲存更新後的簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="以 Aspose.Slides 建置" title="線上移除 PPTX 註解" description="免費的 Aspose.Slides Annotation 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTX 檔案。" button="開啟 Aspose.Slides Annotation" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何移除註解。
- 移除 PPTX 檔案中的所有註解。
- 下載清理後的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="註解支援的其他格式" subTitle="使用 C++，您也可以從其他格式移除註解。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

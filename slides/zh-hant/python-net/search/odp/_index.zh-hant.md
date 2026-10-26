---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 在 ODP 簡報中搜尋文字
url: /zh-hant/python-net/search/odp/
description: 使用 Python 和 Aspose.Slides 在 ODP 簡報中搜尋文字。
keywords: 在 ODP 中搜尋文字，在 ODP 中尋找單字，使用 Python 搜尋 ODP 簡報
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 在 ODP 簡報中搜尋文字" h2="透過 Aspose.Slides 建置在 OpenDocument 簡報中尋找文字的 Python 應用程式。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 在單一 ODP 簡報中搜尋文字" variant="code" %}}

透過 [Aspose.Slides for Python via .NET](/slides/zh-hant/python-net/)，您可以使用 [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) 在每張投影片上尋找包含指定字串的文字框架。

{{< blocks/products/pf/slides-design-update-10-2026/code title="在 ODP 簡報中搜尋文字 – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 在 ODP 中搜尋文字" intro="依照下列步驟在 ODP 簡報中搜尋文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 開啟 ODP 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一走訪投影片，並對每張投影片呼叫 [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}讀取每個相符文字框架的 `text` 屬性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="以 Aspose.Slides 建置" title="線上搜尋 ODP 檔案中的文字" description="免費的 Aspose.Slides Search 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 ODP 檔案。" button="開啟 Aspose.Slides Search" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，了解 Aspose.Slides 如何尋找文字。
- 在您的 ODP 檔案中搜尋純文字或規則運算式。
- 將相符結果下載為文字檔。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援搜尋的格式" subTitle="使用 Python 在其他支援的簡報格式中搜尋文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

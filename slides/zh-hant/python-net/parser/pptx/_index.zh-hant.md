---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 從 PPTX 檔案擷取文字
url: /zh-hant/python-net/parser/pptx/
description: 使用 Python 從 PPTX 簡報擷取文字與文字格式詳細資料。
keywords: 使用 Python 剖析 PPTX, PPTX 剖析器 Python, 在 Python 中從 PPTX 擷取資料, 使用 Python 從 PPTX 擷取文字
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 從 PPTX 簡報擷取文字" h2="建置使用 Aspose.Slides 從 PowerPoint 簡報擷取文字與格式詳細資料的 Python 應用程式。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 從 PPTX 簡報擷取文字的範例" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/zh-hant/python-net/) 在 `SlideUtil` 上提供靜態方法 [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/)。它會傳回整份簡報的 `TextFrame` 物件，並可包含母片投影片中的文字。下列範例會從 PPTX 簡報擷取文字和相關的字型詳細資料。

{{< blocks/products/pf/slides-design-update-10-2026/code title="從 PPTX 簡報擷取文字 - Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.pptx") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 從 PPTX 擷取文字" intro="依照下列步驟從 PPTX 檔案擷取文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 開啟 PPTX 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `SlideUtil.get_all_text_frames` 並指定是否包含母片投影片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理傳回的 `TextFrame` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理每個文字框的 `paragraphs` 集合。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理每個段落的 `portions` 集合。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}讀取目前部分的 `text` 和格式屬性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="以 Aspose.Slides 建置" title="線上擷取文字與影像" description="免費的 Aspose.Slides Parser 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTX 檔案。" button="開啟 Aspose.Slides Parser" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何讀取您的檔案。
- 上傳 PPTX 檔案，取得其中的文字與影像。
- 將所有內容下載為一個 ZIP 壓縮檔。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援剖析的格式" subTitle="使用 Python，也可以從其他支援的簡報格式擷取文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/parser/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

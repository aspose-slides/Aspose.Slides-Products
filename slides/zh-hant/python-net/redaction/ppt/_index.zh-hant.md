---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 對 PPT 簡報中的文字進行去識別化
url: /zh-hant/python-net/redaction/ppt/
description: 使用 Python 尋找並取代 PPT 簡報中的敏感文字。
keywords: PPT 去識別化，在 PPT 中尋找和取代文字，更新 PPT 簡報
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 對 PPT 簡報中的文字進行去識別化" h2="透過 Aspose.Slides 建置在簡報中尋找並取代敏感文字的 Python 應用程式。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 對 PPT 簡報中的文字去識別化" variant="code" %}}

透過 [Aspose.Slides for Python via .NET](/slides/zh-hant/python-net/)，您可以取代整份 PPT 簡報中的敏感文字。將 `Presentation.replace_text` 與 `TextSearchOptions` 搭配使用來控制搜尋，然後儲存修改後的簡報。

{{< blocks/products/pf/slides-design-update-10-2026/code title="對 PPT 簡報中的文字進行去識別化 – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 對 PPT 簡報中的文字進行去識別化" intro="依照下列步驟取代 PPT 簡報中的敏感文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 開啟 PPT 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將 [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) 與 `TextSearchOptions` 搭配使用，取代所需文字。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPT` 儲存修改後的簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="以 Aspose.Slides 建置" title="線上對 PPT 檔案進行去識別化" description="免費的 Aspose.Slides Redaction 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Redaction" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，了解 Aspose.Slides 如何尋找和取代文字。
- 在您的 PPT 檔案中尋找和取代文字，支援規則運算式。
- 下載去識別化後的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援去識別化的格式" subTitle="使用 Python 對其他支援的簡報格式中的文字進行去識別化。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

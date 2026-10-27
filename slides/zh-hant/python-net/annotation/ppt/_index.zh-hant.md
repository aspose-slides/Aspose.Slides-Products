---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: 使用 Python 從 PPT 移除註解
url: /zh-hant/python-net/annotation/ppt/ 
description: 透過 Aspose.Slides for Python via .NET，使用 Python 從 PPT 簡報中移除註解和註解作者。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 從 PPT 移除註解和註解作者" h2="使用 Aspose.Slides for Python via .NET 移除簡報註解及其相關作者。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 Python 從 PPT 移除註解" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/zh-hant/python-net/) 可存取 PPT 簡報中儲存的註解和註解作者。使用 `Presentation` 載入檔案，清空每位作者的 `comments` 集合，清空 `comment_authors`，然後以 PPT 格式儲存結果。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Python 從 PPT 移除註解" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 Python 從 PPT 移除註解" intro="依照下列步驟，從 PPT 簡報中移除所有註解和註解作者。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 開啟 PPT 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理 `comment_authors` 並清空每位作者的 `comments` 集合。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}清空 `comment_authors` 集合。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPT` 呼叫 `save`，寫入更新後的 PPT 簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="以 Aspose.Slides 建置" title="線上移除 PPT 註解" description="免費的 Aspose.Slides Annotation 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Annotation" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何移除註解。
- 移除 PPT 檔案中的所有註解。
- 下載清理後的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="註解支援的其他格式" subTitle="使用 Python，您也可以從其他格式移除註解。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

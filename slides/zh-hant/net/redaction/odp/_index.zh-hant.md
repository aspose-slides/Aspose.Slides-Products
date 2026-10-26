---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 .NET 對 ODP 簡報檔案進行去識別化
url: /zh-hant/net/redaction/odp/
description: 用於在 ODP 簡報中尋找和取代文字的 C# 原始碼。
keywords: ODP 去識別化，在 ODP 中尋找和取代文字，更新 ODP 簡報
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 對 ODP 檔案進行去識別化" h2="建置透過伺服器端 API 在簡報中尋找和取代文字的 .NET 應用程式。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 對 ODP 簡報進行去識別化" variant="code" %}}

透過 [Aspose.Slides for .NET](/slides/zh-hant/net/)，您可以在 ODP 簡報中尋找和取代文字。將 `Presentation.ReplaceText` 與 `TextSearchOptions` 搭配使用來控制搜尋，然後儲存修改後的簡報。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 對 ODP 簡報進行去識別化" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 對 ODP 簡報進行去識別化" intro="依照下列步驟取代 ODP 簡報中的文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 載入 ODP 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將 [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) 與 `TextSearchOptions` 搭配使用，取代所需文字。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Odp` 儲存修改後的簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="以 Aspose.Slides 建置" title="線上對 ODP 檔案進行去識別化" description="免費的 Aspose.Slides Redaction 應用程式以 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 ODP 檔案。" button="開啟 Aspose.Slides Redaction" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，了解 Aspose.Slides 如何尋找和取代文字。
- 在您的 ODP 檔案中尋找和取代文字，支援規則運算式。
- 下載去識別化後的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援去識別化的格式" subTitle="使用 C#，您也可以對下列格式進行去識別化。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 .NET 在 PPT 簡報檔案中搜尋文字
url: /zh-hant/net/search/ppt/
description: 用於在 PPT 簡報中搜尋文字的 C# 原始碼。
keywords: 在 PPT 中搜尋文字，在 PPT 中尋找文字，搜尋 PPT 簡報文字
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 在 PPT 檔案中搜尋文字" h2="建置透過伺服器端 API 在簡報中尋找文字的 .NET 應用程式。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 在 PPT 簡報中搜尋文字" variant="code" %}}

透過 [Aspose.Slides for .NET](/slides/zh-hant/net/)，您可以在 PPT 簡報中搜尋文字。使用 `SlideUtil.GetAllTextBoxes` 取得投影片的文字框架，然後檢查其 `Text` 值是否包含所需片語。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 在 PPT 簡報中搜尋文字" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 在 PPT 簡報中搜尋文字" intro="依照下列步驟在 PPT 簡報中搜尋文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 載入 PPT 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}從 `Presentation.Slides` 取得所需投影片並指派給變數。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/) 取得其文字框架。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}檢查每個框架的 `Text` 值是否包含所需片語。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="以 Aspose.Slides 建置" title="線上搜尋 PPT 檔案中的文字" description="免費的 Aspose.Slides Search 應用程式以 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Search" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，了解 Aspose.Slides 如何尋找文字。
- 在您的 PPT 檔案中搜尋純文字或規則運算式。
- 將相符結果下載為文字檔。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援搜尋的格式" subTitle="使用 C#，您也可以在下列格式中搜尋文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

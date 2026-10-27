---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3070
title: 使用 .NET 從 ODP 檔案擷取文字
url: /zh-hant/net/parser/odp/ 
description: 使用 .NET 從 ODP 檔案擷取文字的 C# 原始程式碼。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 剖析 ODP 檔案" h2="使用伺服器端 .NET API 從 ODP 檔案擷取文字並檢查文字格式。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 剖析 ODP 檔案的方法" %}}

使用 [Aspose.Slides for .NET](/slides/zh-hant/net/) 從 ODP 簡報擷取文字。從 [NuGet](https://www.nuget.org/packages/aspose.slides.net) 安裝套件，或在套件管理器主控台中執行下列命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="剖析 ODP 檔案 - C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 C# 中剖析 ODP 檔案" intro="使用 [Aspose.Slides for .NET](/slides/zh-hant/net/) API 進行基本文件剖析只需幾行程式碼。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 載入 ODP 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SlideUtil.GetAllTextFrames` 取得文字框。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理文字框、段落和文字部分。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}視需要讀取 `Text`、`FontHeight` 和 `LatinFont.FontName` 屬性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統需求" intro="需要受支援的 .NET 執行階段以及 Aspose.Slides for .NET 套件參考。可以使用 Visual Studio 或其他相容的 C# 開發環境。" %}}

- 相容 .NET Framework、.NET、Mono 或 Xamarin 的環境
- Visual Studio 等 C# 開發環境
- 從 NuGet 安裝的 Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="以 Aspose.Slides 建置" title="線上擷取文字與影像" description="免費的 Aspose.Slides Parser 應用程式以 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 ODP 檔案。" button="開啟 Aspose.Slides Parser" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何讀取您的檔案。
- 上傳 ODP 檔案，取得其中的文字與影像。
- 將所有內容下載為一個 ZIP 壓縮檔。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP 檔案使用 OpenDocument Presentation 格式。簡報包含帶有文字、影像、格式、動畫和其他媒體的投影片。OpenOffice 和 StarOffice 等支援 OpenDocument 格式的應用程式可以開啟 ODP 檔案。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援剖析的格式" subTitle="使用 C#，也可以剖析下列格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/parser/ppt/" name="PPT" description="PowerPoint 97-2003 簡報" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/parser/pptx/" name="PPTX" description="PowerPoint Open XML 簡報" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

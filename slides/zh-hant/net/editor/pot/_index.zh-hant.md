---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通過 .NET 編輯 POT 文件
url: /zh-hant/net/editor/pot/ 
description: 用於在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上編輯 POT 文檔的 C# 源代碼。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C# 中編輯 POT 格式" h2="使用用於 .NET API 的服務器端 Aspose.Slides 進行本機和高性能 POT 文檔編輯，無需使用 Microsoft 或 Adob​​e PDF 等任何軟件。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C# 編輯 POT 文件" %}}

為了編輯 POT 文件，我們將使用 <a href="https://products.aspose.com/slides/zh-hant/net">Aspose.Slides for .NET</a> API，這是一個功能豐富、功能強大的 API以及適用於任何編輯器的 C# 平台的易於使用的 API。打開 <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> 包管理器，搜索 <b>Aspose.Slides</b> 並安裝。您還可以從包管理器控制台使用以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="編輯 POT 文件 - C#" >}}
```cs
using var presentation = new Presentation("document.pot");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.pot", SaveFormat.Pot);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="在 C# 中編輯 POT 文件的步驟" intro="一個基本的文檔編輯 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net) 只需幾行代碼即可完成 API。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 物件載入 POT 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}透過變數存取目標投影片和圖形。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}透過 `TextFrame` 更新文字。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Pot` 儲存編輯後的簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統要求" intro="所有主要平台和操作系統都支持我們的 API。在執行以下代碼之前，請確保您的系統具有以下先決條件。" %}}

- Microsoft Windows 或兼容 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台的操作系統
- Microsoft Visual Studio 等開發環境
- 項目中引用的 .NET DLL 的 Aspose.Slides - 使用上面的下載按鈕從 NuGet 安裝

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" %}}

Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Files created with these versions of Microsoft PowerPoint are in binary format as compared to those created in Office OpenXML file formats using the higher versions of PowerPoint. The files, hence, generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

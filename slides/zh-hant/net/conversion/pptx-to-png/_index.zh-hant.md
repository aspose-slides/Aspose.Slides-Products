---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通過 C# 將 PPTX 轉換為 PNG
weight: 5510
url: /zh-hant/net/conversion/pptx-to-png/ 
description: PPTX 到 PNG C# 轉換的示例代碼。使用 API 示例代碼在 VB.NET、Asp.NET 或任何基於 .NET 的應用程序中將 PPTX 文件批量轉換為 PNG。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="通過 C# 將 PPTX 轉換為 PNG" h2="在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上將 PowerPoint® PPTX 文件導出為 PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C# 將 PPTX 轉換為 PNG" %}}

為了將 PPTX 轉換為 PNG，我們將使用
 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net)
 API 是一個功能豐富、功能強大且易於使用的 C# 平台文檔操作和轉換 API。打開
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 包管理器，搜索
 Aspose.Slides
 並安裝。您還可以從包管理器控制台使用以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="包管理器控制台命令" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="此示例代碼顯示 PPTX 到 PNG C# 轉換" >}}
```cs
using (var presentation = new Presentation("template.pptx"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in PNG format
        bitmap.Save(string.Format("Slide_{0}.png", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Png);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="通過 C# 將 PPTX 轉換為 PNG 的步驟" intro=".NET 開發人員只需幾行代碼即可輕鬆加載 PPTX 文件並將其轉換為 PNG。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 類的實例加載 PPTX 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍歷演示文稿中的每張幻燈片{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}每次迭代都將全尺寸圖像創建為位圖{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}以 PNG 文件擴展名和 ImageFormat.Png 作為參數調用 Bitmap.Save 方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統要求" intro="在運行 .NET 轉換示例源代碼之前，請確保您具有以下先決條件。" %}}

- Microsoft Windows 或與 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台兼容的操作系統。
- Microsoft Visual Studio 等開發環境。
- 項目中引用的 .NET DLL 的 Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="pptx-to-png"
  title="免費應用程序將PPTX轉換為PNG"
  description="[嘗試我們的免費應用程序將PPT轉換為PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的轉換" subTitle="您還可以將 PPTX 轉換為許多其他文件格式，包括下面列出的一些文件格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="位圖圖像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-emf/" name="PPTX TO EMF" description="增強的元文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="圖形交換格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-html/" name="PPTX TO HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="JPEG圖像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument 標準格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="便攜式文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="微軟 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="啟用宏的幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="微軟PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="啟用宏的演示文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="可縮放矢量圖形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF 格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="標記圖像格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML 紙張規格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

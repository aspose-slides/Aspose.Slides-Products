---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通過 .NET 合併 ODP 文件
weight: 4610
url: /zh-hant/net/merger/odp/ 
description: 用於在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上組合 ODP 文檔的 C# 源代碼。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C# 中合併 ODP 格式" h2="使用用於 .NET API 的服務器端 Aspose.Slides 進行本機和高性能 ODP 文檔合併，無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C# 合併 ODP 文件" %}}

為了合併 ODP 文件，我們將使用
 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net)
 API 是一個功能豐富、功能強大且易於使用的 C# 平台文檔操作和合併 API。打開
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 包管理器，搜索
 **Aspose.Slides**
 並安裝。您還可以從包管理器控制台使用以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="合併 ODP 文件 - C#" >}}
```cs
var ps1 = new Presentation("presen1.odp");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first ODP presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="在 C# 中合併 ODP 文件的步驟" intro="只需幾行代碼即可完成與 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net) API 合併和連接的基本文檔。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用完整路徑加載所有 ODP 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}製作一份文件作為基礎文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}調用相關方法一一拼接合併文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}調用 Save() 方法並將文件名（完整路徑）和格式 (ODP) 作為參數傳遞。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}現在您可以在 Microsoft Office、Adobe PDF 或任何其他兼容程序中打開和使用 ODP 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統要求" intro="所有主要平台和操作系統都支持我們的 API。在執行以下代碼之前，請確保您的系統具有以下先決條件。" %}}

- Microsoft Windows 或兼容 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台的操作系統
- Microsoft Visual Studio 等開發環境
- 項目中引用的 .NET DLL 的 Aspose.Slides - 使用上面的下載按鈕從 NuGet 安裝

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="在線合併 PDF 文件"
  description="[如何在 Python 中合併 PDF](https://products.aspose.com/slides/zh-hant/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

副檔名為 `.ODP` 的檔案使用由 OASIS OpenDocument 標準定義的 OpenDocument Presentation 格式。ODP 檔案包含一組投影片，可包括文字、影像、格式、動畫和其他媒體。支援 OpenDocument 簡報的應用程式（例如 LibreOffice Impress 和 Apache OpenOffice Impress）可以開啟 ODP 檔案。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的合併格式" subTitle="使用 C#，One 還可以合併許多其他文件格式，包括。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/otp/" name="OTP" description="OpenDocument 標準格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/pot/" name="POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/potm/" name="POTM" description="微軟 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/potx/" name="POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/pps/" name="PPS" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/ppsm/" name="PPSM" description="啟用宏的幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/ppsx/" name="PPSX" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/ppt/" name="PPT" description="微軟PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/pptm/" name="PPTM" description="啟用宏的演示文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/merger/pptx/" name="PPTX" description="打開 XML 表示格式" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

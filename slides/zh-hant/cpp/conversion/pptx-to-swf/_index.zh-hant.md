---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通過 C++ 應用程序將 PPTX 轉換為 SWF
url: /zh-hant/cpp/conversion/pptx-to-swf/ 
description: PPTX 文檔到 SWF 格式的示例 C++ 轉換代碼。在任何 C++ 應用程序中使用示例代碼將 PPTX 批量轉換為 SWF。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="通過 C++ 將 PPTX 轉換為 SWF" h2="無需安裝 Microsoft PowerPoint 即可使用 C++ 庫進行高性能 PPTX 到 SWF 轉換。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C++ 將 PPTX 轉換為 SWF" %}}

為了將 PPTX 轉換為 SWF，我們將使用 <a href="https://products.aspose.com/slides/zh-hant/cpp">Aspose.Slides for C++</a> API，這是一個功能豐富、功能強大的 API和易於使用的 C++ 平台的文檔操作和轉換 API。可以直接下載最新版本，打開<a href="https://www.nuget.org/packages/aspose.slides">NuGet</a>包管理器，搜索<b>Aspose.Slides.Cpp </b> 並安裝。您還可以從包管理器控制台使用以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```cs

PM> Install-Package Aspose.SLIDES.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX 到 SWF C++ 轉換源代碼" >}}
```cs
// Load the PPTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.pptx");
// Save in SWF format.
prs->Save(u"convertedFile.swf", Aspose::Slides::Export::SaveFormat::Swf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="通過 C++ 將 PPTX 轉換為 SWF 的步驟" intro="Aspose.SLIDES API 讓開發人員只需幾行代碼即可輕鬆地將 PPTX 文件轉換為 SWF。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Aspose.Slides for C++ Presentation Object 加載 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}調用 Save() 方法。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}傳遞帶有 (SWF) 文件擴展名的輸出文件路徑。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}SWF文件將保存在指定路徑。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在兼容程序中打開 SWF 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統要求" intro="Aspose.SLIDES for C++ 支持所有主要平台和操作系統。請確保您具有以下先決條件。" %}}

- Microsoft Windows 或具有適用於 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 運行時環境的兼容操作系統。
- 項目中引用的 C++ DLL 的 Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="免費應用程序將PPTX轉換為SWF"
  description="[嘗試我們的免費Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的轉換" subTitle="您還可以將 PPTX 轉換為許多其他文件格式，包括下面列出的一些文件格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmap Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Enhanced Metafile Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Graphical Interchange Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="JPEG Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument Presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument Standard Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Portable Document Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" description="Portable Network Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint Template Files" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint Template File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint Template Presentation" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Macro-enabled Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Macro-enabled Presentation File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Scalable Vector Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Tagged Image Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-xml/" name="PPTX TO XML" description="Extensible Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML 紙張規格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通過 C++ 應用程序將 PPSM 轉換為 PDF
weight: 6930
url: /zh-hant/cpp/conversion/ppsm-to-pdf/ 
description: PPSM 文檔到 PDF 格式的示例 C++ 轉換代碼。在任何 C++ 應用程序中使用示例代碼將 PPSM 批量轉換為 PDF。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="通過 C++ 將 PPSM 轉換為 PDF" h2="無需安裝 Microsoft PowerPoint 即可使用 C++ 庫將高性能 PPSM 轉換為 PDF。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C++ 將 PPSM 轉換為 PDF" %}}

為了將 PPSM 轉換為 PDF，我們將使用
 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/)
 API 是一個功能豐富、功能強大且易於使用的 C++ 平台文檔操作和轉換 API。可以直接下載最新版本，直接打開
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 包管理器，搜索
 Aspose.Slides.Cpp
 並安裝。您還可以從包管理器控制台使用以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM 到 PDF C++ 轉換源代碼" >}}
```cs
// Load the PPSM.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppsm");
// Save in PDF format.
prs->Save(u"convertedFile.pdf", Aspose::Slides::Export::SaveFormat::Pdf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="通過 C++ 將 PPSM 轉換為 PDF 的步驟" intro="C++ 開發人員只需幾行代碼即可輕鬆地將 PPSM 文件轉換為 PDF。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Aspose.Slides for C++ Presentation Object 加載 PPSM 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}調用 Save() 方法。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}傳遞帶有 (PDF) 文件擴展名的輸出文件路徑。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PDF文件將保存在指定路徑。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在兼容程序中打開 PDF 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統要求" intro="在運行 C++ 轉換示例代碼之前，請確保您具有以下先決條件。" %}}

- Microsoft Windows 或具有適用於 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 運行時環境的兼容操作系統。
- 項目中引用的 C++ DLL 的 Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="以 Aspose.Slides 建置" title="線上將 PPSM 轉換為 PDF" description="免費的 Aspose.Slides Conversion 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPSM 檔案。" button="開啟 Aspose.Slides Conversion" note="[所有免費應用程式](https://products.aspose.app/slides/family)" upload="拖放或上傳您的檔案" saveAs="另存為" convert="轉換" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何轉換檔案。
- 上傳 PPSM 檔案並將其另存為 PDF。
- 下載結果或轉換更多檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的轉換" subTitle="您還可以將 PPSM 轉換為許多其他文件格式，包括下面列出的幾種文件格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="位圖圖像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="增強的元文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="圖形交換格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-html/" name="PPSM TO HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="JPEG圖像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument 標準格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-png/" name="PPSM TO PNG" description="便攜式網絡圖形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="微軟 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="微軟PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="啟用宏的演示文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="打開 XML 表示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="可縮放矢量圖形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="標記圖像格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-xml/" name="PPSM TO XML" description="可擴展標記語言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML 紙張規格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

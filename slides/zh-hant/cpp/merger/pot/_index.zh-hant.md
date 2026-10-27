---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通過 C++ 合併 POT 文件
weight: 4530
url: /zh-hant/cpp/merger/pot/ 
description: 用於在 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 運行時環境上組合 POT 文檔的 C++ 示例代碼。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 合併 POT 文件" h2="使用服務器端 C++ API 進行 POT 文檔合併。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C++ 合併 POT 文件" %}}

為了合併 POT 文件，我們將使用
 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)
 API 是一個功能豐富、功能強大且易於使用的 C++ 平台文檔合併 API。可以直接下載最新版本，直接打開
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 包管理器，搜索
 **Aspose.Slides.Cpp**
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="合併 POT 文件 - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.pot";
const String sourceFilePath2 = u"SourceFile3.pot";
const String outputFilePath = u"mergedOutput.pot";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pot);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="在 C++ 中合併 POT 文件的步驟" intro="只需幾行代碼即可完成與 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API 合併和連接的基本文檔。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加載兩個 POT 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 get\_Slides() 方法遍歷每張幻燈片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 AddClone 功能與所需文件合併。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Save() 方法保存在指定路徑{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統要求" intro="Aspose.Slides for C++ 支持所有主要平台和操作系統。請確保您具有以下先決條件。" %}}

- Microsoft Windows 或具有適用於 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 運行時環境的兼容操作系統。
- 項目中引用的 C++ DLL 的 Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="以 Aspose.Slides 建置" title="線上合併 POT 檔案" description="免費的 Aspose.Slides Merger 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 POT 檔案。" button="開啟 Aspose.Slides Merger" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何合併檔案。
- 上傳多個 POT 檔案並將它們合併為一個。
- 將合併結果下載為一個檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" %}}

副檔名為 .POT 的檔案是二進位格式的 Microsoft PowerPoint 簡報範本。此格式屬於 PowerPoint 97-2003 檔案格式系列。POT 檔案儲存可重複使用的投影片版面配置、佈景主題、樣式、背景、色彩配置、字型和其他格式，用於建立新簡報。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的合併格式" subTitle="使用 C++，One 還可以合併許多其他文件格式，包括.." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/odp/" name="ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/otp/" name="OTP" description="OpenDocument 標準格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/potm/" name="POTM" description="微軟 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/pps/" name="PPS" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/ppsm/" name="PPSM" description="啟用宏的幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/ppsx/" name="PPSX" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/ppt/" name="PPT" description="微軟PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/pptm/" name="PPTM" description="啟用宏的演示文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/pptx/" name="PPTX" description="打開 XML 表示格式" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

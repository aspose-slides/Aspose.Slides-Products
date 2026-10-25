---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 460
title: 使用 C++ 從 ODP 簡報擷取文字
url: /zh-hant/cpp/parser/odp/ 
description: 在 C++ 中從 ODP 簡報擷取文字。使用 Aspose.Slides for C++ 剖析投影片、文字框、段落和文字部分。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C++ 中剖析 ODP 簡報" h2="使用 Aspose.Slides for C++，無需 Microsoft PowerPoint 即可從簡報投影片擷取文字。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C++ 剖析 ODP 檔案的方法" %}}

使用 Aspose.Slides for C++ 剖析 ODP 簡報檔案並從投影片擷取文字。此 API 透過 `SlideUtil::GetAllTextBoxes`、`ITextFrame`、`IParagraph` 和 `IPortion` 提供投影片文字，因此無需自動化 Microsoft PowerPoint 即可讀取文字內容。從 NuGet 安裝 [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) 套件，或在套件管理器主控台中使用下方命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="剖析 ODP 檔案 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 C++ 中剖析 ODP 檔案" intro="使用 Aspose.Slides for C++ 從 ODP 檔案擷取文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 ODP 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SlideUtil::GetAllTextBoxes` 取得第一張投影片的 `ITextFrame` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理 `ITextFrame` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理每個 `ITextFrame` 中的 `IParagraph` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理每個 `IParagraph` 中的 `IPortion` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `get_Text` 讀取文字。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統需求" intro="Aspose.Slides for C++ 支援主要的桌面與伺服器平台。請確認您的專案符合下列先決條件。" %}}

-  Microsoft Windows、Linux、macOS 或其他具備受支援 C++ 執行階段的相容作業系統。
-  在專案中參考的 Aspose.Slides for C++ 程式庫。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="以 Aspose.Slides 建置" title="線上擷取文字與影像" description="免費的 Aspose.Slides Parser 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 ODP 檔案。" button="開啟 Aspose.Slides Parser" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何讀取您的檔案。
- 上傳 ODP 檔案，取得其中的文字與影像。
- 將所有內容下載為一個 ZIP 壓縮檔。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

An ODP file is an OpenDocument presentation file used by applications such as OpenOffice Impress and LibreOffice Impress. It stores slides, text, images, formatting, animations, and other presentation content in an open XML-based package.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援剖析的格式" subTitle="使用 C++，也可以剖析其他簡報格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/parser/ppt/" name="PPT" description="PowerPoint 97-2003 簡報" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/parser/pptx/" name="PPTX" description="PowerPoint Open XML 簡報" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

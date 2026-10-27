---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C# 檢視 PPT
keywords: 檢視 PPT, 開啟 PPT, PPT 檢視器, PPT, PowerPoint, C# API, .NET 程式庫
weight: 6310
url: /zh-hant/net/viewer/ppt/ 
description: 使用 C# 檢視 PPT 檔案。透過 Aspose.Slides for .NET 開啟簡報檔案並將其儲存為 HTML。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 檢視 PPT" h2="用於開啟 PPT 檔案並將其儲存為回應式 HTML 的 C# API。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 檢視 PPT" %}}

若要檢視 PPT 檔案，請使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/)，這是一套功能豐富、強大且易於使用的 C# API。開啟 [NuGet](https://www.nuget.org/packages/aspose.slides.net) 套件管理員，搜尋 **Aspose.Slides** 並安裝。也可以在套件管理器主控台中執行下列命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="套件管理器主控台命令" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

透過 [**Aspose.Slides for .NET**](/slides/zh-hant/net/)，只需幾行程式碼即可載入 PPT 檔案並將其儲存為回應式 HTML。

{{< blocks/products/pf/slides-design-update-10-2026/code title="用於檢視 PPT 的 C# 程式碼" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 檢視 PPT" intro="透過 Aspose.Slides，開發人員只需幾行程式碼即可檢視 PPT 檔案。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 **Aspose.Slides for .NET**。請參閱[**安裝**](https://docs.aspose.com/slides/net/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在專案中加入對該程式庫的參考。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 `PPT` 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}建立 `ResponsiveHtmlController` 物件，用於輸出回應式 HTML。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}建立 `HtmlOptions` 物件並設定 `HtmlFormatter` 屬性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Html` 將 PPT 檔案儲存為 HTML。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統需求" intro="Aspose.Slides for .NET 支援所有主要作業系統。請確認符合下列先決條件。" %}}

- Microsoft Windows 或支援 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 的相容作業系統
- Microsoft Visual Studio 等開發環境
- 在專案中參考 Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="以 Aspose.Slides 建置" title="線上檢視 PPT 檔案" description="免費的 Aspose.Slides Viewer 應用程式以 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Viewer" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何呈現您的檔案。
- 上傳 PPT 檔案並立即檢視其投影片。
- 支援桌面與行動裝置，無需 PowerPoint。
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

副檔名為 .ppt 的檔案是包含一組投影片、用於投影片放映的 PowerPoint 簡報。它使用 Microsoft PowerPoint 97–2003 支援的二進位檔案格式。PPT 檔案可以包含多種內容，例如文字、項目符號清單、影像、多媒體和其他內嵌的 OLE 物件。自 PowerPoint 2007 起，Microsoft 推出了較新的 PPTX 格式，它以 Office Open XML 為基礎，而非這種二進位格式。OpenOffice Impress 和 Apple Keynote 等其他應用程式也可以建立 PPT 檔案。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="檢視其他檔案" subTitle="您也可以開啟並檢視其他格式的簡報。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/odp/" name="ODP" description="OpenDocument 簡報" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/otp/" name="OTP" description="OpenDocument 簡報範本" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/pot/" name="POT" description="PowerPoint 97-2003 範本" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/potm/" name="POTM" description="啟用巨集的 PowerPoint 範本" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/potx/" name="POTX" description="PowerPoint 範本" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/pps/" name="PPS" description="PowerPoint 97-2003 播放檔" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/ppsm/" name="PPSM" description="啟用巨集的 PowerPoint 播放檔" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/ppsx/" name="PPSX" description="PowerPoint 播放檔" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/pptm/" name="PPTM" description="啟用巨集的 PowerPoint 簡報" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/pptx/" name="PPTX" description="PowerPoint 簡報" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

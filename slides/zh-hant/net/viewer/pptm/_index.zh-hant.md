---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C# 檢視 PPTM
keywords: 檢視 PPTM, 開啟 PPTM, PPTM 檢視器, PPTM, PowerPoint, C# API, .NET 程式庫
weight: 4190
url: /zh-hant/net/viewer/pptm/ 
description: 使用 C# 檢視 PPTM 檔案。透過 Aspose.Slides for .NET 開啟簡報檔案並將其儲存為 HTML。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 檢視 PPTM" h2="用於開啟 PPTM 檔案並將其儲存為回應式 HTML 的 C# API。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 檢視 PPTM" %}}

若要檢視 PPTM 檔案，請使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/)，這是一套功能豐富、強大且易於使用的 C# API。開啟 [NuGet](https://www.nuget.org/packages/aspose.slides.net) 套件管理員，搜尋 **Aspose.Slides** 並安裝。也可以在套件管理器主控台中執行下列命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="套件管理器主控台命令" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

透過 [**Aspose.Slides for .NET**](/slides/zh-hant/net/)，只需幾行程式碼即可載入 PPTM 檔案並將其儲存為回應式 HTML。

{{< blocks/products/pf/slides-design-update-10-2026/code title="用於檢視 PPTM 的 C# 程式碼" >}}
```cs
using var presentation = new Presentation("presentation.pptm");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 檢視 PPTM" intro="透過 Aspose.Slides，開發人員只需幾行程式碼即可檢視 PPTM 檔案。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 **Aspose.Slides for .NET**。請參閱[**安裝**](https://docs.aspose.com/slides/net/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在專案中加入對該程式庫的參考。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 `PPTM` 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}建立 `ResponsiveHtmlController` 物件，用於輸出回應式 HTML。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}建立 `HtmlOptions` 物件並設定 `HtmlFormatter` 屬性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Html` 將 PPTM 檔案儲存為 HTML。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統需求" intro="Aspose.Slides for .NET 支援所有主要作業系統。請確認符合下列先決條件。" %}}

- Microsoft Windows 或支援 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 的相容作業系統
- Microsoft Visual Studio 等開發環境
- 在專案中參考 Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="以 Aspose.Slides 建置" title="線上檢視 PPTM 檔案" description="免費的 Aspose.Slides Viewer 應用程式以 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTM 檔案。" button="開啟 Aspose.Slides Viewer" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何呈現您的檔案。
- 上傳 PPTM 檔案並立即檢視其投影片。
- 支援桌面與行動裝置，無需 PowerPoint。
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTM" readMoreLink="https://docs.fileformat.com/presentation/pptm/" %}}

Files with PPTM extension are Macro-enabled Presentation files that are created with Microsoft PowerPoint 2007 or higher versions. They are similar to PPTX files with the difference that the lateral can't execute macros though they can contain macros. PPTM files can be edited by opening them in Microsoft PowerPoint and updating the contents. Another similar format is PPSM but it is read-only by default and starts the slideshow when opened. PPTM, like PPTX, contains slides for different presentation elements like text, images, videos, graphs and other related material.

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
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/ppt/" name="PPT" description="PowerPoint 97-2003 簡報" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/net/viewer/pptx/" name="PPTX" description="PowerPoint 簡報" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

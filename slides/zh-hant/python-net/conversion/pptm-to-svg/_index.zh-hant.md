---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 Python 中將 PPTM 轉換為 SVG
weight: 2610
url: /zh-hant/python-net/conversion/pptm-to-svg/ 
keywords: "Convert, PowerPoint, PPTM, SVG, Presentation, Python"
description: PPTM 到 SVG Python 轉換的示例代碼。使用 PowerPoint Python API 將 PPTM 文件批量轉換為 SVG 文件。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Python 中將 PPTM 轉換為 SVG" h2="強大的 PowerPoint Python 庫，用於將 PPTM 轉換為 SVG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Python 中將 PPTM 轉換為 SVG" %}}

需要以編程方式將 PPTM 文件轉換為 SVG？使用 [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/zh-hant/python-net/) 任何開發人員只需幾行 Python 代碼即可將 PPTM 轉換為 SVG 格式。

作為現代的演示處理 API，Aspose.Slides for Python 可以快速從 PPTM 創建 SVG。在您的 [瀏覽器](https://products.aspose.app/slides/conversion) 中測試 PPTM 到 SVG 轉換的質量。 Aspose PowerPoint PPTX 庫允許您將 PPTM 文件轉換為許多流行的格式。

您可以使用以下 pip 命令從 [PyPI](https://pypi.org/project/Aspose.Slides/) 安裝庫：

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="控制台/終端" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Python 中將 PPTM 保存為 SVG" %}}

使用免費應用程序查看 PPTM 到 SVG 轉換過程的演示。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="此示例代碼顯示了 PPTM 到 SVG Python 的轉換" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptm") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 Python 中將 PPTM 轉換為 SVG" intro="這些是使用 Python 將 PPTM 文件轉換為 SVG 的步驟。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 類的實例加載 PPTM 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在指定輸出文件路徑和 SaveFormat.SVG 作為參數時調用 `save` 方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTM 文件將保存在指定路徑{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統要求" intro="在運行 Python 轉換示例源代碼之前，請確保您具有以下先決條件。" %}}

- 基於 Microsoft Windows 或 Linux 的操作系統（參見 [更多](https://docs.aspose.com/slides/python-net/system-requirements/)）。
- Python 3.5 或更高版本
- 項目中引用的用於 Python 的 Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="以 Aspose.Slides 建置" title="線上將 PPTM 轉換為 SVG" description="免費的 Aspose.Slides Conversion 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTM 檔案。" button="開啟 Aspose.Slides Conversion" note="[所有免費應用程式](https://products.aspose.app/slides/family)" upload="拖放或上傳您的檔案" saveAs="另存為" convert="轉換" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何轉換檔案。
- 上傳 PPTM 檔案並將其另存為 SVG。
- 下載結果或轉換更多檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的轉換" subTitle="您還可以將 PPTM 轉換為許多其他文件格式。請參閱下面的其他支持的轉換" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="位圖圖像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="增強的元文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="圖形交換格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-html/" name="PPTM TO HTML" description="超文本標記語言" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="JPEG圖像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument 標準格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="便攜式文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-png/" name="PPTM TO PNG" description="便攜式網絡圖形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="微軟 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="啟用宏的幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="微軟PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="打開 XML 表示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="標記圖像格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="XML 紙張規格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

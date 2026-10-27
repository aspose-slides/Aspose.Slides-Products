---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 Python 中將 PPSM 轉換為 BMP
weight: 1770
url: /zh-hant/python-net/conversion/ppsm-to-bmp/ 
keywords: "Convert, PowerPoint, PPSM, BMP, Presentation, Python"
description: PPSM 到 BMP Python 轉換的示例代碼。使用 PowerPoint Python API 將 PPSM 文件批量轉換為 BMP 文件。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Python 中將 PPSM 轉換為 BMP" h2="用於將 PPSM 轉換為 BMP 的強大 PowerPoint Python 庫"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Python 中將 PPSM 轉換為 BMP" %}}

需要以編程方式將 PPSM 文件轉換為 BMP？使用 [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/zh-hant/python-net/) 任何開發人員只需幾行 Python 代碼即可將 PPSM 轉換為 BMP 格式。

作為現代的演示處理 API，Aspose.Slides for Python 可以快速從 PPSM 創建 BMP。在您的 [瀏覽器](https://products.aspose.app/slides/conversion) 中測試 PPSM 到 BMP 轉換的質量。 Aspose PowerPoint PPTX 庫允許您將 PPSM 文件轉換為許多流行的格式。

您可以使用以下 pip 命令從 [PyPI](https://pypi.org/project/Aspose.Slides/) 安裝庫：

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="控制台/終端" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Python 中將 PPSM 保存為 BMP" %}}

使用免費應用程序查看 PPSM 到 BMP 轉換過程的演示。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="此示例代碼顯示 PPSM 到 BMP Python 轉換" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 Python 中將 PPSM 轉換為 BMP" intro="這些是使用 Python 將 PPSM 文件轉換為 BMP 的步驟。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 類的實例加載 PPSM 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在指定輸出文件路徑和 SaveFormat.BMP 作為參數時調用 `save` 方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSM文件將保存在指定路徑{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統要求" intro="在運行 Python 轉換示例源代碼之前，請確保您具有以下先決條件。" %}}

- 基於 Microsoft Windows 或 Linux 的操作系統（參見 [更多](https://docs.aspose.com/slides/python-net/system-requirements/)）。
- Python 3.5 或更高版本
- 項目中引用的用於 Python 的 Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="以 Aspose.Slides 建置" title="線上將 PPSM 轉換為 BMP" description="免費的 Aspose.Slides Conversion 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPSM 檔案。" button="開啟 Aspose.Slides Conversion" note="[所有免費應用程式](https://products.aspose.app/slides/family)" upload="拖放或上傳您的檔案" saveAs="另存為" convert="轉換" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何轉換檔案。
- 上傳 PPSM 檔案並將其另存為 BMP。
- 下載結果或轉換更多檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的轉換" subTitle="您還可以將 PPSM 轉換為許多其他文件格式。請參閱下面的其他支持的轉換" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="增強的元文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="圖形交換格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="超文本標記語言" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="JPEG圖像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument 標準格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="便攜式文件格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-png/" name="PPSM TO PNG" description="便攜式網絡圖形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="微軟 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="幻燈片放映" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="微軟PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="啟用宏的演示文件" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="打開 XML 表示格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="可縮放矢量圖形" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="標記圖像格式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/python-net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML 紙張規格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

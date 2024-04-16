---
title: 在 Python 中將 PDF 轉換為 PPS
url: /zh-hant/python-java/conversion/pdf-to-pps/
keywords: Python 簡報轉換、將簡報轉換為 Python、Python 簡報、Aspose.Slides Python、PDF 到 PPS 轉換、Python 簡報庫
description: 在 Python 中將 PDF 轉換為 PPS。使用 Python 函式庫 API 將 PDF 檔案轉換為 PPS
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="使用 Python 輕鬆將 PDF 轉換為 PPS：Aspose.Slides 來救援！" h2="使用 Python 為您的簡報注入新的活力。我們的指南將引導您將現有的 PowerPoint 投影片轉換為引人入勝的 Python 簡報。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Python 中將 PDF 轉換為 PPS" %}}

厭倦了與複雜的簡報軟體搏鬥？ [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/zh-hant/python-java/) 就是您的最佳選擇！這個強大的庫使您能夠輕鬆建立、編輯簡報以及在各種格式之間轉換簡報。需要從 PDF 切換到 PPS？ Aspose.Slides 使其變得輕而易舉，只需要幾行 Python 程式碼。

作為尖端的文檔處理 API，**Aspose.Slides for Python via Java** 擁有閃電般的轉換速度，確保將您的 PDF 演示文稿快速轉換為 PPS 格式。擺脫傳統工具的限制 - Aspose.Slides 使您能夠靈活地將簡報從 PDF 轉換為 PPS 以及各種其他格式，使您能夠完美地適應任何情況的簡報。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 將 PDF 轉換為 PPS" %}}
要將 PDF 轉換為 PPS，您需要從 PDF 文件創建演示文稿並將其另存為 PPS。

{{% blocks/products/pf/agp/code-block title="將 PDF 轉換為 PPS 的 Python 教程" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

pres.save("output.pps", SaveFormat.Pps);

jpype.shutdownJVM()

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python 教程。如何透過 Java API 使用 Aspose.Slides for Python 將 PDF 轉換為 PPS。" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="要透過 Java 使用 Aspose.Slides for Python 將 PDF 轉換為 PPS，您需要將套件匯入 Python 腳本中並建立 Presenter 類別的實例。 Presentation 類別表示 PowerPoint 文件並提供存取和操作其元素的方法。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝[**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/zh-hant/python-java/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）新增到您的 Python 專案中。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Python 中開啟來源 PDF 檔案。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 PPS 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將 PDF 轉換為其他支持的格式" subTitle="您還可以轉換 PDF 並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
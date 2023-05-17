---
title: 使用 Python 編輯 ODP 演示文件
url: /zh-hant/python-net/redaction/odp/
keywords: 編輯 ODP，查找並替換 ODP 中的文本，更新 ODP 演示文稿
description: Python 源代碼，用於查找和替換 ODP 演示文稿中的文本。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 Python 編輯 ODP" h2="構建您自己的 Python 應用程序，以使用服務器端 API 查找和替換演示文件中的文本。了解如何搜索和替換 ODP 演示文稿的內容、評論或元數據中的文本" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Python 編輯 ODP 演示文稿" %}}
只需幾行代碼即可使用 Aspose.Slides for Python via .NET API 搜索和替換內容、評論、幻燈片註釋或元數據中的文本。在 PowerPoint 和 OpenOffice 中查找和替換文本。通過正則表達式數據匹配在演示文稿中編輯文本、評論和元數據。
{{% blocks/products/pf/agp/code-block title="使用 Python 編輯 ODP 演示文稿" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.odp") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通過 Python 編輯 ODP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是編輯 ODP 文件的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 實例加載 ODP。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) 方法查找和替換文本。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
以 ODP 格式保存結果
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="在線 ODP 編輯現場演示" sectionDescription="立即在 ODP 文檔的內容、評論或元數據中搜索和替換文本。" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的密文格式" subTitle="使用Python，您還可以編輯以下格式：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
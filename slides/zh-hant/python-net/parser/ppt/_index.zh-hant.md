---
title: 使用 Python 從 PPT 文件中提取文本和圖像
url: /zh-hant/python-net/parser/ppt/
keywords: 使用 Python 解析 PPT，PPT 解析器 Python，從 Python 中的 PPT 中提取數據，使用 Python 從 PPT 中提取文本，使用 Python 從 PPT 中提取圖像
description: Python源代碼解析PPT Presentation。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 Python 從 PPT 演示文稿中提取文本和圖像" h2="構建您自己的 Python 應用程序，以使用服務器端 API 從 PowerPoint 中提取文本、圖像、視頻和音頻文件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Python 從 PPT 演示文稿中提取文本" %}}
要掃描整個演示文稿中的文本，請使用 SlideUtil 類公開的 [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) 靜態方法。下面的代碼掃描演示文稿中的文本和格式信息，包括母版幻燈片。
{{% blocks/products/pf/agp/code-block title="使用 Python 從 PPT 演示文稿中提取文本" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a PPT file
with slides.Presentation("pres.ppt") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the PPT
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通過 Python 從 PPT 中提取文本" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是解析 PPT 文件的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 實例加載 PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
從 PPT 中的所有幻燈片中獲取 TextFrame 對像數組
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
遍歷 TextFrames 數組
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
循環遍歷當前 TextFrame 中的段落
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
遍歷當前段落中的部分
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
獲取當前部分的文本
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的解析格式" subTitle="使用Python，您還可以掃描以下格式：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
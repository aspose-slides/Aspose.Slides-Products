---
title: 使用 Python 从 PPT 文件中提取文本和图像
url: /zh/python-net/parser/ppt/
keywords: 使用 Python 解析 PPT，PPT 解析器 Python，从 Python 中的 PPT 中提取数据，使用 Python 从 PPT 中提取文本，使用 Python 从 PPT 中提取图像
description: Python源代码解析PPT Presentation。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 Python 从 PPT 演示文稿中提取文本和图像" h2="构建您自己的 Python 应用程序，以使用服务器端 API 从 PowerPoint 中提取文本、图像、视频和音频文件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Python 从 PPT 演示文稿中提取文本" %}}
要扫描整个演示文稿中的文本，请使用 SlideUtil 类公开的 [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) 静态方法。下面的代码扫描演示文稿中的文本和格式信息，包括母版幻灯片。
{{% blocks/products/pf/agp/code-block title="使用 Python 从 PPT 演示文稿中提取文本" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="如何通过 Python 从 PPT 中提取文本" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是解析 PPT 文件的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 实例加载 PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
从 PPT 中的所有幻灯片中获取 TextFrame 对象数组
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
遍历 TextFrame 数组
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
循环遍历当前 TextFrame 中的段落
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
遍历当前段落中的部分
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
获取当前部分的文本
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的解析格式" subTitle="使用Python，您还可以扫描以下格式：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
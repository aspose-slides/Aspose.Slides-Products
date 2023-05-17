---
title: 使用 Python 编辑 PPTX 演示文件
url: /zh/python-net/redaction/pptx/
keywords: 编辑 PPTX，查找并替换 PPTX 中的文本，更新 PPTX 演示文稿
description: Python 源代码，用于查找和替换 PPTX 演示文稿中的文本。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 Python 编辑 PPTX" h2="构建您自己的 Python 应用程序，以使用服务器端 API 查找和替换演示文件中的文本。了解如何搜索和替换 PPTX 演示文稿的内容、评论或元数据中的文本" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Python 编辑 PPTX 演示文稿" %}}
只需几行代码即可使用 Aspose.Slides for Python via .NET API 搜索和替换内容、评论、幻灯片注释或元数据中的文本。在 PowerPoint 和 OpenOffice 中查找和替换文本。通过正则表达式数据匹配在演示文稿中编辑文本、评论和元数据。
{{% blocks/products/pf/agp/code-block title="使用 Python 编辑 PPTX 演示文稿" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通过 Python 编辑 PPTX" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是编辑 PPTX 文件的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 实例加载 PPTX。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) 方法查找和替换文本。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
以 PPTX 格式保存结果
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="在线 PPTX 编辑现场演示" sectionDescription="立即在 PPTX 文档的内容、评论或元数据中搜索和替换文本。" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的密文格式" subTitle="使用Python，您还可以编辑以下格式：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
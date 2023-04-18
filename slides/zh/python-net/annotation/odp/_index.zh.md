---
title: 使用 Python 删除 ODP 注释
weight: 4380
url: /zh/python-net/annotation/odp/ 
description: 去除ODP演示文稿注释的Python源码
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="在 Python 中从 ODP 中删除评论和评论作者" h2="构建您自己的 Python 脚本，以使用服务器端 API 操作文档文件中的评论和作者。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Python 从 ODP 中删除评论" %}}
为了从 ODP 文件中删除注释，我们将使用 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh/python-net/) API，这是一个功能丰富的 API，适用于 Python 平台的强大且易于使用的文档操作 API。
{{% blocks/products/pf/agp/code-block title="从 ODP 中删除注释 - Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.odp") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="如何通过 Python 从 ODP 中删除评论" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
通过 .NET 安装 **Aspose.Slides for Python**。请参阅 [**安装**](https://docs.aspose.com/slides/python-net/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 类的实例加载 ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
遍历加载的 ODP 的所有作者
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
删除作者的所有评论
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
最后删除所有作者
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的注释格式" subTitle="使用 Python，可以轻松地注释其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
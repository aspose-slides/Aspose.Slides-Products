---
title: 使用 Python 刪除 ODP 註釋
weight: 4380
url: /zh-hant/python-net/annotation/odp/ 
description: 去除ODP演示文稿註釋的Python源碼
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="在 Python 中從 ODP 中刪除評論和評論作者" h2="構建您自己的 Python 腳本，以使用服務器端 API 操作文檔文件中的評論和作者。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Python 從 ODP 中刪除評論" %}}
為了從 ODP 文件中刪除註釋，我們將使用 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) API，這是一個功能豐富的 API，適用於 Python 平台的強大且易於使用的文檔操作 API。
{{% blocks/products/pf/agp/code-block title="從 ODP 中刪除註釋 - Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="如何通過 Python 從 ODP 中刪除評論" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
通過 .NET 安裝 **Aspose.Slides for Python**。請參閱 [**安裝**](https://docs.aspose.com/slides/python-net/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 類的實例加載 ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
遍歷加載的 ODP 的所有作者
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
刪除作者的所有評論
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
最後刪除所有作者
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的註釋格式" subTitle="使用 Python，可以輕鬆地註釋其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
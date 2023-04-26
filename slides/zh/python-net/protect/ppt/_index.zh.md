---
title: 使用 Python 保护 PPT 演示文件
url: /zh/python-net/protect/ppt/
keywords: 写保护 PPT，加密 PPT，锁定 PPT 演示文稿，保护 PPT
description: Python 源代码保护 PPT 演示。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 Python 锁定或密码保护 PPT" h2="使用服务器端 API 构建您自己的 Python 应用程序以保护演示文稿文件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Python 保护 PPT 演示文稿" %}}
使用 Aspose.Slides for Python via .NET，您可以通过设置密码来保护您的 PPT 演示文稿不被打开或修改。然后，要打开或修改锁定的演示文稿，用户必须提供密码。
{{% blocks/products/pf/agp/code-block title="使用 Python 加密 PPT 演示文稿" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="使用 Python 为 PPT 演示文稿设置写保护" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通过 Python 密码保护 PPT" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是保护 PPT 文件的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 实例加载 PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 ProtectionManager 类保护演示文稿
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
以 PPT 格式保存结果
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的保护格式" subTitle="使用Python，您还可以保护以下格式：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
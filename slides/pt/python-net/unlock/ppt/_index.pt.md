---
title: Desbloqueie arquivos de apresentação PPT usando Python
url: /pt/python-net/unlock/ppt/
keywords: Remover proteção contra gravação PPT, descriptografar uma apresentação PPT, desbloquear apresentação PPT, desproteger PPT
description: Código-fonte Python para remover a proteção da apresentação PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Desbloqueie PPT usando Python" h2="Crie seus próprios aplicativos Python para remover senhas do PowerPoint e descriptografar arquivos de apresentações usando APIs do lado do servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Removendo a criptografia da apresentação PPT via Python" %}}
Usando Aspose.Slides for Python via .NET, você pode remover a criptografia ou proteção por senha na apresentação PPT. Desta forma, os usuários podem acessar ou modificar a apresentação PPT sem restrições.
{{% blocks/products/pf/agp/code-block title="Desativando a proteção por senha de PPT usando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.ppt", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Removendo a proteção contra gravação da apresentação PPT usando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.ppt") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.ppt", slides.export.SaveFormat.PPT)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como remover a senha de PPT via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para remover a proteção dos arquivos PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar PPT com uma instância de Apresentação
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Remova a proteção contra gravação usando a classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos suportados" subTitle="Usando Python, você também pode remover a proteção dos seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
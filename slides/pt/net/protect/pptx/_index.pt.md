---
title: Proteger arquivos de apresentação PPTX usando .NET
url: /pt/net/protect/pptx/
keywords: Proteção contra gravação PPTX, criptografia de uma apresentação PPTX, bloqueio PPTX, proteção PPTX
description: Código-fonte C# para proteger a apresentação PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bloqueie ou proteja com senha PPTX usando C#" h2="Crie seus próprios aplicativos .NET para proteger arquivos de apresentação usando APIs do lado do servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Protegendo uma apresentação PPTX via C#" %}}
Usando Aspose.Slides for .NET, você pode proteger sua apresentação PPTX contra abertura ou modificação definindo uma senha. Então, para abrir ou modificar a apresentação bloqueada, o usuário deve fornecer a senha.
{{% blocks/products/pf/agp/code-block title="Criptografando uma apresentação PPTX usando C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Configurando proteção contra gravação para uma apresentação PPTX usando C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como proteger com senha PPTX via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para proteger arquivos PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar PPTX com uma instância de Apresentação
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Proteja a apresentação usando a classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de proteção suportados" subTitle="Usando C#, você também pode proteger os seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
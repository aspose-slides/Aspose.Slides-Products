---
title: Visualize ou edite metadados de arquivos PPS usando .NET
url: /pt/net/metadata/pps/
keywords: Editar metadados PPS, visualizar metadados PPS, editar propriedades PPS, visualizar propriedades PPS
description: Código-fonte C# para editar ou visualizar metadados do formato PPS.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Edite propriedades PPS usando C#" h2="Crie seus próprios aplicativos .NET para modificar propriedades integradas e personalizadas em arquivos de apresentação usando APIs do lado do servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Modifique as propriedades de PPS por meio de C#" %}}
Usando Aspose.Slides for .NET, os desenvolvedores podem acessar e modificar os valores de propriedades integradas, bem como propriedades personalizadas. Os desenvolvedores podem usar a propriedade [DocumentProperties](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) exposta pelo objeto Presentation para acessar as propriedades do documento do arquivo de apresentação.
{{% blocks/products/pf/agp/code-block title="Modificar propriedades integradas PPS - C#" offSpacer="true" %}}

```cs

// Instantiate the Presentation class that represents the Presentation
Presentation presentation = new Presentation("presentation.pps");

// Create a reference to IDocumentProperties object associated with Presentation
IDocumentProperties documentProperties = presentation.DocumentProperties;

// Set the builtin properties
documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

// Save your presentation to a file
presentation.Save("DocumentProperties_out.pps", SaveFormat.Pps);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Adicionar propriedades personalizadas a PPS - C#" offSpacer="true" %}}

```cs

// Instantiate the Presentation class
Presentation presentation = new Presentation();

// Getting Document Properties
IDocumentProperties documentProperties = presentation.DocumentProperties;

// Adding Custom properties
documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

// Getting property name at particular index
String getPropertyName = documentProperties.GetCustomPropertyName(2);

// Removing selected property
documentProperties.RemoveCustomProperty(getPropertyName);

// Save your presentation to a file
presentation.Save("CustomDocumentProperties_out.pps", SaveFormat.Pps);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como extrair metadados de PPS via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para extrair metadados de arquivos PPS." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instanciar a classe de apresentação com o caminho para o arquivo PPS
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtenha o objeto DocumentProperties associado à apresentação
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Faça um loop sobre os itens no objeto DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Acessar e modificar propriedades personalizadas
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de metadados suportados" subTitle="Usando C#, você também pode manipular metadados de muitos outros formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
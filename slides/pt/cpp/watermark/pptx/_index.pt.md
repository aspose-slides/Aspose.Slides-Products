---
title: Adicionar marca d'água a arquivos de apresentação PPTX usando C++
url: /pt/cpp/watermark/pptx/
keywords: Adicionar marca d'água PPTX, Adicionar marca d'água de texto PPTX, Adicionar marca d'água de imagem PPTX
description: Código-fonte C++ para adicionar marca d'água à apresentação PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Adicionar marca d'água à apresentação PPTX usando C++" h2="Crie seus próprios aplicativos C++ para inserir marca d'água de texto ou imagem em apresentações PPT, PPTX ou ODP usando APIs do lado do servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Adicionar marca d'água à apresentação PPTX via C++" %}}
Usando Aspose.Slides for C++, você pode adicionar marca d'água à apresentação PPTX. As marcas d'água são uma parte essencial de qualquer apresentação. Eles são usados ​​para proteger o conteúdo da apresentação de ser copiado ou usado sem permissão. Uma marca d'água é uma imagem ou texto visível ou invisível que é colocado na parte superior da apresentação. Ele pode ser usado para identificar o proprietário da apresentação e impedir o uso não autorizado. As marcas d'água também podem ser usadas para adicionar um toque profissional à apresentação e torná-la mais polida. 
{{% blocks/products/pf/agp/code-block title="Adicionar marca d'água de texto a PPTX usando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Adicionar marca d'água de imagem à apresentação PPTX usando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como adicionar marca d'água a PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para adicionar marca d'água de texto a arquivos PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar PPTX com uma instância de Apresentação
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Selecione a apresentação mestre
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicionar tipo de forma usando o método AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicionar texto de marca d'água usando o método AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos suportados" subTitle="Usando C++, você também pode adicionar marca d'água nos seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Editar FODP em PHP
url: /pt/php-java/editor/fodp/
keywords: Editar FODP, Editar PowerPoint, FODP, PowerPoint, API PHP, Biblioteca PHP
description: Edite FODP em PHP. Use a API da biblioteca PHP para editar arquivos FODP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Editar FODP em PHP" h2="Biblioteca PHP multiplataforma e de alta velocidade para edição FODP usando código PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Edite FODP usando Aspose.Slides" %}}

[**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/) é uma poderosa biblioteca PHP para editar apresentações de forma rápida e fácil. Ele fornece aos usuários uma ampla gama de recursos para ajudá-los a criar slides com aparência profissional rapidamente. Com o Aspose, os usuários podem editar texto, adicionar imagens, animações e transições à sua apresentação, bem como aplicar várias opções de formatação, como tipo de fonte e seleção de cores. Além disso, a biblioteca oferece suporte para arquivos PowerPoint (PPT) e formatos OpenOffice Presentation (ODP), o que torna mais fácil do que nunca compartilhar apresentações em diferentes plataformas sem problemas de compatibilidade. Aproveitando o poder da biblioteca do Aspose ao criar ou editar sua próxima apresentação, você terá certeza de que seus slides sempre ficarão ótimos!
Você pode editar um arquivo FODP adicionando uma nova linha de texto a ele. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Editar FODP em PHP" %}}
Usando [**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/), você pode adicionar uma nova linha de texto ao documento FODP com apenas um algumas linhas de código.

{{% blocks/products/pf/agp/code-block title="Código PHP para edição FODP" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.fodp", SaveFormat::Fodp);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como editar FODP em PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para PHP via Java**. Consulte [**Instalação**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione a biblioteca como referência em seu projeto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crie uma instância da classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue a apresentação FODP que deseja editar.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma nova linha de texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o arquivo alterado.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Editar outros arquivos" subTitle="Você também pode editar arquivos em outros formatos" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
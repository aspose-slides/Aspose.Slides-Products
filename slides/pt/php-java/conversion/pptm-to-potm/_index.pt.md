---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPTM para POTM em PHP
weight: 2420
url: /pt/php-java/conversion/pptm-to-potm/ 
keywords: "Convert, PowerPoint, PPTM, POTM, Presentation, PHP"
description: Código de exemplo para conversão PHP de PPTM para POTM. Use a API PHP do PowerPoint para conversão em lote de arquivos PPTM para arquivos POTM.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PPTM para POTM em PHP" h2="Poderosa biblioteca PHP do PowerPoint para converter PPTM para POTM"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PPTM para POTM em PHP" %}}

Precisa converter arquivos PPTM para POTM programaticamente? Usando [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/pt/php-java/) qualquer desenvolvedor pode converter o formato PPTM para POTM com apenas algumas linhas de código PHP .

Como uma API de processamento de apresentação moderna, o Aspose.Slides for PHP cria POTM a partir de PPTM rapidamente. Teste a qualidade da conversão de PPTM para POTM diretamente no seu [navegador](https://products.aspose.app/slides/conversion). A biblioteca Aspose PowerPoint PPTX permite converter arquivos PPTM para muitos formatos populares.

Você pode instalar a biblioteca do [Composer](https://packagist.org/packages/aspose/slides) usando o seguinte comando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salve PPTM como POTM em PHP" %}}

Use o aplicativo gratuito para ver uma demonstração do processo de conversão de PPTM para POTM.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de amostra mostra a conversão de PPTM para POTM PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    $pres->save("output.potm", SaveFormat::Potm);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter PPTM para POTM em PHP" intro="Estas são as etapas para converter um arquivo PPTM para POTM usando PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregar arquivo PPTM com uma instância da classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método `save` enquanto especifica o caminho do arquivo de saída e SaveFormat.POTM como parâmetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}O arquivo PPTM será salvo no caminho especificado{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Requisitos de sistema" intro="Antes de executar o código-fonte de amostra de conversão PHP, certifique-se de ter os seguintes pré-requisitos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o PHP 7, adicione o caminho do PHP para a variável `PATH` do sistema e defina `allow_url_include` para `On` no arquivo `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o JRE 8. Defina a variável de ambiente `JAVA_HOME` como um caminho para o local do JRE instalado.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o Apache Tomcat 8.0 (veja [mais](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTM to POTM"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras conversões compatíveis" subTitle="Você também pode converter PPTM para muitos outros formatos de arquivo. Veja outras conversões compatíveis abaixo" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Imagem em formato bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="Apresentação XML Plana OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Formato de intercâmbio gráfico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Linguagem de marcação de hipertexto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="Imagem JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Formato de apresentação do OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Formato padrão do OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Formato de Documento Portátil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Gráficos Portáteis de Rede" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Apresentação de slides habilitada para macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Formato de apresentação XML aberto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Gráficos vetoriais escalonáveis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Formato de imagem marcada" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Especificações do papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

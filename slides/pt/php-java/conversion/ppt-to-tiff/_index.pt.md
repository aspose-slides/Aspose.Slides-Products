---
title: Converter PPT para TIFF em PHP
weight: 2300
url: /pt/php-java/conversion/ppt-to-tiff/ 
keywords: "Convert, PowerPoint, PPT, TIFF, Presentation, PHP"
description: Código de exemplo para conversão PHP de PPT para TIFF. Use a API PHP do PowerPoint para conversão em lote de arquivos PPT para arquivos TIFF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter PPT para TIFF em PHP" h2="Poderosa biblioteca PHP do PowerPoint para converter PPT para TIFF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Converter PPT para TIFF em PHP" %}}

Precisa converter arquivos PPT para TIFF programaticamente? Usando [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/pt/php-java/) qualquer desenvolvedor pode converter o formato PPT para TIFF com apenas algumas linhas de código PHP .

Como uma API de processamento de apresentação moderna, o Aspose.Slides for PHP cria TIFF a partir de PPT rapidamente. Teste a qualidade da conversão de PPT para TIFF diretamente no seu [navegador](https://products.aspose.app/slides/conversion). A biblioteca Aspose PowerPoint PPTX permite converter arquivos PPT para muitos formatos populares.

Você pode instalar a biblioteca do [Composer](https://packagist.org/packages/aspose/slides) usando o seguinte comando:

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Como converter PPT para TIFF em PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter um arquivo PPT para TIFF usando PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar arquivo PPT com uma instância da classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chame o método `save` enquanto especifica o caminho do arquivo de saída e SaveFormat.TIFF como parâmetros
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
O arquivo PPT será salvo no caminho especificado
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código-fonte de amostra de conversão PHP, certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

1. Instale o PHP 7, adicione o caminho do PHP para a variável `PATH` do sistema e defina `allow_url_include` para `On` no arquivo `php.ini`.
1. Instale o JRE 8. Defina a variável de ambiente `JAVA_HOME` como um caminho para o local do JRE instalado.
1. Instale o Apache Tomcat 8.0 (veja [mais](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de amostra mostra a conversão de PPT para TIFF PHP" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.tiff", SaveFormat::Tiff);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Salve PPT como TIFF em PHP" %}}
Use o aplicativo gratuito para ver uma demonstração do processo de conversão de PPT para TIFF. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPT to TIFF" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter PPT para muitos outros formatos de arquivo. Veja outras conversões compatíveis abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Imagem em formato bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-fodp/" name="PPT TO FODP" description="Apresentação XML Plana OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-gif/" name="PPT TO GIF" description="Formato de intercâmbio gráfico" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-html/" name="PPT TO HTML" description="Linguagem de marcação de hipertexto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-jpg/" name="PPT TO JPG" description="Imagem JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-odp/" name="PPT TO ODP" description="Formato de apresentação do OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-otp/" name="PPT TO OTP" description="Formato padrão do OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Formato de Documento Portátil" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-png/" name="PPT TO PNG" description="Gráficos Portáteis de Rede" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pot/" name="PPT TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-potm/" name="PPT TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-potx/" name="PPT TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pps/" name="PPT TO PPS" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Apresentação de slides habilitada para macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Formato de apresentação XML aberto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-svg/" name="PPT TO SVG" description="Gráficos vetoriais escalonáveis" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-swf/" name="PPT TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-xps/" name="PPT TO XPS" description="Especificações do papel XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPT para PNG em PHP
weight: 2190
url: /pt/php-java/conversion/ppt-to-png/ 
keywords: "Convert, PowerPoint, PPT, PNG, Presentation, PHP"
description: Código de exemplo para conversão PHP de PPT para PNG. Use a API PHP do PowerPoint para conversão em lote de arquivos PPT para arquivos PNG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PPT para PNG em PHP" h2="Poderosa biblioteca PHP do PowerPoint para converter PPT para PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PPT para PNG em PHP" %}}

Precisa converter arquivos PPT para PNG programaticamente? Usando [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/pt/php-java/) qualquer desenvolvedor pode converter o formato PPT para PNG com apenas algumas linhas de código PHP .

Como uma API de processamento de apresentação moderna, o Aspose.Slides for PHP cria PNG a partir de PPT rapidamente. Teste a qualidade da conversão de PPT para PNG diretamente no seu [navegador](https://products.aspose.app/slides/conversion/ppt-to-png). A biblioteca Aspose PowerPoint PPTX permite converter arquivos PPT para muitos formatos populares.

Você pode instalar a biblioteca do [Composer](https://packagist.org/packages/aspose/slides) usando o seguinte comando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salve PPT como PNG em PHP" %}}

Use o aplicativo gratuito para ver uma demonstração do processo de conversão de PPT para PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de amostra mostra a conversão de PPT para PNG PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
    }
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter PPT para PNG em PHP" intro="Estas são as etapas para converter um arquivo PPT para PNG usando PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregar arquivo PPT com uma instância da classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método `save` enquanto especifica o caminho do arquivo de saída e SaveFormat.PNG como parâmetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}O arquivo PPT será salvo no caminho especificado{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Requisitos de sistema" intro="Antes de executar o código-fonte de amostra de conversão PHP, certifique-se de ter os seguintes pré-requisitos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o PHP 7, adicione o caminho do PHP para a variável `PATH` do sistema e defina `allow_url_include` para `On` no arquivo `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o JRE 8. Defina a variável de ambiente `JAVA_HOME` como um caminho para o local do JRE instalado.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o Apache Tomcat 8.0 (veja [mais](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPT to PNG"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras conversões compatíveis" subTitle="Você também pode converter PPT para muitos outros formatos de arquivo. Veja outras conversões compatíveis abaixo" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Imagem em formato bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-fodp/" name="PPT TO FODP" description="Apresentação XML Plana OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-gif/" name="PPT TO GIF" description="Formato de intercâmbio gráfico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-html/" name="PPT TO HTML" description="Linguagem de marcação de hipertexto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-jpg/" name="PPT TO JPG" description="Imagem JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-odp/" name="PPT TO ODP" description="Formato de apresentação do OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-otp/" name="PPT TO OTP" description="Formato padrão do OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Formato de Documento Portátil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pot/" name="PPT TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-potm/" name="PPT TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-potx/" name="PPT TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pps/" name="PPT TO PPS" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Apresentação de slides habilitada para macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Formato de apresentação XML aberto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-svg/" name="PPT TO SVG" description="Gráficos vetoriais escalonáveis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-swf/" name="PPT TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Formato de imagem marcada" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/ppt-to-xps/" name="PPT TO XPS" description="Especificações do papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter OTP para PPSX em PHP
weight: 560
url: /pt/php-java/conversion/otp-to-ppsx/ 
keywords: "Convert, PowerPoint, OTP, PPSX, Presentation, PHP"
description: Código de exemplo para conversão PHP de OTP para PPSX. Use a API PHP do PowerPoint para conversão em lote de arquivos OTP para arquivos PPSX.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter OTP para PPSX em PHP" h2="Poderosa biblioteca PHP do PowerPoint para converter OTP para PPSX"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter OTP para PPSX em PHP" %}}

Precisa converter arquivos OTP para PPSX programaticamente? Usando [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/pt/php-java/) qualquer desenvolvedor pode converter o formato OTP para PPSX com apenas algumas linhas de código PHP .

Como uma API de processamento de apresentação moderna, o Aspose.Slides for PHP cria PPSX a partir de OTP rapidamente. Teste a qualidade da conversão de OTP para PPSX diretamente no seu [navegador](https://products.aspose.app/slides/conversion). A biblioteca Aspose PowerPoint PPTX permite converter arquivos OTP para muitos formatos populares.

Você pode instalar a biblioteca do [Composer](https://packagist.org/packages/aspose/slides) usando o seguinte comando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salve OTP como PPSX em PHP" %}}

Use o aplicativo gratuito para ver uma demonstração do processo de conversão de OTP para PPSX.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de amostra mostra a conversão de OTP para PPSX PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.otp");
try
{
    $pres->save("output.ppsx", SaveFormat::Ppsx);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter OTP para PPSX em PHP" intro="Estas são as etapas para converter um arquivo OTP para PPSX usando PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregar arquivo OTP com uma instância da classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método `save` enquanto especifica o caminho do arquivo de saída e SaveFormat.PPSX como parâmetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}O arquivo OTP será salvo no caminho especificado{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Requisitos de sistema" intro="Antes de executar o código-fonte de amostra de conversão PHP, certifique-se de ter os seguintes pré-requisitos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o PHP 7, adicione o caminho do PHP para a variável `PATH` do sistema e defina `allow_url_include` para `On` no arquivo `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o JRE 8. Defina a variável de ambiente `JAVA_HOME` como um caminho para o local do JRE instalado.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o Apache Tomcat 8.0 (veja [mais](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert OTP to PPSX"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras conversões compatíveis" subTitle="Você também pode converter OTP para muitos outros formatos de arquivo. Veja outras conversões compatíveis abaixo" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-bmp/" name="OTP TO BMP" description="Imagem em formato bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-fodp/" name="OTP TO FODP" description="Apresentação XML Plana OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-gif/" name="OTP TO GIF" description="Formato de intercâmbio gráfico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-html/" name="OTP TO HTML" description="Linguagem de marcação de hipertexto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-jpg/" name="OTP TO JPG" description="Imagem JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-odp/" name="OTP TO ODP" description="Formato de apresentação do OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-pdf/" name="OTP TO PDF" description="Formato de Documento Portátil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-png/" name="OTP TO PNG" description="Gráficos Portáteis de Rede" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-pot/" name="OTP TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-potm/" name="OTP TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-potx/" name="OTP TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-pps/" name="OTP TO PPS" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Apresentação de slides habilitada para macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Formato de apresentação XML aberto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-svg/" name="OTP TO SVG" description="Gráficos vetoriais escalonáveis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-swf/" name="OTP TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Formato de imagem marcada" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/otp-to-xps/" name="OTP TO XPS" description="Especificações do papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

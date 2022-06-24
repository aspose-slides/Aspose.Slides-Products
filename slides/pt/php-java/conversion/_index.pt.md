---
title: Conversão de apresentação do Microsoft PowerPoint para PDF em PHP
url: /pt/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: API PHP para converter PPT para PDF. Converta apresentações para JPG, PNG e outros formatos em PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Apresentação do Microsoft<sup>®</sup> PowerPoint para conversão de PDF em PHP" h2="Códigos fonte PHP para diferentes casos de conversão para converter PPT para PDF, PNG, HTML, JPEG, PPTX e outros formatos." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/pt/php-java/) é uma poderosa biblioteca de classes local usada para processar e trabalhar com apresentações. É fácil para os desenvolvedores converter PowerPoint para PDF com velocidade e precisão. Obtenha os resultados em pouco tempo para automatizar os processos de negócios. Estamos discutindo aqui alguns casos para ler ou carregar qualquer entrada [formatos PowerPoint suportados](https://docs.aspose.com/slides/php-java/supported-file-formats/) e gravar ou salvar em qualquer formato de saída suportado . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversão de PowerPoint para PDF em PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/pt/php-java/) permite converter arquivos nos formatos PowerPoint PPT, PPTX e OpenOffice ODP para PDF. Para converter uma apresentação para PDF, basta passar o nome do arquivo e salvar o formato no método `Presentation.save`. A classe `Presentation` expõe o método `save` que pode ser chamado para converter toda a apresentação PPT, PPTX ou ODP em um documento PDF.

{{% blocks/products/pf/feature-page-code h3="Conversão de PowerPoint para PDF em PHP" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.pdf", SaveFormat::Pdf); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf potm-to-pdf potx-to-pdf ppsm-to-pdf odp-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="Conversão de PDF para PPT em PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/pt/php-java/) permite importar apresentações de PDFs. Essencialmente, você converte um PDF em uma apresentação do PowerPoint. Para converter PDF para PowerPoint, siga estas etapas:
- Instanciar um objeto da classe `Presentation`.
- Chame o método `addFromPdf` e passe o arquivo PDF.
- Use o método `save` para salvar o arquivo no formato PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Conversão de PDF de PHP para Powerpoint" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    $pres->save("output.pptx", SaveFormat::Pptx); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-ppt pdf-to-pptx pdf-to-odp pdf-to-png pdf-to-jpg pdf-to-html" >}}


{{% blocks/products/pf/feature-page-section  h2="Converta PPT para PDF com opções personalizadas em PHP" %}}

Para converter slides do PowerPoint para PDF com precisão, os programadores podem carregar o documento usando a classe `Presentation` e usar a classe `PdfOptions` para todas as opções específicas e personalizadas, como nível de compactação de texto, qualidade Jpeg, comportamento de meta-arquivos, conversão de slides ocultos e seleção slides específicos e muito mais. Mesmo existe a opção de proteger o arquivo PDF convertido com senha.
{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint para conversão de PDF com configurações personalizadas" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\PdfOptions;
use aspose\slides\PdfTextCompression;
use aspose\slides\PdfCompliance;
 
$pres = new Presentation("input.pptx");
try
{
    $pdfOptions = new PdfOptions();
    $pdfOptions->setJpegQuality(90);
    $pdfOptions->setSaveMetafilesAsPng(true);
    $pdfOptions->setTextCompression(PdfTextCompression::Flate);
    $pdfOptions->setCompliance(PdfCompliance::Pdf15);
    $pres->save("output.pdf", SaveFormat::Pdf, $pdfOptions);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversão do Microsoft PowerPoint para HTML em PHP" %}}
Sempre que houver necessidade de incorporar apresentações em páginas da Web, será necessário converter slides em HTML. 
{{% blocks/products/pf/feature-page-code h3="Código PHP para conversão de PowerPoint para HTML" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\Html5Options;
 
$pres = new Presentation("input.pptx");
try
{
    $html5Options = new Html5Options();
    $html5Options->setAnimateShapes(false);
    $html5Options->setAnimateTransitions(false);
    $pres->save("output.html", SaveFormat::Html5, $html5Options);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Converter PowerPoint para JPG" %}}
A conversão de formatos do Microsoft<sup>®</sup> PowerPoint para imagens JPEG, PNG, TIFF etc é outro caso de uso comum usado principalmente para criar miniaturas de slides. 
{{% blocks/products/pf/feature-page-code h3="Código de conversão PHP PPT para JPG" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
 
$pres = new Presentation("input.pptx");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(1, 1);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPEG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>  
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-jpg pptx-to-jpg ppt-to-png pptx-to-png ppt-to-gif pptx-to-gif" >}}
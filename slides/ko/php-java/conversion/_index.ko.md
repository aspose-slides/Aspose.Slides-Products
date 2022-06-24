---
title: Microsoft PowerPoint 프레젠테이션을 PHP에서 PDF로 변환
url: /ko/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PPT를 PDF로 변환하는 PHP API. PHP에서 프레젠테이션을 JPG, PNG 및 기타 형식으로 변환합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint 프레젠테이션에서 PHP로 PDF 변환" h2="PPT를 PDF, PNG, HTML, JPEG, PPTX 및 기타 형식으로 변환하는 다양한 변환 사례에 대한 PHP 소스 코드." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ko/php-java/)는 프레젠테이션을 처리하고 작업하는 데 사용되는 강력한 사내 클래스 라이브러리입니다. 개발자가 빠르고 정확하게 PowerPoint를 PDF로 변환하는 것은 쉽습니다. 비즈니스 프로세스를 자동화하기 위해 짧은 시간 안에 결과를 얻으십시오. 여기서는 입력[지원되는 PowerPoint 형식](https://docs.aspose.com/slides/php-java/supported-file-formats/)을 읽거나 로드하고 지원되는 출력 형식으로 쓰거나 저장하는 몇 가지 경우에 대해 논의하고 있습니다. . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PHP에서 PowerPoint에서 PDF로 변환" %}}
[Aspose.Slides](https://products.aspose.com/slides/ko/php-java/)를 사용하면 PowerPoint PPT, PPTX 및 OpenOffice ODP 형식의 파일을 PDF로 변환할 수 있습니다. 프레젠테이션을 PDF로 변환하려면 파일 이름과 저장 형식을 `Presentation.save` 메서드에 전달하기만 하면 됩니다. `Presentation` 클래스는 전체 PPT, PPTX 또는 ODP 프레젠테이션을 PDF 문서로 변환하기 위해 호출할 수 있는 `save` 메소드를 노출합니다.

{{% blocks/products/pf/feature-page-code h3="PHP 파워포인트를 PDF로 변환" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PHP에서 PDF를 PPT로 변환" %}}
[Aspose.Slides](https://products.aspose.com/slides/ko/php-java/)를 사용하면 PDF에서 프레젠테이션을 가져올 수 있습니다. 기본적으로 PDF를 PowerPoint 프레젠테이션으로 변환할 수 있습니다. PDF를 PowerPoint로 변환하려면 다음 단계를 수행하십시오.
- `Presentation` 클래스의 객체를 인스턴스화합니다.
- `addFromPdf` 메소드를 호출하고 PDF 파일을 전달합니다.
- '저장' 방법을 사용하여 파일을 PowerPoint 형식으로 저장합니다.

{{% blocks/products/pf/feature-page-code h3="PHP PDF를 파워포인트로 변환" %}}

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


{{% blocks/products/pf/feature-page-section  h2="PHP의 사용자 정의 옵션을 사용하여 PPT를 PDF로 변환" %}}

PowerPoint 슬라이드를 PDF로 정확하게 변환하기 위해 프로그래머는 `Presentation` 클래스를 사용하여 문서를 로드하고 텍스트 압축 수준, Jpeg 품질, 메타파일 동작, 숨겨진 슬라이드 변환 및 선택과 같은 모든 특정 및 사용자 정의 옵션에 대해 `PdfOptions` 클래스를 사용할 수 있습니다. 특정 슬라이드 등. 변환된 PDF 파일을 암호로 보호하는 옵션도 있습니다.
{{% blocks/products/pf/feature-page-code h3="사용자 정의 설정을 사용하여 PHP PowerPoint에서 PDF로 변환" %}}

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


{{% blocks/products/pf/feature-page-section  h2="PHP에서 Microsoft PowerPoint에서 HTML로 변환" %}}
웹 페이지 내에 프레젠테이션을 포함해야 하는 경우 슬라이드를 HTML로 변환해야 합니다. 
{{% blocks/products/pf/feature-page-code h3="PowerPoint에서 HTML로의 변환을 위한 PHP 코드" %}}

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

{{% blocks/products/pf/feature-page-section  h2="파워포인트를 JPG로 변환" %}}
Microsoft<sup>®</sup> PowerPoint 형식을 JPEG, PNG, TIFF 등의 이미지로 변환하는 것은 슬라이드 축소판을 만드는 데 주로 사용되는 또 다른 일반적인 사용 사례입니다. 
{{% blocks/products/pf/feature-page-code h3="JPG 변환기 코드에 PHP PPT" %}}
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
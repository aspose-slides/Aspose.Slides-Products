---
title: PHP에서 PDF을 Image로 변환
url: /ko/php-java/conversion/pdf-to-image/
keywords: PDF에서 Image으로, PDF에서 Image으로 변환, PHP API, PHP 라이브러리, PDF, Image
description: PHP에서 PDF을 Image로 변환합니다. PowerPoint PHP API를 사용하여 PDF 파일을 Image 파일로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP에서 PDF을 Image로 변환" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고 Microsoft PowerPoint 및 OpenOffice 프레젠테이션 파일을 생성, 병합, 검사 또는 변환할 수 있는 기능을 통해 응용 프로그램을 개발하는 데 도움이 되는 강력한 PowerPoint PHP 라이브러리입니다." >}}

{{% blocks/products/pf/feature-page-section h2="PHP에서 PDF을 Image로 변환" %}}

[**Java를 통한 PHP용 Aspose.Slides**](https://products.aspose.com/slides/ko/php-java/)는 프레젠테이션 파일을 만들고 조작하기 위한 강력한 PHP 라이브러리입니다. 또한 PDF을 Image으로 변환하는 유연한 방법을 제공합니다. **Java를 통한 PHP용 Aspose.Slides**를 사용하면 모든 개발자 또는 애플리케이션이 단 몇 줄의 PHP 코드로 PDF을 Image 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for PHP는 PDF 파일을 Image 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 PDF을 Image 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP를 사용하여 PDF을 Image로 변환" %}}
PDF을 Image로 변환하려면 PDF 파일에서 프레젠테이션을 생성하고 Image로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="PDF을 Image로 변환하기 위한 PHP 코드" offSpacer="true" %}}

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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API를 사용하여 PDF을 Image로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 PHP에서 PDF을 Image으로 변환하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ko/php-java/)를 설치합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP 프로젝트에 라이브러리 참조(라이브러리 가져오기)를 추가합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP에서 소스 PDF 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 Image 파일로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="무료 온라인 변환기" sectionDescription="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="PDF을 지원되는 다른 형식으로 변환" subTitle="PDF을 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식 보기" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pdf-to-xml/" name="PDF TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
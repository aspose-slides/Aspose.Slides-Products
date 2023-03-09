---
title: PHP에서 PDF 파일 병합
url: /ko/php-java/merger/pdf-to-pdf/
keywords: PDF 병합, PDF를 PDF로, PDF 결합, PDF 결합, PHP API, PHP 라이브러리
description: PHP에서 PDF를 PDF로 병합합니다. PHP 라이브러리 API를 사용하여 PDF 파일 결합
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP에서 PDF 병합" h2="PHP 코드를 사용하여 PDF 파일을 병합하기 위한 고속 및 교차 플랫폼 PHP 라이브러리" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides를 사용하여 PDF를 PDF로 병합" %}}

[**Java를 통한 PHP용 Aspose.Slides**](https://products.aspose.com/slides/ko/php-java/)는 프레젠테이션, PDF, 및 기타 문서. PDF를 PDF로 병합하면 2개 문서의 페이지를 효과적으로 결합하여 하나의 PDF 파일을 얻는 것입니다. Aspose.Slides를 사용하면 다양한 방식으로 PDF를 병합할 수 있습니다. PDF를 모든 모양, 스타일, 텍스트, 서식 등으로 병합할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PHP에서 PDF를 PDF로 병합" %}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ko/php-java/)를 사용하면 단 몇 줄의 코드만으로 PDF 파일을 빠르게 병합할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="PDF를 PDF로 병합하기 위한 PHP 코드" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $pres->getSlides()->addFromPdf("document1.pdf");
    $pres->getSlides()->addFromPdf("document2.pdf");

    $pres->save("merged-pdf.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PHP에서 PDF를 병합하는 방법" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Java를 통해 **Aspose.Slides for PHP**를 설치합니다. [**설치**](https://docs.aspose.com/slides/php-java/installation/)를 참조하세요.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프로젝트에서 라이브러리를 참조로 추가하십시오.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
병합하려는 PDF 파일을 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과 PDF를 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="다른 파일 병합" subTitle="다른 형식의 파일을 결합하여 단일 파일을 얻을 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
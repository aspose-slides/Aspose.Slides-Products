---
title: PHP에서 PPS 편집
url: /ko/php-java/editor/pps/
keywords: PPS 편집, PowerPoint 편집, PPS, PowerPoint, PHP API, PHP 라이브러리
description: PHP에서 PPS을 편집합니다. PHP 라이브러리 API를 사용하여 PPS 파일 편집
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP에서 PPS 편집" h2="PHP 코드를 사용하여 PPS 편집을 위한 고속 및 교차 플랫폼 PHP 라이브러리" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides를 사용하여 PPS 편집" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ko/php-java/)는 프레젠테이션을 빠르고 쉽게 편집할 수 있는 강력한 PHP 라이브러리입니다. 전문가 수준의 슬라이드를 즉시 만들 수 있도록 광범위한 기능을 사용자에게 제공합니다. Aspose를 사용하여 사용자는 텍스트를 편집하고 이미지, 애니메이션 및 전환을 프리젠테이션에 추가할 수 있을 뿐만 아니라 글꼴 유형 및 색상 선택과 같은 다양한 서식 옵션을 적용할 수 있습니다. 또한 라이브러리는 PowerPoint(PPT) 파일과 OpenOffice Presentation(ODP) 형식을 모두 지원하므로 호환성 문제 없이 다른 플랫폼에서 프레젠테이션을 이전보다 더 쉽게 공유할 수 있습니다. 다음 프레젠테이션을 만들거나 편집할 때 Aspose 라이브러리의 기능을 활용하면 매번 멋진 슬라이드를 만들 수 있습니다!
새 텍스트 줄을 추가하여 PPS 파일을 편집할 수 있습니다. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP에서 PPS 편집" %}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ko/php-java/)를 사용하면 몇 줄의 코드.

{{% blocks/products/pf/agp/code-block title="PPS 편집을 위한 PHP 코드" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pps");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.pps", SaveFormat::Pps);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="PHP에서 PPS을 편집하는 방법" >}}

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
편집하려는 PPS 프레젠테이션을 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
새 텍스트 줄을 추가합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
변경된 파일을 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="다른 파일 편집" subTitle="다른 형식의 파일도 편집할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
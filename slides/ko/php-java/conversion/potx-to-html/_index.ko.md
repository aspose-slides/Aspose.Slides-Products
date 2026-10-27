---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP에서 POTX을 HTML으로 변환
weight: 1300
url: /ko/php-java/conversion/potx-to-html/ 
keywords: "Convert, PowerPoint, POTX, HTML, Presentation, PHP"
description: POTX에서 HTML PHP로의 변환을 위한 샘플 코드입니다. POTX 파일을 HTML 파일로 일괄 변환하려면 PowerPoint PHP API를 사용하세요.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP에서 POTX을 HTML으로 변환" h2="POTX을 HTML으로 변환하기 위한 강력한 PowerPoint PHP 라이브러리"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP에서 POTX을 HTML으로 변환" %}}

프로그래밍 방식으로 POTX 파일을 HTML으로 변환해야 합니까? [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/ko/php-java/)를 사용하면 모든 개발자가 몇 줄의 PHP 코드로 POTX을 HTML 형식으로 변환할 수 있습니다. .

최신 프레젠테이션 처리 API인 Aspose.Slides for PHP는 POTX에서 HTML을 빠르게 생성합니다. [브라우저](https://products.aspose.app/slides/conversion)에서 바로 POTX에서 HTML으로의 변환 품질을 테스트하세요. Aspose PowerPoint PPTX 라이브러리를 사용하면 POTX 파일을 널리 사용되는 형식으로 변환할 수 있습니다.

다음 명령을 사용하여 [Composer](https://packagist.org/packages/aspose/slides)에서 라이브러리를 설치할 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="콘솔/터미널" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP에서 POTX을 HTML으로 저장" %}}

무료 앱을 사용하여 POTX에서 HTML으로의 변환 과정에 대한 데모를 확인하세요.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="이 샘플 코드는 POTX에서 HTML PHP로의 변환을 보여줍니다." >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potx");
try
{
    $pres->save("output.html", SaveFormat::Html5);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHP에서 POTX을 HTML으로 변환하는 방법" intro="다음은 PHP를 사용하여 POTX 파일을 HTML으로 변환하는 단계입니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스로 POTX 파일 로드{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}출력 파일 경로 및 SaveFormat.HTML을 매개변수로 지정하면서 `save` 메소드 호출{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POTX 파일이 지정된 경로에 저장됩니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="시스템 요구 사항" intro="PHP 변환 샘플 소스 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7을 설치하고 시스템 `PATH` 변수에 PHP 경로를 추가하고 `php.ini` 파일에서 `allow_url_include`를 `On`으로 설정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JRE를 설치합니다. 8. `JAVA_HOME` 환경 변수를 설치된 JRE 위치의 경로로 설정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apache Tomcat 8.0을 설치합니다([자세히](https://docs.aspose.com/slides/php-java/installation/) 참조).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides로 구축" title="POTX에서 HTML로 온라인 변환" description="무료 Aspose.Slides Conversion 앱은 위 코드와 동일한 API인 [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ko/php-java/)로 구축되었습니다. 앱을 열고 내 POTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Conversion 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" upload="파일을 끌어다 놓거나 업로드하세요" saveAs="다른 이름으로 저장" convert="변환" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 변환하는지 확인해 보세요.
- POTX 파일을 업로드하고 HTML로 저장하세요.
- 결과를 다운로드하거나 더 많은 파일을 변환하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 변환" subTitle="POTX을 다른 많은 파일 형식으로 변환할 수도 있습니다. 아래에서 지원되는 다른 변환을 참조하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-bmp/" name="POTX TO BMP" description="비트맵 이미지" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-fodp/" name="POTX TO FODP" description="OpenDocument 플랫 XML 프레젠테이션" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-gif/" name="POTX TO GIF" description="그래픽 교환 형식" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-jpg/" name="POTX TO JPG" description="JPEG 이미지" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-odp/" name="POTX TO ODP" description="OpenDocument 프레젠테이션 형식" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-otp/" name="POTX TO OTP" description="OpenDocument 표준 형식" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-pdf/" name="POTX TO PDF" description="휴대용 문서 형식" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-png/" name="POTX TO PNG" description="휴대용 네트워크 그래픽" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-pot/" name="POTX TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-potm/" name="POTX TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-pps/" name="POTX TO PPS" description="파워포인트 슬라이드 쇼" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="매크로 사용 슬라이드 쇼" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="파워포인트 슬라이드 쇼" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-ppt/" name="POTX TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-pptm/" name="POTX TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Open XML 프레젠테이션 형식" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-svg/" name="POTX TO SVG" description="확장 가능한 벡터 그래픽" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-swf/" name="POTX TO SWF" description="SWF 형식" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-tiff/" name="POTX TO TIFF" description="태그가 지정된 이미지 형식" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/conversion/potx-to-xps/" name="POTX TO XPS" description="XML 용지 사양" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

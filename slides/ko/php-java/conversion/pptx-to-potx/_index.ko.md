---
title: PHP에서 PPTX을 POTX으로 변환
weight: 2640
url: /ko/php-java/conversion/pptx-to-potx/ 
keywords: "Convert, PowerPoint, PPTX, POTX, Presentation, PHP"
description: PPTX에서 POTX PHP로의 변환을 위한 샘플 코드입니다. PPTX 파일을 POTX 파일로 일괄 변환하려면 PowerPoint PHP API를 사용하세요.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PHP에서 PPTX을 POTX으로 변환" h2="PPTX을 POTX으로 변환하기 위한 강력한 PowerPoint PHP 라이브러리" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PHP에서 PPTX을 POTX으로 변환" %}}

프로그래밍 방식으로 PPTX 파일을 POTX으로 변환해야 합니까? [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/ko/php-java/)를 사용하면 모든 개발자가 몇 줄의 PHP 코드로 PPTX을 POTX 형식으로 변환할 수 있습니다. .

최신 프레젠테이션 처리 API인 Aspose.Slides for PHP는 PPTX에서 POTX을 빠르게 생성합니다. [브라우저](https://products.aspose.app/slides/conversion)에서 바로 PPTX에서 POTX으로의 변환 품질을 테스트하세요. Aspose PowerPoint PPTX 라이브러리를 사용하면 PPTX 파일을 널리 사용되는 형식으로 변환할 수 있습니다.

다음 명령을 사용하여 [Composer](https://packagist.org/packages/aspose/slides)에서 라이브러리를 설치할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="콘솔/터미널" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="PHP에서 PPTX을 POTX으로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 PHP를 사용하여 PPTX 파일을 POTX으로 변환하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스로 PPTX 파일 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
출력 파일 경로 및 SaveFormat.POTX을 매개변수로 지정하면서 `save` 메소드 호출
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX 파일이 지정된 경로에 저장됩니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 PHP 변환 샘플 소스 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

1. PHP 7을 설치하고 시스템 `PATH` 변수에 PHP 경로를 추가하고 `php.ini` 파일에서 `allow_url_include`를 `On`으로 설정합니다.
1. JRE를 설치합니다. 8. `JAVA_HOME` 환경 변수를 설치된 JRE 위치의 경로로 설정합니다.
1. Apache Tomcat 8.0을 설치합니다([자세히](https://docs.aspose.com/slides/php-java/installation/) 참조). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 PPTX에서 POTX PHP로의 변환을 보여줍니다." offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
try
{
    $pres->save("output.potx", SaveFormat::Potx);
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
 
{{% blocks/products/pf/agp/content h2="PHP에서 PPTX을 POTX으로 저장" %}}
무료 앱을 사용하여 PPTX에서 POTX으로의 변환 과정에 대한 데모를 확인하세요. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPTX to POTX" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="PPTX을 다른 많은 파일 형식으로 변환할 수도 있습니다. 아래에서 지원되는 다른 변환을 참조하세요." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="비트맵 이미지" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="OpenDocument 플랫 XML 프레젠테이션" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="그래픽 교환 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-html/" name="PPTX TO HTML" description="하이퍼 텍스트 마크업 언어" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="JPEG 이미지" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument 프레젠테이션 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument 표준 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="휴대용 문서 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-png/" name="PPTX TO PNG" description="휴대용 네트워크 그래픽" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-pot/" name="PPTX TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="파워포인트 슬라이드 쇼" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="매크로 사용 슬라이드 쇼" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="파워포인트 슬라이드 쇼" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="확장 가능한 벡터 그래픽" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="태그가 지정된 이미지 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/php-java/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML 용지 사양" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP에서 SVG를 PNG로 병합
url: /ko/php-java/merger/svg-to-png/
keywords: SVG를 PNG로 병합, SVG를 PNG로, SVG를 PNG로 결합, SVG를 PNG로 결합, PHP API, PHP 라이브러리
description: PHP에서 SVG를 PNG로 병합합니다. PHP 라이브러리 API를 사용하여 SVG 및 PNG 파일 결합
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP에서 SVG를 PNG로 병합" h2="PHP 코드를 사용하여 SVG를 PNG 이미지로 병합하기 위한 고속 및 교차 플랫폼 PHP 라이브러리" related="JPG,PNG,HTML,IMAGE,PDF,BMP" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP에서 SVG를 PNG로 병합" variant="code" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ko/php-java/)를 사용하면 단 몇 줄의 코드만으로 SVG를 PNG 파일로 빠르게 병합할 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="SVG를 PNG로 병합하기 위한 PHP 코드" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $svgImage1 = new SvgImage('image1.svg');
    $image1 = $pres->getImages()->addImage($svgImage1);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 0, 0, 360, 540, $image1);
    
    $svgImage2 = new SvgImage('image2.svg');
    $image2 = $pres->getImages()->addImage($svgImage2);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 360, 0, 360, 540, $image2);
    

    $img = $pres->getSlides()->get_Item(0)->getThumbnail(2, 2);
    $imageio = new Java("javax.imageio.ImageIO");
    $javafile = new Java("java.io.File", "merged-image.png");
    $imageio->write($img, "PNG", $javafile);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides를 사용하여 SVG를 PNG로 병합" %}}

[**Java를 통한 PHP용 Aspose.Slides**](https://products.aspose.com/slides/ko/php-java/)는 프레젠테이션, 이미지 및 기타 파일을 병합하고 조작하는 데 사용되는 강력한 PHP 라이브러리입니다. SVG를 PNG로 병합하면 SVG 이미지를 효과적으로 결합하여 PNG 그림을 얻을 수 있습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHP에서 SVG를 PNG로 병합하는 방법" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Java를 통해 **Aspose.Slides for PHP**를 설치합니다. [**설치**](https://docs.aspose.com/slides/php-java/installation/)를 참조하세요.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}프로젝트에서 라이브러리를 참조로 추가하십시오.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스를 만듭니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}함께 병합하려는 SVG 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}결과 PNG 이미지를 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Aspose.Slides로 구축" title="SVG에서 PNG로 온라인 병합" description="무료 Aspose.Slides Merger 앱은 위 코드와 동일한 API인 [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ko/php-java/)로 구축되었습니다. 앱을 열고 내 SVG 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Merger 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 병합하는지 확인해 보세요.
- 여러 SVG 파일을 업로드하고 하나의 PNG 파일로 합치세요.
- 병합된 결과를 하나의 파일로 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="다른 파일 병합" subTitle="다른 형식의 파일을 결합하여 단일 파일을 얻을 수도 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

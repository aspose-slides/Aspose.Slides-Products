---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java를 통해 PPSX를 GIF로 변환
weight: 5090
url: /ko/java/conversion/ppsx-to-gif/ 
description: PPSX 형식을 GIF 파일로 변환하는 샘플 Java 변환 코드. 이 예제 코드를 사용하여 웹 또는 데스크톱 Java 기반 응용 프로그램 내에서 PowerPoint 및 OpenOffice 프레젠테이션을 GIF로 내보냅니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java를 통해 PPSX를 GIF로 변환" h2="온프레미스 Java 라이브러리를 사용하여 단일 또는 여러 페이지를 GIF로 변환하는 PPSX에서 GIF Java 변환."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java를 사용하여 PPSX를 GIF로 변환하는 방법" %}}

PPSX를 GIF로 렌더링하려면 다음을 사용합니다.
 [자바용 Aspose.Slides](https://products.aspose.com/slides/ko/java/)
 기능이 풍부하고 강력하며 사용하기 쉬운 Java 플랫폼용 변환 API인 API입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.
 [메이븐](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 다음 구성을 pom.xml에 추가하여 Maven 기반 프로젝트 내에 설치합니다.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="저장소" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="의존" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX에서 GIF로 Java 변환 소스 코드" >}}
```cs
// load PPSX with Aspose.Slides
Presentation presentation = new Presentation("template.ppsx");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type GIF for every slide
  File outputfile = new File(sld.getSlideNumber() + ".gif");
  
  // save the slide image to disk
  ImageIO.write(bi, "gif", outputfile);
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java를 통해 PPSX를 GIF로 변환하는 단계" intro="Java 개발자는 몇 줄의 코드로 PPSX 파일을 GIF로 쉽게 변환할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스가 있는 PPSX 파일 로드{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}프레젠테이션의 각 슬라이드를 반복합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 반복마다 전체 스케일 이미지를 Bitmap으로 생성{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}GIF 파일 확장자와 ImageFormat을 사용하여 Bitmap.save 메서드를 호출합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="Java 변환 샘플 코드를 실행하기 전에 다음 전제조건이 있는지 확인하십시오." %}}

- Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크탑 애플리케이션용 Java Runtime Environment와 호환되는 OS.
- Maven에서 직접 Java용 Aspose.Slides의 최신 버전을 가져옵니다.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides로 구축" title="PPSX에서 GIF로 온라인 변환" description="무료 Aspose.Slides Conversion 앱은 위 코드와 동일한 API인 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/)로 구축되었습니다. 앱을 열고 내 PPSX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Conversion 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" upload="파일을 끌어다 놓거나 업로드하세요" saveAs="다른 이름으로 저장" convert="변환" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 변환하는지 확인해 보세요.
- PPSX 파일을 업로드하고 GIF로 저장하세요.
- 결과를 다운로드하거나 더 많은 파일을 변환하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 PPSX를 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="비트맵 이미지" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="JPEG 이미지" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML 용지 사양" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

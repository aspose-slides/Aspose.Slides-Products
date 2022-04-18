---
title: Java를 통해 PPS를 GIF로 변환
weight: 1680
url: /ko/java/conversion/pps-to-gif/ 
description: PPS 형식을 GIF 파일로 변환하는 샘플 Java 변환 코드. 이 예제 코드를 사용하여 웹 또는 데스크톱 Java 기반 응용 프로그램 내에서 PowerPoint 및 OpenOffice 프레젠테이션을 GIF로 내보냅니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Java를 통해 PPS를 GIF로 변환" h2="사내 Java 라이브러리를 사용하여 단일 또는 여러 페이지를 GIF로 변환하는 PPS에서 GIF Java 변환." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Java를 사용하여 PPS를 GIF로 변환하는 방법" %}}

 PPS를 GIF로 렌더링하려면 다음을 사용합니다.
 [자바용 Aspose.Slides](https://products.aspose.com/slides/java)
 기능이 풍부하고 강력하며 사용하기 쉬운 Java 플랫폼용 변환 API인 API입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.
 [메이븐](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 다음 구성을 pom.xml에 추가하여 Maven 기반 프로젝트 내에 설치합니다.

{{% blocks/products/pf/agp/code-block title="저장소" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="의존" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 PPS를 GIF로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Java 개발자는 몇 줄의 코드로 PPS 파일을 GIF로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Presentation 클래스의 인스턴스로 PPS 파일 로드
1. 프레젠테이션의 각 슬라이드를 반복합니다.
1. 각 반복마다 전체 스케일 이미지를 Bitmap으로 생성
1. GIF 파일 확장자와 ImageFormat을 사용하여 Bitmap.save 메서드를 호출합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java 변환 샘플 코드를 실행하기 전에 다음 전제조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크탑 애플리케이션용 Java Runtime Environment와 호환되는 OS.
- Maven에서 직접 Java용 Aspose.Slides의 최신 버전을 가져옵니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPS에서 GIF로 Java 변환 소스 코드" offSpacer="" %}}

```cs
// load PPS with Aspose.Slides
Presentation presentation = new Presentation("template.pps");
   
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

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PPS to GIF Conversion Live Demos" sectionDescription="[Convert PPS to GIF](https://products.aspose.app/slides/conversion/pps-to-gif) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPS file, it will be converted instantly to GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="자바 프리젠테이션 조작 라이브러리" %}}

 슬라이드 및 프레젠테이션 API를 사용하여 Microsoft PowerPoint 문서를 읽고, 쓰고, 조작하고, PDF, XPS, HTML, TIFF, ODP 및 기타 다양한 형식으로 변환할 수 있습니다. 처음부터 새 파일을 만들고 지원되는 관련 형식으로 저장할 수 있습니다. Aspose.Slides는 프레젠테이션, 슬라이드 및 요소를 생성, 구문 분석 또는 조작하기 위한 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어에 의존하지 않습니다.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" >}}

PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. The more latest version of this file format is PPSX which is based on Office OpenXML standards. PPS files can still be read by latest versions of Microsoft PowerPoint, but newly created files can only be saved in PPSX file format. When a PPS file is shared with another user and opened, it starts as Powerpoint show unlike PPT file which opens in editable mode.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

A GIF or Graphical Interchange Format is a type of highly compressed image. Owned by Unisys, GIF uses the LZW compression algorithm that does not degrade the image quality. For each image GIF typically allow up to 8 bits per pixel and up to 256 colours are allowed across the image. In contrast to a JPEG image, which can display up to 16 million colours and fairly touches the limits of the human eye. Back when the internet emerged, GIFs remained the best choice because they required low bandwidth and compatible for the graphics that consume solid areas of colour. An animated GIF combines numerous images or frames into a single file and displays them in a sequence to generate an animated clip or a short video. The colour limitations are up to 256 for each frame and are likely to be the least suitable for reproducing other images and photographs with colour gradient.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 PPS를 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-bmp/" name="PPS TO BMP" description="비트맵 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-html/" name="PPS TO HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="JPEG 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-odp/" name="PPS TO ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-pdf/" name="PPS TO PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-png/" name="PPS TO PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-pot/" name="PPS TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-potm/" name="PPS TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-potx/" name="PPS TO POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-ppt/" name="PPS TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-svg/" name="PPS TO SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-swf/" name="PPS TO SWF" description="SWF 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/pps-to-xps/" name="PPS TO XPS" description="XML 용지 사양" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
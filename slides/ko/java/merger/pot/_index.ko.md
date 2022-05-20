---
title: Java를 통해 POT 파일 병합
weight: 1100
url: /ko/java/merger/pot/ 
description: JSP/JSF 응용 프로그램 및 데스크탑 응용 프로그램용 Java Runtime Environment에서 POT 문서를 결합하는 Java 샘플 코드입니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Java에서 POT 형식 병합" h2="서버 측 Java API를 사용하는 기본 POT 문서 병합." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Java를 사용하여 POT 파일을 병합하는 방법" %}}

 POT 파일을 병합하려면 다음을 사용합니다.
 [자바용 Aspose.Slides](https://products.aspose.com/slides/ko/java)
 기능이 풍부하고 강력하며 사용하기 쉬운 Java 플랫폼용 병합 API인 API입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.
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


{{< blocks/products/pf/agp/feature-section-col title="Java에서 POT 파일을 병합하는 단계" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="[Aspose.Slides for Java](https://products.aspose.com/slides/ko/java) API로 기본 문서 병합 및 연결을 몇 줄의 코드로 수행할 수 있습니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스가 있는 첫 번째 POT 파일을 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스로 두 번째 POT 문서를 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
두 번째 POT 파일의 각 슬라이드를 반복합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
각 반복에서 addClone()을 사용하여 첫 번째 파일이 있는 슬라이드를 추가합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
save() 메서드를 사용하여 지정된 경로에 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java용 Aspose.Slides는 모든 주요 플랫폼 및 운영 체제에서 지원합니다. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크탑 애플리케이션용 Java Runtime Environment와 호환되는 OS.
- 최신 버전의 Aspose.Slides for Java를 다음에서 직접 가져옵니다.
 [메이븐](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides) .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="POT 파일 병합 - 자바" offSpacer="" %}}

```cs
// Load first POT File
Presentation prest1 = new Presentation("prest1.pot");

// Load second POT File
Presentation prest2 = new Presentation("prest2.pot");

// Merge
for (ISlide slide : prest2.getSlides()) {
	// Merge from source to target
	prest1.getSlides().addClone(slide);
}

// Save the File
prest1.save("merged-presentation.pot", SaveFormat.Pot);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Java API용 Aspose.Slides 정보" %}}

 Aspose.Slides API는 Microsoft PowerPoint 문서를 읽고, 쓰고, 조작하고, PDF, XPS, HTML, TIFF, ODP 및 기타 다양한 형식으로 변환하는 데 사용할 수 있습니다. 처음부터 새 파일을 만들고 지원되는 관련 형식으로 저장할 수 있습니다. Aspose.Slides는 프레젠테이션, 슬라이드 및 요소를 생성, 구문 분석 또는 조작하기 위한 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어에 의존하지 않습니다.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online POT Merger Live Demos" sectionDescription="Merge POT documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/merger). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your POT files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be merged and concatenated instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" >}}
Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Files created with these versions of Microsoft PowerPoint are in binary format as compared to those created in Office OpenXML file formats using the higher versions of PowerPoint. The files, hence, generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 병합 형식" subTitle="Java를 사용하여 One은 ..를 포함한 다른 많은 파일 형식을 병합할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/odp/" name="ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/otp/" name="OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/potm/" name="POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/potx/" name="POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/pps/" name="PPS" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/ppsm/" name="PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/ppsx/" name="PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/ppt/" name="PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/pptm/" name="PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/merger/pptx/" name="PPTX" description="Open XML 프레젠테이션 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
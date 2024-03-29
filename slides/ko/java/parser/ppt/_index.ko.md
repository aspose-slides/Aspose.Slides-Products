---
title: Java를 통해 PPT 문서에서 텍스트 및 이미지 추출
weight: 7140
url: /ko/java/parser/ppt/ 
description: JSP/JSF 응용 프로그램 및 데스크탑 응용 프로그램용 Java Runtime Environment의 PPT 파일에서 텍스트와 이미지를 추출하는 Java 샘플 코드입니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Java에서 PPT 형식 구문 분석" h2="Microsoft 또는 Adobe PDF와 같은 소프트웨어를 사용하지 않고 Java API용 서버측 Aspose.Slides를 사용하여 기본 및 고성능 PPT 문서 구문 분석." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="https://www.nuget.org/packages/aspose.slides.java" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Java를 사용하여 PPT 파일을 구문 분석하는 방법" %}}

 PPT 파일을 구문 분석하기 위해
 [자바용 Aspose.Slides](https://products.aspose.com/slides/ko/java/)
 기능이 풍부하고 강력하며 사용하기 쉬운 Java 플랫폼용 구문 분석 API인 API입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.
 [메이븐](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 다음 구성을 pom.xml에 추가하여 Maven 기반 프로젝트 내에 설치합니다.

{{% blocks/products/pf/agp/code-block title="저장소" offSpacer="true" %}}

```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="의존" offSpacer="true" %}}

```xml

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


{{< blocks/products/pf/agp/feature-section-col title="Java에서 PPT 파일을 구문 분석하는 단계" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="[Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/) API를 사용한 기본 문서 파싱은 몇 줄의 코드로 완료할 수 있습니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스를 시작하여 PPT 파일을 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
첫 번째 슬라이드 텍스트 프레임을 가져옵니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
각 단락 부분을 반복합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
텍스트, 글꼴 등과 같은 필요한 출력을 가져옵니다.
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

{{% blocks/products/pf/agp/code-block title="PPT 파일 파싱 - 자바" offSpacer="" %}}

```cs
//Load PPT file
Presentation pptPresentation = new Presentation("demo.ppt");
try{
    //Get an Array of TextFrameEx objects from the first slide
    ITextFrame[] textFramesSlideOne = SlideUtil.getAllTextBoxes(pptPresentation.getSlides().get_Item(0));

    //Loop through the Array of TextFrames
    for (int i = 0; i < textFramesSlideOne.length; i++){
        //Loop through paragraphs in current TextFrame
        for (IParagraph para : textFramesSlideOne[0].getParagraphs()){
            //Loop through portions in the current Paragraph
            for (IPortion port : para.getPortions()){
                //Display text in the current portion
                System.out.print(port.getText());

                //Display font height of the text
                System.out.print(port.getPortionFormat().getFontHeight());

                //Display font name of the text
                System.out.print(port.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    if (pptPresentation != null) pptPresentation.dispose();
}
//Similarly extarcting text from the Whole Presentation
//Use getAllTextFrames(pptPresentation, true) method and Iterate through Array   

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Java API용 Aspose.Slides 정보" %}}

 Aspose.Slides API는 Microsoft PowerPoint 문서를 읽고, 쓰고, 조작하고, PDF, XPS, HTML, TIFF, ODP 및 기타 다양한 형식으로 변환하는 데 사용할 수 있습니다. 처음부터 새 파일을 만들고 지원되는 관련 형식으로 저장할 수 있습니다. Aspose.Slides는 프레젠테이션, 슬라이드 및 요소를 생성, 구문 분석 또는 조작하기 위한 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어에 의존하지 않습니다.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Parser Live Demos" sectionDescription="Extract text and images from PPT documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/parser). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPT files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be parsed instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 구문 분석 문서" subTitle="Java를 사용하면 다음을 포함한 다른 형식을 쉽게 구문 분석할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/parser/odp/" name="ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/parser/pptx/" name="PPTX" description="Open XML 프레젠테이션 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
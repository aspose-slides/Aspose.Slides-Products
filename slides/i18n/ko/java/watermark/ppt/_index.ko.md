---
title: Java를 통한 워터마크 PPT 문서
weight: 6020
url: /ko/java/watermark/ppt/ 
description: JSP/JSF 응용 프로그램 및 데스크탑 응용 프로그램용 Java Runtime Environment에서 PPT 파일에 워터마크를 추가하거나 제거하는 Java 샘플 코드입니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Java를 통해 PPT에 텍스트 워터마크 추가" h2="서버 측 API를 사용하여 PPT 파일에 워터마크를 표시하는 자체 Java 앱을 빌드합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Java를 사용하여 PPT 파일에 워터마크를 삽입하는 방법" %}}

 PPT 파일을 워터마크하기 위해, 우리는
 [자바용 Aspose.Slides](https://products.aspose.com/slides/java)
 기능이 풍부하고 강력하며 사용하기 쉬운 Java 플랫폼용 워터마킹 API인 API입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.
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


{{< blocks/products/pf/agp/feature-section-col title="Java를 통해 PPT에 워터마크를 추가하는 단계" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스를 사용하여 PPT 파일 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
모든 슬라이드 반복
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
addTextFrame을 사용하여 텍스트 추가
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
색상, fillType 등과 같은 모든 관련 옵션을 설정합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
문서 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java용 Aspose.Slides는 모든 주요 플랫폼 및 운영 체제에서 지원합니다. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPT에 워터마크 추가 - 자바" offSpacer="" %}}

```cs

Presentation pres = new Presentation("TestPres.ppt");

for(ISlide slide:pres.getSlides()){
    IAutoShape ashp = slide.getShapes()
                    .addAutoShape(ShapeType.Rectangle,50, 50, 500, 500);
    ashp.addTextFrame("Watermark Text");

    ashp.getTextFrame().getParagraphs().get_Item(0).getPortions()
                        .get_Item(0).getPortionFormat().getFillFormat()
                        .setFillType(FillType.Solid);
    ashp.getTextFrame().getParagraphs().get_Item(0).getPortions()
                        .get_Item(0).getPortionFormat().getFillFormat()
                        .getSolidFillColor().setColor(Color.GRAY);
    ashp.getTextFrame().getParagraphs().get_Item(0).getPortions()
                        .get_Item(0).getPortionFormat().setFontHeight(25);

    // Change the line color of the rectangle to White
    ashp.getShapeStyle().getLineColor().setColor(Color.WHITE);
    ashp.getShapeStyle().setLineStyleIndex(LineStyle.ThinThin);

    // Remove any fill formatting in the shape
    ashp.getFillFormat().setFillType(FillType.NoFill);

    ashp.setRotation(-45);

    ashp.getAutoShapeLock().setSelectLocked(true);
    ashp.getAutoShapeLock().setSizeLocked(true);
    ashp.getAutoShapeLock().setTextLocked(true);
    ashp.getAutoShapeLock().setPositionLocked(true);
    ashp.getAutoShapeLock().setGroupingLocked(true);
}
  
pres.save(path + "SavedWatermark.ppt", SaveFormat.Ppt);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Java API용 Aspose.Slides 정보" %}}

 Aspose.Slides API는 Microsoft PowerPoint 문서를 읽고, 쓰고, 조작하고, PDF, XPS, HTML, TIFF, ODP 및 기타 다양한 형식으로 변환하는 데 사용할 수 있습니다. 처음부터 새 파일을 만들고 지원되는 관련 형식으로 저장할 수 있습니다. Aspose.Slides는 프레젠테이션, 슬라이드 및 요소를 생성, 구문 분석 또는 조작하기 위한 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어에 의존하지 않습니다.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Watermark PPT via Online App" sectionDescription="Add watermark to PPT documents by visiting our [Live Demos website](https://products.aspose.app/slides/watermark). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPT file, set your watermark and hit \"Add\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 워터마킹 형식" subTitle="Java를 사용하면 다음을 포함한 다양한 형식을 쉽게 워터마크할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/watermark/pptx/" name="PPTX" description="Open XML 프레젠테이션 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
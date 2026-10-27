---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1000
title: Java로 PPTX 문서에서 텍스트 추출
url: /ko/java/parser/pptx/ 
description: Aspose.Slides for Java를 사용하여 Java에서 PPTX 파일의 텍스트를 추출하세요.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java에서 PPTX 파일 구문 분석" h2="Aspose.Slides for Java의 서버 측 API로 PPTX 문서에서 텍스트와 프레젠테이션 콘텐츠를 추출하세요."
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java로 PPTX 파일 구문 분석하기" %}}

[Aspose.Slides for Java](/slides/ko/java/)를 사용하여 PPTX 프레젠테이션을 구문 분석하고 슬라이드에서 텍스트를 추출하세요. Maven 기반 프로젝트에 라이브러리를 추가하려면 `pom.xml` 파일에 아래 리포지토리 및 종속성 구성을 사용하세요.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="리포지토리" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="종속성" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX 파일 구문 분석 - Java" >}}
```java
Presentation presentation = new Presentation("demo.pptx");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java에서 PPTX 파일을 구문 분석하는 방법" intro="Aspose.Slides for Java를 사용하면 몇 줄의 코드로 PPTX 프레젠테이션에서 텍스트를 추출할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 `PPTX` 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.getAllTextBoxes` 메서드를 호출하여 첫 번째 슬라이드의 텍스트 프레임을 가져옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 `ITextFrame`, `IParagraph`, `IPortion` 객체를 순회합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 `IPortion` 객체에서 텍스트, 글꼴 크기, 글꼴 이름을 읽습니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="Aspose.Slides for Java는 주요 플랫폼과 운영 체제를 지원합니다. 환경이 다음 필수 조건을 충족하는지 확인하세요." %}}

- JSP/JSF 애플리케이션 및 데스크톱 애플리케이션용 Java Runtime Environment가 있는 Microsoft Windows 또는 호환 운영 체제.
- [Maven](https://releases.aspose.com/java/repo/)에서 제공하는 최신 버전의 Aspose.Slides for Java.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides로 구축" title="온라인에서 텍스트와 이미지 추출" description="무료 Aspose.Slides Parser 앱은 위 코드와 동일한 API인 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/)로 구축되었습니다. 앱을 열고 내 PPTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Parser 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 읽는지 확인하세요.
- PPTX 파일을 업로드하고 텍스트와 이미지를 받으세요.
- 모든 결과를 하나의 ZIP 아카이브로 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

확장자가 PPTX인 파일은 Office Open XML 프레젠테이션 형식을 사용합니다. PPTX 파일은 텍스트, 이미지, 서식, 애니메이션 및 기타 프레젠테이션 콘텐츠를 포함할 수 있는 슬라이드를 저장합니다.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 구문 분석 형식" subTitle="Java로 다른 프레젠테이션 형식도 구문 분석할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/parser/odp/" name="ODP" description="OpenDocument 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/parser/ppt/" name="PPT" description="PowerPoint 97-2003 프레젠테이션" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

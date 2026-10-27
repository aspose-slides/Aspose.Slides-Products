---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java에서 PPT를 Word로 변환
url: /ko/java/conversion/ppt-to-word/
keywords: PPT를 Word로, PPT를 Word로, PPT를 DOC로, PowerPoint를 Word로, Java API, Java 라이브러리로 변환
description: Java에서 PPT를 Word로 변환합니다. Java 라이브러리 API를 사용하여 PowerPoint를 Word로 변환
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java에서 PPT를 Word로 변환" h2="Microsoft PowerPoint 또는 Office 없이 Java 코드를 사용하여 PowerPoint를 Word로 변환하기 위한 강력한 교차 플랫폼 Java API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java에서 PowerPoint를 Word로 변환" variant="code" %}}

몇 줄의 코드만으로 PPT를 Word로 빠르게 변환할 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PowerPoint를 Word로 변환하기 위한 Java 코드" >}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides 및 Aspose.Words를 사용하여 PowerPoint를 Word로 변환" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/) 및 [**Aspose.Words for Java**](https://products.aspose.com/ words/java/)는 PowerPoint 프레젠테이션, Word 문서 및 기타 파일을 조작하고 변환하는 데 사용되는 강력한 Java 라이브러리입니다. PowerPoint를 Word로 변환하면 기본적으로 프레젠테이션 슬라이드의 내용이 Word 문서의 페이지로 이동됩니다.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPT를 Word로 변환하는 방법" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for Java** 및 **Aspose.Words for Java** 설치{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스와 Doc 클래스의 인스턴스를 만듭니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Word로 변환하려는 PPT 프레젠테이션을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}슬라이드의 내용을 기반으로 이미지와 텍스트를 생성합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}결과 Word 문서를 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides로 구축" title="PPT에서 Word로 온라인 변환" description="무료 Aspose.Slides Conversion 앱은 위 코드와 동일한 API인 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/)로 구축되었습니다. 앱을 열고 내 PPT 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Conversion 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" upload="파일을 끌어다 놓거나 업로드하세요" saveAs="다른 이름으로 저장" convert="변환" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 변환하는지 확인해 보세요.
- PPT 파일을 업로드하고 Word로 저장하세요.
- 결과를 다운로드하거나 더 많은 파일을 변환하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 변환" subTitle="PowerPoint를 다른 형식의 파일로 변환할 수도 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

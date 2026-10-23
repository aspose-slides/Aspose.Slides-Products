---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 자바에서 HTML 편집
url: /ko/java/editor/html/
keywords: HTML, HTML, Java API, Java 라이브러리 편집
description: Java에서 HTML을 편집합니다. Java 라이브러리 API를 사용하여 HTML 파일 편집
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="자바에서 HTML 편집" h2="Java 코드를 사용하여 HTML을 편집하기 위한 고속 및 교차 플랫폼 Java 라이브러리" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="자바에서 HTML 편집" variant="code" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/)를 사용하면 몇 줄의 코드만으로 HTML 문서에 새로운 텍스트 줄을 추가할 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML 편집을 위한 Java 코드" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        pres.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("page.html", SaveFormat.Html5);
} catch(IOException e) {
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides를 사용하여 HTML 편집" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/)는 프레젠테이션, HTML 문서 및 기타 파일을 조작하고 편집하는 데 사용되는 강력한 Java 라이브러리입니다. 새 텍스트 줄을 추가하여 HTML 문서를 편집할 수 있습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java에서 HTML을 편집하는 방법" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for Java**를 설치합니다. [**설치**](https://docs.aspose.com/slides/java/installation/)를 참조하세요.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}프로젝트에서 라이브러리를 참조로 추가하십시오.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스를 만듭니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}편집할 HTML 문서를 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}새 텍스트 줄을 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}변경된 HTML 파일을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Aspose.Slides로 구축" title="온라인에서 PPTX 파일 편집" description="무료 Aspose.Slides Editor 앱은 위 코드와 동일한 API인 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/)로 구축되었습니다. 앱을 열고 내 PPTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Editor 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 처리하는지 확인하세요.
- PPTX 파일을 업로드하고 바로 편집하세요.
- 편집한 파일을 저장하고 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="다른 파일 편집" subTitle="다른 형식의 파일도 편집할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

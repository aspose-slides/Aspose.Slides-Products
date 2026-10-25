---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java로 PPTX 프레젠테이션 파일에 워터마크 추가
url: /ko/java/watermark/pptx/
description: Aspose.Slides for Java로 Java에서 PPTX 프레젠테이션에 텍스트 및 이미지 워터마크를 추가하세요.
keywords: PPTX에 워터마크 추가, PPTX에 텍스트 워터마크 추가, PPTX에 이미지 워터마크 추가
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java로 PPTX 프레젠테이션에 워터마크 추가하기" h2="서버 측 API로 프레젠테이션 파일에 텍스트 또는 이미지 워터마크를 삽입하는 Java 애플리케이션을 구축하세요." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java를 통해 PPTX 프레젠테이션에 워터마크 추가" variant="code" %}}

[Aspose.Slides for Java](/slides/ko/java/)를 사용하면 PPTX 프레젠테이션에 텍스트 및 이미지 워터마크를 추가할 수 있습니다. 슬라이드 마스터에 워터마크 도형을 추가하면 해당 마스터를 사용하는 슬라이드에 워터마크가 표시됩니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java로 PPTX에 텍스트 워터마크 추가" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java로 PPTX 프레젠테이션에 이미지 워터마크 추가" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java로 PPTX에 워터마크를 추가하는 방법" intro="다음 단계에 따라 PPTX 파일에 텍스트 또는 이미지 워터마크를 추가하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 `PPTX` 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getMasters` 메서드로 슬라이드 마스터를 선택합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`addAutoShape` 메서드를 호출하여 워터마크 도형을 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`addTextFrame` 메서드를 호출하여 워터마크 텍스트를 추가하거나 이미지 워터마크에는 `addImage`를 사용합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}워터마크가 적용된 프레젠테이션을 PPTX 형식으로 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides로 구축" title="온라인에서 PPTX 파일에 워터마크 추가" description="무료 Aspose.Slides Watermark 앱은 위 코드와 동일한 API인 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/)로 구축되었습니다. 앱을 열고 내 PPTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Watermark 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 워터마크를 어떻게 추가하는지 확인하세요.
- PPTX 파일에 텍스트 또는 이미지 워터마크를 추가하세요.
- 워터마크가 적용된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="워터마크를 지원하는 기타 형식" subTitle="Java로 다음 형식에도 워터마크를 추가할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

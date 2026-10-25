---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java로 POTM 파일 메타데이터 보기 또는 편집
url: /ko/java/metadata/potm/
description: Java에서 POTM 메타데이터를 보고 편집하세요. Aspose.Slides for Java로 프레젠테이션의 기본 제공 속성과 사용자 지정 속성을 업데이트할 수 있습니다.
keywords: POTM 메타데이터 편집, POTM 메타데이터 보기, POTM 속성 편집, POTM 속성 보기
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java로 POTM 속성 편집" h2="서버 측 API로 프레젠테이션 파일의 기본 제공 속성과 사용자 지정 속성을 수정하는 Java 앱을 구축하세요." related="FODP,ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java로 POTM 속성 수정" variant="code" %}}

[Aspose.Slides for Java](/slides/ko/java/)를 사용하면 개발자가 프레젠테이션의 기본 제공 속성과 사용자 지정 속성에 액세스하고 수정할 수 있습니다. `Presentation` 객체의 `getDocumentProperties` 메서드로 프레젠테이션 파일의 `IDocumentProperties` 객체에 액세스하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM 기본 제공 속성 수정 - Java" >}}
```java
Presentation presentation = new Presentation("Presentation.potm");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.potm", SaveFormat.Potm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM에 사용자 지정 속성 추가 - Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.potm", SaveFormat.Potm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java에서 POTM 메타데이터를 보거나 편집하는 방법" intro="다음 단계에 따라 POTM 메타데이터를 보거나 편집하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 `POTM` 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getDocumentProperties` 메서드를 호출하여 `IDocumentProperties` 객체를 가져옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Author`, `Title`, `Subject`, `Comments` 같은 기본 제공 속성을 읽거나 업데이트합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`set_Item`, `getCustomPropertyName`, `removeCustomProperty`로 사용자 지정 속성에 액세스하고 수정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides로 구축" title="온라인에서 POTM 메타데이터 보기 및 편집" description="무료 Aspose.Slides Metadata 앱은 위 코드와 동일한 API인 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/)로 구축되었습니다. 앱을 열고 내 POTM 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Metadata 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 속성을 어떻게 읽고 쓰는지 확인하세요.
- POTM 파일의 기본 제공 속성과 사용자 지정 속성을 보고 편집하세요.
- 업데이트된 파일을 저장하고 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 메타데이터 형식" subTitle="Java로 다음 형식의 메타데이터도 관리할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

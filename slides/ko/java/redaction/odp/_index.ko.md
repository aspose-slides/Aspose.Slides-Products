---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java로 ODP 프레젠테이션 파일 마스킹
url: /ko/java/redaction/odp/
description: Aspose.Slides for Java를 사용해 Java에서 ODP 프레젠테이션의 텍스트를 찾아 바꾸세요.
keywords: ODP 마스킹, ODP에서 텍스트 찾기 및 바꾸기, ODP 프레젠테이션 업데이트
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java로 ODP 마스킹" h2="서버 측 API를 사용해 프레젠테이션 파일의 텍스트를 찾아 바꾸는 Java 애플리케이션을 빌드하세요." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java를 통한 ODP 프레젠테이션 마스킹" variant="code" %}}

[Aspose.Slides for Java](/slides/ko/java/)를 사용하면 ODP 프레젠테이션의 텍스트를 찾아 바꿀 수 있습니다. `SlideUtil.findAndReplaceText` 메서드로 프레젠테이션을 검색하고 일치하는 텍스트를 새 값으로 바꾸세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java로 ODP 프레젠테이션 마스킹" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java로 ODP를 마스킹하는 방법" intro="ODP 프레젠테이션을 마스킹하려면 다음 단계를 따르세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 ODP 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.findAndReplaceText` 메서드를 호출해 텍스트를 찾아 바꿉니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}업데이트된 프레젠테이션을 `SaveFormat.Odp` 형식으로 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides로 구축" title="ODP 파일 온라인 마스킹" description="무료 Aspose.Slides Redaction 앱은 위 코드와 동일한 API인 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/)로 구축되었습니다. 앱을 열고 내 ODP 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Redaction 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 텍스트를 찾아 바꾸는 방식을 확인하세요.
- 정규식을 포함해 ODP 파일의 텍스트를 찾아 바꾸세요.
- 마스킹된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="마스킹을 지원하는 기타 형식" subTitle="Java로 다음 형식도 마스킹할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

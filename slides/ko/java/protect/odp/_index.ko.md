---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java로 ODP 프레젠테이션 파일 보호
url: /ko/java/protect/odp/
description: Java에서 ODP 프레젠테이션을 보호하세요. Aspose.Slides for Java를 사용해 프레젠테이션 파일을 암호화하고 쓰기 보호를 설정할 수 있습니다.
keywords: ODP 쓰기 보호, ODP 파일 암호화, ODP 프레젠테이션 잠금, ODP 보호
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java로 ODP 잠그기 또는 암호로 보호하기" h2="서버 측 API로 프레젠테이션 파일을 보호하는 Java 애플리케이션을 빌드하세요." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java로 ODP 프레젠테이션 보호" variant="code" %}}

[Aspose.Slides for Java](/slides/ko/java/)를 사용하면 암호를 설정해 ODP 프레젠테이션을 열거나 수정하지 못하도록 보호할 수 있습니다. `Presentation` 클래스의 `ProtectionManager` 개체를 사용해 `encrypt`, `setWriteProtection` 같은 메서드를 호출하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java로 ODP 프레젠테이션 암호화" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java로 ODP 프레젠테이션에 쓰기 보호 설정" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java로 ODP를 암호로 보호하는 방법" intro="다음 단계에 따라 ODP 프레젠테이션을 보호하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 ODP 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` 개체의 `encrypt` 메서드 또는 `setWriteProtection` 메서드를 호출합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Odp`로 보호된 파일을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides로 구축" title="온라인에서 ODP 파일을 암호로 보호" description="무료 Aspose.Slides Lock 앱은 위 코드와 동일한 API인 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/)로 구축되었습니다. 앱을 열고 내 ODP 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Lock 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 프레젠테이션을 보호하는 방식을 확인하세요.
- ODP 파일을 열거나 편집할 때 필요한 암호를 설정하세요.
- 보호된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="보호를 지원하는 기타 형식" subTitle="Java를 사용하면 다음 형식도 보호할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

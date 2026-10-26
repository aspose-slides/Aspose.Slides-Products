---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java로 ODP 프레젠테이션 파일 잠금 해제
url: /ko/java/unlock/odp/
description: Aspose.Slides for Java를 사용해 Java에서 ODP 프레젠테이션의 암호와 쓰기 보호를 해제하세요.
keywords: ODP 쓰기 보호 해제, ODP 암호 해독, ODP 프레젠테이션 잠금 해제, ODP 보호 해제
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java로 ODP 잠금 해제" h2="서버 측 API로 프레젠테이션 파일의 암호와 쓰기 보호를 해제하는 Java 애플리케이션을 빌드하세요." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java로 ODP 프레젠테이션 보호 해제" variant="code" %}}

[Aspose.Slides for Java](/slides/ko/java/)를 사용하면 ODP 프레젠테이션의 암호화 또는 쓰기 보호를 해제할 수 있습니다. 암호화된 프레젠테이션을 열려면 `LoadOptions.setPassword`를, 보호 설정을 해제하려면 `ProtectionManager`의 `removeEncryption` 및 `removeWriteProtection` 메서드를 사용하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java로 ODP의 암호 보호 해제" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java로 ODP 프레젠테이션 쓰기 보호 해제" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java로 ODP에서 암호를 제거하는 방법" intro="다음 단계에 따라 ODP 프레젠테이션의 보호를 해제하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 ODP 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}프레젠테이션이 암호화된 경우 `LoadOptions.setPassword`를 사용합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` 개체의 `removeEncryption` 또는 `removeWriteProtection`을 호출합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Odp`로 잠금 해제된 프레젠테이션을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides로 구축" title="온라인에서 ODP 파일 잠금 해제" description="무료 Aspose.Slides Unlock 앱은 위 코드와 동일한 API인 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/)로 구축되었습니다. 앱을 열고 내 ODP 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Unlock 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 보호를 해제하는 방식을 확인하세요.
- ODP 파일에서 암호 또는 쓰기 보호를 제거하세요.
- 잠금 해제된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="잠금 해제를 지원하는 기타 형식" subTitle="Java를 사용하면 다음 형식의 보호도 해제할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

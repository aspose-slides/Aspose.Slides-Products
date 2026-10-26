---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++로 PPTX 프레젠테이션 보호
url: /ko/cpp/protect/pptx/
description: C++에서 PPTX 프레젠테이션을 보호하세요. Aspose.Slides for C++를 사용해 파일을 암호화하고 쓰기 보호를 설정할 수 있습니다.
keywords: PPTX 쓰기 보호, PPTX 암호화, PPTX 프레젠테이션 잠금, PPTX 보호
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++로 PPTX 잠그기 또는 암호로 보호하기" h2="Aspose.Slides for C++를 사용하면 Microsoft PowerPoint 없이 프레젠테이션을 암호화하고 쓰기 보호를 설정할 수 있습니다." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++로 PPTX 프레젠테이션 보호" variant="code" %}}

Aspose.Slides for C++를 사용하면 PPTX 프레젠테이션을 열거나 수정하지 못하도록 보호할 수 있습니다. `Presentation` 클래스의 `ProtectionManager` 개체를 사용해 `Encrypt`로 파일을 암호화하거나 `SetWriteProtection`으로 편집을 제한하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++로 PPTX 프레젠테이션 암호화" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++로 PPTX 프레젠테이션에 쓰기 보호 설정" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++로 PPTX를 암호로 보호하는 방법" intro="다음 단계에 따라 PPTX 프레젠테이션을 보호하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 PPTX 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` 개체로 프레젠테이션을 보호합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}암호 보호에는 `Encrypt`를, 쓰기 보호에는 `SetWriteProtection`을 사용합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat::Pptx`로 보호된 파일을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides로 구축" title="온라인에서 PPTX 파일을 암호로 보호" description="무료 Aspose.Slides Lock 앱은 위 코드와 동일한 API인 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/)로 구축되었습니다. 앱을 열고 내 PPTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Lock 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 프레젠테이션을 보호하는 방식을 확인하세요.
- PPTX 파일을 열거나 편집할 때 필요한 암호를 설정하세요.
- 보호된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="보호를 지원하는 기타 형식" subTitle="C++를 사용하면 다음 형식도 보호할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++로 PPSX 메타데이터 보기 또는 편집
url: /ko/cpp/metadata/ppsx/
description: C++에서 PPSX 메타데이터를 보고 편집하세요. Aspose.Slides for C++로 프레젠테이션의 기본 제공 속성과 사용자 지정 속성을 업데이트할 수 있습니다.
keywords: PPSX 메타데이터 편집, PPSX 메타데이터 보기, PPSX 속성 편집, PPSX 속성 보기
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++로 PPSX 메타데이터 편집" h2="Aspose.Slides for C++로 프레젠테이션 파일의 기본 제공 속성과 사용자 지정 속성을 보고 업데이트하세요." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++로 PPSX 속성 수정" variant="code" %}}

Aspose.Slides for C++를 사용하면 Microsoft PowerPoint 없이 PPSX 파일의 메타데이터를 읽고 업데이트할 수 있습니다. `Presentation::get_DocumentProperties`가 제공하는 [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) 객체로 `Author`, `Title` 같은 기본 제공 속성을 변경하거나 `idx_set`, `GetCustomPropertyName`, `RemoveCustomProperty`로 사용자 지정 속성을 관리하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX 기본 제공 속성 수정 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppsx");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.ppsx", SaveFormat::Ppsx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX에 사용자 지정 속성 추가 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppsx");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.ppsx", SaveFormat::Ppsx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++에서 PPSX 메타데이터를 보거나 편집하는 방법" intro="다음 단계에 따라 PPSX 메타데이터를 보거나 편집하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 PPSX 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_DocumentProperties`로 `DocumentProperties` 객체를 가져옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Author`, `Title` 같은 기본 제공 속성을 읽거나 업데이트합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`idx_set`, `GetCustomPropertyName`, `RemoveCustomProperty`로 사용자 지정 속성을 추가, 읽기 또는 제거합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides로 구축" title="온라인에서 PPSX 메타데이터 보기 및 편집" description="무료 Aspose.Slides Metadata 앱은 위 코드와 동일한 API인 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/)로 구축되었습니다. 앱을 열고 내 PPSX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Metadata 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 속성을 어떻게 읽고 쓰는지 확인하세요.
- PPSX 파일의 기본 제공 속성과 사용자 지정 속성을 보고 편집하세요.
- 업데이트된 파일을 저장하고 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 메타데이터 형식" subTitle="C++로 다음 형식의 메타데이터도 관리할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

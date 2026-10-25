---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET으로 POTX 파일 메타데이터 보기 또는 편집
url: /ko/net/metadata/potx/
description: POTX 메타데이터를 보거나 편집하는 C# 소스 코드.
keywords: POTX 메타데이터 편집, POTX 메타데이터 보기, POTX 속성 편집, POTX 속성 보기
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#으로 POTX 속성 편집" h2="서버 측 API로 프레젠테이션의 기본 제공 속성과 사용자 지정 속성을 읽고 수정하는 .NET 앱을 구축하세요." related="FODP,ODP,OTP,POT,POTM,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#으로 POTX 속성 수정" variant="code" %}}

[Aspose.Slides for .NET](/slides/ko/net/)을 사용하면 개발자가 프레젠테이션의 기본 제공 속성과 사용자 지정 속성에 액세스하고 수정할 수 있습니다. `Presentation` 객체의 [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) 속성을 사용하여 POTX 메타데이터를 읽고 업데이트하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTX 기본 제공 속성 수정 - C#" >}}
```cs
using var presentation = new Presentation("presentation.potx");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.potx", SaveFormat.Potx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="POTX에 사용자 지정 속성 추가 - C#" >}}
```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.potx", SaveFormat.Potx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#에서 POTX 메타데이터를 보거나 편집하는 방법" intro="다음 단계에 따라 POTX 메타데이터를 보거나 편집하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation`으로 POTX 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}프레젠테이션에서 `DocumentProperties` 객체를 가져옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Author`, `Title`, `Subject` 같은 기본 제공 속성을 읽거나 업데이트합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`DocumentProperties`로 사용자 지정 속성에 액세스하고 수정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides로 구축" title="온라인에서 POTX 메타데이터 보기 및 편집" description="무료 Aspose.Slides Metadata 앱은 위 코드와 동일한 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net/)로 구축되었습니다. 앱을 열고 내 POTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Metadata 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 속성을 어떻게 읽고 쓰는지 확인하세요.
- POTX 파일의 기본 제공 속성과 사용자 지정 속성을 보고 편집하세요.
- 업데이트된 파일을 저장하고 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 메타데이터 형식" subTitle="C#으로 다음 형식의 메타데이터도 관리할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET으로 ODP 프레젠테이션 파일 보호
url: /ko/net/protect/odp/
description: ODP 프레젠테이션을 암호로 보호하는 C# 소스 코드입니다.
keywords: ODP 쓰기 보호, ODP 암호화, ODP 프레젠테이션 잠금, ODP 보호
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#으로 ODP 파일 잠그기 또는 암호로 보호하기" h2="서버 측 API로 프레젠테이션을 암호화하고 수정을 제한하는 .NET 앱을 빌드하세요." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#으로 ODP 프레젠테이션 보호" variant="code" %}}

[Aspose.Slides for .NET](/slides/ko/net/)을 사용하면 ODP 프레젠테이션을 암호화하거나 암호로 수정을 제한할 수 있습니다. `ProtectionManager.Encrypt`로 암호화한 프레젠테이션을 열려면 암호가 필요합니다. `ProtectionManager.SetWriteProtection`을 사용하면 프레젠테이션을 열 수는 있지만 변경은 제한됩니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#으로 ODP 프레젠테이션 암호화" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C#으로 ODP 프레젠테이션에 쓰기 보호 설정" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#으로 ODP 프레젠테이션을 암호로 보호하는 방법" intro="다음 단계에 따라 ODP 프레젠테이션을 암호로 보호하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation`으로 ODP 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager.Encrypt`로 프레젠테이션을 암호화하거나 `ProtectionManager.SetWriteProtection`으로 변경을 제한합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Odp`로 보호된 파일을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides로 구축" title="온라인에서 ODP 파일을 암호로 보호" description="무료 Aspose.Slides Lock 앱은 위 코드와 동일한 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net/)로 구축되었습니다. 앱을 열고 내 ODP 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Lock 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 프레젠테이션을 보호하는 방식을 확인하세요.
- ODP 파일을 열거나 편집할 때 필요한 암호를 설정하세요.
- 보호된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="보호를 지원하는 기타 형식" subTitle="C#을 사용하면 다음 형식도 보호할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET으로 PPTX 프레젠테이션 파일 잠금 해제
url: /ko/net/unlock/pptx/
description: PPTX 프레젠테이션에서 암호 보호를 해제하는 C# 소스 코드입니다.
keywords: PPTX 쓰기 보호 해제, PPTX 암호 해독, PPTX 프레젠테이션 잠금 해제, PPTX 보호 해제
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#으로 PPTX 파일 잠금 해제" h2="서버 측 API로 프레젠테이션의 암호화와 쓰기 보호를 해제하는 .NET 앱을 빌드하세요." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#으로 PPTX 프레젠테이션 보호 해제" variant="code" %}}

[Aspose.Slides for .NET](/slides/ko/net/)을 사용하면 PPTX 프레젠테이션의 암호화 또는 쓰기 보호를 해제할 수 있습니다. 암호화를 해제하려면 올바른 암호로 프레젠테이션을 로드한 후 `ProtectionManager.RemoveEncryption`을 호출하세요. 쓰기 보호를 해제하려면 `ProtectionManager.RemoveWriteProtection`을 호출하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#으로 PPTX 프레젠테이션 암호화 해제" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.pptx", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C#으로 PPTX 프레젠테이션 쓰기 보호 해제" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.pptx");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#으로 PPTX 프레젠테이션의 보호를 해제하는 방법" intro="다음 단계에 따라 PPTX 프레젠테이션의 보호를 해제하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation`으로 PPTX 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}암호화된 파일은 로드하기 전에 `LoadOptions.Password`로 암호를 지정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}적용된 보호에 따라 `ProtectionManager.RemoveEncryption` 또는 `ProtectionManager.RemoveWriteProtection`을 호출합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Pptx`로 잠금 해제된 프레젠테이션을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides로 구축" title="온라인에서 PPTX 파일 잠금 해제" description="무료 Aspose.Slides Unlock 앱은 위 코드와 동일한 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net/)로 구축되었습니다. 앱을 열고 내 PPTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Unlock 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 보호를 해제하는 방식을 확인하세요.
- PPTX 파일에서 암호 또는 쓰기 보호를 제거하세요.
- 잠금 해제된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="잠금 해제를 지원하는 기타 형식" subTitle="C#을 사용하면 다음 형식의 보호도 해제할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

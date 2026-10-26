---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python으로 ODP 프레젠테이션 잠금 해제
url: /ko/python-net/unlock/odp/
description: Python으로 ODP 프레젠테이션의 암호화와 쓰기 보호를 해제하세요.
keywords: ODP 잠금 해제, ODP 암호 제거, ODP 암호화 해제, ODP 쓰기 보호 해제
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python으로 ODP 프레젠테이션 잠금 해제" h2="Aspose.Slides로 ODP 프레젠테이션의 열기 암호와 쓰기 보호 설정을 해제하는 Python 애플리케이션을 빌드하세요." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python으로 ODP의 암호화와 쓰기 보호 해제" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ko/python-net/)을 사용하면 ODP 프레젠테이션을 열 때 암호를 요구하는 암호화를 해제하거나 쓰기 보호 설정을 해제할 수 있습니다. 암호화된 파일을 열려면 `LoadOptions`로 현재 암호를 지정하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP 프레젠테이션 암호화 해제 – Python" >}}
```python
load_options = slides.LoadOptions()
load_options.password = "current_password"

with slides.Presentation("encrypted-presentation.odp", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("decrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP 프레젠테이션 쓰기 보호 해제 – Python" >}}
```python
with slides.Presentation("write-protected-presentation.odp") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python으로 ODP의 보호를 해제하는 방법" intro="다음 단계에 따라 ODP 프레젠테이션의 보호를 해제하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}암호화된 ODP 파일은 `LoadOptions`에 현재 암호를 설정한 다음 `Presentation`으로 파일을 엽니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}열기 암호를 제거하려면 `ProtectionManager.remove_encryption`을, 쓰기 보호를 해제하려면 `ProtectionManager.remove_write_protection`을 호출합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.ODP`로 결과 프레젠테이션을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides로 구축" title="온라인에서 ODP 파일 잠금 해제" description="무료 Aspose.Slides Unlock 앱은 위 코드와 동일한 API인 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ko/python-net/)로 구축되었습니다. 앱을 열고 내 ODP 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Unlock 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 보호를 해제하는 방식을 확인하세요.
- ODP 파일에서 암호 또는 쓰기 보호를 제거하세요.
- 잠금 해제된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="잠금 해제를 지원하는 기타 형식" subTitle="Python으로 지원되는 다른 프레젠테이션 형식의 보호도 해제할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

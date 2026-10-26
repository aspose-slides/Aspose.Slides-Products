---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python으로 PPT 프레젠테이션의 텍스트 마스킹
url: /ko/python-net/redaction/ppt/
description: Python으로 PPT 프레젠테이션의 민감한 텍스트를 찾아 바꾸세요.
keywords: PPT 마스킹, PPT에서 텍스트 찾기 및 바꾸기, PPT 프레젠테이션 업데이트
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python으로 PPT 프레젠테이션의 텍스트 마스킹" h2="Aspose.Slides로 프레젠테이션의 민감한 텍스트를 찾아 바꾸는 Python 애플리케이션을 빌드하세요." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python을 사용한 PPT 프레젠테이션 텍스트 마스킹" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ko/python-net/)을 사용하면 PPT 프레젠테이션 전체에서 민감한 텍스트를 바꿀 수 있습니다. `Presentation.replace_text`와 `TextSearchOptions`로 검색을 제어한 다음 수정된 프레젠테이션을 저장하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT 프레젠테이션 텍스트 마스킹 – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python으로 PPT 프레젠테이션의 텍스트를 마스킹하는 방법" intro="PPT 프레젠테이션의 민감한 텍스트를 바꾸려면 다음 단계를 따르세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation`으로 PPT 파일을 엽니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/)와 `TextSearchOptions`를 사용해 필요한 텍스트를 바꿉니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}수정된 프레젠테이션을 `SaveFormat.PPT` 형식으로 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides로 구축" title="PPT 파일 온라인 마스킹" description="무료 Aspose.Slides Redaction 앱은 위 코드와 동일한 API인 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ko/python-net/)로 구축되었습니다. 앱을 열고 내 PPT 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Redaction 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 텍스트를 찾아 바꾸는 방식을 확인하세요.
- 정규식을 포함해 PPT 파일의 텍스트를 찾아 바꾸세요.
- 마스킹된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="마스킹을 지원하는 기타 형식" subTitle="Python으로 지원되는 다른 프레젠테이션 형식의 텍스트도 마스킹하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

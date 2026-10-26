---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python으로 PPT 프레젠테이션에서 텍스트 검색
url: /ko/python-net/search/ppt/
description: Python과 Aspose.Slides로 PPT 프레젠테이션의 텍스트를 검색하세요.
keywords: PPT에서 텍스트 검색, PPT에서 단어 찾기, Python으로 PPT 프레젠테이션 검색
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python으로 PPT 프레젠테이션에서 텍스트 검색" h2="Aspose.Slides로 PowerPoint 프레젠테이션의 텍스트를 찾는 Python 애플리케이션을 빌드하세요." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python을 사용한 PPT 프레젠테이션 텍스트 검색" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ko/python-net/)을 사용하면 [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/)로 각 슬라이드에서 지정한 문자열이 포함된 텍스트 프레임을 찾을 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT 프레젠테이션 텍스트 검색 – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python으로 PPT에서 텍스트를 검색하는 방법" intro="PPT 프레젠테이션에서 텍스트를 검색하려면 다음 단계를 따르세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation`으로 PPT 파일을 엽니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}슬라이드를 순회하며 각 슬라이드에 대해 [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/)를 호출합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}일치하는 각 텍스트 프레임의 `text` 속성을 읽습니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides로 구축" title="PPT 파일 온라인 텍스트 검색" description="무료 Aspose.Slides Search 앱은 위 코드와 동일한 API인 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ko/python-net/)로 구축되었습니다. 앱을 열고 내 PPT 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Search 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 텍스트를 찾는 방식을 확인하세요.
- PPT 파일에서 일반 텍스트나 정규식으로 검색하세요.
- 검색 결과를 텍스트 파일로 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="검색을 지원하는 기타 형식" subTitle="Python으로 지원되는 다른 프레젠테이션 형식에서도 텍스트를 검색하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

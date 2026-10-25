---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python으로 PPTX 파일에서 텍스트 추출
url: /ko/python-net/parser/pptx/
description: Python으로 PPTX 프레젠테이션에서 텍스트와 텍스트 서식 정보를 추출하세요.
keywords: Python으로 PPTX 구문 분석, PPTX 파서 Python, Python에서 PPTX 데이터 추출, Python으로 PPTX 텍스트 추출
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python으로 PPTX 프레젠테이션에서 텍스트 추출하기" h2="Aspose.Slides로 PowerPoint 프레젠테이션에서 텍스트와 서식 정보를 추출하는 Python 애플리케이션을 구축하세요." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python으로 PPTX 프레젠테이션의 텍스트 추출 예제" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/ko/python-net/)은 `SlideUtil`의 정적 메서드 [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/)를 제공합니다. 이 메서드는 전체 프레젠테이션의 `TextFrame` 객체를 반환하며 마스터 슬라이드의 텍스트도 포함할 수 있습니다. 다음 예제는 PPTX 프레젠테이션에서 텍스트와 관련 글꼴 정보를 추출합니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX 프레젠테이션에서 텍스트 추출 - Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.pptx") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python으로 PPTX에서 텍스트를 추출하는 방법" intro="다음 단계에 따라 PPTX 파일에서 텍스트를 추출하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation`으로 PPTX 파일을 엽니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.get_all_text_frames`를 호출하고 마스터 슬라이드 포함 여부를 지정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}반환된 `TextFrame` 객체를 순회합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 텍스트 프레임의 `paragraphs` 컬렉션을 순회합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 단락의 `portions` 컬렉션을 순회합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}현재 부분의 `text`와 서식 속성을 읽습니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides로 구축" title="온라인에서 텍스트와 이미지 추출" description="무료 Aspose.Slides Parser 앱은 위 코드와 동일한 API인 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ko/python-net/)로 구축되었습니다. 앱을 열고 내 PPTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Parser 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 읽는지 확인하세요.
- PPTX 파일을 업로드하고 텍스트와 이미지를 받으세요.
- 모든 결과를 하나의 ZIP 아카이브로 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 구문 분석 형식" subTitle="Python으로 지원되는 다른 프레젠테이션 형식에서도 텍스트를 추출할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/parser/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

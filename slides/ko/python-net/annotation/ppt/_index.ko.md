---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Python으로 PPT에서 메모 제거
url: /ko/python-net/annotation/ppt/ 
description: Aspose.Slides for Python via .NET을 사용하여 Python에서 PPT 프레젠테이션의 메모와 메모 작성자를 제거합니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python에서 PPT의 메모 및 메모 작성자 제거" h2="Aspose.Slides for Python via .NET을 사용하여 프레젠테이션 메모와 관련 작성자를 제거하세요." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python으로 PPT에서 메모 제거" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ko/python-net/)은 PPT 프레젠테이션에 저장된 메모와 메모 작성자에 대한 액세스를 제공합니다. `Presentation`으로 파일을 로드하고, 각 작성자의 `comments` 컬렉션과 `comment_authors`를 비운 다음, 결과를 PPT 형식으로 저장하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python으로 PPT에서 메모 제거" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python으로 PPT에서 메모를 제거하는 방법" intro="PPT 프레젠테이션에서 모든 메모와 메모 작성자를 제거하려면 다음 단계를 따르세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/)을 설치합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation`으로 PPT 파일을 엽니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`comment_authors`를 반복하며 각 작성자의 `comments` 컬렉션을 비웁니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`comment_authors` 컬렉션을 비웁니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.PPT`와 함께 `save`를 호출하여 업데이트된 PPT 프레젠테이션을 씁니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides로 구축" title="온라인에서 PPT 메모 제거" description="무료 Aspose.Slides Annotation 앱은 위 코드와 동일한 API인 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ko/python-net/)로 구축되었습니다. 앱을 열고 내 PPT 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Annotation 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 메모를 제거하는 방식을 확인하세요.
- PPT 파일의 모든 메모를 제거합니다.
- 정리된 파일을 다운로드합니다.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="주석에 지원되는 기타 형식" subTitle="Python을 사용하면 다른 형식에서도 주석을 제거할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

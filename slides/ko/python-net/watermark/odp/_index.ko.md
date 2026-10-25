---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python으로 ODP 프레젠테이션에 워터마크 추가
url: /ko/python-net/watermark/odp/
description: Python과 Aspose.Slides로 ODP 프레젠테이션에 텍스트 및 이미지 워터마크를 추가하세요.
keywords: ODP에 워터마크 추가, ODP에 텍스트 워터마크 추가, ODP에 이미지 워터마크 추가
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python으로 ODP 프레젠테이션에 워터마크 추가" h2="Aspose.Slides로 ODP 프레젠테이션에 텍스트 또는 이미지 워터마크를 추가하는 Python 애플리케이션을 구축하세요." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python으로 ODP 프레젠테이션에 워터마크 추가하기" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ko/python-net/)을 사용하면 OpenOffice 없이 ODP 프레젠테이션에 텍스트 또는 이미지 워터마크를 추가할 수 있습니다. 워터마크는 소유권을 표시하거나, 프레젠테이션을 기밀 또는 초안으로 표시하거나, 일관된 브랜딩을 제공할 수 있습니다. 아래 예제는 첫 번째 슬라이드 마스터에 워터마크를 배치하므로 해당 마스터를 사용하는 슬라이드에 워터마크가 표시됩니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP 프레젠테이션에 텍스트 워터마크 추가 - Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 100, 100, 400, 50)
    watermark_text_frame = watermark_shape.add_text_frame("CONFIDENTIAL")

    watermark_shape.fill_format.fill_type = slides.FillType.NO_FILL
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    watermark_portion = watermark_text_frame.paragraphs[0].portions[0]
    watermark_portion.portion_format.font_height = 32

    watermark_shape.auto_shape_lock.select_locked = True
    watermark_shape.auto_shape_lock.size_locked = True
    watermark_shape.auto_shape_lock.text_locked = True
    watermark_shape.auto_shape_lock.position_locked = True
    watermark_shape.auto_shape_lock.grouping_locked = True

    presentation.save("watermarked.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP 프레젠테이션에 이미지 워터마크 추가 - Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python으로 ODP에 워터마크를 추가하는 방법" intro="다음 단계에 따라 ODP 프레젠테이션에 텍스트 워터마크를 추가하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation`으로 ODP 파일을 엽니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`masters` 컬렉션에서 첫 번째 슬라이드 마스터를 가져옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`add_auto_shape`를 호출하여 슬라이드 마스터에 사각형을 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`add_text_frame`을 호출하여 워터마크 텍스트를 추가한 다음 도형의 서식을 지정하고 잠급니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.ODP`와 함께 `save`를 호출하여 워터마크가 적용된 프레젠테이션을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides로 구축" title="온라인에서 ODP 파일에 워터마크 추가" description="무료 Aspose.Slides Watermark 앱은 위 코드와 동일한 API인 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ko/python-net/)로 구축되었습니다. 앱을 열고 내 ODP 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Watermark 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 워터마크를 어떻게 추가하는지 확인하세요.
- ODP 파일에 텍스트 또는 이미지 워터마크를 추가하세요.
- 워터마크가 적용된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="워터마크를 지원하는 기타 형식" subTitle="Python으로 지원되는 다른 프레젠테이션 형식에도 워터마크를 추가할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

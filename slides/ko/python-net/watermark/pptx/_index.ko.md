---
title: Python을(를) 사용하여 PPTX 프레젠테이션 파일에 워터마크 추가
url: /ko/python-net/watermark/pptx/
keywords: 워터마크 추가 PPTX, 텍스트 워터마크 추가 PPTX, 이미지 워터마크 추가 PPTX
description: PPTX 프레젠테이션에 워터마크를 추가하기 위한 Python 소스 코드입니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python을(를) 사용하여 PPTX 프레젠테이션에 워터마크 추가" h2="서버 측 API를 사용하여 텍스트 또는 이미지 워터마크를 PPT, PPTX 또는 ODP 프레젠테이션에 삽입하는 나만의 Python 앱을 구축하세요." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python을(를) 통해 PPTX 프레젠테이션에 워터마크 추가" %}}
Aspose.Slides for Python via .NET을(를) 사용하여 PPTX 프레젠테이션에 워터마크를 추가할 수 있습니다. 워터마크는 프레젠테이션의 필수 요소입니다. 프리젠테이션 내용을 허가 없이 복사하거나 사용하지 못하도록 보호하는 데 사용됩니다. 워터마크는 프리젠테이션 위에 표시되는 보이거나 보이지 않는 이미지 또는 텍스트입니다. 프레젠테이션의 소유자를 식별하고 무단 사용을 방지하는 데 사용할 수 있습니다. 워터마크를 사용하여 프레젠테이션에 전문적인 느낌을 더하고 더욱 세련되게 보이게 할 수 있습니다. 
{{% blocks/products/pf/agp/code-block title="Python을 사용하여 PPTX에 텍스트 워터마크 추가" offSpacer="true" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as draw

with slides.Presentation() as pres:
    master = pres.masters[0]

    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, 100, 100)
    watermarkTextFrame = watermarkShape.add_text_frame("Watermark")

    # Lock Watermark from Editing
    watermarkShape.shape_lock.select_locked = True
    watermarkShape.shape_lock.size_locked = True
    watermarkShape.shape_lock.text_locked = True
    watermarkShape.shape_lock.position_locked = True
    watermarkShape.shape_lock.grouping_locked = True
    
    # Set Text Watermark Transparency
    watermarkPortion = watermarkTextFrame.paragraphs[0].portions[0]
    watermarkPortion.portion_format.fill_format.fill_type = slides.FillType.SOLID
    watermarkPortion.portion_format.fill_format.solid_fill_color.color = draw.Color.from_argb(150, 200, 200, 200)
    
    # Set Font Size of Text Watermark
    watermarkPortion.portion_format.font_height = 16

    pres.save("watermark.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python을(를) 사용하여 PPTX 프레젠테이션에 이미지 워터마크 추가" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation() as presentation:
    with open("image1.png", "rb") as fs:
        data = fs.read()
    image = presentation.images.add_image(data)

    master = presentation.masters[0]
    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, image.width, image.height)
    
    watermarkShape.fill_format.fill_type = slides.FillType.PICTURE
    watermarkShape.fill_format.picture_fill_format.picture.image = image
    watermarkShape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH

    presentation.save("watermark2.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python을(를) 통해 PPTX에 워터마크를 추가하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="PPTX 파일에 텍스트 워터마크를 추가하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션 인스턴스로 PPTX 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
마스터 프레젠테이션 선택
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddAutoShape 메서드를 사용하여 도형 유형 추가
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddTextFrame 메서드를 사용하여 워터마크 텍스트 추가
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PPTX 형식으로 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 형식" subTitle="Python을(를) 사용하여 다음 형식에 워터마크를 추가할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
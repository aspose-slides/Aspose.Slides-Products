---
title: Python에서 JPG를 PPTX로 변환
url: /ko/python-net/conversion/jpg-to-pptx/
keywords: JPG를 PPTX로, JPG를 PPTX, PowerPoint, JPG, PPTX, Python API, Python 라이브러리로 변환
description: Python에서 JPG를 PPTX로 변환합니다. Python 라이브러리 API를 사용하여 JPG 이미지를 PowerPoint로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python에서 JPG를 PPTX로 변환" h2="Python 코드를 사용하여 JPG를 PPTX로 변환하기 위한 강력한 크로스 플랫폼 Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides를 사용하여 JPG를 PPTX로 변환" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)은 PowerPoint 프레젠테이션, PDF, HTML 문서 및 기타 파일. JPG를 PPTX로 변환하면 본질적으로 JPG 이미지를 기반으로 하는 슬라이드가 포함된 PowerPoint 프레젠테이션을 만드는 것입니다.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Python에서 JPG를 PPTX로 변환" %}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)을 사용하면 몇 줄의 코드만으로 JPG 이미지를 PowerPoint 프레젠테이션으로 변환할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="JPG를 PPTX로 변환하는 Python 코드" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.jpg", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Python에서 JPG를 PPTX로 변환하는 방법" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프로젝트에서 라이브러리를 참조로 추가하십시오.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX로 변환하려는 JPG 이미지를 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과 파일을 PPTX 프레젠테이션으로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="무료 온라인 변환기" sectionDescription="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 PowerPoint 변환" subTitle="다른 형식의 파일을 PowerPoint로 변환할 수도 있습니다." >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
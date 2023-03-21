---
title: Python에서 SVG을 PNG으로 변환
url: /ko/python-net/conversion/svg-to-png/
keywords: SVG에서 PNG으로, SVG에서 PNG으로 변환, Python API, Python 라이브러리, SVG, PNG
description: Python에서 SVG을 PNG으로 변환합니다. Python 라이브러리 API를 사용하여 SVG 파일을 PNG 파일로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python에서 SVG을 PNG으로 변환" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고 Microsoft PowerPoint 및 OpenOffice 프레젠테이션 파일을 생성, 병합, 검사 또는 변환할 수 있는 기능으로 응용 프로그램을 개발하는 데 도움이 되는 고속 및 교차 플랫폼 Python 라이브러리입니다." >}}

{{% blocks/products/pf/feature-page-section h2="Python에서 SVG을 PNG으로 변환" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)은 프레젠테이션 파일을 만들고 조작하기 위한 강력한 Python 라이브러리입니다. 또한 SVG을 PNG으로 변환하는 유연한 방법을 제공합니다. **Aspose.Slides for Python via .NET**을 사용하면 모든 개발자 또는 애플리케이션이 단 몇 줄의 Python 코드로 SVG을 PNG 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for Python은 SVG 파일을 PNG 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 SVG을 PNG 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python을 사용하여 SVG을 PNG로 변환" %}}
SVG을 PNG로 변환하려면 SVG 파일에서 프레젠테이션을 생성하고 PNG로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="SVG을 PNG로 변환하기 위한 Python 코드" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open("image.svg", "rb") as file:
        svgContent = file.read()
    svgImage = slides.SvgImage(svgContent)
    ppImage = pres.images.add_image(svgImage)
    pres.slides[0].shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, ppImage.width, ppImage.height, ppImage)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API를 사용하여 SVG을 PNG로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Python에서 SVG을 PNG으로 변환하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)를 설치합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python에서 소스 SVG 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PNG 파일로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="무료 온라인 변환기" sectionDescription="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="SVG을 지원되는 다른 형식으로 변환" subTitle="SVG을 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식 보기" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
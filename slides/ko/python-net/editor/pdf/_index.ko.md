---
title: 파이썬에서 PDF 편집
url: /ko/python-net/editor/pdf/
keywords: PDF, PDF, Python API, Python 라이브러리 편집
description: Python에서 PDF를 편집합니다. Python 라이브러리 API를 사용하여 PDF 문서 편집
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="파이썬에서 PDF 편집" h2="Python 코드를 사용하여 PDF를 편집하기 위한 고속 및 교차 플랫폼 Python 라이브러리" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides를 사용하여 PDF 편집" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)은 프레젠테이션, PDF 문서 및 기타 파일을 조작하고 편집하는 데 사용되는 강력한 Python 라이브러리입니다. . 새 텍스트 줄을 추가하여 PDF 문서를 편집할 수 있습니다. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="파이썬에서 PDF 편집" %}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)을 사용하면 몇 가지만으로 PDF 문서에 새 텍스트 줄을 추가할 수 있습니다. 코드 줄.

{{% blocks/products/pf/agp/code-block title="PDF 편집을 위한 Python 코드" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Python에서 PDF를 편집하는 방법" >}}


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
편집하려는 PDF 문서를 불러옵니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
새 텍스트 줄을 추가합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
변경된 PDF 파일을 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="다른 파일 편집" subTitle="다른 형식의 파일도 편집할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
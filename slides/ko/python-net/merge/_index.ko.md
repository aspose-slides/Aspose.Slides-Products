---
title: Python을 사용하여 PDF, PPT, PPTX 및 기타 여러 파일 형식 병합
url: /ko/python-net/merge/
keywords: 병합, 조인, PowerPoint, 프레젠테이션, Python, Aspose
description: Python PPT, PPTX, ODP, PDF, PNG, JPG 등의 여러 파일을 병합합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python에서 PowerPoint, PDF, PPT 또는 기타 문서 병합" h2="PPT, PPTX, PDF, PNG, JPEG 및 기타 형식을 병합하는 고속 Python 라이브러리." >}}

{{% blocks/products/pf/feature-page-section h2="Python을 사용하여 PPT, PPTX, PDF 병합" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)는 프레젠테이션 파일을 만들고 조작하기 위한 강력한 Python 라이브러리입니다. 또한 여러 PPT/PPTX 프레젠테이션을 결합하는 유연한 방법을 제공합니다. 한 프리젠테이션을 다른 프리젠테이션에 병합하면 하나의 프리젠테이션에서 슬라이드를 효과적으로 결합하여 하나의 파일을 얻는 것입니다. Aspose.Slides를 사용하면 두 개의 프레젠테이션을 서로 다른 방식으로 병합할 수 있습니다. 품질이나 데이터 손실에 대해 걱정할 필요 없이 모든 모양, 스타일, 텍스트, 서식, 주석, 애니메이션 등으로 프레젠테이션을 병합할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python에서 PowerPoint 프레젠테이션 병합" %}}
PowerPoint 프레젠테이션을 병합하려면 한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복제해야 합니다.

{{% blocks/products/pf/agp/code-block title="Python을 사용하여 PPTX 파일 병합" offSpacer="true" %}}

```python

import aspose.slides as slides

# open first presentation
with slides.Presentation("presentation1.pptx") as pres1:
    # open second presentation
    with slides.Presentation("presentation2.pptx") as pres2:
        # loop through slides
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
        # save merged presentation
        pres1.save("combined.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python을 사용하여 프레젠테이션을 슬라이드 마스터와 병합" %}}
이 파이썬 코드는 여러 프레젠테이션을 하나로 병합하고 슬라이드 마스터 프레젠테이션 템플릿의 스타일을 적용하는 방법을 보여줍니다. 따라서 결과 프레젠테이션은 동일한 소스 서식을 유지하고 다른 프레젠테이션의 마스터 슬라이드에서 서식을 포함합니다.

{{% blocks/products/pf/agp/code-block title="Python에서 여러 PPT를 하나로 병합" offSpacer="true" %}}

```python

import aspose.slides as slides

files = ['pres1.pptx', 'pres2.pptx', 'pres3.pptx']

with slides.Presentation('master.pptx') as master:
    masterSlide = master.masters[0]

    for file in files:
        with slides.Presentation(file) as source:
            for slide in source.slides:
                clone = master.slides.add_clone(slide)

                for shape in masterSlide.shapes:
                    clone.shapes.add_clone(shape)
    
    master.save("combined.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python API용 Aspose.Slides를 사용하여 프레젠테이션을 병합하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 두 개의 PPTX 파일을 병합하고 결과를 Python에서 PDF로 저장하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)를 설치합니다.
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python에서 소스 PPTX 파일을 엽니다.
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**add_clone** 방법을 사용하여 PPTX 파일을 결합합니다.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션을 저장하고 단일 PDF 파일로 결과를 얻으십시오.
```
pres1.save("document.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="병합할 기타 지원 형식" subTitle="다른 파일 형식을 결합할 수도 있습니다. 아래에서 지원되는 다른 형식을 참조하세요." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/ppt/" name="PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptx/" name="PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pdf/" name="PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/odp/" name="ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/otp/" name="OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pot/" name="POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/potm/" name="POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/potx/" name="POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pps/" name="PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/ppsm/" name="PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/ppsx/" name="PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm/" name="PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/fodp/" name="FODP" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
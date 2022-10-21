---
title: Python을 사용하여 PPTM 파일을 OTP에 병합
url: /ko/python-net/merge/pptm-to-otp/
keywords: PPTM을 OTP에 병합, PPTM을 OTP에 결합, PPTM을 OTP에 결합, PowerPoint, Presentation, OTP, Python, Aspose
description: Python에서 여러 PPTM 파일을 병합합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python에서 PPTM 파일을 OTP으로 병합" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고도 Microsoft PowerPoint 및 OpenOffice 프레젠테이션 파일을 생성, 병합, 검사 또는 변환할 수 있는 기능으로 응용 프로그램 개발에 도움이 되는 고속 교차 플랫폼 Python API입니다." >}}

{{% blocks/products/pf/feature-page-section h2="Python에서 PPTM을 OTP으로 병합" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)는 프레젠테이션 파일을 만들고 조작하기 위한 강력한 Python 라이브러리입니다. 또한 여러 PPTM 프레젠테이션을 결합하는 유연한 방법을 제공합니다. 한 프리젠테이션을 다른 프리젠테이션에 병합하면 하나의 프리젠테이션에서 슬라이드를 효과적으로 결합하여 하나의 파일을 얻는 것입니다. Aspose.Slides를 사용하면 두 개의 프레젠테이션을 서로 다른 방식으로 병합할 수 있습니다. 품질이나 데이터 손실에 대해 걱정할 필요 없이 모든 모양, 스타일, 텍스트, 서식, 주석, 애니메이션 등으로 프레젠테이션을 병합할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python을 사용하여 PPTM 파일을 OTP에 병합" %}}
PowerPoint 프레젠테이션을 병합하려면 한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복제해야 합니다.

{{% blocks/products/pf/agp/code-block title="여러 PPTM을 단일 OTP 파일로 병합하기 위한 Python 코드" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.pptm") as pres1:
    with slides.Presentation("presentation2.pptm") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.otp", slides.export.SaveFormat.OTP)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API를 사용하여 PPTM을 OTP으로 병합하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 두 개의 PPTM 파일을 병합하고 결과를 Python에서 OTP으로 저장하는 단계입니다." >}}

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
Python에서 소스 PPTM 파일을 엽니다.
```
pres1 = slides.Presentation('pres1.pptm')
pres2 = slides.Presentation('pres2.pptm')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) 메서드를 사용하여 PPTM 파일을 결합합니다.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션을 저장하고 단일 OTP 파일로 결과를 가져옵니다.
```
pres1.save("presentation.otp", slides.export.SaveFormat.OTP)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="지원되는 다른 형식으로 PPTM 내보내기" subTitle="PPTM을 결합하여 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식 보기" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-pptx/" name="PPTM TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-ppt/" name="PPTM TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-pdf/" name="PPTM TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-html/" name="PPTM TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-png/" name="PPTM TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-bmp/" name="PPTM TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-jpg/" name="PPTM TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-fodp/" name="PPTM TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-gif/" name="PPTM TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-odp/" name="PPTM TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-pot/" name="PPTM TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-potm/" name="PPTM TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-potx/" name="PPTM TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-pps/" name="PPTM TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-ppsm/" name="PPTM TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-ppsx/" name="PPTM TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-svg/" name="PPTM TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-tiff/" name="PPTM TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/merge/pptm-to-xps/" name="PPTM TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
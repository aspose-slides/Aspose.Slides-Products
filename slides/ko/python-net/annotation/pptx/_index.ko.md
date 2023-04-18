---
title: Python을 사용하여 PPTX 주석 제거
weight: 4380
url: /ko/python-net/annotation/pptx/ 
description: PPTX 프레젠테이션 주석을 제거하는 Python 소스 코드
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python의 PPTX에서 주석 및 주석 작성자 제거" h2="서버 측 API를 사용하여 문서 파일에서 댓글과 작성자를 조작하는 자신만의 Python 스크립트를 빌드합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python을 통해 PPTX에서 주석 제거" %}}
PPTX 파일에서 주석을 제거하기 위해 기능이 풍부한 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ko/python-net/) API를 사용합니다. 강력하고 사용하기 쉬운 Python 플랫폼용 문서 조작 API.
{{% blocks/products/pf/agp/code-block title="PPTX에서 주석 삭제 - Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.pptx") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Python을 통해 PPTX에서 주석을 제거하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스로 PPTX 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
로드된 PPTX의 모든 작성자에 대해 반복
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
작성자의 모든 주석 제거
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
마지막에 모든 작성자 제거
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 주석 형식" subTitle="Python을 사용하면 다음을 포함한 다른 형식에 쉽게 주석을 달 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
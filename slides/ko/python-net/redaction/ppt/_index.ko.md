---
title: Python을(를) 사용하여 PPT 프레젠테이션 파일 수정
url: /ko/python-net/redaction/ppt/
keywords: PPT 수정, PPT에서 텍스트 찾기 및 바꾸기, PPT 프레젠테이션 업데이트
description: PPT Presentation에서 텍스트를 찾고 교체하기 위한 Python 소스 코드.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python을 사용하여 PPT 수정" h2="서버 측 API를 사용하여 프리젠테이션 파일에서 텍스트를 찾고 교체하는 나만의 Python 앱을 빌드하세요. PPT 프레젠테이션의 콘텐츠, 댓글 또는 메타데이터에서 텍스트를 검색하고 바꾸는 방법을 알아보세요." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python을(를) 통해 PPT 프레젠테이션 수정" %}}
Aspose.Slides for Python via .NET API를 사용하여 콘텐츠, 댓글, 슬라이드 노트 또는 메타데이터의 기본 문서 검색 및 텍스트 바꾸기를 단 몇 줄의 코드로 수행할 수 있습니다. PowerPoint 및 OpenOffice에서 텍스트를 찾고 바꿉니다. 정규식 데이터 일치를 통해 프레젠테이션의 텍스트, 주석, 메타데이터를 편집합니다.
{{% blocks/products/pf/agp/code-block title="Python을(를) 사용하여 PPT 프레젠테이션 수정" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.ppt") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python을 통해 PPT을(를) 수정하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 PPT 파일을 수정하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션 인스턴스로 PPT를 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
[FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) 메서드를 사용하여 텍스트를 찾고 바꿉니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PPT 형식으로 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="온라인 PPT 리댁션 라이브 데모" sectionDescription="지금 바로 PPT 문서의 콘텐츠, 댓글 또는 메타데이터에서 텍스트를 검색하고 교체하세요." >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 교정 형식" subTitle="Python을(를) 사용하여 다음 형식을 수정할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Python을 사용하여 PPTX 파일에서 텍스트 및 이미지 추출
url: /ko/python-net/parser/pptx/
keywords: Python을 사용하여 PPTX 구문 분석, PPTX 구문 분석기 Python, Python의 PPTX에서 데이터 추출, Python을 사용하여 PPTX에서 텍스트 추출, Python을 사용하여 PPTX에서 이미지 추출
description: PPTX 프레젠테이션을 구문 분석하기 위한 Python 소스 코드입니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python을 사용하여 PPTX 프레젠테이션에서 텍스트 및 이미지 추출" h2="서버 측 API를 사용하여 PowerPoint에서 텍스트, 이미지, 비디오 및 오디오 파일을 추출하기 위한 고유한 Python 앱을 빌드하세요." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python을 통해 PPTX 프레젠테이션에서 텍스트 추출" %}}
전체 프레젠테이션에서 텍스트를 스캔하려면 SlideUtil 클래스에 의해 노출된 [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) 정적 메서드를 사용합니다. 아래 코드는 마스터 슬라이드를 포함하여 프레젠테이션의 텍스트 및 서식 정보를 스캔합니다.
{{% blocks/products/pf/agp/code-block title="Python을 사용하여 PPTX 프레젠테이션에서 텍스트 추출" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a PPTX file
with slides.Presentation("pres.pptx") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the PPTX
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python을 통해 PPTX에서 텍스트를 추출하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 PPTX 파일을 구문 분석하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션 인스턴스로 PPTX 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX의 모든 슬라이드에서 TextFrame 개체의 배열을 가져옵니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
TextFrame 배열을 통해 반복
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
현재 TextFrame에서 단락 반복
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
현재 단락의 부분을 반복합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
현재 부분에서 텍스트 가져오기
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 구문 분석 형식" subTitle="Python을(를) 사용하여 다음 형식도 스캔할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/parser/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
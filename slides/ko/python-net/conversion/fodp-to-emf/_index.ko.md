---
title: Python에서 FODP를 EMF로 변환
weight: 20
url: /ko/python-net/conversion/fodp-to-emf/ 
keywords: "Convert, PowerPoint, FODP, EMF, Presentation, Python"
description: FODP에서 EMF Python으로의 변환을 위한 샘플 코드입니다. FODP 파일을 EMF 파일로 일괄 변환하려면 PowerPoint Python API를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Python에서 FODP를 EMF로 변환" h2="FODP를 EMF로 변환하기 위한 강력한 PowerPoint Python 라이브러리" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Python에서 FODP를 EMF로 변환" %}}

프로그래밍 방식으로 FODP 파일을 EMF로 변환해야 합니까? [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/ko/python-net/)을 사용하면 모든 개발자가 몇 줄의 Python 코드로 FODP를 EMF 형식으로 변환할 수 있습니다.

최신 프레젠테이션 처리 API인 Aspose.Slides for Python은 FODP에서 EMF를 빠르게 생성합니다. [브라우저](https://products.aspose.app/slides/conversion)에서 바로 FODP에서 EMF로의 변환 품질을 테스트하십시오. Aspose PowerPoint PPTX 라이브러리를 사용하면 FODP 파일을 널리 사용되는 여러 형식으로 변환할 수 있습니다.

다음 pip 명령을 사용하여 [PyPI](https://pypi.org/project/Aspose.Slides/)에서 라이브러리를 설치할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="콘솔/터미널" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Python에서 FODP를 EMF로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 Python을 사용하여 FODP 파일을 EMF로 변환하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스로 FODP 파일 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
출력 파일 경로 및 SaveFormat.EMF를 매개변수로 지정하면서 `save` 메소드 호출
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
FODP 파일은 지정된 경로에 저장됩니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Python 변환 샘플 소스 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 Linux 기반 OS([자세히](https://docs.aspose.com/slides/python-net/system-requirements/) 참조).
- 파이썬 3.5 이상
- 프로젝트에서 참조되는 Python용 Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 FODP에서 EMF Python으로의 변환을 보여줍니다." offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.fodp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Python에서 FODP를 EMF로 저장" %}}
무료 앱을 사용하여 FODP에서 EMF로의 변환 프로세스의 데모를 확인하십시오. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="FODP을 EMF로 변환하는 무료 앱" 
        sectionDescription="[무료 Collage 앱을 사용해보십시오](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="FODP를 다른 많은 파일 형식으로 변환할 수도 있습니다. 아래에서 지원되는 다른 변환을 참조하세요." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-bmp/" name="FODP TO BMP" description="비트맵 이미지" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-gif/" name="FODP TO GIF" description="그래픽 교환 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-html/" name="FODP TO HTML" description="하이퍼 텍스트 마크업 언어" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-jpg/" name="FODP TO JPG" description="JPEG 이미지" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-odp/" name="FODP TO ODP" description="OpenDocument 프레젠테이션 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-otp/" name="FODP TO OTP" description="OpenDocument 표준 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-pdf/" name="FODP TO PDF" description="휴대용 문서 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-png/" name="FODP TO PNG" description="휴대용 네트워크 그래픽" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-pot/" name="FODP TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-potm/" name="FODP TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-potx/" name="FODP TO POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-pps/" name="FODP TO PPS" description="파워포인트 슬라이드 쇼" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="매크로 사용 슬라이드 쇼" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="파워포인트 슬라이드 쇼" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-ppt/" name="FODP TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Open XML 프레젠테이션 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-svg/" name="FODP TO SVG" description="확장 가능한 벡터 그래픽" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="태그가 지정된 이미지 형식" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/fodp-to-xps/" name="FODP TO XPS" description="XML 용지 사양" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: C++ 응용 프로그램을 통해 PPS를 XPS로 변환
weight: 3440
url: /ko/cpp/conversion/pps-to-xps/ 
description: PPS 문서를 XPS 형식으로 변환하는 샘플 C++ 변환 코드. C++ 응용 프로그램 내에서 일괄 PPS에서 XPS로 변환하는 예제 코드를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C++를 통해 PPS를 XPS로 변환" h2="Microsoft PowerPoint를 설치할 필요 없이 C++ 라이브러리를 사용하여 고성능 PPS에서 XPS로 변환합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XPS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++를 사용하여 PPS를 XPS로 변환하는 방법" %}}

 PPS를 XPS로 변환하려면 다음을 사용합니다.
 [C++용 Aspose.Slides](https://products.aspose.com/slides/ko/cpp/)
 기능이 풍부하고 강력하며 사용하기 쉬운 C++ 플랫폼용 문서 조작 및 변환 API인 API입니다. 최신 버전을 직접 다운로드할 수 있습니다.
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 패키지 관리자, 검색
 Aspose.Slides.Cpp
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++를 통해 PPS를 XPS로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 개발자는 몇 줄의 코드로 PPS 파일을 XPS로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Slides for C++ Presentation Object로 PPS 파일을 로드합니다.
1. Save() 메서드를 호출합니다.
1. 파일 확장자가 (XPS)인 출력 파일 경로를 전달합니다.
1. XPS 파일은 지정된 경로에 저장됩니다.
1. 호환되는 프로그램에서 XPS 파일을 엽니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 변환 예제 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경과 호환되는 OS.
- 프로젝트에서 참조되는 C++ DLL용 Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPS에서 XPS C++로의 변환 소스 코드" offSpacer="" %}}

```cs
// Load the PPS.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.pps");
// Save in XPS format.
prs->Save(u"convertedFile.xps", Aspose::Slides::Export::SaveFormat::Xps);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="PPS을 XPS로 변환하는 무료 앱" 
        sectionDescription="[무료 Collage 앱을 사용해보십시오](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 PPS를 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-bmp/" name="PPS TO BMP" description="비트맵 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-emf/" name="PPS TO EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-gif/" name="PPS TO GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-html/" name="PPS TO HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="JPEG 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-odp/" name="PPS TO ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-pdf/" name="PPS TO PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-png/" name="PPS TO PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-pot/" name="PPS TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-potm/" name="PPS TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-potx/" name="PPS TO POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-ppt/" name="PPS TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-pptm/" name="PPS TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-svg/" name="PPS TO SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-tiff/" name="PPS TO TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/pps-to-xml/" name="PPS TO XML" description="확장 가능한 마크업 언어" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
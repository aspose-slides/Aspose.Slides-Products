---
title: C++ 응용 프로그램을 통해 XML을 PNG로 변환
weight: 7000
url: /ko/cpp/conversion/xml-to-png/ 
description: XML 문서를 PNG 형식으로 변환하는 샘플 C++ 변환 코드. 모든 C++ 애플리케이션 내에서 배치 XML에서 PNG로 변환을 위한 예제 코드를 사용하십시오.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C++를 통해 XML을 PNG로 변환" h2="Microsoft PowerPoint를 설치할 필요 없이 C++ 라이브러리를 사용하여 고성능 XML을 PNG로 변환합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++를 사용하여 XML을 PNG로 변환하는 방법" %}}

 XML을 PNG로 변환하려면 다음을 사용합니다.
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

{{% blocks/products/pf/agp/feature-section-col title="C++를 통해 XML을 PNG로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 개발자는 몇 줄의 코드로 XML 파일을 PNG로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Slides for C++ Presentation Object로 XML 파일을 로드합니다.
1. 첫 번째 슬라이드를 선택합니다.
1. 원하는 치수를 설정합니다.
1. 원하는 크기의 썸네일을 가져옵니다.
1. PNG 출력 매개변수가 있는 Save() 메서드를 호출합니다.
1. 호환되는 프로그램에서 PNG 파일을 엽니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 변환 예제 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경과 호환되는 OS.
- 프로젝트에서 참조되는 C++ DLL용 Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XML에서 PNG C++로의 변환 소스 코드" offSpacer="" %}}

```cs
// Load the XML
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.xml");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.png", ImageFormat::get_Png());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="XML을 PNG로 변환하는 무료 앱" 
        sectionDescription="[무료 Collage 앱을 사용해보십시오](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 XML을 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-bmp/" name="XML TO BMP" description="비트맵 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-emf/" name="XML TO EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-gif/" name="XML TO GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-html/" name="XML TO HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-jpeg/" name="XML TO JPEG" description="JPEG 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-odp/" name="XML TO ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-otp/" name="XML TO OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-pdf/" name="XML TO PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-pot/" name="XML TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-potm/" name="XML TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-potx/" name="XML TO POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-pps/" name="XML TO PPS" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-ppsm/" name="XML TO PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-ppsx/" name="XML TO PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-ppt/" name="XML TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-pptm/" name="XML TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-pptx/" name="XML TO PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-svg/" name="XML TO SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-tiff/" name="XML TO TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/xml-to-xps/" name="XML TO XPS" description="XML 용지 사양" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
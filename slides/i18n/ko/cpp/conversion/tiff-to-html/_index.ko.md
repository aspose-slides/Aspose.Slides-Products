---
title: C++ 응용 프로그램을 통해 TIFF를 HTML로 변환
weight: 440
url: /ko/cpp/conversion/tiff-to-html/ 
description: TIFF 문서를 HTML 형식으로 변환하는 샘플 C++ 변환 코드. C++ 응용 프로그램 내에서 일괄 TIFF에서 HTML로 변환하는 예제 코드를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C++를 통해 TIFF를 HTML로 변환" h2="Microsoft PowerPoint를 설치할 필요 없이 C++ 라이브러리를 사용하여 고성능 TIFF를 HTML로 변환합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TIFF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++를 사용하여 TIFF를 HTML로 변환하는 방법" %}}

 TIFF를 HTML로 변환하기 위해 다음을 사용합니다.
 [C++용 Aspose.Slides](https://products.aspose.com/slides/cpp)
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

{{% blocks/products/pf/agp/feature-section-col title="C++를 통해 TIFF를 HTML로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 개발자는 몇 줄의 코드로 TIFF 파일을 HTML로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Slides for C++ Presentation Object로 TIFF 파일을 로드합니다.
1. Save() 메서드를 호출합니다.
1. 파일 확장자가 (HTML)인 출력 파일 경로를 전달합니다.
1. HTML 파일은 지정된 경로에 저장됩니다.
1. 호환되는 프로그램에서 HTML 파일을 엽니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 변환 예제 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경과 호환되는 OS.
- 프로젝트에서 참조되는 C++ DLL용 Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TIFF에서 HTML C++로의 변환 소스 코드" offSpacer="" %}}

```cs
// Load the TIFF.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.tiff");
// Save in HTML format.
prs->Save(u"convertedFile.html", Aspose::Slides::Export::SaveFormat::Html);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TIFF to HTML Conversion Live Demos" sectionDescription="[Convert TIFF to HTML](https://products.aspose.app/slides/conversion/tiff-to-html) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your TIFF file, it will be converted instantly to HTML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="C++ 프레젠테이션 조작 라이브러리" %}}

 슬라이드 및 프레젠테이션 API를 사용하여 Microsoft PowerPoint 문서를 읽고, 쓰고, 조작하고, PDF, XPS, HTML, TIFF, ODP 및 기타 다양한 형식으로 변환할 수 있습니다. 처음부터 새 파일을 만들고 지원되는 관련 형식으로 저장할 수 있습니다. Aspose.Slides는 프레젠테이션, 슬라이드 및 요소를 생성, 구문 분석 또는 조작하기 위한 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어에 의존하지 않습니다.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" >}}

TIFF or TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. It supports lossy as well as lossless compression schemes to choose between space and time for applications using the format. The format is extensible and has underwent several revisions that allows the inclusion of an unlimited amount of private or special-purpose information. The format is not machine dependent and is free from bounds like processor, operating system, or file systems.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) is the extension for web pages created for display in browsers. Known as language of the web, HTML has evolved with requirements of new information requirements to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from server, where these are hosted, or can be loaded from local system as well. Each HTML page is made up of HTML elements such as forms, text, images, animations, links, etc. These elements are represented by tags such as img, a, p and several others where each tag has start and end. It can also embed applications written in scripting languages such as JavaScript and Style Sheets (CSS) for overall layout representation.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 TIFF를 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-bmp/" name="TIFF TO BMP" description="비트맵 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-emf/" name="TIFF TO EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-gif/" name="TIFF TO GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-jpeg/" name="TIFF TO JPEG" description="JPEG 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-odp/" name="TIFF TO ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-otp/" name="TIFF TO OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-pdf/" name="TIFF TO PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-png/" name="TIFF TO PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-pot/" name="TIFF TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-potm/" name="TIFF TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-potx/" name="TIFF TO POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-pps/" name="TIFF TO PPS" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-ppsm/" name="TIFF TO PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-ppsx/" name="TIFF TO PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-ppt/" name="TIFF TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-pptm/" name="TIFF TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-pptx/" name="TIFF TO PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-svg/" name="TIFF TO SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-xml/" name="TIFF TO XML" description="확장 가능한 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/tiff-to-xps/" name="TIFF TO XPS" description="XML 용지 사양" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
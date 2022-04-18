---
title: C#을 통해 PPT를 PDF로 변환
weight: 1960
url: /ko/net/conversion/ppt-to-pdf/ 
description: PPT에서 PDF로 C# 변환을 위한 샘플 코드입니다. VB.NET, Asp.NET 또는 모든 .NET 기반 응용 프로그램 내에서 일괄 PPT 파일을 PDF로 변환하는 API 예제 코드를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C#을 통해 PPT를 PDF로 변환" h2=".NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 PowerPoint® PPT 파일을 PDF로 내보내기" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#을 사용하여 PPT를 PDF로 변환하는 방법" %}}

 PPT를 PDF로 변환하려면 다음을 사용합니다.
 [.NET용 Aspose.Slides](https://products.aspose.com/slides/net)
 기능이 풍부하고 강력하며 사용하기 쉬운 C# 플랫폼용 문서 조작 및 변환 API인 API입니다. 열려 있는
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 패키지 관리자, 검색
 Aspose.슬라이드
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="패키지 관리자 콘솔 명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C#을 통해 PPT를 PDF로 변환하는 단계" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET 개발자는 몇 줄의 코드로 PPT 파일을 PDF로 쉽게 로드하고 변환할 수 있습니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스로 PPT 파일 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
출력 파일 경로 및 SaveFormat.Pdf를 매개변수로 지정하면서 Save 메서드를 호출합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PDF 파일은 지정된 경로에 저장됩니다
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 변환 샘플 소스 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼과 호환되는 OS.
- Microsoft Visual Studio와 같은 개발 환경.
- 프로젝트에서 참조되는 .NET DLL용 Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 PPT에서 PDF로 C# 변환을 보여줍니다." offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a PPT file
var presentation = new Presentation("template.ppt");
// save the presentation as PDF
presentation.Save("output.pdf", SaveFormat.Pdf); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert PPT to PDF" sectionDescription="Check our live demos for [PPT to PDF conversion](https://products.aspose.app/slides/conversion/ppt-to-pdf) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPT file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PDF file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 PowerPoint 및 OpenOffice 프레젠테이션 형식용 프레젠테이션 처리 라이브러리. API를 사용하면 애플리케이션이 .NET C#에서 프레젠테이션을 읽고, 쓰고, 보호하고, 수정하고, 변환할 수 있습니다. 개발자는 이를 사용하여 텍스트, 모양, 차트, 표 및 애니메이션을 관리하고, 슬라이드에 오디오 및 비디오를 추가하고, 슬라이드를 미리 보는 등의 작업을 수행할 수 있습니다.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. PDF files can be opened in Adobe Acrobat Reader/Writer as well in most modern browsers like Chrome, Safari, Firefox via extensions/plug-ins. Most of the commercially available software suites also offer conversion of their documents to PDF file format without the requirement of any additional software component. Thus, PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, digital signatures, attachments, metadata, Geospatial features and 3D objects in it that can become as part of source document.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 PPT를 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="비트맵 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-emf/" name="PPT TO EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-gif/" name="PPT TO GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-html/" name="PPT TO HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="JPEG 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-png/" name="PPT TO PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-pot/" name="PPT TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-potm/" name="PPT TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-potx/" name="PPT TO POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-pps/" name="PPT TO PPS" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-svg/" name="PPT TO SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML 용지 사양" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
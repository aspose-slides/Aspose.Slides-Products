---
title: C++를 통해 PPT 문서 보호 및 잠금
weight: 2570
url: /ko/cpp/protect/ppt/ 
description: Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경에서 암호를 사용하여 PPT 파일을 잠그는 C++ 예제 코드.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C++를 통해 PPT 파일 암호화" h2=".NET 라이브러리를 사용하여 PPT 형식을 포함한 PowerPoint 프레젠테이션을 암호로 보호합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp/" installationsDocsLink="https://docs.aspose.com/slides/cpp/" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++를 사용하여 PPT 파일을 보호하는 방법" %}}

 PPT 파일을 보호하기 위해
 [C++용 Aspose.Slides](https://products.aspose.com/slides/ko/cpp)
 기능이 풍부하고 강력하며 사용하기 쉬운 C++ 플랫폼용 문서 암호화 API인 API입니다. 최신 버전을 직접 다운로드할 수 있습니다.
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 패키지 관리자, 검색
 **Aspose.Slides.Cpp**
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="Aspose.슬라이드" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C++를 통해 PPT 파일을 보호하는 단계" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aspose.Slides API를 사용한 문서 보호는 몇 줄의 코드로 수행할 수 있습니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT 파일 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
get\_ProtectionManager()->Encrypt(.) 메서드를 사용하여 암호 설정
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
보호된 PPT 프레젠테이션 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 C++용 Aspose.Slides는 모든 주요 플랫폼 및 운영 체제를 지원합니다. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경과 호환되는 OS.
- 프로젝트에서 참조되는 C++ DLL용 Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="명령" offSpacer="" %}}

```cs

const String sourceFilePath = u"SourcePath\SourceFile.ppt";
const String outputFilePath = u"OutputPath\OutPutFile.ppt";

// Load the PPT file
SharedPtr<Presentation> pptFile = MakeObject<Presentation>(sourceFilePath);

// Protect with password
pptFile->get_ProtectionManager()->Encrypt(u"password");

// Save the PPT
pptFile->Save(outputFilePath, SaveFormat::Ppt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="C++ API용 Aspose.Slides 정보" %}}

 Aspose.Slides API는 Microsoft PowerPoint 문서를 읽고, 쓰고, 조작하고, PDF, XPS, HTML, TIFF, ODP 및 기타 다양한 형식으로 변환하는 데 사용할 수 있습니다. 처음부터 새 파일을 만들고 지원되는 관련 형식으로 저장할 수 있습니다. Aspose.Slides는 프레젠테이션, 슬라이드 및 요소를 생성, 구문 분석 또는 조작하기 위한 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어에 의존하지 않습니다.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect PPT" sectionDescription="Check our live demos to [encrypt PPT files](https://products.aspose.app/slides/protect/ppt) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload PPT file and hit the \"Unlock\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant PPT file from the link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 보호 문서" subTitle="C++를 사용하면 다음을 포함한 다른 파일을 보호할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/protect/odp/" name="ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/protect/pptx/" name="PPTX" description="Open XML 프레젠테이션 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: C#을 통해 PPS를 BMP로 변환
weight: 1980
url: /ko/net/conversion/pps-to-bmp/ 
description: PPS에서 BMP로의 C# 변환을 위한 샘플 코드입니다. VB.NET, Asp.NET 또는 .NET 기반 응용 프로그램 내에서 일괄 PPS 파일을 BMP로 변환하는 API 예제 코드를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C#을 통해 PPS를 BMP로 변환" h2=".NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 PowerPoint® PPS 파일을 BMP로 내보내기" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#을 사용하여 PPS를 BMP로 변환하는 방법" %}}

 PPS를 BMP로 변환하려면 다음을 사용합니다.
 [.NET용 Aspose.Slides](https://products.aspose.com/slides/ko/net)
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


{{< blocks/products/pf/agp/feature-section-col title="C#을 통해 PPS를 BMP로 변환하는 단계" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET 개발자는 몇 줄의 코드로 PPS 파일을 쉽게 로드하고 BMP로 변환할 수 있습니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스로 PPS 파일 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션의 각 슬라이드를 반복합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
반복할 때마다 전체 크기 이미지를 Bitmap으로 생성
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
BMP 파일 확장자와 ImageFormat.Bmp를 매개변수로 사용하여 Bitmap.Save 메서드를 호출합니다.
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

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 PPS에서 BMP C#으로의 변환을 보여줍니다." offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.pps"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in BMP format
        bitmap.Save(string.Format("Slide_{0}.bmp", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Bmp);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="PPS을 BMP로 변환하는 무료 앱" 
        sectionDescription="[PPT을 BMP로 변환하려면 무료 앱을 사용해보십시오.](https://products.aspose.app/slides/conversion/ppt-to-bmp)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 PPS를 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-emf/" name="PPS TO EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-gif/" name="PPS TO GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-html/" name="PPS TO HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="JPEG 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-odp/" name="PPS TO ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-pdf/" name="PPS TO PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-png/" name="PPS TO PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-pot/" name="PPS TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-potm/" name="PPS TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-potx/" name="PPS TO POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-ppt/" name="PPS TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-svg/" name="PPS TO SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-swf/" name="PPS TO SWF" description="SWF 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-tiff/" name="PPS TO TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pps-to-xps/" name="PPS TO XPS" description="XML 용지 사양" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: C#에서 이미지를 PDF로 변환
weight: 30
url: /ko/net/conversion/image-to-pdf/ 
keywords: 이미지를 PDF로, 이미지를 PDF로 변환, C# API, .NET 라이브러리, 이미지, JPG, PNG, PDF
description: C#에서 이미지를 PDF로 변환합니다. .NET 라이브러리 API를 사용하여 이미지를 PDF 문서로 변환합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C#에서 이미지를 PDF로 변환" h2="NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 이미지를 PDF 문서로 변환하기 위한 PowerPoint .NET API" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="jpg" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}


{{% blocks/products/pf/agp/content h2="C#에서 이미지를 PDF로 변환하는 방법" %}}

프로그래밍 방식으로 이미지를 PDF로 변환하려면 어떻게 해야 합니까?

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)을 사용하면 모든 개발자 또는 응용 프로그램에서 몇 줄의 C# 코드로 이미지를 PDF 형식으로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for .NET은 JPG 또는 PNG 이미지에서 PDF를 빠르게 생성합니다. Aspose PowerPoint 라이브러리를 사용하면 이미지를 PDF 및 기타 여러 파일 형식으로 변환할 수 있습니다.

Aspose.Slides를 설치하려면: [NuGet](https://www.nuget.org/packages/aspose.slides.net) 패키지 관리자를 엽니다. *Aspose.Slides*를 검색하여 설치합니다.
 
또는 패키지 관리자 콘솔에서 이 명령을 실행하여 **Aspose.Slides**를 설치할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="패키지 관리자 콘솔 명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C#에서 이미지를 PDF로 변환하는 단계" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="개발자와 응용 프로그램은 다음과 같은 방법으로 이미지를 PDF로 변환할 수 있습니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
이미지를 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
액자를 추가합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
파일을 PDF로 저장하려면 save 메소드를 호출하십시오.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 이미지를 PDF로 변환 C# 코드를 실행하기 전에 컴퓨터에 다음과 같은 전제 조건이 있어야 합니다.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼과 호환되는 OS.
- Microsoft Visual Studio와 같은 개발 환경.
- .NET DLL용 Aspose.Slides가 프로젝트에서 참조되었습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이미지를 PDF로 변환하는 C# 코드" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes(imagePath));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("image.pdf", SaveFormat.Pdf);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="무료 온라인 변환기" sectionDescription="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/python-net/conversion/ppt-to-html/)" >}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->
    
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="Aspose.Slides는 다양한 파일 형식에 대한 변환 작업을 지원합니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmap Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-png/" name="PPT TO PNG" description="PNG Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-png/" name="PPT TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Open XML presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-svg/" name="PPT TO SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Tagged Image Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML Paper Specifications" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
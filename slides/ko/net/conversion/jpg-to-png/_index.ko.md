---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C#에서 JPG를 PNG로 변환
weight: 220
url: /ko/net/conversion/jpg-to-png/ 
keywords: JPG를 PNG로, JPG를 PNG로 변환, C# API, .NET 라이브러리
description: C#에서 JPG를 PNG로 변환합니다. .NET 라이브러리 API를 사용하여 JPG를 PNG 파일로 변환합니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#에서 JPG를 PNG로 변환" h2="NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 JPG를 PNG 이미지 파일로 변환하기 위한 PowerPoint .NET API"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#에서 JPG를 PNG로 변환" %}}

코드에서 JPG를 PNG로 어떻게 변환합니까?

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)을 사용하면 모든 개발자나 응용 프로그램이 몇 줄의 C# 코드로 JPG를 PNG로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for .NET은 JPG 파일을 PNG로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 JPG를 PNG로 변환하고 이미지를 다른 형식으로 변환할 수 있습니다.

Aspose.Slides를 설치하려면: [NuGet](https://www.nuget.org/packages/aspose.slides.net) 패키지 관리자를 엽니다. Aspose.Slides를 검색하여 설치합니다.
 
또는 패키지 관리자 콘솔에서 이 명령을 실행하여 **Aspose.Slides**를 설치할 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="패키지 관리자 콘솔 명령" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="JPG를 PNG로 변환하는 C# 코드" >}}
```cs
using (Presentation pres = new Presentation())
    {
        IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
        pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

        pres.Slides[0].GetThumbnail(new Size(960, 720)).Save($"image.png", ImageFormat.png);
    }
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#에서 JPG를 PNG로 변환하는 방법" intro="개발자와 응용 프로그램은 다음과 같은 방법으로 JPG를 PNG로 변환할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스를 만듭니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JPG 이미지를 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}액자를 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}파일을 PNG 이미지로 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="JPG에서 PNG로 변환 C# 코드를 실행하기 전에 컴퓨터에 다음과 같은 전제 조건이 있어야 합니다." %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼과 호환되는 OS.
- Microsoft Visual Studio와 같은 개발 환경.
- .NET DLL용 Aspose.Slides가 프로젝트에서 참조되었습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="무료 온라인 변환기"
  description="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 변환" subTitle="Aspose.Slides는 다양한 파일 형식에 대한 변환 작업을 지원합니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmap Image" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="JPEG Image" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-png/" name="PPT TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Open XML presentation Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-svg/" name="PPT TO SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Tagged Image Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML Paper Specifications" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

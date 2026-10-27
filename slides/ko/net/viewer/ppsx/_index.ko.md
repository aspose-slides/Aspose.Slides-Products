---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C#에서 PPSX 보기
keywords: PPSX 보기, PPSX 열기, PPSX 뷰어, PPSX, PowerPoint, C# API, .NET 라이브러리
weight: 2370
url: /ko/net/viewer/ppsx/ 
description: C#에서 PPSX 파일을 확인하세요. Aspose.Slides for .NET으로 프레젠테이션 파일을 열고 HTML로 저장할 수 있습니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#에서 PPSX 보기" h2="PPSX 파일을 열고 반응형 HTML로 저장하는 C# API."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides로 PPSX 보기" %}}

PPSX 파일을 보려면 강력하고 사용하기 쉬운 C#용 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net/)을 사용하세요. [NuGet](https://www.nuget.org/packages/aspose.slides.net) 패키지 관리자를 열고 **Aspose.Slides**를 검색하여 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 실행할 수도 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="패키지 관리자 콘솔 명령" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

[**Aspose.Slides for .NET**](/slides/ko/net/)를 사용하면 몇 줄의 코드로 PPSX 파일을 로드하고 반응형 HTML로 저장할 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX를 보는 C# 코드" >}}
```cs
using var presentation = new Presentation("presentation.ppsx");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#에서 PPSX를 보는 방법" intro="Aspose.Slides를 사용하면 몇 줄의 코드만으로 PPSX 파일을 볼 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET**를 설치합니다. [**설치**](https://docs.aspose.com/slides/net/installation/)를 참조하세요.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}프로젝트에 라이브러리를 참조로 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 `PPSX` 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}반응형 HTML 출력을 위해 `ResponsiveHtmlController` 객체를 만듭니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`HtmlOptions` 객체를 만들고 `HtmlFormatter` 속성을 설정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Html`을 사용하여 PPSX 파일을 HTML로 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="Aspose.Slides for .NET은 모든 주요 운영 체제를 지원합니다. 다음 필수 조건을 갖추었는지 확인하세요." %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Windows Azure, Mono, Xamarin을 지원하는 OS
- Microsoft Visual Studio와 같은 개발 환경
- 프로젝트에서 Aspose.Slides for .NET 참조

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Aspose.Slides로 구축" title="온라인에서 PPSX 파일 보기" description="무료 Aspose.Slides Viewer 앱은 위 코드와 동일한 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net/)로 구축되었습니다. 앱을 열고 내 PPSX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Viewer 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 렌더링하는지 확인하세요.
- PPSX 파일을 업로드하고 슬라이드를 바로 확인하세요.
- PowerPoint 없이 데스크톱과 모바일에서 작동합니다.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

PPSX 파일은 Microsoft PowerPoint 2007 이상에서 만든 Open XML 형식의 PowerPoint 슬라이드 쇼입니다. PowerPoint 97–2003에서 사용하는 PPS 형식의 Open XML 기반 후속 형식입니다. 기본적으로 편집 모드로 열리는 PPTX 파일과 달리 PPSX 파일은 바로 슬라이드 쇼로 열립니다. 프레젠테이션의 슬라이드 순서를 유지하며 이미지, 오디오 및 기타 포함된 미디어를 담을 수 있습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="다른 파일 보기" subTitle="다른 형식의 프레젠테이션도 열고 볼 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/odp/" name="ODP" description="OpenDocument 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/otp/" name="OTP" description="OpenDocument 프레젠테이션 서식 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/pot/" name="POT" description="PowerPoint 97-2003 서식 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/potm/" name="POTM" description="PowerPoint 매크로 사용 서식 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/potx/" name="POTX" description="PowerPoint 서식 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/pps/" name="PPS" description="PowerPoint 97-2003 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/ppsm/" name="PPSM" description="PowerPoint 매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/ppt/" name="PPT" description="PowerPoint 97-2003 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/pptm/" name="PPTM" description="PowerPoint 매크로 사용 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/viewer/pptx/" name="PPTX" description="PowerPoint 프레젠테이션" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

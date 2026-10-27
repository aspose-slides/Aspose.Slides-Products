---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1480
title: .NET으로 PPTX 파일에서 텍스트 추출
url: /ko/net/parser/pptx/ 
description: .NET으로 PPTX 파일에서 텍스트를 추출하는 C# 소스 코드.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#으로 PPTX 파일 구문 분석" h2="서버 측 .NET API로 PPTX 파일에서 텍스트를 추출하고 텍스트 서식을 확인하세요."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#으로 PPTX 파일 구문 분석하기" %}}

[Aspose.Slides for .NET](/slides/ko/net/)을 사용하여 PPTX 프레젠테이션에서 텍스트를 추출하세요. [NuGet](https://www.nuget.org/packages/aspose.slides.net)에서 패키지를 설치하거나 패키지 관리자 콘솔에서 다음 명령을 실행하세요.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="명령" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX 파일 구문 분석 - C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#에서 PPTX 파일을 구문 분석하는 방법" intro="[Aspose.Slides for .NET](/slides/ko/net/) API를 사용한 기본 문서 구문 분석은 몇 줄의 코드만으로 가능합니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation`으로 PPTX 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.GetAllTextFrames`로 텍스트 프레임을 가져옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}텍스트 프레임, 단락, 텍스트 부분을 순회합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}필요에 따라 `Text`, `FontHeight`, `LatinFont.FontName` 속성을 읽습니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="지원되는 .NET 런타임과 Aspose.Slides for .NET 패키지 참조가 필요합니다. Visual Studio 또는 호환되는 다른 C# 개발 환경을 사용할 수 있습니다." %}}

- .NET Framework, .NET, Mono 또는 Xamarin 호환 환경
- Visual Studio와 같은 C# 개발 환경
- NuGet에서 설치한 Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides로 구축" title="온라인에서 텍스트와 이미지 추출" description="무료 Aspose.Slides Parser 앱은 위 코드와 동일한 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net/)로 구축되었습니다. 앱을 열고 내 PPTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Parser 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 읽는지 확인하세요.
- PPTX 파일을 업로드하고 텍스트와 이미지를 받으세요.
- 모든 결과를 하나의 ZIP 아카이브로 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

PPTX 파일은 Microsoft PowerPoint로 만든 프레젠테이션입니다. 바이너리 형식인 PPT와 달리 PPTX는 Office Open XML 형식을 사용합니다. 프레젠테이션에는 텍스트, 이미지, 서식, 애니메이션 및 기타 미디어가 포함된 슬라이드가 들어 있으며 슬라이드 쇼로 표시됩니다.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 구문 분석 형식" subTitle="C#으로 다음 형식도 구문 분석할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/parser/odp/" name="ODP" description="OpenDocument 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/parser/ppt/" name="PPT" description="PowerPoint 97-2003 프레젠테이션" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

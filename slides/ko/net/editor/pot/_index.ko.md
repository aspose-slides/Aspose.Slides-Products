---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET을 통해 POT 파일 편집
url: /ko/net/editor/pot/ 
description: .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 POT 문서를 편집하는 C# 소스 코드.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#에서 POT 형식 편집" h2="Microsoft 또는 Adobe PDF와 같은 소프트웨어를 사용하지 않고 .NET API용 서버측 Aspose.Slides를 사용하여 기본 및 고성능 POT 문서 편집."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#을 사용하여 POT 파일을 편집하는 방법" %}}

POT 파일을 편집하기 위해 우리는 기능이 풍부하고 강력한 <a href="https://products.aspose.com/slides/ko/net">Aspose.Slides for .NET</a> API를 사용할 것입니다. 모든 편집기에서 사용하기 쉬운 C# 플랫폼용 API입니다. <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> 패키지 관리자를 열고 <b>Aspose.Slides</b>를 검색하여 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="명령" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="POT 파일 편집 - C#" >}}
```cs
using var presentation = new Presentation("document.pot");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.pot", SaveFormat.Pot);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#에서 POT 파일을 편집하는 단계" intro="기본 문서 편집 [.NET용 Aspose.Slides](https://products.aspose.com/slides/ko/net) API는 몇 줄의 코드로 수행할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 개체로 POT 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}변수를 통해 대상 슬라이드와 도형에 액세스합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`TextFrame`을 통해 텍스트를 업데이트합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Pot`로 편집한 프레젠테이션을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="당사의 API는 모든 주요 플랫폼 및 운영 체제에서 지원됩니다. 아래 코드를 실행하기 전에 시스템에 다음 전제 조건이 있는지 확인하십시오." %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼과 호환되는 OS
- Microsoft Visual Studio와 같은 개발 환경
- 프로젝트에서 참조하는 .NET DLL용 Aspose.Slides - 위의 다운로드 버튼을 사용하여 NuGet에서 설치

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" %}}

Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Files created with these versions of Microsoft PowerPoint are in binary format as compared to those created in Office OpenXML file formats using the higher versions of PowerPoint. The files, hence, generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

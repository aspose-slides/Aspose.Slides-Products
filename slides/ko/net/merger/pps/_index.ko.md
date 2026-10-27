---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET을 통해 PPS 파일 병합
weight: 5830
url: /ko/net/merger/pps/ 
description: .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 PPS 문서를 결합하는 C# 소스 코드.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#에서 PPS 형식 병합" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고 .NET API용 서버측 Aspose.Slides를 사용하여 기본 및 고성능 PPS 문서 병합."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#을 사용하여 PPS 파일을 병합하는 방법" %}}

PPS 파일을 병합하려면 다음을 사용합니다.
 [.NET용 Aspose.Slides](https://products.aspose.com/slides/ko/net)
 기능이 풍부하고 강력하며 사용하기 쉬운 문서 조작 및 병합 API인 C# 플랫폼용 API입니다. 열려 있는
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 패키지 관리자, 검색
 **아포즈.슬라이드**
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="명령" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPS 파일 병합 - C#" >}}
```cs
var ps1 = new Presentation("presen1.pps");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPS presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#에서 PPS 파일 병합 단계" intro="[Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net) API로 기본 문서 병합 및 연결을 몇 줄의 코드로 수행할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}전체 경로로 모든 PPS 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}하나의 문서를 기본 파일로 만들기{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}파일을 하나씩 연결하고 병합하는 해당 메서드를 호출합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save() 메서드를 호출하고 파일 이름(전체 경로) 및 형식(PPS)을 매개 변수로 전달합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}이제 Microsoft Office, Adobe PDF 또는 기타 호환 프로그램에서 PPS 파일을 열고 사용할 수 있습니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="당사의 API는 모든 주요 플랫폼 및 운영 체제에서 지원됩니다. 아래 코드를 실행하기 전에 시스템에 다음 전제 조건이 있는지 확인하십시오." %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼과 호환되는 OS
- Microsoft Visual Studio와 같은 개발 환경
- 프로젝트에서 참조하는 .NET DLL용 Aspose.Slides - 위의 다운로드 버튼을 사용하여 NuGet에서 설치

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Aspose.Slides로 구축" title="온라인에서 PPS 파일 병합" description="무료 Aspose.Slides Merger 앱은 위 코드와 동일한 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net/)로 구축되었습니다. 앱을 열고 내 PPS 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Merger 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 병합하는지 확인해 보세요.
- 여러 PPS 파일을 업로드하고 하나로 합치세요.
- 병합된 결과를 하나의 파일로 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

PPS(PowerPoint 슬라이드 쇼)는 PowerPoint 97–2003에서 사용하는 바이너리 슬라이드 쇼 형식입니다. PPSX는 Office Open XML 표준을 기반으로 하는 최신 슬라이드 쇼 형식입니다. 현재 버전의 PowerPoint에서도 PPS 파일을 열 수 있으며 프레젠테이션을 여전히 PPS 형식으로 저장할 수 있습니다. 일반적인 방법으로 열면 PPS 파일은 슬라이드 쇼 모드로 시작되고 PPT 파일은 편집 모드로 열립니다.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 병합 형식" subTitle="C#을 사용하여 One은 다음을 포함한 많은 다른 파일 형식을 병합할 수도 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/odp/" name="ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/otp/" name="OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/pot/" name="POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/potm/" name="POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/potx/" name="POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/ppsm/" name="PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/ppsx/" name="PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/ppt/" name="PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/pptm/" name="PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/merger/pptx/" name="PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

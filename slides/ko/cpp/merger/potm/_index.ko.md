---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++를 통해 POTM 파일 병합
weight: 7950
url: /ko/cpp/merger/potm/ 
description: Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경에서 POTM 문서를 결합하는 C++ 예제 코드.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++를 사용하여 POTM 파일 병합" h2="서버측 C++ API를 사용한 POTM 문서 병합."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++를 사용하여 POTM 파일을 병합하는 방법" %}}

POTM 파일을 병합하려면 다음을 사용합니다.
 [C++용 Aspose.Slides](https://products.aspose.com/slides/ko/cpp/)
 기능이 풍부하고 강력하며 사용하기 쉬운 C++ 플랫폼용 문서 병합 API인 API입니다. 최신 버전을 직접 다운로드할 수 있습니다.
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 패키지 관리자, 검색
 **Aspose.Slides.Cpp**
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="명령" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM 파일 병합 - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.potm";
const String sourceFilePath2 = u"SourceFile3.potm";
const String outputFilePath = u"mergedOutput.potm";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Potm);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++에서 POTM 파일 병합 단계" intro="[Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/) API로 기본 문서 병합 및 연결을 몇 줄의 코드로 수행할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}두 POTM 파일을 모두 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}get\_Slides() 메서드를 사용하여 각 슬라이드를 반복합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}AddClone 기능을 사용하여 원하는 파일과 병합합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save() 메서드를 사용하여 지정된 경로에 저장{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="C++용 Aspose.Slides는 모든 주요 플랫폼 및 운영 체제를 지원합니다. 다음 전제 조건이 있는지 확인하십시오." %}}

- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경과 호환되는 OS.
- 프로젝트에서 참조되는 C++ DLL용 Aspose.Slides.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Aspose.Slides로 구축" title="온라인에서 POTM 파일 병합" description="무료 Aspose.Slides Merger 앱은 위 코드와 동일한 API인 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/)로 구축되었습니다. 앱을 열고 내 POTM 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Merger 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 병합하는지 확인해 보세요.
- 여러 POTM 파일을 업로드하고 하나로 합치세요.
- 병합된 결과를 하나의 파일로 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

확장자가 `.POTM`인 파일은 PowerPoint 2007과 함께 도입된 매크로 지원 Microsoft PowerPoint 템플릿입니다. 레이아웃, 스타일, 배경, 색상표, 글꼴, 기본 서식, VBA 매크로 등 재사용 가능한 프레젠테이션 설정을 저장할 수 있습니다. PowerPoint 2007 이상에서 POTM 파일을 열고 편집할 수 있습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 병합 형식" subTitle="C++를 사용하면 ..를 포함한 다른 많은 파일 형식을 병합할 수도 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/odp/" name="ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/otp/" name="OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/pot/" name="POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/potx/" name="POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/pps/" name="PPS" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/ppsm/" name="PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/ppsx/" name="PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/ppt/" name="PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/pptm/" name="PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/merger/pptx/" name="PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

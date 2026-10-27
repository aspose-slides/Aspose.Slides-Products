---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 460
title: C++로 ODP 프레젠테이션에서 텍스트 추출
url: /ko/cpp/parser/odp/ 
description: C++에서 ODP 프레젠테이션의 텍스트를 추출하세요. Aspose.Slides for C++로 슬라이드, 텍스트 프레임, 단락, 텍스트 부분을 구문 분석할 수 있습니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++에서 ODP 프레젠테이션 구문 분석" h2="Aspose.Slides for C++를 사용하면 Microsoft PowerPoint 없이 프레젠테이션 슬라이드에서 텍스트를 추출할 수 있습니다."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++로 ODP 파일 구문 분석하기" %}}

Aspose.Slides for C++를 사용하여 ODP 프레젠테이션 파일을 구문 분석하고 슬라이드에서 텍스트를 추출하세요. 이 API는 `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph`, `IPortion`을 통해 슬라이드 텍스트를 제공하므로 Microsoft PowerPoint를 자동화하지 않고도 텍스트를 읽을 수 있습니다. NuGet에서 [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) 패키지를 설치하거나 패키지 관리자 콘솔에서 아래 명령을 사용하세요.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="명령" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP 파일 구문 분석 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++에서 ODP 파일을 구문 분석하는 방법" intro="Aspose.Slides for C++로 ODP 파일에서 텍스트를 추출하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 ODP 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil::GetAllTextBoxes`로 첫 번째 슬라이드의 `ITextFrame` 객체를 가져옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ITextFrame` 객체를 순회합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 `ITextFrame`의 `IParagraph` 객체를 순회합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 `IParagraph`의 `IPortion` 객체를 순회합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_Text`로 텍스트를 읽습니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="Aspose.Slides for C++는 주요 데스크톱 및 서버 플랫폼을 지원합니다. 프로젝트가 다음 필수 조건을 충족하는지 확인하세요." %}}

-  지원되는 C++ 런타임이 있는 Microsoft Windows, Linux, macOS 또는 기타 호환 운영 체제.
-  프로젝트에서 참조하는 Aspose.Slides for C++ 라이브러리.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides로 구축" title="온라인에서 텍스트와 이미지 추출" description="무료 Aspose.Slides Parser 앱은 위 코드와 동일한 API인 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/)로 구축되었습니다. 앱을 열고 내 ODP 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Parser 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 읽는지 확인하세요.
- ODP 파일을 업로드하고 텍스트와 이미지를 받으세요.
- 모든 결과를 하나의 ZIP 아카이브로 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP 파일은 OpenOffice Impress, LibreOffice Impress 같은 애플리케이션에서 사용하는 OpenDocument 프레젠테이션 파일입니다. 슬라이드, 텍스트, 이미지, 서식, 애니메이션 및 기타 프레젠테이션 콘텐츠를 개방형 XML 기반 패키지에 저장합니다.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 구문 분석 형식" subTitle="C++로 다른 프레젠테이션 형식도 구문 분석할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/parser/ppt/" name="PPT" description="PowerPoint 97-2003 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/parser/pptx/" name="PPTX" description="PowerPoint Open XML 프레젠테이션" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

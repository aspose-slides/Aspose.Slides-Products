---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++로 PPT 프레젠테이션에서 텍스트 검색
url: /ko/cpp/search/ppt/
description: C++로 PPT 프레젠테이션의 텍스트를 검색하세요. Aspose.Slides for C++를 사용해 프레젠테이션 파일에서 텍스트를 찾을 수 있습니다.
keywords: PPT에서 단어 검색, PPT에서 텍스트 찾기, PPT 프레젠테이션 텍스트 검색
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++로 PPT에서 텍스트 검색" h2="Aspose.Slides for C++를 사용하면 Microsoft PowerPoint 없이 프레젠테이션 파일에서 텍스트를 찾을 수 있습니다." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++를 통한 PPT 프레젠테이션 텍스트 검색" variant="code" %}}

Aspose.Slides for C++를 사용하면 PPT 프레젠테이션에서 텍스트를 검색할 수 있습니다. `SlideUtil::GetAllTextBoxes`로 슬라이드의 텍스트 프레임을 수집한 다음 텍스트에 필요한 문구가 있는지 확인하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++를 사용한 PPT 프레젠테이션 텍스트 검색" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++로 PPT에서 텍스트를 검색하는 방법" intro="PPT 프레젠테이션에서 텍스트를 검색하려면 다음 단계를 따르세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 PPT 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation::get_Slides`로 필요한 슬라이드를 가져오고 [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/)로 텍스트 프레임을 가져옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 프레임의 텍스트에 필요한 문구가 있는지 확인합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides로 구축" title="PPT 파일 온라인 텍스트 검색" description="무료 Aspose.Slides Search 앱은 위 코드와 동일한 API인 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/)로 구축되었습니다. 앱을 열고 내 PPT 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Search 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 텍스트를 찾는 방식을 확인하세요.
- PPT 파일에서 일반 텍스트나 정규식으로 검색하세요.
- 검색 결과를 텍스트 파일로 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="검색을 지원하는 기타 형식" subTitle="C++로 다음 형식에서도 텍스트를 검색할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: C++로 ODP 주석 제거
url: /ko/cpp/annotation/odp/ 
description: ODP 프레젠테이션에서 주석을 제거하는 C++ 소스 코드입니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++에서 ODP의 메모 및 메모 작성자 제거" h2="서버 측 API를 사용하여 프레젠테이션 파일의 메모와 작성자를 다루는 C++ 앱을 빌드하세요." related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++로 ODP에서 메모 제거" variant="code" %}}

[Aspose.Slides for C++](/slides/ko/cpp/)를 사용하여 ODP 프레젠테이션에서 메모와 메모 작성자를 제거하세요. 아래 예제는 `get_CommentAuthors`에서 가져온 각 작성자의 메모를 지운 다음 메모 작성자 컬렉션을 비웁니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP에서 주석 삭제 – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.odp");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++로 ODP에서 메모를 제거하는 방법" intro="ODP 프레젠테이션에서 메모와 메모 작성자를 제거하려면 다음 단계를 따르세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for C++를 설치합니다. [설치](https://docs.aspose.com/slides/cpp/installation/)를 참조하세요.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 ODP 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_CommentAuthors`에서 가져온 메모 작성자를 반복합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_Comments()->Clear()`로 각 작성자의 메모를 지웁니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}메모 작성자 컬렉션을 비웁니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat::Odp`로 업데이트된 프레젠테이션을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides로 구축" title="온라인에서 ODP 메모 제거" description="무료 Aspose.Slides Annotation 앱은 위 코드와 동일한 API인 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/)로 구축되었습니다. 앱을 열고 내 ODP 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Annotation 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 메모를 제거하는 방식을 확인하세요.
- ODP 파일의 모든 메모를 제거합니다.
- 정리된 파일을 다운로드합니다.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="주석에 지원되는 기타 형식" subTitle="C++를 사용하면 다른 형식에서도 주석을 제거할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

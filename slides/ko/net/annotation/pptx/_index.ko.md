---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: .NET으로 PPTX 주석 제거
url: /ko/net/annotation/pptx/ 
description: C#에서 PPTX 프레젠테이션의 메모와 메모 작성자를 제거합니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#에서 PPTX의 메모 및 메모 작성자 제거" h2="서버 측 API를 사용하여 프레젠테이션 파일의 메모와 작성자를 다루는 .NET 애플리케이션을 빌드하세요." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#으로 PPTX에서 메모 제거" variant="code" %}}

[Aspose.Slides for .NET](/slides/ko/net/)을 사용하여 PPTX 프레젠테이션 파일에서 메모와 메모 작성자를 제거하세요. 아래 예제는 각 작성자의 `Comments` 컬렉션을 비운 다음 프레젠테이션의 `CommentAuthors` 컬렉션을 비웁니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX에서 주석 삭제 – C#" >}}
```cs
using var presentation = new Presentation("example.pptx");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#으로 PPTX에서 메모를 제거하는 방법" intro="PPTX 프레젠테이션에서 메모와 메모 작성자를 제거하려면 다음 단계를 따르세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for .NET을 설치합니다. [설치](https://docs.aspose.com/slides/net/installation/)를 참조하세요.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 PPTX 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`CommentAuthors` 컬렉션을 반복합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 메모 작성자의 `Comments` 컬렉션을 비웁니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`CommentAuthors` 컬렉션을 비웁니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Pptx`로 업데이트된 프레젠테이션을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides로 구축" title="온라인에서 PPTX 메모 제거" description="무료 Aspose.Slides Annotation 앱은 위 코드와 동일한 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net/)로 구축되었습니다. 앱을 열고 내 PPTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Annotation 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 메모를 제거하는 방식을 확인하세요.
- PPTX 파일의 모든 메모를 제거합니다.
- 정리된 파일을 다운로드합니다.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="주석에 지원되는 기타 형식" subTitle="C#을 사용하면 다른 형식에서도 주석을 제거할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++에서 HTML 편집
url: /ko/cpp/editor/html/
keywords: HTML, HTML, C++ API, C++ 라이브러리 편집
description: C++에서 HTML을 편집합니다. C++ 라이브러리 API를 사용하여 HTML 파일 편집
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++에서 HTML 편집" h2="C++ 코드를 사용하여 HTML을 편집하기 위한 고속 및 교차 플랫폼 C++ 라이브러리" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++에서 HTML 편집" variant="code" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ko/cpp/)를 사용하면 몇 줄의 코드만으로 HTML 문서에 새로운 텍스트 줄을 추가할 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML 편집을 위한 C++ 코드" >}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromHtml(htmlText1);

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"page.html", SaveFormat::Html5);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides를 사용하여 HTML 편집" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ko/cpp/)는 프레젠테이션, HTML 문서 및 기타 파일을 조작하고 편집하는 데 사용되는 강력한 C++ 라이브러리입니다. 새 텍스트 줄을 추가하여 HTML 문서를 편집할 수 있습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++에서 HTML을 편집하는 방법" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for C++**를 설치합니다. [**설치**](https://docs.aspose.com/slides/cpp/installation/)를 참조하세요.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}프로젝트에서 라이브러리를 참조로 추가하십시오.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스를 만듭니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}편집할 HTML 문서를 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}새 텍스트 줄을 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}변경된 HTML 파일을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="다른 파일 편집" subTitle="다른 형식의 파일도 편집할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C#에서 PDF 편집
url: /ko/net/editor/pdf/
keywords: PDF, PDF, C# API, .NET 라이브러리 편집
description: C#에서 PDF를 편집합니다. .NET 라이브러리 API를 사용하여 PDF 문서 편집
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#에서 PDF 편집" h2="NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 C# 코드를 사용하여 PDF를 편집하기 위한 강력한 크로스 플랫폼 .NET API" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#에서 PDF 편집" variant="code" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)을 사용하면 단 몇 줄의 코드만으로 PDF 문서에 새로운 텍스트 줄을 추가할 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PDF 편집을 위한 C# 코드" >}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides를 사용하여 PDF 편집" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)은 프레젠테이션, PDF 문서 및 기타 파일을 조작하고 편집하는 데 사용되는 강력한 .NET 라이브러리입니다. 새 텍스트 줄을 추가하여 PDF 문서를 편집할 수 있습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#에서 PDF를 편집하는 방법" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET**을 설치합니다. [**설치**](https://docs.aspose.com/slides/net/installation/)를 참조하세요.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}프로젝트에서 라이브러리를 참조로 추가하십시오.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스를 만듭니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}편집하려는 PDF 문서를 불러옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}새 텍스트 줄을 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}변경된 PDF 파일을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="다른 파일 편집" subTitle="다른 형식의 파일도 편집할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

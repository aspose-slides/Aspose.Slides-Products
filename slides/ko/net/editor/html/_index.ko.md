---
title: C#에서 HTML 편집
url: /ko/net/editor/html/
keywords: HTML, HTML, C# API, .NET 라이브러리 편집
description: C#에서 HTML을 편집합니다. .NET 라이브러리 API를 사용하여 HTML 파일 편집
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C#에서 HTML 편집" h2="NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 C# 코드를 사용하여 HTML을 편집하기 위한 강력한 크로스 플랫폼 .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides를 사용하여 HTML 편집" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)은 프레젠테이션, HTML 문서 및 기타 파일을 조작하고 편집하는 데 사용되는 강력한 .NET 라이브러리입니다. 새 텍스트 줄을 추가하여 HTML 문서를 편집할 수 있습니다. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C#에서 HTML 편집" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)을 사용하면 몇 줄의 코드만으로 HTML 문서에 새로운 텍스트 줄을 추가할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="HTML 편집을 위한 C# 코드" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide
    pres.Slides.AddFromHtml("page.html");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("page.html", SaveFormat.Html);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C#에서 HTML을 편집하는 방법" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET**을 설치합니다. [**설치**](https://docs.aspose.com/slides/net/installation/)를 참조하세요.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프로젝트에서 라이브러리를 참조로 추가하십시오.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
편집할 HTML 문서를 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
새 텍스트 줄을 추가합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
변경된 HTML 파일을 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="다른 파일 편집" subTitle="다른 형식의 파일도 편집할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
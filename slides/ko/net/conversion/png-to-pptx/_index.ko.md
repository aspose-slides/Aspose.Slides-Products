---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C#에서 PNG를 PPTX로 변환
url: /ko/net/conversion/png-to-pptx/
keywords: PNG를 PPTX로, PNG를 PPTX로, PowerPoint, PNG, PPTX, C# API, .NET 라이브러리로 변환
description: C#에서 PNG를 PPTX로 변환합니다. .NET 라이브러리 API를 사용하여 PNG 이미지를 PowerPoint로 변환
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#에서 PNG를 PPTX로 변환" h2="NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 C# 코드를 사용하여 PNG를 PPTX로 변환하기 위한 강력한 크로스 플랫폼 .NET API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#에서 PNG를 PPTX로 변환" variant="code" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)을 사용하면 몇 줄의 코드만으로 PNG 이미지를 PowerPoint 프레젠테이션으로 변환할 수 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PNG를 PPTX로 변환하기 위한 C# 코드" >}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.pptx", SaveFormat.Pptx);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides를 사용하여 PNG를 PPTX로 변환" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)은 PowerPoint 프레젠테이션, PDF, HTML 문서, 및 기타 파일. PNG를 PPTX로 변환하면 본질적으로 PNG 이미지를 기반으로 하는 슬라이드가 포함된 PowerPoint 프레젠테이션을 만드는 것입니다.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#에서 PNG를 PPTX로 변환하는 방법" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET**을 설치합니다. [**설치**](https://docs.aspose.com/slides/net/installation/)를 참조하세요.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}프로젝트에서 라이브러리를 참조로 추가하십시오.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스를 만듭니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX로 변환할 PNG 이미지를 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}결과 파일을 PPTX 프레젠테이션으로 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="무료 온라인 변환기"
  description="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 PowerPoint 변환" subTitle="다른 형식의 파일을 PowerPoint로 변환할 수도 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

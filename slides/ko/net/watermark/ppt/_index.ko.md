---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C#으로 PPT 프레젠테이션에 워터마크 추가
url: /ko/net/watermark/ppt/
description: Aspose.Slides for .NET으로 C#에서 PPT 프레젠테이션에 텍스트 및 이미지 워터마크를 추가하세요.
keywords: PPT에 워터마크 추가, PPT에 텍스트 워터마크 추가, PPT에 이미지 워터마크 추가
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C#으로 PPT 프레젠테이션에 워터마크 추가하기" h2="프레젠테이션 파일에 텍스트 또는 이미지 워터마크를 삽입하는 .NET 애플리케이션을 구축하세요." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C#을 통해 PPT 프레젠테이션에 워터마크 추가" variant="code" %}}

[Aspose.Slides for .NET](/slides/ko/net/)을 사용하면 PPT 프레젠테이션에 텍스트 및 이미지 워터마크를 추가할 수 있습니다. 슬라이드 마스터에 워터마크 도형을 추가하면 해당 마스터를 사용하는 슬라이드에 워터마크가 표시됩니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#으로 PPT에 텍스트 워터마크 추가" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C#으로 PPT 프레젠테이션에 이미지 워터마크 추가" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#으로 PPT에 워터마크를 추가하는 방법" intro="다음 단계에 따라 PPT 파일에 텍스트 또는 이미지 워터마크를 추가하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 `PPT` 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation.Masters` 컬렉션에서 슬라이드 마스터를 선택합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddAutoShape` 메서드를 호출하여 워터마크 도형을 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddTextFrame` 메서드를 호출하여 워터마크 텍스트를 추가하거나 이미지 워터마크에는 `AddImage`를 사용합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Ppt`로 워터마크가 적용된 파일을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides로 구축" title="온라인에서 PPT 파일에 워터마크 추가" description="무료 Aspose.Slides Watermark 앱은 위 코드와 동일한 API인 [Aspose.Slides for .NET](https://products.aspose.com/slides/ko/net/)로 구축되었습니다. 앱을 열고 내 PPT 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Watermark 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 워터마크를 어떻게 추가하는지 확인하세요.
- PPT 파일에 텍스트 또는 이미지 워터마크를 추가하세요.
- 워터마크가 적용된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="워터마크를 지원하는 기타 형식" subTitle="C#으로 다음 형식에도 워터마크를 추가할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

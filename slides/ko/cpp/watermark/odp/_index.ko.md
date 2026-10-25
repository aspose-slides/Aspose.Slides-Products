---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++로 ODP 프레젠테이션에 워터마크 추가
url: /ko/cpp/watermark/odp/
description: C++에서 ODP 프레젠테이션에 텍스트 또는 이미지 워터마크를 추가하세요. Aspose.Slides for C++로 슬라이드에 워터마크를 배치할 수 있습니다.
keywords: ODP에 워터마크 추가, ODP에 텍스트 워터마크 추가, ODP에 이미지 워터마크 추가
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++로 ODP 프레젠테이션에 워터마크 추가하기" h2="Aspose.Slides for C++를 사용하면 Microsoft PowerPoint 없이 프레젠테이션 파일에 텍스트 또는 이미지 워터마크를 추가할 수 있습니다." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++를 통해 ODP 프레젠테이션에 워터마크 추가" variant="code" %}}

Aspose.Slides for C++를 사용하면 ODP 프레젠테이션에 텍스트 또는 이미지 워터마크를 추가할 수 있습니다. `AddAutoShape`로 슬라이드 마스터에 워터마크 도형을 추가하고, `AddTextFrame`으로 텍스트를 추가하거나 `File::ReadAllBytes`와 `AddImage`로 불러온 이미지로 도형을 채우세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++로 ODP에 텍스트 워터마크 추가" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++로 ODP 프레젠테이션에 이미지 워터마크 추가" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++로 ODP에 워터마크를 추가하는 방법" intro="다음 단계에 따라 ODP 파일에 텍스트 또는 이미지 워터마크를 추가하세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 클래스로 ODP 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation::get_Masters` 컬렉션에서 슬라이드 마스터를 선택합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddAutoShape` 메서드로 워터마크 도형을 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddTextFrame` 메서드로 워터마크 텍스트를 추가하거나 `AddImage`로 그림 채우기를 설정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat::Odp`로 워터마크가 적용된 파일을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides로 구축" title="온라인에서 ODP 파일에 워터마크 추가" description="무료 Aspose.Slides Watermark 앱은 위 코드와 동일한 API인 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/)로 구축되었습니다. 앱을 열고 내 ODP 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Watermark 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 워터마크를 어떻게 추가하는지 확인하세요.
- ODP 파일에 텍스트 또는 이미지 워터마크를 추가하세요.
- 워터마크가 적용된 파일을 다운로드하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="워터마크를 지원하는 기타 형식" subTitle="C++로 다음 형식에도 워터마크를 추가할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

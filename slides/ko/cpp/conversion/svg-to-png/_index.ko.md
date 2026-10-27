---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++에서 SVG을 PNG로 변환
url: /ko/cpp/conversion/svg-to-png/
keywords: SVG에서 PNG으로, SVG에서 PNG으로 변환, C++ API, C++ 라이브러리, SVG, PNG
description: C++에서 SVG을 PNG으로 변환합니다. C++ 라이브러리 API를 사용하여 SVG 파일을 PNG 파일로 변환
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++에서 SVG을 PNG로 변환" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고 Microsoft PowerPoint 및 OpenOffice 프레젠테이션 파일을 생성, 병합, 검사 또는 변환할 수 있는 기능으로 응용 프로그램을 개발하는 데 도움이 되는 고속 및 교차 플랫폼 C++ 라이브러리입니다." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++를 사용하여 SVG을 PNG로 변환" variant="code" %}}

SVG을 PNG로 변환하려면 SVG 파일에서 프레젠테이션을 생성하고 PNG로 저장해야 합니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="SVG을 PNG으로 변환하기 위한 C++ 코드" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
System::String svgContent = System::IO::File::ReadAllText(svgPath);
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
System::SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(Aspose::Slides::ShapeType::Rectangle, 0.0f, 0.0f, 
    static_cast<float>(ppImage->get_Width()), 
    static_cast<float>(ppImage->get_Height()), ppImage);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++에서 SVG을 PNG로 변환" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ko/cpp/)는 프레젠테이션 파일을 만들고 조작하기 위한 강력한 C++ 라이브러리입니다. 또한 SVG을 PNG으로 변환하는 유연한 방법을 제공합니다. **Aspose.Slides for C++**를 사용하면 모든 개발자 또는 애플리케이션이 단 몇 줄의 C++ 코드로 SVG을 PNG 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for C++는 SVG 파일을 PNG 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 SVG을 PNG 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Aspose.Slides for C++ API를 사용하여 SVG을 PNG로 변환하는 방법" intro="다음은 C++에서 SVG을 PNG으로 변환하는 단계입니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for C++**](https://products.aspose.com/slides/ko/cpp/)를 설치합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++ 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++에서 소스 SVG 파일을 엽니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}결과를 PNG 파일로 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides로 구축" title="SVG에서 PNG로 온라인 변환" description="무료 Aspose.Slides Conversion 앱은 위 코드와 동일한 API인 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/)로 구축되었습니다. 앱을 열고 내 SVG 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Conversion 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" upload="파일을 끌어다 놓거나 업로드하세요" saveAs="다른 이름으로 저장" convert="변환" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 변환하는지 확인해 보세요.
- SVG 파일을 업로드하고 PNG로 저장하세요.
- 결과를 다운로드하거나 더 많은 파일을 변환하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="SVG을 지원되는 다른 형식으로 변환" subTitle="SVG을 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식 보기" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python에서 이미지를 PPTX로 변환
url: /ko/python-net/conversion/image-to-pptx/
keywords: 이미지를 PPTX로, 이미지를 PPTX로 변환, Python API, Python 라이브러리, 이미지, PPTX
description: Python에서 이미지를 PPTX로 변환합니다. Python 라이브러리 API를 사용하여 이미지 파일을 PDF로 변환
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python에서 이미지를 PPTX로 변환" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고 Microsoft PowerPoint 및 OpenOffice 프레젠테이션 파일을 생성, 병합, 검사 또는 변환할 수 있는 기능으로 응용 프로그램을 개발하는 데 도움이 되는 고속 및 교차 플랫폼 Python 라이브러리입니다." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python을 사용하여 이미지를 PPTX로 변환" variant="code" %}}

이미지를 PPTX로 변환하려면 이미지 파일에서 프레젠테이션을 만들고 PPTX로 저장해야 합니다.

{{< blocks/products/pf/slides-design-update-10-2026/code title="이미지를 PPTX로 변환하기 위한 Python 코드" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.pptx", slides.export.SaveFormat.PPTX)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python에서 이미지를 PPTX로 변환" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)은 프레젠테이션 파일을 만들고 조작하기 위한 강력한 Python 라이브러리입니다. 또한 이미지를 PPTX로 변환하는 유연한 방법을 제공합니다. **Aspose.Slides for Python via .NET**을 사용하면 모든 개발자 또는 애플리케이션이 몇 줄의 Python 코드만으로 이미지를 PPTX 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for Python은 이미지 파일을 PPTX 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 이미지를 PDF 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Aspose.Slides for Python API를 사용하여 이미지를 PPTX로 변환하는 방법" intro="다음은 Python에서 이미지를 PPTX로 변환하는 단계입니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)를 설치합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Python 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Python에서 소스 이미지 파일을 엽니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}결과를 PPTX 파일로 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides로 구축" title="이미지에서 PPTX로 온라인 변환" description="무료 Aspose.Slides Conversion 앱은 위 코드와 동일한 API인 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ko/python-net/)로 구축되었습니다. 앱을 열고 내 이미지 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Conversion 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" upload="파일을 끌어다 놓거나 업로드하세요" saveAs="다른 이름으로 저장" convert="변환" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 파일을 어떻게 변환하는지 확인해 보세요.
- 이미지 파일을 업로드하고 PPTX로 저장하세요.
- 결과를 다운로드하거나 더 많은 파일을 변환하세요.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="지원되는 다른 형식으로 이미지 변환" subTitle="이미지를 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식 보기" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/python-net/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

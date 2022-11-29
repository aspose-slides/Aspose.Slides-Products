---
title: Python에서 HTML을 PDF으로 변환
url: /ko/python-net/conversion/html-to-pdf/
keywords: HTML에서 PDF으로, HTML에서 PDF으로 변환, Python API, Python 라이브러리, HTML, PDF
description: Python에서 HTML을 PDF으로 변환합니다. Python 라이브러리 API를 사용하여 HTML 파일을 PDF 파일로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python에서 HTML을 PDF으로 변환" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고 Microsoft PowerPoint 및 OpenOffice 프레젠테이션 파일을 생성, 병합, 검사 또는 변환할 수 있는 기능으로 응용 프로그램을 개발하는 데 도움이 되는 고속 및 교차 플랫폼 Python 라이브러리입니다." >}}

{{% blocks/products/pf/feature-page-section h2="Python에서 HTML을 PDF으로 변환" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)은 프레젠테이션 파일을 만들고 조작하기 위한 강력한 Python 라이브러리입니다. 또한 HTML을 PDF으로 변환하는 유연한 방법을 제공합니다. **Aspose.Slides for Python via .NET**을 사용하면 모든 개발자 또는 애플리케이션이 단 몇 줄의 Python 코드로 HTML을 PDF 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for Python은 HTML 파일을 PDF 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 HTML을 PDF 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python을 사용하여 HTML을 PDF로 변환" %}}
HTML을 PDF로 변환하려면 HTML 파일에서 프레젠테이션을 생성하고 PDF로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="HTML을 PDF로 변환하기 위한 Python 코드" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open(dataDir + "file.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API를 사용하여 HTML을 PDF로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Python에서 HTML을 PDF으로 변환하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ko/python-net/)를 설치합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python에서 소스 HTML 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PDF 파일로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="HTML을 지원되는 다른 형식으로 변환" subTitle="HTML을 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식 보기" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Python에서 PDF을 PPSM으로 변환
url: /ko/python-java/conversion/pdf-to-ppsm/
keywords: Python 프레젠테이션 변환, 프레젠테이션을 Python으로 변환, 프레젠테이션용 Python, Aspose.Slides Python, PDF에서 PPSM으로 변환, Python 프레젠테이션 라이브러리
description: Python에서 PDF을 PPSM으로 변환합니다. Python 라이브러리 API를 사용하여 PDF 파일을 PPSM으로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python: Aspose.Slides를 사용하여 손쉽게 PDF을 PPSM으로 변환하세요!" h2="Python으로 프레젠테이션에 새로운 생명을 불어넣어 보세요. 우리 가이드는 기존 PowerPoint 슬라이드를 매력적인 Python 프레젠테이션으로 변환하는 과정을 안내합니다." >}}

{{% blocks/products/pf/feature-page-section h2="Python에서 PDF을 PPSM으로 변환" %}}

복잡한 프레젠테이션 소프트웨어와 씨름하는 데 지치셨나요? [**Java를 통한 Python용 Aspose.Slides**](https://products.aspose.com/slides/ko/python-java/)만 보세요! 이 강력한 라이브러리를 사용하면 다양한 형식 간에 프레젠테이션을 쉽게 생성, 편집 및 변환할 수 있습니다. PDF에서 PPSM으로 전환해야 합니까? Aspose.Slides를 사용하면 Python 코드 몇 줄만 있으면 쉽게 작업할 수 있습니다.

최첨단 문서 처리 API인 **Aspose.Slides for Python via Java**는 매우 빠른 변환 속도를 자랑하며 PDF 프레젠테이션을 PPSM 형식으로 신속하게 변환합니다. 기존 도구의 한계를 극복하세요 - Aspose.Slides는 프레젠테이션을 PDF에서 PPSM뿐만 아니라 다양한 다른 형식으로 변환할 수 있는 유연성을 제공하여 어떤 상황에도 프레젠테이션을 완벽하게 적용할 수 있도록 해줍니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python을 사용하여 PDF을 PPSM으로 변환" %}}
PDF을 PPSM으로 변환하려면 PDF 파일에서 프레젠테이션을 생성하고 이를 PPSM으로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="PDF을 PPSM으로 변환하기 위한 Python 튜토리얼" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

pres.save("output.ppsm", SaveFormat.Ppsm);

jpype.shutdownJVM()

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="파이썬 튜토리얼. Java API를 통해 Python용 Aspose.Slides를 사용하여 PDF을 PPSM으로 변환하는 방법." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java를 통해 Python용 Aspose.Slides를 사용하여 PDF을 PPSM으로 변환하려면 패키지를 Python 스크립트로 가져오고 프레젠테이션 클래스의 인스턴스를 생성해야 합니다. Presentation 클래스는 PowerPoint 문서를 나타내며 해당 요소에 액세스하고 조작하는 메서드를 제공합니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Java를 통해 Python용 Aspose.Slides**](https://products.aspose.com/slides/ko/python-java/)를 설치합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python에서 소스 PDF 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PPSM 파일로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PDF을 지원되는 다른 형식으로 변환" subTitle="PDF을(를) 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식을 확인하세요." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
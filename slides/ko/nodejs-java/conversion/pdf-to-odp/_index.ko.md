---
title: Node.js에서 PDF을 ODP으로 변환
url: /ko/nodejs-java/conversion/pdf-to-odp/
keywords: PDF에서 ODP으로, PDF에서 ODP으로 변환, Node.js API, Node.js 라이브러리, PDF, ODP
description: Node.js에서 PDF을 ODP으로 변환합니다. Node.js 라이브러리 API를 사용하여 PDF 파일을 ODP 파일로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Node.js에서 PDF을 ODP으로 변환" h2="Aspose.Slides for Node.js via Java는 PowerPoint 프레젠테이션을 Node.js의 다양한 형식으로 변환할 수 있는 강력하고 사용하기 쉬운 라이브러리입니다. 모든 프레젠테이션 요소와 형식을 지원하며 이에 액세스하고 수정할 수 있는 풍부한 API를 제공합니다. 또한 추가 처리 또는 공유를 위해 슬라이드를 다양한 형식으로 내보낼 수도 있습니다." >}}

{{% blocks/products/pf/feature-page-section h2="Node.js에서 PDF을 ODP으로 변환" %}}

[**Java를 통한 Node.js용 Aspose.Slides**](https://products.aspose.com/slides/ko/nodejs-java/)는 프레젠테이션 파일을 생성하고 조작하기 위한 강력한 Node.js 라이브러리입니다. 또한 PDF을 ODP으로 변환하는 유연한 방법을 제공합니다. **Java를 통해 Node.js용 Aspose.Slides**를 사용하면 모든 개발자나 애플리케이션은 단 몇 줄의 코드만으로 PDF을 ODP 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Node.js용 Aspose.Slides는 PDF 파일을 ODP 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 PDF을 ODP 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Node.js를 사용하여 PDF을 ODP으로 변환" %}}
PDF을 ODP으로 변환하려면 PDF 파일에서 프레젠테이션을 생성하고 이를 ODP으로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="PDF을 ODP으로 변환하기 위한 Node.js 코드" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation();
try
{
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

    pres.save("output.odp", aspose.slides.SaveFormat.Odp);
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java API를 통해 Node.js용 Aspose.Slides를 사용하여 PDF을 ODP으로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java를 통해 Node.js용 Aspose.Slides를 사용하여 PDF을 ODP으로 변환하려면 JavaScript 파일로 패키지를 가져오고 Presentation 클래스의 인스턴스를 생성해야 합니다. Presentation 클래스는 PowerPoint 문서를 나타내며 해당 요소에 액세스하고 조작하는 메서드를 제공합니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Java를 통해 Node.js용 Aspose.Slides**](https://products.aspose.com/slides/ko/nodejs-java/)를 설치합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js에서 소스 PDF 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 ODP 파일로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PDF을 지원되는 다른 형식으로 변환" subTitle="PDF을(를) 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식을 확인하세요." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
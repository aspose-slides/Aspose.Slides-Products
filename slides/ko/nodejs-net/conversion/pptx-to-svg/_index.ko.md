---
title: JavaScript에서 PPTX을(를) SVG(으)로 변환
url: /ko/nodejs-net/conversion/pptx-to-svg/
keywords: PPTX을(를) SVG(으)로, PPTX을(를) SVG(으)로 변환, Node.js API, JavaScript 라이브러리, PPTX, SVG
description: JavaScript에서 PPTX을 SVG으로 변환합니다. Node.js 라이브러리 API를 사용하여 PPTX 파일을 SVG으로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="JavaScript에서 PPTX을(를) SVG(으)로 변환" h2=".NET을 통한 Node.js용 Aspose.Slides는 PowerPoint 프레젠테이션을 JavaScript의 다양한 형식으로 변환할 수 있는 강력하고 사용하기 쉬운 라이브러리입니다. 모든 프레젠테이션 요소와 형식을 지원하며 이에 액세스하고 수정할 수 있는 풍부한 API를 제공합니다. 또한 추가 처리 또는 공유를 위해 슬라이드를 다양한 형식으로 내보낼 수도 있습니다." >}}

{{% blocks/products/pf/feature-page-section h2="Node.js에서 PPTX을 SVG으로 변환" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ko/nodejs-net/)은 프레젠테이션 파일을 생성하고 조작하기 위한 강력한 Node.js 라이브러리입니다. 또한 PPTX을 SVG으로 변환하는 유연한 방법을 제공합니다. .NET을 통해 **Aspose.Slides for Node.js**를 사용하면 모든 개발자나 애플리케이션은 단 몇 줄의 코드만으로 PPTX을 SVG 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for Node.js는 .NET을 통해 PPTX 파일을 SVG 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 PPTX을 SVG 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="JavaScript를 사용하여 PPTX을(를) SVG(으)로 변환" %}}
PPTX을 SVG으로 변환하려면 PPTX 파일에서 프레젠테이션을 생성하고 이를 SVG으로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="PPTX을 SVG으로 변환하기 위한 JavaScript 코드" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pptx");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slideByteArray = pres.slides.get(i).getAsSvg();
        fs.writeFile('slide" + i + ".svg', Buffer.from(slideByteArray), (err) => {
            if (err)
                console.error(err);
        });
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2=".NET API를 통해 Node.js용 Aspose.Slides를 사용하여 PPTX을 SVG으로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET을 통해 Node.js용 Aspose.Slides를 사용하여 PPTX을 SVG으로 변환하려면 JavaScript 파일에서 패키지를 가져오고 Presentation 클래스의 인스턴스를 생성해야 합니다. Presentation 클래스는 PowerPoint 문서를 나타내며 해당 요소에 액세스하고 조작하는 메서드를 제공합니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**.NET을 통해 Node.js용 Aspose.Slides**](https://products.aspose.com/slides/ko/nodejs-net/)를 설치합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js에서 소스 PPTX 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 SVG 파일로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPTX을 지원되는 다른 형식으로 변환" subTitle="PPTX을(를) 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식을 확인하세요." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
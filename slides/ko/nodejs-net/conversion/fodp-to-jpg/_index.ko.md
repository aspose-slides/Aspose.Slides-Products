---
title: JavaScript에서 FODP을(를) JPG(으)로 변환
url: /ko/nodejs-net/conversion/fodp-to-jpg/
keywords: FODP을(를) JPG(으)로, FODP을(를) JPG(으)로 변환, Node.js API, JavaScript 라이브러리, FODP, JPG
description: JavaScript에서 FODP을 JPG으로 변환합니다. Node.js 라이브러리 API를 사용하여 FODP 파일을 JPG으로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="JavaScript에서 FODP을(를) JPG(으)로 변환" h2=".NET을 통한 Node.js용 Aspose.Slides는 PowerPoint 프레젠테이션을 JavaScript의 다양한 형식으로 변환할 수 있는 강력하고 사용하기 쉬운 라이브러리입니다. 모든 프레젠테이션 요소와 형식을 지원하며 이에 액세스하고 수정할 수 있는 풍부한 API를 제공합니다. 또한 추가 처리 또는 공유를 위해 슬라이드를 다양한 형식으로 내보낼 수도 있습니다." >}}

{{% blocks/products/pf/feature-page-section h2="Node.js에서 FODP을 JPG으로 변환" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ko/nodejs-net/)은 프레젠테이션 파일을 생성하고 조작하기 위한 강력한 Node.js 라이브러리입니다. 또한 FODP을 JPG으로 변환하는 유연한 방법을 제공합니다. .NET을 통해 **Aspose.Slides for Node.js**를 사용하면 모든 개발자나 애플리케이션은 단 몇 줄의 코드만으로 FODP을 JPG 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for Node.js는 .NET을 통해 FODP 파일을 JPG 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 FODP을 JPG 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="JavaScript를 사용하여 FODP을(를) JPG(으)로 변환" %}}
FODP을 JPG으로 변환하려면 FODP 파일에서 프레젠테이션을 생성하고 이를 JPG으로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="FODP을 JPG으로 변환하기 위한 JavaScript 코드" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.fodp");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".jpg", ImageFormat.Jpeg); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2=".NET API를 통해 Node.js용 Aspose.Slides를 사용하여 FODP을 JPG으로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET을 통해 Node.js용 Aspose.Slides를 사용하여 FODP을 JPG으로 변환하려면 JavaScript 파일에서 패키지를 가져오고 Presentation 클래스의 인스턴스를 생성해야 합니다. Presentation 클래스는 PowerPoint 문서를 나타내며 해당 요소에 액세스하고 조작하는 메서드를 제공합니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**.NET을 통해 Node.js용 Aspose.Slides**](https://products.aspose.com/slides/ko/nodejs-net/)를 설치합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js에서 소스 FODP 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 JPG 파일로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="FODP을 지원되는 다른 형식으로 변환" subTitle="FODP을(를) 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식을 확인하세요." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/nodejs-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
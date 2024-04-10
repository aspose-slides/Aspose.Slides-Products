---
title: Chuyển đổi ODP sang PNG trong JavaScript
url: /vi/nodejs-net/conversion/odp-to-png/
keywords: ODP sang PNG, Chuyển đổi ODP sang PNG, API Node.js, Thư viện JavaScript, ODP, PNG
description: Chuyển đổi ODP thành PNG trong JavaScript. Sử dụng API thư viện Node.js để chuyển đổi tệp ODP sang PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi ODP sang PNG trong JavaScript" h2="Aspose.Slides cho Node.js qua .NET là một thư viện mạnh mẽ và dễ sử dụng cho phép bạn chuyển đổi bản trình bày PowerPoint sang nhiều định dạng khác nhau trong JavaScript. Nó hỗ trợ tất cả các thành phần và định dạng trình bày, đồng thời cung cấp API phong phú để truy cập và sửa đổi chúng. Nó cũng cho phép bạn xuất các slide của mình sang nhiều định dạng khác nhau để xử lý hoặc chia sẻ thêm." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi ODP thành PNG trong Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/vi/nodejs-net/) là thư viện Node.js mạnh mẽ để tạo và thao tác với các tệp bản trình bày. Hơn nữa, nó cung cấp những cách linh hoạt để chuyển đổi ODP sang PNG. Bằng cách sử dụng **Aspose.Slides cho Node.js qua .NET**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi tệp ODP thành PNG chỉ bằng một vài dòng mã.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Node.js thông qua .NET xuất các tệp ODP sang định dạng tệp PNG một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi ODP sang PNG và nhiều định dạng tệp khác

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi ODP sang PNG bằng JavaScript" %}}
Để chuyển đổi ODP sang PNG, bạn cần tạo Bản trình bày từ tệp ODP và lưu dưới dạng PNG.

{{% blocks/products/pf/agp/code-block title="Mã JavaScript để chuyển đổi ODP thành PNG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.odp");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".png", ImageFormat.Png); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách chuyển đổi ODP sang PNG bằng Aspose.Slides cho Node.js qua .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Để chuyển đổi ODP sang PNG bằng Aspose.Slides cho Node.js qua .NET, bạn cần nhập gói trong tệp JavaScript của mình và tạo một phiên bản của lớp Trình bày. Lớp Trình bày đại diện cho một tài liệu PowerPoint và cung cấp các phương thức để truy cập và thao tác các phần tử của nó." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides cho Node.js qua .NET**](https://products.aspose.com/slides/vi/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Node.js của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp nguồn ODP trong Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi ODP sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi ODP và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-bmp/" name="ODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-net/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
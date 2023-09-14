---
title: Chuyển đổi PPS thành BMP trong Node.js
url: /vi/nodejs-java/conversion/pps-to-bmp/
keywords: PPS sang BMP, Chuyển đổi PPS sang BMP, API Node.js, Thư viện Node.js, PPS, BMP
description: Chuyển đổi PPS thành BMP trong Node.js. Sử dụng API thư viện Node.js để chuyển đổi tệp PPS thành tệp BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi PPS thành BMP trong Node.js" h2="Aspose.Slides cho Node.js qua Java là một thư viện mạnh mẽ và dễ sử dụng cho phép bạn chuyển đổi bản trình bày PowerPoint sang các định dạng khác nhau trong Node.js. Nó hỗ trợ tất cả các thành phần và định dạng trình bày, đồng thời cung cấp API phong phú để truy cập và sửa đổi chúng. Nó cũng cho phép bạn xuất các slide của mình sang nhiều định dạng khác nhau để xử lý hoặc chia sẻ thêm." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi PPS thành BMP trong Node.js" %}}

[**Aspose.Slides dành cho Node.js qua Java**](https://products.aspose.com/slides/vi/nodejs-java/) là thư viện Node.js mạnh mẽ để tạo và thao tác với các tệp bản trình bày. Hơn nữa, nó cung cấp những cách linh hoạt để chuyển đổi PPS sang BMP. Bằng cách sử dụng **Aspose.Slides cho Node.js qua Java**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi tệp PPS sang BMP chỉ bằng một vài dòng mã.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Node.js xuất các tệp PPS sang định dạng tệp BMP một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi PPS sang BMP và nhiều định dạng tệp khác

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PPS sang BMP bằng Node.js" %}}
Để chuyển đổi PPS sang BMP, bạn cần tạo Bản trình bày từ tệp PPS và lưu dưới dạng BMP.

{{% blocks/products/pf/agp/code-block title="Mã Node.js để chuyển đổi PPS thành BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pps");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".bmp");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "bmp", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách chuyển đổi PPS sang BMP bằng cách sử dụng Aspose.Slides cho Node.js qua API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Để chuyển đổi PPS sang BMP bằng Aspose.Slides cho Node.js qua Java, bạn cần nhập gói trong tệp JavaScript của mình và tạo một phiên bản của lớp Trình bày. Lớp Trình bày đại diện cho một tài liệu PowerPoint và cung cấp các phương thức để truy cập và thao tác các phần tử của nó." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides cho Node.js qua Java**](https://products.aspose.com/slides/vi/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Node.js của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp nguồn PPS trong Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi PPS sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPS và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-jpg/" name="PPS TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-svg/" name="PPS TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/nodejs-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
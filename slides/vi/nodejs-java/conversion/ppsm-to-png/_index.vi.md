---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi PPSM thành PNG trong Node.js
url: /vi/nodejs-java/conversion/ppsm-to-png/
keywords: PPSM sang PNG, Chuyển đổi PPSM sang PNG, API Node.js, Thư viện Node.js, PPSM, PNG
description: Chuyển đổi PPSM thành PNG trong Node.js. Sử dụng API thư viện Node.js để chuyển đổi tệp PPSM thành tệp PNG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi PPSM thành PNG trong Node.js" h2="Aspose.Slides cho Node.js qua Java là một thư viện mạnh mẽ và dễ sử dụng cho phép bạn chuyển đổi bản trình bày PowerPoint sang các định dạng khác nhau trong Node.js. Nó hỗ trợ tất cả các thành phần và định dạng trình bày, đồng thời cung cấp API phong phú để truy cập và sửa đổi chúng. Nó cũng cho phép bạn xuất các slide của mình sang nhiều định dạng khác nhau để xử lý hoặc chia sẻ thêm." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PPSM sang PNG bằng Node.js" variant="code" %}}

Để chuyển đổi PPSM sang PNG, bạn cần tạo Bản trình bày từ tệp PPSM và lưu dưới dạng PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã Node.js để chuyển đổi PPSM thành PNG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppsm");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".png");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "png", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PPSM thành PNG trong Node.js" %}}

[**Aspose.Slides dành cho Node.js qua Java**](https://products.aspose.com/slides/vi/nodejs-java/) là thư viện Node.js mạnh mẽ để tạo và thao tác với các tệp bản trình bày. Hơn nữa, nó cung cấp những cách linh hoạt để chuyển đổi PPSM sang PNG. Bằng cách sử dụng **Aspose.Slides cho Node.js qua Java**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi tệp PPSM sang PNG chỉ bằng một vài dòng mã.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Node.js xuất các tệp PPSM sang định dạng tệp PNG một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi PPSM sang PNG và nhiều định dạng tệp khác

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi PPSM sang PNG bằng cách sử dụng Aspose.Slides cho Node.js qua API Java" intro="Để chuyển đổi PPSM sang PNG bằng Aspose.Slides cho Node.js qua Java, bạn cần nhập gói trong tệp JavaScript của mình và tạo một phiên bản của lớp Trình bày. Lớp Trình bày đại diện cho một tài liệu PowerPoint và cung cấp các phương thức để truy cập và thao tác các phần tử của nó." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt [**Aspose.Slides cho Node.js qua Java**](https://products.aspose.com/slides/vi/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm tham chiếu thư viện (nhập thư viện) vào dự án Node.js của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp nguồn PPSM trong Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu kết quả dưới dạng tệp PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chuyển đổi PPSM sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPSM và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

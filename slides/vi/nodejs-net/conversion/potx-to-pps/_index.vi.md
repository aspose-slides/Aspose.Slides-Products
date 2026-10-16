---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi POTX sang PPS trong JavaScript
url: /vi/nodejs-net/conversion/potx-to-pps/
keywords: POTX sang PPS, Chuyển đổi POTX sang PPS, API Node.js, Thư viện JavaScript, POTX, PPS
description: Chuyển đổi POTX thành PPS trong JavaScript. Sử dụng API thư viện Node.js để chuyển đổi tệp POTX sang PPS
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi POTX sang PPS trong JavaScript" h2="Aspose.Slides cho Node.js qua .NET là một thư viện mạnh mẽ và dễ sử dụng cho phép bạn chuyển đổi bản trình bày PowerPoint sang nhiều định dạng khác nhau trong JavaScript. Nó hỗ trợ tất cả các thành phần và định dạng trình bày, đồng thời cung cấp API phong phú để truy cập và sửa đổi chúng. Nó cũng cho phép bạn xuất các slide của mình sang nhiều định dạng khác nhau để xử lý hoặc chia sẻ thêm." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi POTX sang PPS bằng JavaScript" variant="code" %}}

Để chuyển đổi POTX sang PPS, bạn cần tạo Bản trình bày từ tệp POTX và lưu dưới dạng PPS.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã JavaScript để chuyển đổi POTX thành PPS" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.potx");
try
{
    pres.save("output.pps", SaveFormat.Pps);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi POTX thành PPS trong Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/vi/nodejs-net/) là thư viện Node.js mạnh mẽ để tạo và thao tác với các tệp bản trình bày. Hơn nữa, nó cung cấp những cách linh hoạt để chuyển đổi POTX sang PPS. Bằng cách sử dụng **Aspose.Slides cho Node.js qua .NET**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi tệp POTX thành PPS chỉ bằng một vài dòng mã.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Node.js thông qua .NET xuất các tệp POTX sang định dạng tệp PPS một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi POTX sang PPS và nhiều định dạng tệp khác

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi POTX sang PPS bằng Aspose.Slides cho Node.js qua .NET API" intro="Để chuyển đổi POTX sang PPS bằng Aspose.Slides cho Node.js qua .NET, bạn cần nhập gói trong tệp JavaScript của mình và tạo một phiên bản của lớp Trình bày. Lớp Trình bày đại diện cho một tài liệu PowerPoint và cung cấp các phương thức để truy cập và thao tác các phần tử của nó." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt [**Aspose.Slides cho Node.js qua .NET**](https://products.aspose.com/slides/vi/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm tham chiếu thư viện (nhập thư viện) vào dự án Node.js của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp nguồn POTX trong Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu kết quả dưới dạng tệp PPS.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chuyển đổi POTX sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi POTX và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-bmp/" name="POTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/nodejs-net/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

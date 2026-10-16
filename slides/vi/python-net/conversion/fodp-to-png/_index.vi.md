---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi FODP sang PNG bằng Python
weight: 90
url: /vi/python-net/conversion/fodp-to-png/ 
keywords: "Convert, PowerPoint, FODP, PNG, Presentation, Python"
description: Mã mẫu để chuyển đổi FODP sang PNG Python. Sử dụng API Python của PowerPoint để chuyển đổi hàng loạt tệp FODP sang tệp PNG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi FODP sang PNG bằng Python" h2="Thư viện PowerPoint Python mạnh mẽ để chuyển đổi FODP sang PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi FODP sang PNG bằng Python" %}}

Bạn cần lập trình chuyển đổi tệp FODP sang PNG? Sử dụng [* Aspose.Slides cho Python qua .NET *](https://products.aspose.com/slides/vi/python-net/), bất kỳ nhà phát triển nào cũng có thể chuyển đổi định dạng FODP sang PNG chỉ với một vài dòng mã Python.

Là một API xử lý bản trình bày hiện đại, Aspose.Slides for Python tạo PNG từ FODP một cách nhanh chóng. Kiểm tra chất lượng chuyển đổi FODP sang PNG ngay trong [trình duyệt] của bạn (https://products.aspose.app/slides/conversion/ppt-to-png). Thư viện Aspose PowerPoint PPTX cho phép bạn chuyển đổi các tập tin FODP sang nhiều định dạng phổ biến.

Bạn có thể cài đặt thư viện từ [PyPI](https://pypi.org/project/Aspose.Slides/) bằng lệnh pip sau:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Bảng điều khiển / Thiết bị đầu cuối" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Lưu FODP dưới dạng PNG bằng Python" %}}

Sử dụng ứng dụng miễn phí để xem trình diễn về quá trình chuyển đổi FODP sang PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã mẫu này hiển thị Chuyển đổi Python từ FODP sang PNG" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.fodp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển FODP sang PNG bằng Python" intro="Đây là các bước để chuyển đổi tệp FODP sang PNG bằng Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp FODP với một phiên bản của lớp Trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat.PNG làm tham số{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tệp FODP sẽ được lưu tại đường dẫn được chỉ định{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Trước khi chạy mã nguồn mẫu chuyển đổi Python, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau." %}}

- Hệ điều hành dựa trên Microsoft Windows hoặc Linux (xem [thêm](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 trở lên
- Aspose.Slides cho Python được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ứng dụng miễn phí để chuyển đổi FODP thành PNG"
  description="[Hãy thử ứng dụng Video miễn phí của chúng tôi](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi FODP sang nhiều định dạng tệp khác. Xem các chuyển đổi được hỗ trợ khác bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Hình ảnh bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-emf/" name="FODP TO EMF" description="Định dạng siêu tệp nâng cao" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-gif/" name="FODP TO GIF" description="Định dạng trao đổi đồ họa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-html/" name="FODP TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-jpg/" name="FODP TO JPG" description="Hình ảnh JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-odp/" name="FODP TO ODP" description="Định dạng bản trình bày OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-otp/" name="FODP TO OTP" description="Định dạng chuẩn OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Định dạng tài liệu di động" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-pot/" name="FODP TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-potm/" name="FODP TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-potx/" name="FODP TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-pps/" name="FODP TO PPS" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Trình chiếu hỗ trợ macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Định dạng bản trình bày XML mở" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-svg/" name="FODP TO SVG" description="Đồ họa vector có thể mở rộng" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-swf/" name="FODP TO SWF" description="Định dạng SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/fodp-to-xps/" name="FODP TO XPS" description="Thông số kỹ thuật giấy XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

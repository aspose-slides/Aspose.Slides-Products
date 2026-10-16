---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi PDF sang BMP bằng Python
weight: 670
url: /vi/python-net/conversion/pdf-to-bmp/ 
keywords: "Convert, PowerPoint, PDF, BMP, Presentation, Python"
description: Mã mẫu để chuyển đổi PDF sang Python BMP. Sử dụng PowerPoint Python API để chuyển đổi hàng loạt tệp PDF sang tệp BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi PDF sang BMP bằng Python" h2="Thư viện PowerPoint Python mạnh mẽ để chuyển đổi PDF sang BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PDF sang BMP bằng Python" %}}

Bạn cần chuyển đổi các tệp PDF sang BMP theo lập trình? Sử dụng [* Aspose.Slides cho Python qua .NET *](https://products.aspose.com/slides/vi/python-net/), bất kỳ nhà phát triển nào cũng có thể chuyển đổi định dạng PDF sang BMP chỉ với một vài dòng mã Python.

Là một API xử lý bản trình bày hiện đại, Aspose.Slides for Python tạo BMP từ PDF một cách nhanh chóng. Kiểm tra chất lượng chuyển đổi PDF sang BMP ngay trong [trình duyệt] của bạn (https://products.aspose.app/slides/conversion). Thư viện Aspose PowerPoint PPTX cho phép bạn chuyển đổi các tập tin PDF sang nhiều định dạng phổ biến.

Bạn có thể cài đặt thư viện từ [PyPI](https://pypi.org/project/Aspose.Slides/) bằng lệnh pip sau:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Bảng điều khiển / Thiết bị đầu cuối" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Lưu PDF dưới dạng BMP bằng Python" %}}

Sử dụng ứng dụng miễn phí để xem trình diễn về quy trình chuyển đổi PDF sang BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã mẫu này hiển thị Chuyển đổi từ PDF sang Python BMP" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi PDF sang BMP bằng Python" intro="Đây là các bước để chuyển đổi tệp PDF sang BMP bằng Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PDF với một phiên bản của lớp Trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat.BMP làm tham số{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tệp PDF sẽ được lưu theo đường dẫn được chỉ định{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Trước khi chạy mã nguồn mẫu chuyển đổi Python, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau." %}}

- Hệ điều hành dựa trên Microsoft Windows hoặc Linux (xem [thêm](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 trở lên
- Aspose.Slides cho Python được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ứng dụng miễn phí để chuyển đổi PDF thành BMP"
  description="[Hãy thử ứng dụng miễn phí của chúng tôi để chuyển đổi PDF sang BMP](https://products.aspose.app/slides/import/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PDF sang nhiều định dạng tập tin khác. Xem các chuyển đổi được hỗ trợ khác bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-emf/" name="PDF TO EMF" description="Định dạng siêu tệp nâng cao" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-fodp/" name="PDF TO FODP" description="Bản trình bày XML phẳng OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-gif/" name="PDF TO GIF" description="Định dạng trao đổi đồ họa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-html/" name="PDF TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" description="Hình ảnh JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-odp/" name="PDF TO ODP" description="Định dạng bản trình bày OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-otp/" name="PDF TO OTP" description="Định dạng chuẩn OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-png/" name="PDF TO PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-pot/" name="PDF TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-potm/" name="PDF TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-potx/" name="PDF TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-pps/" name="PDF TO PPS" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Trình chiếu hỗ trợ macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Định dạng bản trình bày XML mở" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" description="Đồ họa vector có thể mở rộng" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-swf/" name="PDF TO SWF" description="Định dạng SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-xps/" name="PDF TO XPS" description="Thông số kỹ thuật giấy XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

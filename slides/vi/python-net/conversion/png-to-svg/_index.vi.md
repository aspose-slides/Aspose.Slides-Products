---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi PNG thành SVG trong Python
url: /vi/python-net/conversion/png-to-svg/
keywords: PNG sang SVG, Chuyển đổi PNG sang SVG, API Python, Thư viện Python, PNG, SVG
description: Chuyển đổi PNG thành SVG trong Python. Sử dụng API thư viện Python để chuyển đổi tệp PNG thành tệp SVG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi PNG thành SVG trong Python" h2="Thư viện Python tốc độ cao và đa nền tảng giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp bản trình bày Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PNG sang SVG bằng Python" variant="code" %}}

Để chuyển đổi PNG sang SVG, bạn cần tạo Bản trình bày từ tệp PNG và lưu dưới dạng SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã Python để chuyển đổi PNG thành SVG" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.svg".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PNG thành SVG trong Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/) là một thư viện Python mạnh mẽ để tạo và thao tác với các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi PNG thành SVG. Bằng cách sử dụng **Aspose.Slides cho Python qua .NET**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp PNG sang SVG chỉ bằng một vài dòng mã Python.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Python nhanh chóng xuất tệp PNG sang định dạng tệp SVG. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi PNG thành SVGs và nhiều định dạng tệp khác

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi PNG sang SVG bằng API Aspose.Slides cho Python" intro="Đây là các bước để chuyển đổi PNG thành SVG trong Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm tham chiếu thư viện (nhập thư viện) vào dự án Python của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp nguồn PNG bằng Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu kết quả dưới dạng tệp SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Được xây dựng bằng Aspose.Slides" title="Chuyển đổi PNG sang SVG trực tuyến" description="Ứng dụng Aspose.Slides Conversion miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PNG của riêng bạn." button="Mở Aspose.Slides Conversion" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" upload="Thả hoặc tải lên tệp của bạn" saveAs="Lưu dưới dạng" convert="Chuyển đổi" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides chuyển đổi tệp trước khi bạn viết mã.
- Tải lên các tệp PNG và lưu chúng dưới dạng SVG.
- Tải xuống kết quả hoặc chuyển đổi thêm tệp.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chuyển đổi PNG sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PNG và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

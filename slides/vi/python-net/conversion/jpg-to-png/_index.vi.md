---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi JPG thành PNG trong Python
url: /vi/python-net/conversion/jpg-to-png/
keywords: JPG sang PNG, Chuyển đổi JPG sang PNG, API Python, Thư viện Python, JPG, PNG
description: Chuyển đổi JPG thành PNG trong Python. Sử dụng API thư viện Python để chuyển đổi tệp JPG thành tệp PNG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi JPG thành PNG trong Python" h2="Thư viện Python tốc độ cao và đa nền tảng giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp bản trình bày Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi JPG sang PNG bằng Python" variant="code" %}}

Để chuyển đổi JPG sang PNG, bạn cần tạo Bản trình bày từ tệp JPG và lưu dưới dạng PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã Python để chuyển đổi JPG thành PNG" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi JPG thành PNG trong Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/) là một thư viện Python mạnh mẽ để tạo và thao tác với các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi JPG thành PNG. Bằng cách sử dụng **Aspose.Slides cho Python qua .NET**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp JPG sang PNG chỉ bằng một vài dòng mã Python.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Python nhanh chóng xuất tệp JPG sang định dạng tệp PNG. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi JPG thành PNGs và nhiều định dạng tệp khác

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi JPG sang PNG bằng API Aspose.Slides cho Python" intro="Đây là các bước để chuyển đổi JPG thành PNG trong Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm tham chiếu thư viện (nhập thư viện) vào dự án Python của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp nguồn JPG bằng Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu kết quả dưới dạng tệp PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Được xây dựng bằng Aspose.Slides" title="Chuyển đổi JPG sang PNG trực tuyến" description="Ứng dụng Aspose.Slides Conversion miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp JPG của riêng bạn." button="Mở Aspose.Slides Conversion" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" upload="Thả hoặc tải lên tệp của bạn" saveAs="Lưu dưới dạng" convert="Chuyển đổi" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides chuyển đổi tệp trước khi bạn viết mã.
- Tải lên các tệp JPG và lưu chúng dưới dạng PNG.
- Tải xuống kết quả hoặc chuyển đổi thêm tệp.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chuyển đổi JPG sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi JPG và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

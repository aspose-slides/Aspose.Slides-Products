---
title: Chuyển đổi hình ảnh sang PPT trong Python
url: /vi/python-net/conversion/image-to-ppt/
keywords: Hình ảnh thành PPT, Chuyển đổi hình ảnh thành PPT, API Python, Thư viện Python, Hình ảnh, PPT
description: Chuyển đổi hình ảnh sang PPT trong Python. Sử dụng API thư viện Python để chuyển đổi tệp Hình ảnh thành PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi hình ảnh sang PPT trong Python" h2="Thư viện Python tốc độ cao và đa nền tảng giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp bản trình bày Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi hình ảnh sang PPT trong Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/) là một thư viện Python mạnh mẽ để tạo và thao tác với các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi Hình ảnh sang PPT. Sử dụng **Aspose.Slides cho Python qua .NET**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi Hình ảnh thành tệp PPT chỉ bằng một vài dòng mã Python.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Python xuất tệp Hình ảnh sang định dạng tệp PPT một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển Image sang PDF và nhiều định dạng file khác

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi hình ảnh sang PPT bằng Python" %}}
Để chuyển đổi Hình ảnh sang PPT, bạn sẽ cần tạo Bản trình bày từ tệp Hình ảnh và lưu dưới dạng PPT.

{{% blocks/products/pf/agp/code-block title="Mã Python để chuyển đổi Hình ảnh thành PPT" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.ppt", slides.export.SaveFormat.PPT)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách chuyển đổi Hình ảnh sang PPT bằng API Aspose.Slides cho Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để chuyển đổi Hình ảnh sang PPT trong Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Python của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp hình ảnh nguồn bằng Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi hình ảnh sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi Hình ảnh và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
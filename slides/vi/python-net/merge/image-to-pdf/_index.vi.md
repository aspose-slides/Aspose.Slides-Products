---
title: Hợp nhất hình ảnh thành PDF trong Python
url: /vi/python-net/merge/image-to-pdf/
keywords: Hình ảnh thành PDF, Hợp nhất hình ảnh thành PDF, Nối hình ảnh thành PDF, PDF, Hình ảnh, API Python, Thư viện Python
description: Hợp nhất hình ảnh thành PDF bằng Python. Sử dụng API thư viện Python để kết hợp Hình ảnh và PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Hợp nhất hình ảnh thành PDF trong Python" h2="Thư viện Python tốc độ cao và đa nền tảng để hợp nhất các tệp Hình ảnh thành PDF bằng mã Python" >}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất hình ảnh thành PDF bằng Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/) là một thư viện Python mạnh mẽ dùng để tạo, chuyển đổi, hợp nhất và thao tác với bản trình bày, tệp PDF , hình ảnh và các tệp khác. Khi bạn hợp nhất hình ảnh thành PDF, bạn đang kết hợp các hình ảnh một cách hiệu quả để thu được một tệp PDF duy nhất.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Hợp nhất hình ảnh thành PDF trong Python" %}}
Sử dụng [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/), bạn có thể hợp nhất hình ảnh thành PDF một cách nhanh chóng chỉ với một vài dòng mã

{{% blocks/products/pf/agp/code-block title="Mã Python để hợp nhất Hình ảnh thành PDF" offSpacer="true" %}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image1 = pres.images.add_image(drawing.Bitmap("image1.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 100, 100, image1)

    image2 = pres.images.add_image(drawing.Bitmap("image2.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 200, 100, 100, image2)

    pres.save("pres.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách hợp nhất hình ảnh thành PDF trong Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho Python qua .NET**. Xem [**Cài đặt**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm thư viện làm tài liệu tham khảo trong dự án của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tạo một thể hiện của lớp Trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải các hình ảnh bạn muốn hợp nhất với nhau dưới dạng khung ảnh.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tệp PDF kết quả.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Hợp nhất các tệp khác" subTitle="Bạn cũng có thể kết hợp các tệp ở các định dạng khác để có được một tệp duy nhất" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
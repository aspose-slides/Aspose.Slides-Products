---
title: Chỉnh sửa PPT bằng Python
url: /vi/python-net/editor/ppt/
keywords: Chỉnh sửa PPT, Chỉnh sửa PowerPoint, PPT, PowerPoint, API Python, Thư viện Python
description: Chỉnh sửa PPT bằng Python. Sử dụng API thư viện Python để chỉnh sửa bản trình bày PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chỉnh sửa PPT bằng Python" h2="Thư viện Python tốc độ cao và đa nền tảng để chỉnh sửa PPT bằng mã Python" >}}

{{% blocks/products/pf/feature-page-section h2="Chỉnh sửa PPT bằng Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/) là một thư viện Python mạnh mẽ dùng để thao tác và chỉnh sửa bản trình bày. Bạn có thể chỉnh sửa bản trình bày PPT bằng cách thêm một dòng văn bản mới vào đó. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Chỉnh sửa PPT bằng Python" %}}
Sử dụng [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/), bạn có thể thêm một dòng văn bản mới vào tài liệu PPT chỉ với một vài thao tác dòng mã.

{{% blocks/products/pf/agp/code-block title="Mã Python để chỉnh sửa PPT" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách chỉnh sửa PPT trong Python" >}}


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
Tải bản trình bày PPT mà bạn muốn chỉnh sửa.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm một dòng văn bản mới.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tệp PowerPoint đã thay đổi.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Chỉnh sửa các tệp khác" subTitle="Bạn cũng có thể chỉnh sửa tệp ở các định dạng khác" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
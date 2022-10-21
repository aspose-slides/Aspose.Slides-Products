---
title: Hợp nhất PDF, PPT, PPTX và nhiều định dạng tệp khác bằng Python
url: /vi/python-net/merge/
keywords: Hợp nhất, Tham gia, PowerPoint, Bản trình bày, Python, Aspose
description: Hợp nhất nhiều tệp bằng Python PPT, PPTX, ODP, PDF, PNG, JPG và nhiều tệp khác.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Hợp nhất Powerpoint, PDF, PPT hoặc các tài liệu khác với nhau bằng Python" h2="Thư viện Python tốc độ cao để hợp nhất PPT, PPTX, PDF, PNG, JPEG và các định dạng khác." >}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất PPT, PPTX, PDF bằng Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/) là một thư viện Python mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để kết hợp nhiều bài thuyết trình PPT / PPTX. Khi bạn hợp nhất một bản trình bày với một bản trình bày khác, bạn đang kết hợp hiệu quả các trang trình bày của chúng trong một bản trình bày duy nhất để có được một tệp. Aspose.Slides cho phép bạn hợp nhất hai bản trình bày theo những cách khác nhau. Bạn có thể hợp nhất các bản trình bày với tất cả các hình dạng, phong cách, văn bản, định dạng, nhận xét, hoạt ảnh, v.v. của chúng mà không phải lo lắng về việc mất chất lượng hoặc dữ liệu.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hợp nhất các bản trình bày PowerPoint bằng Python" %}}
Để hợp nhất các bản trình bày PowerPoint, bạn sẽ cần sao chép các trang chiếu từ bản trình bày này sang bản trình bày khác.

{{% blocks/products/pf/agp/code-block title="Hợp nhất các tệp PPTX bằng Python" offSpacer="true" %}}

```python

import aspose.slides as slides

# open first presentation
with slides.Presentation("presentation1.pptx") as pres1:
    # open second presentation
    with slides.Presentation("presentation2.pptx") as pres2:
        # loop through slides
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
        # save merged presentation
        pres1.save("combined.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hợp nhất các bản trình bày với Slide Master bằng Python" %}}
Mã python này trình bày cách hợp nhất một số bản trình bày thành một và áp dụng các kiểu từ mẫu bản trình bày trang chiếu cái. Vì vậy, bản trình bày kết quả sẽ giữ nguyên định dạng nguồn và sẽ chứa định dạng từ trang chiếu chính của bản trình bày khác.

{{% blocks/products/pf/agp/code-block title="Hợp nhất nhiều PPT thành một trong Python" offSpacer="true" %}}

```python

import aspose.slides as slides

files = ['pres1.pptx', 'pres2.pptx', 'pres3.pptx']

with slides.Presentation('master.pptx') as master:
    masterSlide = master.masters[0]

    for file in files:
        with slides.Presentation(file) as source:
            for slide in source.slides:
                clone = master.slides.add_clone(slide)

                for shape in masterSlide.shapes:
                    clone.shapes.add_clone(shape)
    
    master.save("combined.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách hợp nhất các bản trình bày bằng cách sử dụng Aspose.Slides cho Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để hợp nhất hai tệp PPTX và lưu kết quả dưới dạng PDF bằng Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Python của bạn.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở các tệp PPTX nguồn bằng Python.
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kết hợp các tệp PPTX bằng phương pháp ** add_clone **.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu bản trình bày và nhận kết quả dưới dạng tệp PDF duy nhất.
```
pres1.save("document.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng được hỗ trợ khác để hợp nhất" subTitle="Bạn cũng có thể kết hợp các định dạng tệp khác. Xem các định dạng được hỗ trợ khác bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/ppt/" name="PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pptx/" name="PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf/" name="PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/odp/" name="ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp/" name="OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pot/" name="POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/potm/" name="POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/potx/" name="POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pps/" name="PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/ppsm/" name="PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/ppsx/" name="PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pptm/" name="PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/fodp/" name="FODP" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
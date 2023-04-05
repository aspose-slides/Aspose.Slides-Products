---
title: Hợp nhất các tệp PDF thành ODP bằng Python
url: /vi/python-net/merge/pdf-to-odp/
keywords: Hợp nhất PDF thành ODP, Nối PDF thành ODP, Kết hợp PDF thành ODP, PowerPoint, Bản trình bày, ODP, Python, Aspose
description: Hợp nhất nhiều tệp PDF bằng Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Hợp nhất các tệp PDF thành ODP với nhau bằng Python" h2="API Python tốc độ cao và đa nền tảng giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp trình bày Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất PDF với ODP bằng Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/) là một thư viện Python mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để kết hợp nhiều bản trình bày PDF. Khi bạn hợp nhất một bản trình bày với một bản trình bày khác, bạn đang kết hợp hiệu quả các trang trình bày của chúng trong một bản trình bày duy nhất để có được một tệp. Aspose.Slides cho phép bạn hợp nhất hai bản trình bày theo những cách khác nhau. Bạn có thể hợp nhất các bản trình bày với tất cả các hình dạng, phong cách, văn bản, định dạng, nhận xét, hoạt ảnh, v.v. của chúng mà không phải lo lắng về việc mất chất lượng hoặc dữ liệu.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hợp nhất các tệp PDF thành ODP bằng Python" %}}
Để hợp nhất các bản trình bày PowerPoint, bạn sẽ cần sao chép các trang chiếu từ bản trình bày này sang bản trình bày khác.

{{% blocks/products/pf/agp/code-block title="Mã Python để hợp nhất nhiều PDF thành một tệp ODP duy nhất" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation() as pres1:
    pres1.slides.remove_at(0)
    pres1.slides.add_from_pdf("document1.pdf")
    with slides.Presentation() as pres2:
        pres2.slides.remove_at(0)
        pres2.slides.add_from_pdf("document2.pdf")
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
    pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách hợp nhất PDF với ODP bằng cách sử dụng Aspose.Slides cho Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để hợp nhất hai tệp PDF và lưu kết quả dưới dạng ODP bằng Python." >}}

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
Mở tệp nguồn PDF bằng Python.
```
pres1 = slides.Presentation('pres1.pdf')
pres2 = slides.Presentation('pres2.pdf')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kết hợp các tệp PDF bằng phương pháp [** add_clone **](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu bản trình bày và nhận kết quả dưới dạng tệp ODP duy nhất.
```
pres1.save("presentation.odp", slides.export.SaveFormat.ODP)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Hợp nhất các tệp PDF trực tuyến" sectionDescription="[Cách hợp nhất PDF trong Python](https://products.aspose.com/slides/vi/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Xuất PDF sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể kết hợp PDF và lưu vào các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-pptx/" name="PDF TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-ppt/" name="PDF TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-html/" name="PDF TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-png/" name="PDF TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-bmp/" name="PDF TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-jpg/" name="PDF TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-fodp/" name="PDF TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-gif/" name="PDF TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-otp/" name="PDF TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-pot/" name="PDF TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-potm/" name="PDF TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-potx/" name="PDF TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-pps/" name="PDF TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-ppsm/" name="PDF TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-ppsx/" name="PDF TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-pptm/" name="PDF TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-svg/" name="PDF TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-tiff/" name="PDF TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/pdf-to-xps/" name="PDF TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
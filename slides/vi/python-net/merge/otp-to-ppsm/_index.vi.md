---
title: Hợp nhất các tệp OTP thành PPSM bằng Python
url: /vi/python-net/merge/otp-to-ppsm/
keywords: Hợp nhất OTP thành PPSM, Nối OTP thành PPSM, Kết hợp OTP thành PPSM, PowerPoint, Bản trình bày, PPSM, Python, Aspose
description: Hợp nhất nhiều tệp OTP bằng Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Hợp nhất các tệp OTP thành PPSM với nhau bằng Python" h2="API Python tốc độ cao và đa nền tảng giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp trình bày Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất OTP với PPSM bằng Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/) là một thư viện Python mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để kết hợp nhiều bản trình bày OTP. Khi bạn hợp nhất một bản trình bày với một bản trình bày khác, bạn đang kết hợp hiệu quả các trang trình bày của chúng trong một bản trình bày duy nhất để có được một tệp. Aspose.Slides cho phép bạn hợp nhất hai bản trình bày theo những cách khác nhau. Bạn có thể hợp nhất các bản trình bày với tất cả các hình dạng, phong cách, văn bản, định dạng, nhận xét, hoạt ảnh, v.v. của chúng mà không phải lo lắng về việc mất chất lượng hoặc dữ liệu.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hợp nhất các tệp OTP thành PPSM bằng Python" %}}
Để hợp nhất các bản trình bày PowerPoint, bạn sẽ cần sao chép các trang chiếu từ bản trình bày này sang bản trình bày khác.

{{% blocks/products/pf/agp/code-block title="Mã Python để hợp nhất nhiều OTP thành một tệp PPSM duy nhất" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.otp") as pres1:
    with slides.Presentation("presentation2.otp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.ppsm", slides.export.SaveFormat.PPSM)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách hợp nhất OTP với PPSM bằng cách sử dụng Aspose.Slides cho Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để hợp nhất hai tệp OTP và lưu kết quả dưới dạng PPSM bằng Python." >}}

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
Mở tệp nguồn OTP bằng Python.
```
pres1 = slides.Presentation('pres1.otp')
pres2 = slides.Presentation('pres2.otp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kết hợp các tệp OTP bằng phương pháp [** add_clone **](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu bản trình bày và nhận kết quả dưới dạng tệp PPSM duy nhất.
```
pres1.save("presentation.ppsm", slides.export.SaveFormat.PPSM)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Hợp nhất các tệp PDF trực tuyến" sectionDescription="[Cách hợp nhất PDF trong Python](https://products.aspose.com/slides/vi/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Xuất OTP sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể kết hợp OTP và lưu vào các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-pptx/" name="OTP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-ppt/" name="OTP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-pdf/" name="OTP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-html/" name="OTP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-png/" name="OTP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-bmp/" name="OTP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-jpg/" name="OTP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-fodp/" name="OTP TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-gif/" name="OTP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-odp/" name="OTP TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-pot/" name="OTP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-potm/" name="OTP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-potx/" name="OTP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-pps/" name="OTP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-ppsx/" name="OTP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-pptm/" name="OTP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-svg/" name="OTP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-tiff/" name="OTP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/merge/otp-to-xps/" name="OTP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
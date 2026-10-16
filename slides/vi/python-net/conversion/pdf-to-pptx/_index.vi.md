---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi PDF thành PPTX trong Python
url: /vi/python-net/conversion/pdf-to-pptx/
keywords: PDF sang PPTX, Chuyển đổi PDF sang PPTX, API Python, Thư viện Python, PDF, PPTX
description: Chuyển đổi PDF thành PPTX trong Python. Sử dụng API thư viện Python để chuyển đổi tệp PDF thành tệp PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi PDF thành PPTX trong Python" h2="Thư viện Python tốc độ cao và đa nền tảng giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp bản trình bày Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PDF sang PPTX bằng Python" variant="code" %}}

Để chuyển đổi PDF sang PPTX, bạn cần tạo Bản trình bày từ tệp PDF và lưu dưới dạng PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã Python để chuyển đổi PDF thành PPTX" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing
        
with slides.Presentation() as pres:
    pres.slides.add_from_pdf("document.pdf")
    pres.save("OutputPresentation.pptx", slides.export.SaveFormat.PPTX)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PDF thành PPTX trong Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/) là một thư viện Python mạnh mẽ để tạo và thao tác với các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi PDF thành PPTX. Bằng cách sử dụng **Aspose.Slides cho Python qua .NET**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp PDF sang PPTX chỉ bằng một vài dòng mã Python.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Python nhanh chóng xuất tệp PDF sang định dạng tệp PPTX. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi PDF thành PPTXs và nhiều định dạng tệp khác

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi PDF sang PPTX bằng API Aspose.Slides cho Python" intro="Đây là các bước để chuyển đổi PDF thành PPTX trong Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/vi/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm tham chiếu thư viện (nhập thư viện) vào dự án Python của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp nguồn PDF bằng Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu kết quả dưới dạng tệp PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Chuyển đổi trực tuyến miễn phí"
  description="[Cách chuyển đổi PPT sang HTML bằng Python](https://products.aspose.com/slides/vi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chuyển đổi PDF sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PDF và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

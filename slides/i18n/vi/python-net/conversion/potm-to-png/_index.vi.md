---
title: Chuyển đổi POTM sang PNG bằng Python
weight: 1200
url: /vi/python-net/conversion/potm-to-png/ 
keywords: "Convert, PowerPoint, POTM, PNG, Presentation, Python"
description: Mã mẫu để chuyển đổi POTM sang PNG Python. Sử dụng API Python của PowerPoint để chuyển đổi hàng loạt tệp POTM sang tệp PNG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi POTM sang PNG bằng Python" h2="Thư viện PowerPoint Python mạnh mẽ để chuyển đổi POTM sang PNG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Chuyển đổi POTM sang PNG bằng Python" %}}

Bạn cần lập trình chuyển đổi tệp POTM sang PNG? Sử dụng [* Aspose.Slides cho Python qua .NET *](https://products.aspose.com/slides/python-net/), bất kỳ nhà phát triển nào cũng có thể chuyển đổi định dạng POTM sang PNG chỉ với một vài dòng mã Python.

Là một API xử lý bản trình bày hiện đại, Aspose.Slides for Python tạo PNG từ POTM một cách nhanh chóng. Kiểm tra chất lượng của chuyển đổi POTM sang PNG ngay trong [trình duyệt] của bạn (https://products.aspose.app/slides/conversion/ppt-to-png). Thư viện PPTX của Aspose PowerPoint cho phép bạn chuyển đổi các tập tin POTM sang nhiều định dạng phổ biến.

Bạn có thể cài đặt thư viện từ [PyPI](https://pypi.org/project/Aspose.Slides/) bằng lệnh pip sau:

{{% blocks/products/pf/agp/code-block title="Bảng điều khiển / Thiết bị đầu cuối" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi POTM sang PNG bằng Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để chuyển đổi tệp POTM sang PNG bằng Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải tệp POTM với một phiên bản của lớp Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat.PNG làm tham số
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tệp POTM sẽ được lưu theo đường dẫn đã chỉ định
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã nguồn mẫu chuyển đổi Python, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Hệ điều hành dựa trên Microsoft Windows hoặc Linux (xem [thêm](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 trở lên
- Aspose.Slides cho Python được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã mẫu này hiển thị Chuyển đổi Python từ POTM sang PNG" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.potm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Lưu POTM dưới dạng PNG bằng Python" %}}
Sử dụng ứng dụng miễn phí để xem trình diễn về quá trình chuyển đổi POTM sang PNG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="potm-to-png"
        sectionTitle="Ứng dụng miễn phí để chuyển đổi POTM thành PNG" 
        sectionDescription="[Hãy thử ứng dụng miễn phí của chúng tôi để chuyển đổi PPT sang PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi POTM sang nhiều định dạng tập tin khác. Xem các chuyển đổi được hỗ trợ khác bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-bmp/" name="POTM TO BMP" description="Hình ảnh bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-emf/" name="POTM TO EMF" description="Định dạng siêu tệp nâng cao" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-fodp/" name="POTM TO FODP" description="Bản trình bày XML phẳng OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-gif/" name="POTM TO GIF" description="Định dạng trao đổi đồ họa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-html/" name="POTM TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-jpg/" name="POTM TO JPG" description="Hình ảnh JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-odp/" name="POTM TO ODP" description="Định dạng bản trình bày OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-otp/" name="POTM TO OTP" description="Định dạng chuẩn OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pdf/" name="POTM TO PDF" description="Định dạng tài liệu di động" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pot/" name="POTM TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-potx/" name="POTM TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pps/" name="POTM TO PPS" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Trình chiếu hỗ trợ macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Định dạng bản trình bày XML mở" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-svg/" name="POTM TO SVG" description="Đồ họa vector có thể mở rộng" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-swf/" name="POTM TO SWF" description="Định dạng SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-xps/" name="POTM TO XPS" description="Thông số kỹ thuật giấy XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
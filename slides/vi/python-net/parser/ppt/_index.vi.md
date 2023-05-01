---
title: Trích xuất Văn bản và Hình ảnh từ Tệp PPT bằng Python
url: /vi/python-net/parser/ppt/
keywords: phân tích cú pháp PPT bằng Python, trình phân tích cú pháp PPT Python, trích xuất dữ liệu từ PPT trong Python, trích xuất văn bản từ PPT bằng Python, trích xuất hình ảnh từ PPT bằng Python
description: Mã nguồn Python để phân tích bản trình bày PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Trích xuất văn bản và hình ảnh từ bản trình bày PPT bằng Python" h2="Xây dựng các ứng dụng Python của riêng bạn để trích xuất các tệp văn bản, hình ảnh, video và âm thanh từ PowerPoint bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Trích xuất văn bản từ bản trình bày PPT qua Python" %}}
Để quét văn bản từ toàn bộ bản trình bày, hãy sử dụng phương thức tĩnh [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) do lớp SlideUtil đưa ra. Mã bên dưới quét văn bản và thông tin định dạng từ bản trình bày, bao gồm các trang chiếu chính.
{{% blocks/products/pf/agp/code-block title="Trích xuất Văn bản từ Bản trình bày PPT bằng Python" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a PPT file
with slides.Presentation("pres.ppt") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the PPT
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách trích xuất văn bản từ PPT qua Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để Phân tích tệp PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPT với phiên bản Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nhận một mảng các đối tượng TextFrame từ tất cả các trang chiếu trong PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lặp qua Mảng TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lặp qua các đoạn trong TextFrame hiện tại
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lặp qua các phần trong Đoạn văn hiện tại
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nhận văn bản trong phần hiện tại
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng phân tích cú pháp được hỗ trợ khác" subTitle="Sử dụng Python, Bạn cũng có thể quét các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
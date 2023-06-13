---
title: Thêm Hình mờ vào Tệp Bản trình bày ODP bằng Python
url: /vi/python-net/watermark/odp/
keywords: Thêm Hình mờ ODP, Thêm Hình mờ Văn bản ODP, Thêm Hình mờ Hình ảnh ODP
description: Mã nguồn Python để thêm Hình mờ vào Bản trình bày ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Thêm Hình mờ vào Bản trình bày ODP bằng Python" h2="Xây dựng các ứng dụng Python của riêng bạn để chèn hình mờ văn bản hoặc hình ảnh vào bản trình bày PPT, PPTX hoặc ODP bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Thêm Hình mờ vào Bản trình bày ODP qua Python" %}}
Sử dụng Aspose.Slides for Python via .NET, bạn có thể thêm hình mờ vào bản trình bày ODP. Hình mờ là một phần thiết yếu của bất kỳ bài thuyết trình nào. Chúng được sử dụng để bảo vệ nội dung của bài thuyết trình không bị sao chép hoặc sử dụng trái phép. Hình mờ là một hình ảnh hoặc văn bản hiển thị hoặc không nhìn thấy được đặt ở trên cùng của bản trình bày. Nó có thể được sử dụng để xác định chủ sở hữu của bài thuyết trình và để ngăn chặn việc sử dụng trái phép. Hình nền mờ cũng có thể được sử dụng để thêm nét chuyên nghiệp cho bản trình bày và làm cho bản trình bày trông bóng bẩy hơn. 
{{% blocks/products/pf/agp/code-block title="Thêm Hình mờ văn bản vào ODP bằng Python" offSpacer="true" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as draw

with slides.Presentation() as pres:
    master = pres.masters[0]

    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, 100, 100)
    watermarkTextFrame = watermarkShape.add_text_frame("Watermark")

    # Lock Watermark from Editing
    watermarkShape.shape_lock.select_locked = True
    watermarkShape.shape_lock.size_locked = True
    watermarkShape.shape_lock.text_locked = True
    watermarkShape.shape_lock.position_locked = True
    watermarkShape.shape_lock.grouping_locked = True
    
    # Set Text Watermark Transparency
    watermarkPortion = watermarkTextFrame.paragraphs[0].portions[0]
    watermarkPortion.portion_format.fill_format.fill_type = slides.FillType.SOLID
    watermarkPortion.portion_format.fill_format.solid_fill_color.color = draw.Color.from_argb(150, 200, 200, 200)
    
    # Set Font Size of Text Watermark
    watermarkPortion.portion_format.font_height = 16

    pres.save("watermark.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Thêm hình mờ vào bản trình bày ODP bằng Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation() as presentation:
    with open("image1.png", "rb") as fs:
        data = fs.read()
    image = presentation.images.add_image(data)

    master = presentation.masters[0]
    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, image.width, image.height)
    
    watermarkShape.fill_format.fill_type = slides.FillType.PICTURE
    watermarkShape.fill_format.picture_fill_format.picture.image = image
    watermarkShape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH

    presentation.save("watermark2.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách thêm Hình mờ vào ODP qua Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để thêm hình mờ văn bản vào tệp ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải ODP với phiên bản Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chọn bản trình bày chính
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm loại hình bằng phương pháp AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm văn bản hình mờ bằng phương pháp AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng được hỗ trợ khác" subTitle="Sử dụng Python, Bạn cũng có thể thêm Hình mờ vào các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
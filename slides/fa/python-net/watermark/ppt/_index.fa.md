---
title: اضافه کردن واترمارک به فایل‌های ارائه PPT با استفاده از Python
url: /fa/python-net/watermark/ppt/
keywords: افزودن واترمارک PPT، افزودن واترمارک متنی PPT، افزودن واترمارک تصویری PPT
description: کد منبع Python برای افزودن واترمارک به ارائه PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="اضافه کردن واترمارک به ارائه PPT با استفاده از Python" h2="برنامه های Python خود را بسازید تا با استفاده از API های سمت سرور، متن یا علامت تصویر را در ارائه PPT، PPTX یا ODP وارد کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="اضافه کردن واترمارک به ارائه PPT از طریق Python" %}}
با استفاده از Aspose.Slides for Python via .NET، می‌توانید واترمارک را به ارائه PPT اضافه کنید. واترمارک ها بخش مهمی از هر ارائه هستند. آنها برای محافظت از محتوای ارائه در برابر کپی یا استفاده بدون اجازه استفاده می شوند. واترمارک یک تصویر یا متن قابل مشاهده یا نامرئی است که در بالای ارائه قرار می گیرد. می توان از آن برای شناسایی صاحب ارائه و جلوگیری از استفاده غیرمجاز استفاده کرد. همچنین می‌توان از واترمارک‌ها برای افزودن حسی حرفه‌ای به ارائه استفاده کرد و آن را صیقلی‌تر نشان داد. 
{{% blocks/products/pf/agp/code-block title="اضافه کردن متن واترمارک به PPT با استفاده از Python" offSpacer="true" %}}

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

    pres.save("watermark.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="اضافه کردن واترمارک تصویر به ارائه PPT با استفاده از Python" offSpacer="true" %}}

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

    presentation.save("watermark2.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه افزودن واترمارک به PPT از طریق Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای افزودن واترمارک متنی به فایل‌های PPT است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT را با یک نمونه از Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه اصلی را انتخاب کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نوع شکل را با استفاده از روش AddAutoShape اضافه کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
متن واترمارک را با استفاده از روش AddTextFrame اضافه کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب PPT ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده" subTitle="با استفاده از Python، می‌توانید واترمارک را نیز به قالب‌های زیر اضافه کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
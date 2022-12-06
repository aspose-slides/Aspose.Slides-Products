---
title: PNG را به PDF در پایتون ادغام کنید
url: /fa/python-net/merge/png-to-pdf/
keywords: PNG به PDF، ادغام PNG به PDF، پیوستن PNG به PDF، PDF، PNG، Python API، کتابخانه Python
description: PNG را به PDF در پایتون ادغام کنید. از API کتابخانه پایتون برای ترکیب PNG و PDF استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PNG را به PDF در پایتون ادغام کنید" h2="کتابخانه Python پرسرعت و چند پلتفرمی برای ادغام فایل‌های PNG با PDF با استفاده از کد پایتون" >}}

{{% blocks/products/pf/feature-page-section h2="ادغام PNG به PDF با استفاده از Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون است که برای ایجاد، تبدیل، ادغام و دستکاری ارائه ها، تصاویر استفاده می شود. و فایل های دیگر هنگامی که PNG را با PDF ادغام می کنید، به طور موثر تصاویر PNG را برای به دست آوردن یک فایل PDF ترکیب می کنید.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PNG را به PDF در پایتون ادغام کنید" %}}
با استفاده از [**Aspose.Slides برای Python از طریق .NET**](https://products.aspose.com/slides/fa/python-net/)، می توانید PNG را به سرعت با چند خط کد به PDF ادغام کنید.

{{% blocks/products/pf/agp/code-block title="کد پایتون برای ادغام PNG به PDF" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="نحوه ادغام PNG با PDF در پایتون" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک نمونه از کلاس Presentation ایجاد کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تصاویر PNG را که می خواهید به عنوان قاب عکس ادغام کنید بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PDF حاصل را ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="فایل های دیگر را ادغام کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ترکیب کنید تا یک فایل واحد بدست آورید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
title: تبدیل تصویر به PPT در پایتون
url: /fa/python-net/conversion/image-to-ppt/
keywords: تصویر به PPT، تبدیل تصویر به PPT، Python API، کتابخانه Python، تصویر، PPT
description: تبدیل تصویر به PPT در پایتون برای تبدیل فایل های تصویری به PDF از API کتابخانه پایتون استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل تصویر به PPT در پایتون" h2="کتابخانه Python با سرعت بالا و چند پلتفرمی که به توسعه برنامه‌هایی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="تبدیل تصویر به PPT در پایتون" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه های انعطاف پذیری را برای تبدیل تصویر به PPT ارائه می دهد. با استفاده از **Aspose.Slides برای پایتون از طریق دات نت**، هر توسعه دهنده یا برنامه ای می تواند تصویر را تنها با چند خط کد پایتون به فایل های PPT تبدیل کند.

Aspose.Slides برای Python به عنوان یک API مدرن برای پردازش اسناد، فایل‌های تصویر را به سرعت به فرمت‌های فایل PPT صادر می‌کند. کتابخانه Aspose PowerPoint به شما امکان تبدیل تصویر به PDF و بسیاری از فرمت های فایل دیگر را می دهد

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با پایتون تصویر را به PPT تبدیل کنید" %}}
برای تبدیل تصویر به PPT، باید Presentation را از فایل Image ایجاد کنید و آن را به عنوان PPT ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد پایتون برای تبدیل تصویر به PPT" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.ppt", slides.export.SaveFormat.PPT)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل تصویر به PPT با استفاده از Aspose.Slides برای Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل تصویر به PPT در پایتون است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه پایتون خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های Image منبع را در پایتون باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PPT ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل تصویر به سایر فرمت های پشتیبانی شده" subTitle="شما همچنین می توانید تصویر را تبدیل کرده و به فرمت های فایل دیگر ذخیره کنید. همه فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
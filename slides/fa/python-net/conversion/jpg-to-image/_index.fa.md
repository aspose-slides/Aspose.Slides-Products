---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: در پایتون JPG را به Image تبدیل کنید
url: /fa/python-net/conversion/jpg-to-image/
keywords: JPG به Image، تبدیل JPG به Image، Python API، Python Library، JPG، Image
description: در پایتون JPG را به Image تبدیل کنید. از API کتابخانه پایتون برای تبدیل فایل‌های JPG به Image استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="در پایتون JPG را به Image تبدیل کنید" h2="کتابخانه Python با سرعت بالا و چند پلتفرمی که به توسعه برنامه‌هایی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از پایتون، JPG را به Image تبدیل کنید" variant="code" %}}

برای تبدیل JPG به Image، باید Presentation را از فایل JPG ایجاد کنید و آن را به عنوان Image ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد پایتون برای تبدیل JPG به Image" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="در پایتون JPG را به Image تبدیل کنید" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل JPG به Image ارائه می‌کند. با استفاده از **Aspose.Slides برای پایتون از طریق دات نت**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های JPG را تنها با چند خط کد پایتون به Image تبدیل کند.

Aspose.Slides برای Python به عنوان یک API مدرن برای پردازش اسناد، فایل‌های JPG را به فرمت‌های فایل Image صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد JPG را به Image و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل JPG به Image با استفاده از Aspose.Slides for Python API" intro="این مراحل برای تبدیل JPG به Image در پایتون است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) را نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه پایتون خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های منبع JPG را در پایتون باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نتیجه را به عنوان فایل Image ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="مبدل آنلاین رایگان"
  description="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تبدیل JPG به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید JPG را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: در پایتون Image را به PDF تبدیل کنید
url: /fa/python-net/conversion/image-to-pdf/
keywords: Image به PDF، تبدیل Image به PDF، Python API، Python Library، Image، PDF
description: در پایتون Image را به PDF تبدیل کنید. از API کتابخانه پایتون برای تبدیل فایل‌های Image به PDF استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="در پایتون Image را به PDF تبدیل کنید" h2="کتابخانه Python با سرعت بالا و چند پلتفرمی که به توسعه برنامه‌هایی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از پایتون، Image را به PDF تبدیل کنید" variant="code" %}}

برای تبدیل Image به PDF، باید Presentation را از فایل Image ایجاد کنید و آن را به عنوان PDF ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد پایتون برای تبدیل Image به PDF" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="در پایتون Image را به PDF تبدیل کنید" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل Image به PDF ارائه می‌کند. با استفاده از **Aspose.Slides برای پایتون از طریق دات نت**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های Image را تنها با چند خط کد پایتون به PDF تبدیل کند.

Aspose.Slides برای Python به عنوان یک API مدرن برای پردازش اسناد، فایل‌های Image را به فرمت‌های فایل PDF صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد Image را به PDF و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل Image به PDF با استفاده از Aspose.Slides for Python API" intro="این مراحل برای تبدیل Image به PDF در پایتون است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) را نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه پایتون خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های منبع Image را در پایتون باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نتیجه را به عنوان فایل PDF ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="مبدل آنلاین رایگان"
  description="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تبدیل Image به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید Image را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

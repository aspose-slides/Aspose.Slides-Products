---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: در پایتون SVG را به PNG تبدیل کنید
url: /fa/python-net/conversion/svg-to-png/
keywords: SVG به PNG، تبدیل SVG به PNG، Python API، Python Library، SVG، PNG
description: در پایتون SVG را به PNG تبدیل کنید. از API کتابخانه پایتون برای تبدیل فایل‌های SVG به PNG استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="در پایتون SVG را به PNG تبدیل کنید" h2="کتابخانه Python با سرعت بالا و چند پلتفرمی که به توسعه برنامه‌هایی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از پایتون، SVG را به PNG تبدیل کنید" variant="code" %}}

برای تبدیل SVG به PNG، باید Presentation را از فایل SVG ایجاد کنید و آن را به عنوان PNG ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد پایتون برای تبدیل SVG به PNG" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open("image.svg", "rb") as file:
        svgContent = file.read()
    svgImage = slides.SvgImage(svgContent)
    ppImage = pres.images.add_image(svgImage)
    pres.slides[0].shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, ppImage.width, ppImage.height, ppImage)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="در پایتون SVG را به PNG تبدیل کنید" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل SVG به PNG ارائه می‌کند. با استفاده از **Aspose.Slides برای پایتون از طریق دات نت**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های SVG را تنها با چند خط کد پایتون به PNG تبدیل کند.

Aspose.Slides برای Python به عنوان یک API مدرن برای پردازش اسناد، فایل‌های SVG را به فرمت‌های فایل PNG صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد SVG را به PNG و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل SVG به PNG با استفاده از Aspose.Slides for Python API" intro="این مراحل برای تبدیل SVG به PNG در پایتون است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) را نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه پایتون خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های منبع SVG را در پایتون باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نتیجه را به عنوان فایل PNG ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="ساخته شده با Aspose.Slides" title="تبدیل آنلاین SVG به PNG" description="برنامه رایگان Aspose.Slides Conversion با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های SVG شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Conversion" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" upload="فایل خود را رها یا بارگذاری کنید" saveAs="ذخیره با فرمت" convert="تبدیل" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌ها را تبدیل می‌کند.
- فایل‌های SVG را بارگذاری کنید و آن‌ها را با فرمت PNG ذخیره کنید.
- نتیجه را دانلود کنید یا فایل‌های بیشتری را تبدیل کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تبدیل SVG به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید SVG را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

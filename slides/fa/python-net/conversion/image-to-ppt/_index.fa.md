---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل تصویر به PPT در پایتون
url: /fa/python-net/conversion/image-to-ppt/
keywords: تصویر به PPT، تبدیل تصویر به PPT، Python API، کتابخانه Python، تصویر، PPT
description: تبدیل تصویر به PPT در پایتون برای تبدیل فایل های تصویری به PDF از API کتابخانه پایتون استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل تصویر به PPT در پایتون" h2="کتابخانه Python با سرعت بالا و چند پلتفرمی که به توسعه برنامه‌هایی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با پایتون تصویر را به PPT تبدیل کنید" variant="code" %}}

برای تبدیل تصویر به PPT، باید Presentation را از فایل Image ایجاد کنید و آن را به عنوان PPT ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد پایتون برای تبدیل تصویر به PPT" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.ppt", slides.export.SaveFormat.PPT)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تبدیل تصویر به PPT در پایتون" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه های انعطاف پذیری را برای تبدیل تصویر به PPT ارائه می دهد. با استفاده از **Aspose.Slides برای پایتون از طریق دات نت**، هر توسعه دهنده یا برنامه ای می تواند تصویر را تنها با چند خط کد پایتون به فایل های PPT تبدیل کند.

Aspose.Slides برای Python به عنوان یک API مدرن برای پردازش اسناد، فایل‌های تصویر را به سرعت به فرمت‌های فایل PPT صادر می‌کند. کتابخانه Aspose PowerPoint به شما امکان تبدیل تصویر به PDF و بسیاری از فرمت های فایل دیگر را می دهد

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل تصویر به PPT با استفاده از Aspose.Slides برای Python API" intro="این مراحل برای تبدیل تصویر به PPT در پایتون است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) را نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه پایتون خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های Image منبع را در پایتون باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نتیجه را به عنوان فایل PPT ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="ساخته شده با Aspose.Slides" title="تبدیل آنلاین تصویر به PPT" description="برنامه رایگان Aspose.Slides Conversion با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های تصویر شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Conversion" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" upload="فایل خود را رها یا بارگذاری کنید" saveAs="ذخیره با فرمت" convert="تبدیل" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌ها را تبدیل می‌کند.
- فایل‌های تصویر را بارگذاری کنید و آن‌ها را با فرمت PPT ذخیره کنید.
- نتیجه را دانلود کنید یا فایل‌های بیشتری را تبدیل کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تبدیل تصویر به سایر فرمت های پشتیبانی شده" subTitle="شما همچنین می توانید تصویر را تبدیل کرده و به فرمت های فایل دیگر ذخیره کنید. همه فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

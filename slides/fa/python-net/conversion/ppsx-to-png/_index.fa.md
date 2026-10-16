---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPSX را به PNG در پایتون تبدیل کنید
weight: 2080
url: /fa/python-net/conversion/ppsx-to-png/ 
keywords: "Convert, PowerPoint, PPSX, PNG, Presentation, Python"
description: کد نمونه برای تبدیل PPSX به PNG پایتون. برای تبدیل دسته ای فایل های PPSX به فایل های PNG از PowerPoint Python API استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSX را به PNG در پایتون تبدیل کنید" h2="کتابخانه قدرتمند پاورپوینت پایتون برای تبدیل PPSX به PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSX را به PNG در پایتون تبدیل کنید" %}}

آیا نیاز به تبدیل فایل های PPSX به PNG دارید؟ با استفاده از [*Aspose.Slides برای پایتون از طریق .NET*](https://products.aspose.com/slides/fa/python-net/) هر توسعه دهنده می تواند PPSX را تنها با چند خط کد پایتون به فرمت PNG تبدیل کند.

Aspose.Slides برای Python به عنوان یک API پردازش ارائه مدرن، به سرعت PNG را از PPSX ایجاد می کند. کیفیت تبدیل PPSX به PNG را دقیقاً در [مرورگر] خود آزمایش کنید (https://products.aspose.app/slides/conversion/ppt-to-png). کتابخانه Aspose PowerPoint PPTX به شما امکان می دهد فایل های PPSX را به بسیاری از فرمت های محبوب تبدیل کنید.

می‌توانید کتابخانه را از [PyPI](https://pypi.org/project/Aspose.Slides/) با استفاده از دستور pip زیر نصب کنید:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="کنسول / ترمینال" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSX را به عنوان PNG در پایتون ذخیره کنید" %}}

از برنامه رایگان برای مشاهده نمایشی از فرآیند تبدیل PPSX به PNG استفاده کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="این کد نمونه تبدیل PPSX به PNG Python را نشان می دهد" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsx") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل PPSX به PNG در پایتون" intro="این مراحل برای تبدیل یک فایل PPSX به PNG با استفاده از پایتون است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPSX را با یک نمونه از کلاس Presentation بارگیری کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با مشخص کردن مسیر فایل خروجی و SaveFormat.PNG به عنوان پارامتر، متد «save» را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPSX در مسیر مشخص شده ذخیره می شود{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="قبل از اجرای کد منبع نمونه تبدیل پایتون، مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- سیستم عامل مبتنی بر ویندوز مایکروسافت یا لینوکس (به [بیشتر](https://docs.aspose.com/slides/python-net/system-requirements/) مراجعه کنید).
- پایتون 3.5 یا بالاتر
- Aspose.Slides برای پایتون در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="برنامه رایگان برای تبدیل PPSX به PNG"
  description="[برنامه رایگان ما را برای تبدیل PPT به PNG امتحان کنید](https://products.aspose.app/slides/conversion/ppt-to-png)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="شما همچنین می توانید PPSX را به بسیاری از فرمت های فایل دیگر تبدیل کنید. سایر تبدیل های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="تصویر بیت مپ" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="فرمت متافایل پیشرفته" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocument Flat XML Presentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="فرمت تبادل گرافیکی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="زبان نشانه گذاری فرا متنی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="تصویر JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="فرمت ارائه اسناد باز" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="فرمت استاندارد OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="فرمت سند قابل حمل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="قالب ارائه XML را باز کنید" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="گرافیک برداری مقیاس پذیر" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="فرمت SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="فرمت تصویر برچسب شده" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

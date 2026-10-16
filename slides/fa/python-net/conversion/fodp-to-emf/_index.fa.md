---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل FODP به EMF در پایتون
weight: 20
url: /fa/python-net/conversion/fodp-to-emf/ 
keywords: "Convert, PowerPoint, FODP, EMF, Presentation, Python"
description: کد نمونه برای تبدیل FODP به EMF پایتون. برای تبدیل دسته ای فایل های FODP به فایل های EMF از PowerPoint Python API استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل FODP به EMF در پایتون" h2="کتابخانه قدرتمند پاورپوینت پایتون برای تبدیل FODP به EMF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تبدیل FODP به EMF در پایتون" %}}

آیا نیاز به تبدیل فایل های FODP به EMF دارید؟ با استفاده از [*Aspose.Slides برای پایتون از طریق .NET*](https://products.aspose.com/slides/fa/python-net/) هر توسعه دهنده می تواند FODP را تنها با چند خط کد پایتون به فرمت EMF تبدیل کند.

به عنوان یک API پردازش ارائه مدرن، Aspose.Slides برای Python به سرعت EMF را از FODP ایجاد می کند. کیفیت تبدیل FODP به EMF را درست در [مرورگر] خود آزمایش کنید (https://products.aspose.app/slides/conversion). کتابخانه Aspose PowerPoint PPTX به شما امکان می دهد فایل های FODP را به بسیاری از فرمت های محبوب تبدیل کنید.

می‌توانید کتابخانه را از [PyPI](https://pypi.org/project/Aspose.Slides/) با استفاده از دستور pip زیر نصب کنید:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="کنسول / ترمینال" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="FODP را به عنوان EMF در پایتون ذخیره کنید" %}}

از برنامه رایگان برای دیدن نمایشی از فرآیند تبدیل FODP به EMF استفاده کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="این کد نمونه تبدیل FODP به EMF Python را نشان می دهد" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.fodp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل FODP به EMF در پایتون" intro="این مراحل برای تبدیل یک فایل FODP به EMF با استفاده از پایتون است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل FODP را با نمونه ای از کلاس Presentation بارگیری کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با مشخص کردن مسیر فایل خروجی و SaveFormat.EMF به عنوان پارامتر، متد «save» را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل FODP در مسیر مشخص شده ذخیره می شود{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="قبل از اجرای کد منبع نمونه تبدیل پایتون، مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- سیستم عامل مبتنی بر ویندوز مایکروسافت یا لینوکس (به [بیشتر](https://docs.aspose.com/slides/python-net/system-requirements/) مراجعه کنید).
- پایتون 3.5 یا بالاتر
- Aspose.Slides برای پایتون در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="برنامه رایگان برای تبدیل FODP به EMF"
  description="[برنامه رایگان Collage ما را امتحان کنید](https://products.aspose.app/slides/collage/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="شما همچنین می توانید FODP را به بسیاری از فرمت های فایل دیگر تبدیل کنید. سایر تبدیل های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-bmp/" name="FODP TO BMP" description="تصویر بیت مپ" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-gif/" name="FODP TO GIF" description="فرمت تبادل گرافیکی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-html/" name="FODP TO HTML" description="زبان نشانه گذاری فرا متنی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-jpg/" name="FODP TO JPG" description="تصویر JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-odp/" name="FODP TO ODP" description="فرمت ارائه اسناد باز" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-otp/" name="FODP TO OTP" description="فرمت استاندارد OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-pdf/" name="FODP TO PDF" description="فرمت سند قابل حمل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-png/" name="FODP TO PNG" description="گرافیک شبکه قابل حمل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-pot/" name="FODP TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-potm/" name="FODP TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-potx/" name="FODP TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-pps/" name="FODP TO PPS" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-ppt/" name="FODP TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="قالب ارائه XML را باز کنید" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-svg/" name="FODP TO SVG" description="گرافیک برداری مقیاس پذیر" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-swf/" name="FODP TO SWF" description="فرمت SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="فرمت تصویر برچسب شده" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/fodp-to-xps/" name="FODP TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل PPSM به EMF در پایتون
weight: 1780
url: /fa/python-net/conversion/ppsm-to-emf/ 
keywords: "Convert, PowerPoint, PPSM, EMF, Presentation, Python"
description: کد نمونه برای تبدیل PPSM به EMF پایتون. برای تبدیل دسته ای فایل های PPSM به فایل های EMF از PowerPoint Python API استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل PPSM به EMF در پایتون" h2="کتابخانه قدرتمند پاورپوینت پایتون برای تبدیل PPSM به EMF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تبدیل PPSM به EMF در پایتون" %}}

آیا نیاز به تبدیل فایل های PPSM به EMF دارید؟ با استفاده از [*Aspose.Slides برای پایتون از طریق .NET*](https://products.aspose.com/slides/fa/python-net/) هر توسعه دهنده می تواند تنها با چند خط کد پایتون، PPSM را به فرمت EMF تبدیل کند.

به عنوان یک API پردازش ارائه مدرن، Aspose.Slides برای Python به سرعت EMF را از PPSM ایجاد می کند. کیفیت تبدیل PPSM به EMF را مستقیماً در [مرورگر] خود آزمایش کنید (https://products.aspose.app/slides/conversion). کتابخانه Aspose PowerPoint PPTX به شما امکان می دهد فایل های PPSM را به بسیاری از فرمت های محبوب تبدیل کنید.

می‌توانید کتابخانه را از [PyPI](https://pypi.org/project/Aspose.Slides/) با استفاده از دستور pip زیر نصب کنید:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="کنسول / ترمینال" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSM را به عنوان EMF در پایتون ذخیره کنید" %}}

برای مشاهده نمایشی از فرآیند تبدیل PPSM به EMF از برنامه رایگان استفاده کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="این کد نمونه تبدیل PPSM به EMF Python را نشان می دهد" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل PPSM به EMF در پایتون" intro="این مراحل برای تبدیل یک فایل PPSM به EMF با استفاده از پایتون است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPSM را با نمونه ای از کلاس Presentation بارگیری کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با مشخص کردن مسیر فایل خروجی و SaveFormat.EMF به عنوان پارامتر، متد «save» را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPSM در مسیر مشخص شده ذخیره می شود{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="قبل از اجرای کد منبع نمونه تبدیل پایتون، مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- سیستم عامل مبتنی بر ویندوز مایکروسافت یا لینوکس (به [بیشتر](https://docs.aspose.com/slides/python-net/system-requirements/) مراجعه کنید).
- پایتون 3.5 یا بالاتر
- Aspose.Slides برای پایتون در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="ساخته شده با Aspose.Slides" title="تبدیل آنلاین PPSM به EMF" description="برنامه رایگان Aspose.Slides Conversion با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPSM شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Conversion" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" upload="فایل خود را رها یا بارگذاری کنید" saveAs="ذخیره با فرمت" convert="تبدیل" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌ها را تبدیل می‌کند.
- فایل‌های PPSM را بارگذاری کنید و آن‌ها را با فرمت EMF ذخیره کنید.
- نتیجه را دانلود کنید یا فایل‌های بیشتری را تبدیل کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="شما همچنین می توانید PPSM را به بسیاری از فرمت های فایل دیگر تبدیل کنید. سایر تبدیل های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="تصویر بیت مپ" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="OpenDocument Flat XML Presentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="فرمت تبادل گرافیکی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="زبان نشانه گذاری فرا متنی" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="تصویر JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="فرمت ارائه اسناد باز" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="فرمت استاندارد OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="فرمت سند قابل حمل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-png/" name="PPSM TO PNG" description="گرافیک شبکه قابل حمل" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="نمایش اسلاید پاورپوینت" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="قالب ارائه XML را باز کنید" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="گرافیک برداری مقیاس پذیر" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="فرمت SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="فرمت تصویر برچسب شده" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

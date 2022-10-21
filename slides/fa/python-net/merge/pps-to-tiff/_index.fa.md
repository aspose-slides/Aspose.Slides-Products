---
title: با استفاده از پایتون، فایل‌های PPS را با TIFF ادغام کنید
url: /fa/python-net/merge/pps-to-tiff/
keywords: ادغام PPS به TIFF، پیوستن به PPS به TIFF، ترکیب PPS به TIFF، PowerPoint، Presentation، TIFF، Python، Aspose
description: چندین فایل PPS را در پایتون ادغام کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="فایل‌های PPS را با TIFF در پایتون ادغام کنید" h2="API Python با سرعت بالا و چند پلتفرمی که به توسعه برنامه‌هایی با توانایی ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="ادغام PPS به TIFF در پایتون" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای ترکیب چندین ارائه PPS ارائه می‌کند. هنگامی که یک ارائه را با ارائه دیگری ادغام می کنید، به طور موثر اسلایدهای آنها را در یک ارائه واحد ترکیب می کنید تا یک فایل به دست آورید. Aspose.Slides به شما امکان می دهد دو ارائه را به روش های مختلف ادغام کنید. می‌توانید ارائه‌ها را با تمام اشکال، سبک‌ها، متون، قالب‌بندی، نظرات، انیمیشن‌ها و غیره ادغام کنید بدون اینکه نگران از دست دادن کیفیت یا داده باشید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از پایتون فایل‌های PPS را با TIFF ادغام کنید" %}}
برای ادغام ارائه های پاورپوینت، باید اسلایدها را از یک ارائه به ارائه دیگر شبیه سازی کنید.

{{% blocks/products/pf/agp/code-block title="کد پایتون برای ادغام چند PPS در یک فایل TIFF" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.pps") as pres1:
    with slides.Presentation("presentation2.pps") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.tiff", slides.export.SaveFormat.TIFF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه ادغام PPS به TIFF با استفاده از Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای ادغام دو فایل PPS و ذخیره نتیجه به عنوان TIFF در پایتون است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) را نصب کنید.
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه پایتون خود اضافه کنید.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع PPS را در پایتون باز کنید.
```
pres1 = slides.Presentation('pres1.pps')
pres2 = slides.Presentation('pres2.pps')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل‌های PPS را با استفاده از روش [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) ترکیب کنید.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه را ذخیره کنید و نتیجه را به صورت تک فایل TIFF دریافت کنید.
```
pres1.save("presentation.tiff", slides.export.SaveFormat.TIFF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPS را به سایر قالب‌های پشتیبانی شده صادر کنید" subTitle="همچنین می‌توانید PPS را ترکیب کرده و در قالب‌های دیگر فایل ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-pptx/" name="PPS TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-ppt/" name="PPS TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-pdf/" name="PPS TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-html/" name="PPS TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-png/" name="PPS TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-bmp/" name="PPS TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-jpg/" name="PPS TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-fodp/" name="PPS TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-gif/" name="PPS TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-odp/" name="PPS TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-otp/" name="PPS TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-pot/" name="PPS TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-potm/" name="PPS TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-potx/" name="PPS TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-ppsm/" name="PPS TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-ppsx/" name="PPS TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-pptm/" name="PPS TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-svg/" name="PPS TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pps-to-xps/" name="PPS TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
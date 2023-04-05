---
title: با استفاده از پایتون، فایل‌های POT را با SVG ادغام کنید
url: /fa/python-net/merge/pot-to-svg/
keywords: ادغام POT به SVG، پیوستن به POT به SVG، ترکیب POT به SVG، PowerPoint، Presentation، SVG، Python، Aspose
description: چندین فایل POT را در پایتون ادغام کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="فایل‌های POT را با SVG در پایتون ادغام کنید" h2="API Python با سرعت بالا و چند پلتفرمی که به توسعه برنامه‌هایی با توانایی ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="ادغام POT به SVG در پایتون" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای ترکیب چندین ارائه POT ارائه می‌کند. هنگامی که یک ارائه را با ارائه دیگری ادغام می کنید، به طور موثر اسلایدهای آنها را در یک ارائه واحد ترکیب می کنید تا یک فایل به دست آورید. Aspose.Slides به شما امکان می دهد دو ارائه را به روش های مختلف ادغام کنید. می‌توانید ارائه‌ها را با تمام اشکال، سبک‌ها، متون، قالب‌بندی، نظرات، انیمیشن‌ها و غیره ادغام کنید بدون اینکه نگران از دست دادن کیفیت یا داده باشید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از پایتون فایل‌های POT را با SVG ادغام کنید" %}}
برای ادغام ارائه های پاورپوینت، باید اسلایدها را از یک ارائه به ارائه دیگر شبیه سازی کنید.

{{% blocks/products/pf/agp/code-block title="کد پایتون برای ادغام چند POT در یک فایل SVG" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.pot") as pres1:
    with slides.Presentation("presentation2.pot") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه ادغام POT به SVG با استفاده از Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای ادغام دو فایل POT و ذخیره نتیجه به عنوان SVG در پایتون است." >}}

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
فایل های منبع POT را در پایتون باز کنید.
```
pres1 = slides.Presentation('pres1.pot')
pres2 = slides.Presentation('pres2.pot')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل‌های POT را با استفاده از روش [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) ترکیب کنید.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه را ذخیره کنید و نتیجه را به صورت تک فایل SVG دریافت کنید.
```
for slide in pres1.slides:
    with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
        slide.write_as_svg(file)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="ادغام فایل های PDF به صورت آنلاین" sectionDescription="[نحوه ادغام PDF در پایتون](https://products.aspose.com/slides/fa/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="POT را به سایر قالب‌های پشتیبانی شده صادر کنید" subTitle="همچنین می‌توانید POT را ترکیب کرده و در قالب‌های دیگر فایل ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-pptx/" name="POT TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-ppt/" name="POT TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-pdf/" name="POT TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-html/" name="POT TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-png/" name="POT TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-bmp/" name="POT TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-jpg/" name="POT TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-fodp/" name="POT TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-gif/" name="POT TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-odp/" name="POT TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-otp/" name="POT TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-potm/" name="POT TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-potx/" name="POT TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-pps/" name="POT TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-ppsm/" name="POT TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-ppsx/" name="POT TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-pptm/" name="POT TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-tiff/" name="POT TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pot-to-xps/" name="POT TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
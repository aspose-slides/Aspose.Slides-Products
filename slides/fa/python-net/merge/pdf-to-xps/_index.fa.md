---
title: با استفاده از پایتون، فایل‌های PDF را با XPS ادغام کنید
url: /fa/python-net/merge/pdf-to-xps/
keywords: ادغام PDF به XPS، پیوستن به PDF به XPS، ترکیب PDF به XPS، PowerPoint، Presentation، XPS، Python، Aspose
description: چندین فایل PDF را در پایتون ادغام کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="فایل‌های PDF را با XPS در پایتون ادغام کنید" h2="API Python با سرعت بالا و چند پلتفرمی که به توسعه برنامه‌هایی با توانایی ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="ادغام PDF به XPS در پایتون" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fa/python-net/) یک کتابخانه قدرتمند پایتون برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای ترکیب چندین ارائه PDF ارائه می‌کند. هنگامی که یک ارائه را با ارائه دیگری ادغام می کنید، به طور موثر اسلایدهای آنها را در یک ارائه واحد ترکیب می کنید تا یک فایل به دست آورید. Aspose.Slides به شما امکان می دهد دو ارائه را به روش های مختلف ادغام کنید. می‌توانید ارائه‌ها را با تمام اشکال، سبک‌ها، متون، قالب‌بندی، نظرات، انیمیشن‌ها و غیره ادغام کنید بدون اینکه نگران از دست دادن کیفیت یا داده باشید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از پایتون فایل‌های PDF را با XPS ادغام کنید" %}}
برای ادغام ارائه های پاورپوینت، باید اسلایدها را از یک ارائه به ارائه دیگر شبیه سازی کنید.

{{% blocks/products/pf/agp/code-block title="کد پایتون برای ادغام چند PDF در یک فایل XPS" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation() as pres1:
    pres1.slides.remove_at(0)
    pres1.slides.add_from_pdf("document1.pdf")
    with slides.Presentation() as pres2:
        pres2.slides.remove_at(0)
        pres2.slides.add_from_pdf("document2.pdf")
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
    pres1.save("presentation.xps", slides.export.SaveFormat.XPS)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه ادغام PDF به XPS با استفاده از Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای ادغام دو فایل PDF و ذخیره نتیجه به عنوان XPS در پایتون است." >}}

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
فایل های منبع PDF را در پایتون باز کنید.
```
pres1 = slides.Presentation('pres1.pdf')
pres2 = slides.Presentation('pres2.pdf')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل‌های PDF را با استفاده از روش [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) ترکیب کنید.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه را ذخیره کنید و نتیجه را به صورت تک فایل XPS دریافت کنید.
```
pres1.save("presentation.xps", slides.export.SaveFormat.XPS)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PDF را به سایر قالب‌های پشتیبانی شده صادر کنید" subTitle="همچنین می‌توانید PDF را ترکیب کرده و در قالب‌های دیگر فایل ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-pptx/" name="PDF TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-ppt/" name="PDF TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-html/" name="PDF TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-png/" name="PDF TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-bmp/" name="PDF TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-jpg/" name="PDF TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-fodp/" name="PDF TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-gif/" name="PDF TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-odp/" name="PDF TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-otp/" name="PDF TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-pot/" name="PDF TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-potm/" name="PDF TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-potx/" name="PDF TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-pps/" name="PDF TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-ppsm/" name="PDF TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-ppsx/" name="PDF TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-pptm/" name="PDF TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-svg/" name="PDF TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/merge/pdf-to-tiff/" name="PDF TO TIFF" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
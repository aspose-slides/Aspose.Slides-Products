---
title: PPS را در Python به BMP تبدیل کنید
url: /fa/python-java/conversion/pps-to-bmp/
keywords: تبدیل ارائه Python، تبدیل ارائه ها به Python، Python برای ارائه، Aspose.Slides Python، تبدیل PPS به BMP، کتابخانه ارائه Python
description: در پایتون PPS را به BMP تبدیل کنید. از API کتابخانه پایتون برای تبدیل فایل‌های PPS به BMP استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="بدون زحمت PPS را به BMP با Python تبدیل کنید: Aspose.Slides to the Rescue!" h2="با پایتون جان تازه ای به ارائه های خود بدهید. راهنمای ما شما را در تبدیل اسلایدهای پاورپوینت موجود به ارائه های جذاب پایتون راهنمایی می کند." >}}

{{% blocks/products/pf/feature-page-section h2="PPS را در Python به BMP تبدیل کنید" %}}

از مبارزه با نرم افزارهای پیچیده ارائه خسته شده اید؟ به دنبال [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/fa/python-java/) نباشید! این کتابخانه قدرتمند به شما این امکان را می دهد که به راحتی ارائه ها را بین فرمت های مختلف ایجاد، ویرایش و تبدیل کنید. آیا باید از PPS به BMP جابجا شوید؟ Aspose.Slides این کار را بسیار ساده می کند و فقط به چند خط کد پایتون نیاز دارد.

**Aspose.Slides برای Python از طریق جاوا** به عنوان یک API پیشرفته برای پردازش اسناد، دارای سرعت تبدیل بسیار سریع است و از تبدیل سریع ارائه های PPS شما به فرمت BMP اطمینان حاصل می کند. محدودیت‌های ابزارهای سنتی را کنار بگذارید - Aspose.Slides به شما این امکان را می‌دهد که ارائه‌ها را از PPS نه تنها به BMP بلکه به طیف گسترده‌ای از قالب‌های دیگر تبدیل کنید، و به شما این امکان را می‌دهد که ارائه‌های خود را به‌طور بی‌نقص با هر موقعیتی تطبیق دهید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از پایتون، PPS را به BMP تبدیل کنید" %}}
برای تبدیل PPS به BMP، باید Presentation را از فایل PPS ایجاد کنید و آن را به عنوان BMP ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="آموزش پایتون برای تبدیل PPS به BMP" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.pps");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "BMP", File("slide" + str(i) + ".bmp"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="آموزش پایتون. نحوه تبدیل PPS به BMP با استفاده از Aspose.Slides برای Python از طریق Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="برای تبدیل PPS به BMP با استفاده از Aspose.Slides برای پایتون از طریق جاوا، باید بسته را به اسکریپت پایتون خود وارد کنید و نمونه ای از کلاس Presentation ایجاد کنید. کلاس Presentation یک سند پاورپوینت را نشان می دهد و روش هایی را برای دسترسی و دستکاری عناصر آن ارائه می دهد." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides برای پایتون از طریق جاوا**](https://products.aspose.com/slides/fa/python-java/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه پایتون خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع PPS را در پایتون باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل BMP ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل PPS به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید PPS را تبدیل کنید و در فرمت‌های فایل دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-jpg/" name="PPS TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-svg/" name="PPS TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
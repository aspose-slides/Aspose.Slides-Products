---
title: PDF را در Python به PPT تبدیل کنید
url: /fa/python-java/conversion/pdf-to-ppt/
keywords: تبدیل ارائه Python، تبدیل ارائه ها به Python، Python برای ارائه، Aspose.Slides Python، تبدیل PDF به PPT، کتابخانه ارائه Python
description: در پایتون PDF را به PPT تبدیل کنید. از API کتابخانه پایتون برای تبدیل فایل‌های PDF به PPT استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="بدون زحمت PDF را به PPT با Python تبدیل کنید: Aspose.Slides to the Rescue!" h2="با پایتون جان تازه ای به ارائه های خود بدهید. راهنمای ما شما را در تبدیل اسلایدهای پاورپوینت موجود به ارائه های جذاب پایتون راهنمایی می کند." >}}

{{% blocks/products/pf/feature-page-section h2="PDF را در Python به PPT تبدیل کنید" %}}

از مبارزه با نرم افزارهای پیچیده ارائه خسته شده اید؟ به دنبال [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/fa/python-java/) نباشید! این کتابخانه قدرتمند به شما این امکان را می دهد که به راحتی ارائه ها را بین فرمت های مختلف ایجاد، ویرایش و تبدیل کنید. آیا باید از PDF به PPT جابجا شوید؟ Aspose.Slides این کار را بسیار ساده می کند و فقط به چند خط کد پایتون نیاز دارد.

**Aspose.Slides برای Python از طریق جاوا** به عنوان یک API پیشرفته برای پردازش اسناد، دارای سرعت تبدیل بسیار سریع است و از تبدیل سریع ارائه های PDF شما به فرمت PPT اطمینان حاصل می کند. محدودیت‌های ابزارهای سنتی را کنار بگذارید - Aspose.Slides به شما این امکان را می‌دهد که ارائه‌ها را از PDF نه تنها به PPT بلکه به طیف گسترده‌ای از قالب‌های دیگر تبدیل کنید، و به شما این امکان را می‌دهد که ارائه‌های خود را به‌طور بی‌نقص با هر موقعیتی تطبیق دهید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از پایتون، PDF را به PPT تبدیل کنید" %}}
برای تبدیل PDF به PPT، باید Presentation را از فایل PDF ایجاد کنید و آن را به عنوان PPT ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="آموزش پایتون برای تبدیل PDF به PPT" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

pres.save("output.ppt", SaveFormat.Ppt);

jpype.shutdownJVM()

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="آموزش پایتون. نحوه تبدیل PDF به PPT با استفاده از Aspose.Slides برای Python از طریق Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="برای تبدیل PDF به PPT با استفاده از Aspose.Slides برای پایتون از طریق جاوا، باید بسته را به اسکریپت پایتون خود وارد کنید و نمونه ای از کلاس Presentation ایجاد کنید. کلاس Presentation یک سند پاورپوینت را نشان می دهد و روش هایی را برای دسترسی و دستکاری عناصر آن ارائه می دهد." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides برای پایتون از طریق جاوا**](https://products.aspose.com/slides/fa/python-java/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه پایتون خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع PDF را در پایتون باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PPT ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل PDF به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید PDF را تبدیل کنید و در فرمت‌های فایل دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
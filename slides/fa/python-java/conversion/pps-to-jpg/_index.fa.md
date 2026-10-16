---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPS را در Python به JPG تبدیل کنید
url: /fa/python-java/conversion/pps-to-jpg/
keywords: تبدیل ارائه Python، تبدیل ارائه ها به Python، Python برای ارائه، Aspose.Slides Python، تبدیل PPS به JPG، کتابخانه ارائه Python
description: در پایتون PPS را به JPG تبدیل کنید. از API کتابخانه پایتون برای تبدیل فایل‌های PPS به JPG استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="بدون زحمت PPS را به JPG با Python تبدیل کنید: Aspose.Slides to the Rescue!" h2="با پایتون جان تازه ای به ارائه های خود بدهید. راهنمای ما شما را در تبدیل اسلایدهای پاورپوینت موجود به ارائه های جذاب پایتون راهنمایی می کند." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از پایتون، PPS را به JPG تبدیل کنید" variant="code" %}}

برای تبدیل PPS به JPG، باید Presentation را از فایل PPS ایجاد کنید و آن را به عنوان JPG ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="آموزش پایتون برای تبدیل PPS به JPG" >}}
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
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPS را در Python به JPG تبدیل کنید" %}}

از مبارزه با نرم افزارهای پیچیده ارائه خسته شده اید؟ به دنبال [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/fa/python-java/) نباشید! این کتابخانه قدرتمند به شما این امکان را می دهد که به راحتی ارائه ها را بین فرمت های مختلف ایجاد، ویرایش و تبدیل کنید. آیا باید از PPS به JPG جابجا شوید؟ Aspose.Slides این کار را بسیار ساده می کند و فقط به چند خط کد پایتون نیاز دارد.

**Aspose.Slides برای Python از طریق جاوا** به عنوان یک API پیشرفته برای پردازش اسناد، دارای سرعت تبدیل بسیار سریع است و از تبدیل سریع ارائه های PPS شما به فرمت JPG اطمینان حاصل می کند. محدودیت‌های ابزارهای سنتی را کنار بگذارید - Aspose.Slides به شما این امکان را می‌دهد که ارائه‌ها را از PPS نه تنها به JPG بلکه به طیف گسترده‌ای از قالب‌های دیگر تبدیل کنید، و به شما این امکان را می‌دهد که ارائه‌های خود را به‌طور بی‌نقص با هر موقعیتی تطبیق دهید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="آموزش پایتون. نحوه تبدیل PPS به JPG با استفاده از Aspose.Slides برای Python از طریق Java API." intro="برای تبدیل PPS به JPG با استفاده از Aspose.Slides برای پایتون از طریق جاوا، باید بسته را به اسکریپت پایتون خود وارد کنید و نمونه ای از کلاس Presentation ایجاد کنید. کلاس Presentation یک سند پاورپوینت را نشان می دهد و روش هایی را برای دسترسی و دستکاری عناصر آن ارائه می دهد." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides برای پایتون از طریق جاوا**](https://products.aspose.com/slides/fa/python-java/) را نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه پایتون خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های منبع PPS را در پایتون باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نتیجه را به عنوان فایل JPG ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تبدیل PPS به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید PPS را تبدیل کنید و در فرمت‌های فایل دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-svg/" name="PPS TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/python-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: در جاوا اسکریپت ODP را به PPT تبدیل کنید
url: /fa/nodejs-net/conversion/odp-to-ppt/
keywords: ODP به PPT، تبدیل ODP به PPT، Node.js API، کتابخانه جاوا اسکریپت، ODP، PPT
description: در جاوا اسکریپت ODP را به PPT تبدیل کنید. از Node.js library API برای تبدیل فایل‌های ODP به PPT استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="در جاوا اسکریپت ODP را به PPT تبدیل کنید" h2="Aspose.Slides for Node.js via .NET یک کتابخانه قدرتمند و آسان برای استفاده است که به شما امکان می دهد ارائه های پاورپوینت را به فرمت های مختلف در جاوا اسکریپت تبدیل کنید. از تمام عناصر و قالب‌های ارائه پشتیبانی می‌کند و یک API غنی برای دسترسی و اصلاح آنها ارائه می‌کند. همچنین به شما امکان می دهد اسلایدهای خود را به فرمت های مختلف برای پردازش یا اشتراک گذاری بیشتر صادر کنید." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از جاوا اسکریپت، ODP را به PPT تبدیل کنید" variant="code" %}}

برای تبدیل ODP به PPT، باید Presentation را از فایل ODP ایجاد کنید و آن را به عنوان PPT ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد جاوا اسکریپت برای تبدیل ODP به PPT" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.odp");
try
{
    pres.save("output.ppt", SaveFormat.Ppt);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="در Node.js ODP را به PPT تبدیل کنید" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/fa/nodejs-net/) یک کتابخانه قدرتمند Node.js برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل ODP به PPT ارائه می‌کند. با استفاده از **Aspose.Slides برای Node.js از طریق NET**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های ODP را تنها با چند خط کد به PPT تبدیل کند.

به عنوان یک API مدرن پردازش اسناد، Aspose.Slides برای Node.js از طریق .NET فایل‌های ODP را به فرمت‌های فایل PPT به سرعت صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد ODP را به PPT و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل ODP به PPT با استفاده از Aspose.Slides برای Node.js از طریق NET API" intro="برای تبدیل ODP به PPT با استفاده از Aspose.Slides برای Node.js از طریق دات نت، باید بسته را در فایل جاوا اسکریپت خود وارد کنید و یک نمونه از کلاس Presentation ایجاد کنید. کلاس Presentation یک سند پاورپوینت را نشان می دهد و روش هایی را برای دسترسی و دستکاری عناصر آن ارائه می دهد." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides را برای Node.js از طریق .NET**](https://products.aspose.com/slides/fa/nodejs-net/) نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه Node.js خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های منبع ODP را در Node.js باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نتیجه را به عنوان فایل PPT ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تبدیل ODP به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید ODP را تبدیل کنید و در فرمت‌های فایل دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-png/" name="ODP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-bmp/" name="ODP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

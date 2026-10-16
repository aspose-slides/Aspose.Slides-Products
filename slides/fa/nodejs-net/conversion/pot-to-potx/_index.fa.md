---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: در جاوا اسکریپت POT را به POTX تبدیل کنید
url: /fa/nodejs-net/conversion/pot-to-potx/
keywords: POT به POTX، تبدیل POT به POTX، Node.js API، کتابخانه جاوا اسکریپت، POT، POTX
description: در جاوا اسکریپت POT را به POTX تبدیل کنید. از Node.js library API برای تبدیل فایل‌های POT به POTX استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="در جاوا اسکریپت POT را به POTX تبدیل کنید" h2="Aspose.Slides for Node.js via .NET یک کتابخانه قدرتمند و آسان برای استفاده است که به شما امکان می دهد ارائه های پاورپوینت را به فرمت های مختلف در جاوا اسکریپت تبدیل کنید. از تمام عناصر و قالب‌های ارائه پشتیبانی می‌کند و یک API غنی برای دسترسی و اصلاح آنها ارائه می‌کند. همچنین به شما امکان می دهد اسلایدهای خود را به فرمت های مختلف برای پردازش یا اشتراک گذاری بیشتر صادر کنید." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از جاوا اسکریپت، POT را به POTX تبدیل کنید" variant="code" %}}

برای تبدیل POT به POTX، باید Presentation را از فایل POT ایجاد کنید و آن را به عنوان POTX ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد جاوا اسکریپت برای تبدیل POT به POTX" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pot");
try
{
    pres.save("output.potx", SaveFormat.Potx);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="در Node.js POT را به POTX تبدیل کنید" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/fa/nodejs-net/) یک کتابخانه قدرتمند Node.js برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل POT به POTX ارائه می‌کند. با استفاده از **Aspose.Slides برای Node.js از طریق NET**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های POT را تنها با چند خط کد به POTX تبدیل کند.

به عنوان یک API مدرن پردازش اسناد، Aspose.Slides برای Node.js از طریق .NET فایل‌های POT را به فرمت‌های فایل POTX به سرعت صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد POT را به POTX و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل POT به POTX با استفاده از Aspose.Slides برای Node.js از طریق NET API" intro="برای تبدیل POT به POTX با استفاده از Aspose.Slides برای Node.js از طریق دات نت، باید بسته را در فایل جاوا اسکریپت خود وارد کنید و یک نمونه از کلاس Presentation ایجاد کنید. کلاس Presentation یک سند پاورپوینت را نشان می دهد و روش هایی را برای دسترسی و دستکاری عناصر آن ارائه می دهد." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides را برای Node.js از طریق .NET**](https://products.aspose.com/slides/fa/nodejs-net/) نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه Node.js خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های منبع POT را در Node.js باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نتیجه را به عنوان فایل POTX ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تبدیل POT به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید POT را تبدیل کنید و در فرمت‌های فایل دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-bmp/" name="POT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-jpg/" name="POT TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-svg/" name="POT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/pot-to-tiff/" name="POT TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

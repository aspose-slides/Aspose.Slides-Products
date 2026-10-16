---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: در جاوا اسکریپت POTM را به PDF تبدیل کنید
url: /fa/nodejs-net/conversion/potm-to-pdf/
keywords: POTM به PDF، تبدیل POTM به PDF، Node.js API، کتابخانه جاوا اسکریپت، POTM، PDF
description: در جاوا اسکریپت POTM را به PDF تبدیل کنید. از Node.js library API برای تبدیل فایل‌های POTM به PDF استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="در جاوا اسکریپت POTM را به PDF تبدیل کنید" h2="Aspose.Slides for Node.js via .NET یک کتابخانه قدرتمند و آسان برای استفاده است که به شما امکان می دهد ارائه های پاورپوینت را به فرمت های مختلف در جاوا اسکریپت تبدیل کنید. از تمام عناصر و قالب‌های ارائه پشتیبانی می‌کند و یک API غنی برای دسترسی و اصلاح آنها ارائه می‌کند. همچنین به شما امکان می دهد اسلایدهای خود را به فرمت های مختلف برای پردازش یا اشتراک گذاری بیشتر صادر کنید." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از جاوا اسکریپت، POTM را به PDF تبدیل کنید" variant="code" %}}

برای تبدیل POTM به PDF، باید Presentation را از فایل POTM ایجاد کنید و آن را به عنوان PDF ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد جاوا اسکریپت برای تبدیل POTM به PDF" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.potm");
try
{
    pres.save("output.pdf", SaveFormat.Pdf);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="در Node.js POTM را به PDF تبدیل کنید" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/fa/nodejs-net/) یک کتابخانه قدرتمند Node.js برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل POTM به PDF ارائه می‌کند. با استفاده از **Aspose.Slides برای Node.js از طریق NET**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های POTM را تنها با چند خط کد به PDF تبدیل کند.

به عنوان یک API مدرن پردازش اسناد، Aspose.Slides برای Node.js از طریق .NET فایل‌های POTM را به فرمت‌های فایل PDF به سرعت صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد POTM را به PDF و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل POTM به PDF با استفاده از Aspose.Slides برای Node.js از طریق NET API" intro="برای تبدیل POTM به PDF با استفاده از Aspose.Slides برای Node.js از طریق دات نت، باید بسته را در فایل جاوا اسکریپت خود وارد کنید و یک نمونه از کلاس Presentation ایجاد کنید. کلاس Presentation یک سند پاورپوینت را نشان می دهد و روش هایی را برای دسترسی و دستکاری عناصر آن ارائه می دهد." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides را برای Node.js از طریق .NET**](https://products.aspose.com/slides/fa/nodejs-net/) نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه Node.js خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل های منبع POTM را در Node.js باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نتیجه را به عنوان فایل PDF ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تبدیل POTM به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید POTM را تبدیل کنید و در فرمت‌های فایل دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-html/" name="POTM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-bmp/" name="POTM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-jpg/" name="POTM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-svg/" name="POTM TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/nodejs-net/conversion/potm-to-tiff/" name="POTM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

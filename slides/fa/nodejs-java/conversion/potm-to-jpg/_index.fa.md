---
title: در Node.js POTM را به JPG تبدیل کنید
url: /fa/nodejs-java/conversion/potm-to-jpg/
keywords: POTM به JPG، تبدیل POTM به JPG، Node.js API، Node.js Library، POTM، JPG
description: در Node.js POTM را به JPG تبدیل کنید. از Node.js library API برای تبدیل فایل‌های POTM به JPG استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="در Node.js POTM را به JPG تبدیل کنید" h2="Aspose.Slides برای Node.js از طریق جاوا یک کتابخانه قدرتمند و آسان برای استفاده است که به شما امکان می دهد ارائه های پاورپوینت را به فرمت های مختلف در Node.js تبدیل کنید. از همه عناصر و قالب‌های ارائه پشتیبانی می‌کند و یک API غنی برای دسترسی و اصلاح آنها ارائه می‌کند. همچنین به شما امکان می دهد اسلایدهای خود را به فرمت های مختلف برای پردازش یا اشتراک گذاری بیشتر صادر کنید." >}}

{{% blocks/products/pf/feature-page-section h2="در Node.js POTM را به JPG تبدیل کنید" %}}

[**Aspose.Slides for Node.js از طریق جاوا**](https://products.aspose.com/slides/fa/nodejs-java/) یک کتابخانه قدرتمند Node.js برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل POTM به JPG ارائه می‌کند. با استفاده از **Aspose.Slides برای Node.js از طریق جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های POTM را تنها با چند خط کد به JPG تبدیل کند.

Aspose.Slides برای Node.js به عنوان یک API مدرن برای پردازش اسناد، فایل‌های POTM را به فرمت‌های فایل JPG صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد POTM را به JPG و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از Node.js، POTM را به JPG تبدیل کنید" %}}
برای تبدیل POTM به JPG، باید Presentation را از فایل POTM ایجاد کنید و آن را به عنوان JPG ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد Node.js برای تبدیل POTM به JPG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.potm");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".jpg");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "jpeg", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل POTM به JPG با استفاده از Aspose.Slides برای Node.js از طریق Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="برای تبدیل POTM به JPG با استفاده از Aspose.Slides برای Node.js از طریق جاوا، باید بسته را در فایل جاوا اسکریپت خود وارد کنید و یک نمونه از کلاس Presentation ایجاد کنید. کلاس Presentation یک سند پاورپوینت را نشان می دهد و روش هایی را برای دسترسی و دستکاری عناصر آن ارائه می دهد." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides برای Node.js از طریق جاوا**](https://products.aspose.com/slides/fa/nodejs-java/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه Node.js خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع POTM را در Node.js باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل JPG ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل POTM به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید POTM را تبدیل کنید و در فرمت‌های فایل دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-pdf/" name="POTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-html/" name="POTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-bmp/" name="POTM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-svg/" name="POTM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/potm-to-tiff/" name="POTM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
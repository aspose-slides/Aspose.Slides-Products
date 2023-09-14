---
title: در Node.js ODP را به PNG تبدیل کنید
url: /fa/nodejs-java/conversion/odp-to-png/
keywords: ODP به PNG، تبدیل ODP به PNG، Node.js API، Node.js Library، ODP، PNG
description: در Node.js ODP را به PNG تبدیل کنید. از Node.js library API برای تبدیل فایل‌های ODP به PNG استفاده کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="در Node.js ODP را به PNG تبدیل کنید" h2="Aspose.Slides برای Node.js از طریق جاوا یک کتابخانه قدرتمند و آسان برای استفاده است که به شما امکان می دهد ارائه های پاورپوینت را به فرمت های مختلف در Node.js تبدیل کنید. از همه عناصر و قالب‌های ارائه پشتیبانی می‌کند و یک API غنی برای دسترسی و اصلاح آنها ارائه می‌کند. همچنین به شما امکان می دهد اسلایدهای خود را به فرمت های مختلف برای پردازش یا اشتراک گذاری بیشتر صادر کنید." >}}

{{% blocks/products/pf/feature-page-section h2="در Node.js ODP را به PNG تبدیل کنید" %}}

[**Aspose.Slides for Node.js از طریق جاوا**](https://products.aspose.com/slides/fa/nodejs-java/) یک کتابخانه قدرتمند Node.js برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل ODP به PNG ارائه می‌کند. با استفاده از **Aspose.Slides برای Node.js از طریق جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های ODP را تنها با چند خط کد به PNG تبدیل کند.

Aspose.Slides برای Node.js به عنوان یک API مدرن برای پردازش اسناد، فایل‌های ODP را به فرمت‌های فایل PNG صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد ODP را به PNG و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از Node.js، ODP را به PNG تبدیل کنید" %}}
برای تبدیل ODP به PNG، باید Presentation را از فایل ODP ایجاد کنید و آن را به عنوان PNG ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد Node.js برای تبدیل ODP به PNG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.odp");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".png");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "png", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل ODP به PNG با استفاده از Aspose.Slides برای Node.js از طریق Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="برای تبدیل ODP به PNG با استفاده از Aspose.Slides برای Node.js از طریق جاوا، باید بسته را در فایل جاوا اسکریپت خود وارد کنید و یک نمونه از کلاس Presentation ایجاد کنید. کلاس Presentation یک سند پاورپوینت را نشان می دهد و روش هایی را برای دسترسی و دستکاری عناصر آن ارائه می دهد." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides برای Node.js از طریق جاوا**](https://products.aspose.com/slides/fa/nodejs-java/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه Node.js خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع ODP را در Node.js باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PNG ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل ODP به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید ODP را تبدیل کنید و در فرمت‌های فایل دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-bmp/" name="ODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/nodejs-java/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
title: در جاوا HTML را به PDF تبدیل کنید
url: /fa/java/conversion/html-to-pdf/
keywords: HTML به PDF، تبدیل HTML به PDF، Java API، Java Library، HTML، PDF
description: تبدیل HTML به PDF در جاوا. برای تبدیل فایل‌های HTML به PDF از API کتابخانه جاوا استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="در جاوا HTML را به PDF تبدیل کنید" h2="کتابخانه جاوا پرسرعت و چند پلتفرمی که به توسعه برنامه‌هایی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="در جاوا HTML را به PDF تبدیل کنید" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) یک کتابخانه قدرتمند جاوا برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل HTML به PDF ارائه می‌کند. با استفاده از **Aspose.Slides برای جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های HTML را تنها با چند خط کد جاوا به PDF تبدیل کند.

Aspose.Slides برای جاوا به عنوان یک API مدرن برای پردازش اسناد، فایل‌های HTML را به فرمت‌های فایل PDF صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد HTML را به PDF و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از جاوا، HTML را به PDF تبدیل کنید" %}}
برای تبدیل HTML به PDF، باید Presentation را از فایل HTML ایجاد کنید و آن را به عنوان PDF ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد جاوا برای تبدیل HTML به PDF" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل HTML به PDF با استفاده از Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل HTML به PDF در جاوا است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source HTML files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as PDF file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل HTML به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید HTML را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
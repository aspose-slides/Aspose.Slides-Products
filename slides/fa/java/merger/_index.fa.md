---
title: PDF، PPT، PPTX و بسیاری از فرمت های فایل دیگر را با استفاده از جاوا ادغام کنید
url: /fa/java/merger/
keywords: Merge, Join, PowerPoint, Presentation, Java, Aspose
description: چندین فایل را در Java PPT، PPTX، ODP، PDF، PNG، JPG و بسیاری موارد دیگر ادغام کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="پاورپوینت، PDF، PPT یا سایر اسناد را با هم در جاوا ادغام کنید" h2="کتابخانه جاوا با سرعت بالا برای ادغام PPT، PPTX، PDF، PNG، JPEG و فرمت های دیگر." >}}

{{% blocks/products/pf/feature-page-section h2="PPT، PPTX، PDF را با استفاده از جاوا ادغام کنید" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) یک کتابخانه قدرتمند جاوا برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای ترکیب چندین ارائه PPT/PPTX فراهم می‌کند. هنگامی که یک ارائه را با ارائه دیگری ادغام می کنید، به طور مؤثر اسلایدهای آنها را در یک ارائه واحد ترکیب می کنید تا یک فایل به دست آورید. Aspose.Slides به شما امکان می دهد دو ارائه را به روش های مختلف ادغام کنید. می‌توانید ارائه‌ها را با تمام اشکال، سبک‌ها، متون، قالب‌بندی، نظرات، انیمیشن‌ها و غیره ادغام کنید بدون اینکه نگران از دست دادن کیفیت یا داده باشید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ادغام ارائه های پاورپوینت در جاوا" %}}
برای ادغام ارائه های پاورپوینت، باید اسلایدها را از یک ارائه به ارائه دیگر شبیه سازی کنید.

{{% blocks/products/pf/agp/code-block title="فایل های PPTX را با استفاده از جاوا ادغام کنید" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ادغام ارائه ها با اسلاید مستر با استفاده از جاوا" %}}
این کد جاوا نحوه ادغام چندین ارائه را در یک و اعمال سبک ها از الگوی ارائه اصلی اسلاید نشان می دهد. بنابراین، ارائه نتیجه همان قالب بندی منبع را حفظ می کند و شامل قالب بندی از اسلاید اصلی ارائه دیگری خواهد بود.

{{% blocks/products/pf/agp/code-block title="ادغام چند PPT به تک در جاوا" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه ادغام ارائه ها با استفاده از Aspose.Slides برای Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای ادغام دو فایل PPTX و ذخیره نتیجه به صورت PDF در جاوا هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Java**](https://docs.aspose.com/slides/java/installation/) را نصب کنید. 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه جاوا خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع PPTX را در جاوا باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های PPTX را با استفاده از روش **addClone** ترکیب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه را ذخیره کنید و نتیجه را به عنوان یک فایل PDF دریافت کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده برای ادغام" subTitle="همچنین می توانید فرمت های دیگر فایل را با هم ترکیب کنید. سایر فرمت های پشتیبانی شده را در زیر مشاهده کنید." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
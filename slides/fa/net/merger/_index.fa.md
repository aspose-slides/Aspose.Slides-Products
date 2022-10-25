---
title: ادغام PDF، PPT، PPTX و بسیاری از فرمت های فایل دیگر با استفاده از C#
url: /fa/net/merger/
keywords: Merge, Join, PowerPoint, Presentation, C#, .NET, Aspose
description: چندین فایل را در C# PPT، PPTX، ODP، PDF، PNG، JPG و بسیاری دیگر ادغام کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="پاورپوینت، PDF، PPT یا سایر اسناد را با هم در سی شارپ ادغام کنید" h2="کتابخانه C# با سرعت بالا برای ادغام فرمت های PPT، PPTX، PDF، PNG، JPEG و سایر فرمت ها." >}}

{{% blocks/products/pf/feature-page-section h2="ادغام PPT، PPTX، PDF با استفاده از C#" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/fa/net/) یک کتابخانه قدرتمند C# برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای ترکیب چندین ارائه PPT/PPTX فراهم می‌کند. هنگامی که یک ارائه را با ارائه دیگری ادغام می کنید، به طور مؤثر اسلایدهای آنها را در یک ارائه واحد ترکیب می کنید تا یک فایل به دست آورید. Aspose.Slides به شما امکان می دهد دو ارائه را به روش های مختلف ادغام کنید. می‌توانید ارائه‌ها را با تمام اشکال، سبک‌ها، متون، قالب‌بندی، نظرات، انیمیشن‌ها و غیره ادغام کنید بدون اینکه نگران از دست دادن کیفیت یا داده باشید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ادغام ارائه های پاورپوینت در سی شارپ" %}}
برای ادغام ارائه های پاورپوینت، باید اسلایدها را از یک ارائه به ارائه دیگر شبیه سازی کنید.

{{% blocks/products/pf/agp/code-block title="ادغام فایل های PPTX با استفاده از سی شارپ" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ادغام ارائه ها با اسلاید مستر با استفاده از سی شارپ" %}}
این کد سی شارپ نحوه ادغام چندین ارائه را در یک و اعمال سبک ها از الگوی ارائه اصلی اسلاید نشان می دهد. بنابراین، ارائه نتیجه همان قالب بندی منبع را حفظ می کند و شامل قالب بندی از اسلاید اصلی ارائه دیگری خواهد بود.

{{% blocks/products/pf/agp/code-block title="چند PPT را در سی شارپ ادغام کنید" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه ادغام Presentations با استفاده از Aspose.Slides برای NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای ادغام دو فایل PPTX و ذخیره نتیجه به صورت PDF در دات نت است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for .NET**](https://docs.aspose.com/slides/net/installation/) را نصب کنید. 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه C# خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع PPTX را در سی شارپ باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های PPTX را با استفاده از روش **AddClone** ترکیب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه را ذخیره کنید و نتیجه را به عنوان یک فایل PDF دریافت کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده برای ادغام" subTitle="همچنین می توانید فرمت های دیگر فایل را با هم ترکیب کنید. سایر فرمت های پشتیبانی شده را در زیر مشاهده کنید." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
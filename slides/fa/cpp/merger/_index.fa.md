---
title: PDF، PPT، PPTX و بسیاری از فرمت های فایل دیگر را با استفاده از C++ ادغام کنید
url: /fa/cpp/merger/
keywords: Merge, Join, PowerPoint, Presentation, C++, Aspose
description: چندین فایل را در C++ PPT، PPTX، ODP، PDF، PNG، JPG و بسیاری دیگر ادغام کنید.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="پاورپوینت، PDF، PPT یا سایر اسناد را با هم در C++ ادغام کنید" h2="کتابخانه C++ پرسرعت برای ادغام PPT، PPTX، PDF، PNG، JPEG و فرمت های دیگر." >}}

{{% blocks/products/pf/feature-page-section h2="PPT، PPTX، PDF را با استفاده از C++ ادغام کنید" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) یک کتابخانه قدرتمند C++ برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای ترکیب چندین ارائه PPT/PPTX فراهم می‌کند. هنگامی که یک ارائه را با ارائه دیگری ادغام می کنید، به طور مؤثر اسلایدهای آنها را در یک ارائه واحد ترکیب می کنید تا یک فایل به دست آورید. Aspose.Slides به شما امکان می دهد دو ارائه را به روش های مختلف ادغام کنید. می‌توانید ارائه‌ها را با تمام اشکال، سبک‌ها، متون، قالب‌بندی، نظرات، انیمیشن‌ها و غیره ادغام کنید بدون اینکه نگران از دست دادن کیفیت یا داده باشید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ادغام ارائه های پاورپوینت در C++" %}}
برای ادغام ارائه های پاورپوینت، باید اسلایدها را از یک ارائه به ارائه دیگر شبیه سازی کنید.

{{% blocks/products/pf/agp/code-block title="فایل های PPTX را با استفاده از C++ ادغام کنید" offSpacer="true" %}}

```cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation2.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides())
{
	// Merge slides from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ادغام ارائه ها با Slide Master با استفاده از C++" %}}
این کد ++C نشان می دهد که چگونه چندین ارائه را در یک نمایش ادغام کرده و سبک ها را از الگوی ارائه اصلی اسلاید اعمال می کند. بنابراین، ارائه نتیجه همان قالب بندی منبع را حفظ می کند و شامل قالب بندی از اسلاید اصلی ارائه دیگری خواهد بود.

{{% blocks/products/pf/agp/code-block title="چند PPT را در C++ به یک واحد ادغام کنید" offSpacer="true" %}}

``` cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Load the presentation files
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

// Merge the first slide using slide master
presentation1->get_Slides()->AddClone(presentation2->get_Slides()->idx_get(0), presentation1->get_Masters()->idx_get(0), true);

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه ادغام Presentations با استفاده از Aspose.Slides برای C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای ادغام دو فایل PPTX و ذخیره نتیجه به صورت PDF در C++ هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://docs.aspose.com/slides/cpp/installation/) را نصب کنید. 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه ++C خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع PPTX را در C++ باز کنید.
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/cpp/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
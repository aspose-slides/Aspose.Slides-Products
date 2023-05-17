---
title: ویرایش فایل‌های ارائه ODP با استفاده از .NET
url: /fa/net/redaction/odp/
keywords: ویرایش ODP، یافتن و جایگزینی متن در ODP، به روز رسانی ODP ارائه
description: کد منبع C# برای یافتن و جایگزینی متن در ارائه ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ویرایش ODP با استفاده از C#" h2="برنامه های .NET خود را بسازید تا متن را در فایل های ارائه با استفاده از API های سمت سرور پیدا کرده و جایگزین کنید. با نحوه جستجو و جایگزینی متن در محتوا، نظرات یا ابرداده ارائه‌های ODP آشنا شوید" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="ویرایش ODP ارائه از طریق C#" %}}
جستجوی اولیه سند و جایگزینی متن در محتوا، نظرات، یادداشت‌های اسلاید یا ابرداده با APIهای Aspose.Slides for .NET تنها با چند خط کد انجام می‌شود. متن را در پاورپوینت و اپن آفیس پیدا و جایگزین کنید. ویرایش متن، نظرات، ابرداده در ارائه از طریق تطبیق داده های regexp.
{{% blocks/products/pf/agp/code-block title="ویرایش ODP ارائه با استفاده از C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.odp"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه ویرایش ODP از طریق C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای ویرایش فایل‌های ODP هستند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP را با یک نمونه از Presentation بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
برای یافتن و جایگزینی متن از روش [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) استفاده کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب ODP ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="نسخه‌های نمایشی زنده ویرایش آنلاین ODP" sectionDescription="در حال حاضر متن، نظرات یا ابرداده را در اسناد ODP جستجو و جایگزین کنید." >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده Redact" subTitle="با استفاده از C#، می‌توانید قالب‌های زیر را نیز ویرایش کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: مشاهده یا ویرایش فراداده فایل‌های POT با استفاده از .NET
url: /fa/net/metadata/pot/
keywords: ویرایش فراداده POT، مشاهده فراداده POT، ویرایش ویژگی‌های POT، مشاهده ویژگی‌های POT
description: کد منبع C# برای ویرایش یا مشاهده فراداده قالب POT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ویرایش ویژگی‌های POT با استفاده از C#" h2="برنامه‌های .NET خود را بسازید تا ویژگی‌های داخلی و سفارشی را در فایل‌های ارائه با استفاده از APIهای سمت سرور تغییر دهید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="اصلاح ویژگی‌های POT از طریق C#" %}}
با استفاده از Aspose.Slides for .NET، توسعه‌دهندگان می‌توانند به مقادیر ویژگی‌های داخلی و همچنین ویژگی‌های سفارشی دسترسی داشته باشند و آن‌ها را تغییر دهند. توسعه‌دهندگان می‌توانند از ویژگی [DocumentProperties](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) که توسط شی Presentation در معرض دید قرار می‌گیرد برای دسترسی به ویژگی‌های سند فایل ارائه استفاده کنند.
{{% blocks/products/pf/agp/code-block title="اصلاح ویژگی‌های داخلی POT - C#" offSpacer="true" %}}

```cs

// Instantiate the Presentation class that represents the Presentation
Presentation presentation = new Presentation("presentation.pot");

// Create a reference to IDocumentProperties object associated with Presentation
IDocumentProperties documentProperties = presentation.DocumentProperties;

// Set the builtin properties
documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

// Save your presentation to a file
presentation.Save("DocumentProperties_out.pot", SaveFormat.Pot);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="افزودن ویژگی های سفارشی به POT - C#" offSpacer="true" %}}

```cs

// Instantiate the Presentation class
Presentation presentation = new Presentation();

// Getting Document Properties
IDocumentProperties documentProperties = presentation.DocumentProperties;

// Adding Custom properties
documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

// Getting property name at particular index
String getPropertyName = documentProperties.GetCustomPropertyName(2);

// Removing selected property
documentProperties.RemoveCustomProperty(getPropertyName);

// Save your presentation to a file
presentation.Save("CustomDocumentProperties_out.pot", SaveFormat.Pot);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه استخراج فراداده POT از طریق C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای استخراج فراداده از فایل‌های POT است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
کلاس Presentation را با مسیر فایل POT نمونه سازی کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
دریافت شی DocumentProperties مرتبط با Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حلقه روی آیتم ها در شی DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
دسترسی و اصلاح خواص سفارشی
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های فراداده پشتیبانی شده" subTitle="با استفاده از C#، می‌توانید ابرداده‌های بسیاری از قالب‌های دیگر از جمله را نیز دستکاری کنید." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
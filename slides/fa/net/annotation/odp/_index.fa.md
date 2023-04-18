---
title: حاشیه نویسی ODP را با استفاده از دات نت حذف کنید
weight: 4380
url: /fa/net/annotation/odp/ 
description: کد منبع سی شارپ برای حذف حاشیه نویسی های فرمت ODP در .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="حذف نظرات و نویسندگان نظرات از ODP در C#" h2="برنامه های دات نت خود را برای دستکاری نظرات و نویسندگان در فایل های سند با استفاده از API های سمت سرور بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="حذف نظرات از ODP از طریق C#" %}}
برای حذف حاشیه‌نویسی‌ها از فایل ODP، از [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net) API استفاده می‌کنیم که دارای ویژگی‌های غنی، قدرتمند و آسان برای استفاده است. API دستکاری اسناد برای پلتفرم سی شارپ.
{{% blocks/products/pf/agp/code-block title="حذف حاشیه نویسی از ODP - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.odp"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="نحوه حذف نظرات از ODP از طریق C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای NET** نصب کنید. [**نصب**](https://docs.aspose.com/slides/net/installation/) را ببینید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP را با یک نمونه از کلاس Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تکرار روی همه نویسندگان ODP بارگذاری شده
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تمام نظرات یک نویسنده را حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
در پایان تمام نویسندگان را حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های حاشیه نویسی پشتیبانی شده" subTitle="با استفاده از سی شارپ، می توان به راحتی فرمت های دیگر از جمله حاشیه نویسی کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
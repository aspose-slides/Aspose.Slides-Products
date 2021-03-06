---
title: حاشیه نویسی PPTX را از طریق دات نت حذف کنید
weight: 6550
url: /fa/net/annotation/pptx/ 
description: کد منبع سی شارپ برای حذف حاشیه‌نویسی‌های فرمت PPTX در پلتفرم‌های NET Framework، NET Core، Windows Azure، Mono یا Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="حذف نظرات و نویسندگان نظرات از PPTX از طریق C#" h2="برنامه های دات نت خود را بسازید تا نظرات و نویسندگان را در فایل های سند با استفاده از API های سمت سرور دستکاری کنید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه حاشیه نویسی فایل PPTX با استفاده از سی شارپ" %}}

 به منظور حاشیه نویسی فایل PPTX، ما استفاده خواهیم کرد
 [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net)
 API که یک API دستکاری اسناد غنی، قدرتمند و آسان برای پلتفرم C# است. باز کن
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 مدیر بسته، جستجو کنید
 **Aspose.Slides**
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{% blocks/products/pf/agp/code-block title="فرمان" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="حذف نظرات از PPTX از طریق C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="شما به [aspose.slides.dll](https://downloads.aspose.com/slides/net) نیاز دارید تا کد را در محیط خود امتحان کنید." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX را با یک نمونه از کلاس Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تکرار روی همه نویسندگان PPTX بارگذاری شده
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
همه نظرات هر نویسنده را حلقه بزنید و بررسی کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حذف تمام نظرات یک نویسنده
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
در پایان نویسنده را حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for .NET در تمام سیستم عامل های اصلی پشتیبانی می شود. فقط مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin.
- محیط توسعه مانند Microsoft Visual Studio.
- Aspose.Slides برای DLL NET که در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="حذف حاشیه نویسی از PPTX - C#" offSpacer="" %}}

```cs
// load PPTX with a new instance of Presentation class
var presentation = new Aspose.Slides.Presentation("template.odp");
// iterate over comment authors
foreach (var author in presentation.CommentAuthors)
{
    // iterate over author comments
    foreach (var comment in author.Comments)
    {
        // remove comments
        author.Comments.Remove(comment);
    }
    // remove author
    author.Remove();
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="درباره Aspose.Slides for .NET API" %}}

 Aspose.Slides API را می توان برای خواندن، نوشتن، دستکاری و تبدیل اسناد Microsoft PowerPoint به PDF، XPS، HTML، TIFF، ODP و فرمت های مختلف دیگر استفاده کرد. می توان فایل های جدید را از ابتدا ایجاد کرد و آن ها را در قالب های پشتیبانی شده مربوطه ذخیره کرد. Aspose.Slides یک API مستقل برای ایجاد، تجزیه یا دستکاری ارائه ها، اسلایدها و عناصر است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice وابسته نیست.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Remove Annotation from PPTX via Online App" sectionDescription="Delete PPTX document annotations right now by visiting our [Live Demos website](https://products.aspose.app/slides/annotation). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPTX file and hit the \"Remove\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های حاشیه نویسی پشتیبانی شده" subTitle="با استفاده از سی شارپ، می توان به راحتی فرمت های دیگر از جمله حاشیه نویسی کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/annotation/odp/" name="ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/annotation/ppt/" name="PPT" description="مایکروسافت پاورپوینت 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
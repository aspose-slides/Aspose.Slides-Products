---
title: جستجو و جایگزینی متن در سند PPTX از طریق دات نت
weight: 4070
url: /fa/net/redaction/pptx/ 
description: کد منبع سی شارپ برای ویرایش اطلاعات حساس در فایل PPTX بر روی پلتفرم‌های NET Framework، NET Core، Windows Azure، Mono یا Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="ویرایش فرمت های PPTX در سی شارپ" h2="PPTX بومی و با کارایی بالا، اطلاعات ویرایش حساس را با استفاده از Aspose.Slides سمت سرور برای API های NET، بدون استفاده از نرم افزارهایی مانند Microsoft یا Adobe PDF، ثبت می کند." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه ویرایش فایل PPTX با استفاده از سی شارپ" %}}

 به منظور ویرایش فایل PPTX، ما استفاده خواهیم کرد
 [Aspose.Slides for .NET](https://products.aspose.com/slides/net)
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


{{< blocks/products/pf/agp/feature-section-col title="مراحل ویرایش فایل های PPTX در سی شارپ" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="جستجوی اولیه سند و جایگزینی متن در محتوا، نظرات یا ابرداده با [Aspose.Slides for .NET](https://products.aspose.com/slides/net) APIها را می توان تنها با چند خط کد انجام داد. متن را در پاورپوینت و اپن آفیس پیدا و جایگزین کنید. ویرایش متن، نظرات، ابرداده در ارائه از طریق تطبیق داده های regexp." >}}

{{< blocks/products/pf/agp/step-autogen >}}
بارگزاری PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
در هر اسلاید حلقه بزنید و مجموعه textFrame را دریافت کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
حلقه از طریق مجموعه.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
از روش Replace و سپس Highlight Text استفاده کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ذخیره ارائه
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 API های ما در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می شوند. لطفا قبل از اجرای کد زیر، از داشتن پیش نیازهای زیر در سیستم خود اطمینان حاصل کنید.

{{% /blocks/products/pf/agp/text %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin Platforms
- محیط توسعه مانند Microsoft Visual Studio
- Aspose.Slides برای DLL.NET که در پروژه شما ارجاع داده شده است - از NuGet با استفاده از دکمه دانلود در بالا نصب کنید

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ویرایش فایل های PPTX - C#" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation("pres.pptx")){
    const string toRedact = "bKIM";
    string stub = new string(' ', toRedact.Length);
   //Using Aspose.Slides, one can use highlight text color feature to Redact text.
    foreach (ISlide slide in pres.Slides){
        ITextFrame[] textFrames = SlideUtil.GetAllTextBoxes(slide);
        foreach (ITextFrame textFrame in textFrames){
            textFrame.Text = textFrame.Text.Replace(toRedact, stub);
            textFrame.HighlightText(stub, Color.Black);
        }
    }

    pres.Save("pres-edited.pptx", SaveFormat.Pptx);
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

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in PPTX documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/redaction). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPTX files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های ویرایش پشتیبانی شده" subTitle="با استفاده از سی شارپ، می توان به راحتی فرمت های مختلف از جمله را ویرایش کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/redaction/odp/" name="ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/redaction/ppt/" name="PPT" description="مایکروسافت پاورپوینت 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
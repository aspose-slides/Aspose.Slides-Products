---
title: مشاهده فرمت های فایل POTX از طریق دات نت
weight: 5740
url: /fa/net/viewer/potx/ 
description: کد منبع سی شارپ برای بارگیری، رندر و نمایش اسناد POTX بر روی پلتفرم‌های NET Framework، NET Core، Windows Azure، Mono یا Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="نمایشگر فایل POTX برای دات نت" h2="مشاهده فایل های ارائه مانند POTX بدون Microsoft PowerPoint یا Office Automation" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه مشاهده فایل POTX با استفاده از سی شارپ" %}}

 برای مشاهده فایل POTX از
 [Aspose.Slides for .NET](https://products.aspose.com/slides/net)
 API که یک API غنی از ویژگی، قدرتمند و آسان برای پلتفرم C# است که با هر Viewer قابل استفاده است. باز کن
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 مدیر بسته، جستجو کنید
 **Aspose.Slides**
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{% blocks/products/pf/agp/code-block title="فرمان کنسول Package Manager" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="مراحل مشاهده POTX از طریق C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aspose.Slides مشاهده فایل POTX را تنها با چند خط کد برای توسعه دهندگان آسان می کند." >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک شی Presentation را نمونه‌سازی کنید و فایل POTX را بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک نمونه از ResponsiveHtmlController برای قالب بندی ایجاد کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک نمونه از HtmlOptions ایجاد کنید و ویژگی HtmlFormatter را تنظیم کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه POTX را در قالب HTML ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فراخوانی Process.Start با مسیر به HTML حاصل برای بارگیری محتوای POTX در مرورگر پیش فرض
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for .NET در تمام سیستم عامل های اصلی پشتیبانی می شود. فقط مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin Platforms
- محیط توسعه مانند Microsoft Visual Studio
- Aspose.Slides برای دات نت که در پروژه شما ارجاع داده شده است

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="کد مثال سی شارپ برای مشاهده فایل POTX" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// instantiate a Presentation object & load the POTX file
using (var presentation = new Aspose.Slides.Presentation("templatepotx"))
{
    // create HTML export controller
    var controller = new Aspose.Slides.Export.ResponsiveHtmlController();
    // create an instance of HtmlOptions and set HtmlFormatter property
    var htmlOptions = new Aspose.Slides.Export.HtmlOptions 
    { 
        HtmlFormatter = Aspose.Slides.Export.HtmlFormatter.CreateCustomFormatter(controller) 
    };

    // save the presentation in HTML
    presentation.Save(output, Aspose.Slides.Export.SaveFormat.Html, htmlOptions);
}
// load HTML to view the presentation content
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="درباره Aspose.Slides for .NET API" %}}

 Aspose.Slides API را می توان برای خواندن، نوشتن، دستکاری و تبدیل اسناد Microsoft PowerPoint به PDF، XPS، HTML، TIFF، ODP و فرمت های مختلف دیگر استفاده کرد. می توان فایل های جدید را از ابتدا ایجاد کرد و آن ها را در قالب های پشتیبانی شده مربوطه ذخیره کرد. Aspose.Slides یک API مستقل برای ایجاد، تجزیه یا دستکاری ارائه ها، اسلایدها و عناصر است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice وابسته نیست.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to View POTX" sectionDescription="Check our live demos to [View POTX](https://products.aspose.app/slides/viewer/potx) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload POTX file and hit the \"View\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download POTX file from the link, if required" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POTX" readMoreLink="https://docs.fileformat.com/presentation/potx/" >}}
Files with .POTX extension represent Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. This format was created to replace the POT file format that is based on the binary file format and is supported with PowerPoint 97-2003. The files generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های نمایشگر پشتیبانی شده" subTitle="با استفاده از سی شارپ، می توان بسیاری از فرمت های فایل دیگر از جمله را مشاهده کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/odp/" name="ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/otp/" name="OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/pot/" name="POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/potm/" name="POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/pps/" name="PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/ppsm/" name="PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/ppsx/" name="PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/ppt/" name="PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/pptm/" name="PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/viewer/pptx/" name="PPTX" description="قالب ارائه XML را باز کنید" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
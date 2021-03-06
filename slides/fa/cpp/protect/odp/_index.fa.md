---
title: از طریق C++ سند ODP را محافظت و قفل کنید
weight: 670
url: /fa/cpp/protect/odp/ 
description: کد مثال C++ برای قفل کردن فایل ODP با استفاده از رمز عبور در C++ Runtime Environment برای ویندوز 32 بیت، ویندوز 64 بیت و لینوکس 64 بیت.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="فایل های ODP را از طریق C++ رمزگذاری کنید" h2="ارائه های پاورپوینت از جمله فرمت ODP با استفاده از کتابخانه دات نت محافظت از رمز عبور." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp/" installationsDocsLink="https://docs.aspose.com/slides/cpp/" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="نحوه ایمن کردن فایل ODP با استفاده از C++" %}}

 به منظور محافظت از فایل ODP، استفاده خواهیم کرد
 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp)
 API که یک API رمزگذاری اسناد غنی، قدرتمند و آسان برای پلتفرم C++ است. می توانید آخرین نسخه آن را مستقیما دانلود کنید، فقط باز کنید
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 مدیر بسته، جستجو کنید
 **Aspose.Slides.Cpp**
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{% blocks/products/pf/agp/code-block title="Aspose.Slides" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="مراحل محافظت از فایل های ODP از طریق C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="حفاظت از اسناد با استفاده از APIهای Aspose.Slides را می توان تنها با چند خط کد انجام داد." >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل ODP را بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
رمز عبور را با استفاده از متد get\_ProtectionManager()->Encrypt(.) تنظیم کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ارائه ODP محافظت شده را ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides برای C++ در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می کند. لطفا مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با C++ Runtime Environment برای ویندوز 32 بیت، ویندوز 64 بیت و لینوکس 64 بیت.
- Aspose.Slides برای C++ DLL که در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="فرمان" offSpacer="" %}}

```cs

const String sourceFilePath = u"SourcePath\SourceFile.odp";
const String outputFilePath = u"OutputPath\OutPutFile.odp";

// Load the ODP file
SharedPtr<Presentation> odpFile = MakeObject<Presentation>(sourceFilePath);

// Protect with password
odpFile->get_ProtectionManager()->Encrypt(u"password");

// Save the ODP
odpFile->Save(outputFilePath, SaveFormat::Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="درباره Aspose.Slides for C++ API" %}}

 Aspose.Slides API را می توان برای خواندن، نوشتن، دستکاری و تبدیل اسناد Microsoft PowerPoint به PDF، XPS، HTML، TIFF، ODP و فرمت های مختلف دیگر استفاده کرد. می توان فایل های جدید را از ابتدا ایجاد کرد و آن ها را در قالب های پشتیبانی شده مربوطه ذخیره کرد. Aspose.Slides یک API مستقل برای ایجاد، تجزیه یا دستکاری ارائه ها، اسلایدها و عناصر است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice وابسته نیست.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect ODP" sectionDescription="Check our live demos to [encrypt ODP files](https://products.aspose.app/slides/protect/odp) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload ODP file and hit the \"Unlock\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant ODP file from the link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر اسناد حفاظتی پشتیبانی شده" subTitle="با استفاده از C++، می توان از فایل های دیگر از جمله محافظت کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/protect/ppt/" name="PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/protect/pptx/" name="PPTX" description="قالب ارائه XML را باز کنید" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
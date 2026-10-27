---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ادغام فایل های PPSM از طریق دات نت
weight: 3860
url: /fa/net/merger/ppsm/ 
description: کد منبع سی شارپ برای ترکیب اسناد PPSM بر روی پلتفرم‌های NET Framework، NET Core، Windows Azure، Mono یا Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ادغام فرمت های PPSM در سی شارپ" h2="ادغام اسناد PPSM بومی و با کارایی بالا با استفاده از Aspose.Slides سمت سرور برای APIهای دات نت، بدون استفاده از هیچ نرم افزاری مانند Microsoft یا Open Office، Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه ادغام فایل PPSM با استفاده از سی شارپ" %}}

برای ادغام فایل PPSM، از
 [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net)
 API که یک API غنی از ویژگی، قدرتمند و آسان برای دستکاری اسناد و ادغام API برای پلتفرم C# است. باز کن
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 مدیر بسته، جستجو کنید
 **Aspose.Slides**
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="فرمان" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ادغام فایل های PPSM - C#" >}}
```cs
var ps1 = new Presentation("presen1.ppsm");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPSM presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل ادغام فایل های PPSM در سی شارپ" intro="یک سند اساسی که با APIهای [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net) ادغام و الحاق می شود، تنها با چند خط کد قابل انجام است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تمام فایل های PPSM را با مسیر کامل بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک سند را به عنوان فایل پایه بسازید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روش مربوطه را برای الحاق و ادغام فایل ها یک به یک فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد Save() را فراخوانی کنید و نام فایل (مسیر کامل) و فرمت (PPSM) را به عنوان پارامتر ارسال کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اکنون می توانید فایل PPSM را در Microsoft Office، Adobe PDF یا هر برنامه سازگار دیگری باز کرده و از آن استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="API های ما در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می شوند. لطفا قبل از اجرای کد زیر، از داشتن پیش نیازهای زیر در سیستم خود اطمینان حاصل کنید." %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin Platforms
- محیط توسعه مانند Microsoft Visual Studio
- Aspose.Slides برای DLL.NET که در پروژه شما ارجاع داده شده است - از NuGet با استفاده از دکمه دانلود در بالا نصب کنید

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="ساخته شده با Aspose.Slides" title="ادغام آنلاین فایل‌های PPSM" description="برنامه رایگان Aspose.Slides Merger با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPSM شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Merger" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌ها را ادغام می‌کند.
- چند فایل PPSM را بارگذاری کنید و آن‌ها را در یک فایل ترکیب کنید.
- نتیجه ادغام‌شده را به‌صورت یک فایل دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" %}}

فایل‌هایی با پسوند PPSM فایل‌های اسلایدشو با پشتیبانی از ماکرو هستند که همراه با Microsoft PowerPoint 2007 معرفی شدند. برخلاف PPTM، فایل PPSM به‌طور پیش‌فرض در نمای اسلایدشو باز می‌شود. این حالت پیش‌فرض باز شدن، محافظت از فایل نیست؛ فایل PPSM را می‌توان برای ویرایش در Microsoft PowerPoint نیز باز کرد.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت های ادغام پشتیبانی شده" subTitle="با استفاده از سی شارپ، One می‌تواند بسیاری از فرمت‌های فایل دیگر از جمله را ادغام کند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/odp/" name="ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/otp/" name="OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/pot/" name="POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/potm/" name="POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/potx/" name="POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/pps/" name="PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/ppsx/" name="PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/ppt/" name="PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/pptm/" name="PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/net/merger/pptx/" name="PPTX" description="قالب ارائه XML را باز کنید" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

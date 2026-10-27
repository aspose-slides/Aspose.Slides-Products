---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ادغام فایل های POT از طریق ++C
weight: 4530
url: /fa/cpp/merger/pot/ 
description: کد مثال C++ برای ترکیب اسناد POT در C++ Runtime Environment برای ویندوز 32 بیت، ویندوز 64 بیت و لینوکس 64 بیت.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ادغام فایل های POT با استفاده از ++C" h2="ادغام سند POT با استفاده از APIهای C++ سمت سرور."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه ادغام فایل POT با استفاده از ++C" %}}

به منظور ادغام فایل POT، ما استفاده خواهیم کرد
 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)
 API که یک API ادغام اسناد با ویژگی های غنی، قدرتمند و آسان برای پلتفرم C++ است. می توانید آخرین نسخه آن را مستقیما دانلود کنید، فقط باز کنید
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 مدیر بسته، جستجو کنید
 **Aspose.Slides.Cpp**
 و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="فرمان" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ادغام فایل های POT - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.pot";
const String sourceFilePath2 = u"SourceFile3.pot";
const String outputFilePath = u"mergedOutput.pot";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pot);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل ادغام فایل های POT در C++" intro="یک سند اساسی که با APIهای [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) ادغام و الحاق می شود، تنها با چند خط کد قابل انجام است." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}هر دو فایل POT را بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از متد get\_Slides() برای تکرار در هر اسلاید استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از تابع AddClone برای ادغام با فایل مورد نظر استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از متد Save() برای ذخیره در مسیر مشخص شده استفاده کنید{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="Aspose.Slides برای C++ در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می کند. لطفا مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با C++ Runtime Environment برای ویندوز 32 بیت، ویندوز 64 بیت و لینوکس 64 بیت.
- Aspose.Slides برای C++ DLL که در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="ساخته شده با Aspose.Slides" title="ادغام آنلاین فایل‌های POT" description="برنامه رایگان Aspose.Slides Merger با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های POT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Merger" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌ها را ادغام می‌کند.
- چند فایل POT را بارگذاری کنید و آن‌ها را در یک فایل ترکیب کنید.
- نتیجه ادغام‌شده را به‌صورت یک فایل دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" %}}

فایل‌هایی با پسوند .POT قالب‌های ارائه دودویی Microsoft PowerPoint هستند. این قالب به خانواده قالب‌های فایل PowerPoint 97-2003 تعلق دارد. فایل‌های POT چیدمان اسلایدها، تم‌ها، سبک‌ها، پس‌زمینه‌ها، طرح‌های رنگی، فونت‌ها و دیگر قالب‌بندی‌های قابل استفاده مجدد را برای ساخت ارائه‌های جدید ذخیره می‌کنند.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت های ادغام پشتیبانی شده" subTitle="با استفاده از C++، One می‌تواند بسیاری از فرمت‌های فایل دیگر از جمله ..." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/odp/" name="ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/otp/" name="OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/potm/" name="POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/potx/" name="POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/pps/" name="PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/ppsm/" name="PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/ppsx/" name="PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/ppt/" name="PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/pptm/" name="PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/merger/pptx/" name="PPTX" description="قالب ارائه XML را باز کنید" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

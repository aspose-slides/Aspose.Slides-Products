---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل POTX به SVG از طریق برنامه ++C
weight: 4120
url: /fa/cpp/conversion/potx-to-svg/ 
description: نمونه کد تبدیل C++ برای سند POTX به فرمت SVG. از کد مثال برای تبدیل دسته ای POTX به SVG در هر برنامه C++ استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل POTX به SVG از طریق C++" h2="تبدیل POTX به SVG با کارایی بالا با استفاده از کتابخانه ++C بدون نیاز به نصب پاورپوینت مایکروسافت."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه تبدیل POTX به SVG با استفاده از ++C" %}}

به منظور تبدیل POTX به SVG، ما استفاده خواهیم کرد
 [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/)
 API که یک API غنی از ویژگی، قدرتمند و آسان برای دستکاری و تبدیل اسناد برای پلتفرم ++C است. می توانید آخرین نسخه آن را مستقیما دانلود کنید، فقط باز کنید
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 مدیر بسته، جستجو کنید
 Aspose.Slides.Cpp
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد منبع تبدیل POTX به SVG C++" >}}
```cs
// Load the POTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.potx");
// Save in SVG format.
for (int32_t index = 0; index < prs->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = prs->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل تبدیل POTX به SVG از طریق C++" intro="توسعه دهندگان ++C می توانند به راحتی فایل POTX را تنها در چند خط کد به SVG تبدیل کنند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل POTX را با Aspose.Slides برای C++ Presentation Object بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد Save() را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مسیر فایل خروجی را با پسوند فایل (SVG) عبور دهید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل SVG در مسیر مشخص شده ذخیره می شود.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل SVG را در برنامه سازگار باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="قبل از اجرای کد مثال تبدیل C++، مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با C++ Runtime Environment برای ویندوز 32 بیت، ویندوز 64 بیت و لینوکس 64 بیت.
- Aspose.Slides برای C++ DLL که در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="برنامه رایگان برای تبدیل POTX به SVG"
  description="[برنامه رایگان Editor ما را امتحان کنید](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید POTX را به بسیاری از فرمت‌های فایل دیگر از جمله تعداد کمی از آنها در زیر تبدیل کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-bmp/" name="POTX TO BMP" description="تصویر بیت مپ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-emf/" name="POTX TO EMF" description="فرمت متافایل پیشرفته" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-gif/" name="POTX TO GIF" description="فرمت تبادل گرافیکی" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-html/" name="POTX TO HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="تصویر JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-odp/" name="POTX TO ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-otp/" name="POTX TO OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-pdf/" name="POTX TO PDF" description="فرمت سند قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-png/" name="POTX TO PNG" description="گرافیک شبکه قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-pot/" name="POTX TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-potm/" name="POTX TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-pps/" name="POTX TO PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-ppt/" name="POTX TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-pptm/" name="POTX TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-pptx/" name="POTX TO PPTX" description="قالب ارائه XML را باز کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-tiff/" name="POTX TO TIFF" description="فرمت تصویر برچسب شده" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-xml/" name="POTX TO XML" description="زبان نشانه گذاری توسعه پذیر" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/potx-to-xps/" name="POTX TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

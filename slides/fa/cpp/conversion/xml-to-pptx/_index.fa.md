---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل XML به PPTX از طریق برنامه ++C
weight: 6320
url: /fa/cpp/conversion/xml-to-pptx/ 
description: نمونه کد تبدیل C++ برای سند XML به فرمت PPTX. از کد مثال برای تبدیل دسته ای XML به PPTX در هر برنامه C++ استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="XML را از طریق C++ به PPTX تبدیل کنید" h2="تبدیل XML به PPTX با کارایی بالا با استفاده از کتابخانه ++C بدون نیاز به نصب پاورپوینت مایکروسافت."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه تبدیل XML به PPTX با استفاده از ++C" %}}

برای تبدیل XML به PPTX، ما استفاده خواهیم کرد
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد منبع تبدیل XML به PPTX C++" >}}
```cs
// Load the XML.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.xml");
// Save in PPTX format.
prs->Save(u"convertedFile.pptx", Aspose::Slides::Export::SaveFormat::Pptx);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل تبدیل XML به PPTX از طریق C++" intro="توسعه دهندگان ++C می توانند به راحتی فایل XML را تنها در چند خط کد به PPTX تبدیل کنند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل XML را با Aspose.Slides برای C++ Presentation Object بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد Save() را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مسیر فایل خروجی را با پسوند فایل (PPTX) عبور دهید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTX در مسیر مشخص شده ذخیره می شود.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTX را در برنامه سازگار باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="قبل از اجرای کد مثال تبدیل C++، مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با C++ Runtime Environment برای ویندوز 32 بیت، ویندوز 64 بیت و لینوکس 64 بیت.
- Aspose.Slides برای C++ DLL که در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="ساخته شده با Aspose.Slides" title="تبدیل آنلاین XML به PPTX" description="برنامه رایگان Aspose.Slides Conversion با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های XML شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Conversion" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" upload="فایل خود را رها یا بارگذاری کنید" saveAs="ذخیره با فرمت" convert="تبدیل" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌ها را تبدیل می‌کند.
- فایل‌های XML را بارگذاری کنید و آن‌ها را با فرمت PPTX ذخیره کنید.
- نتیجه را دانلود کنید یا فایل‌های بیشتری را تبدیل کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید XML را به بسیاری از فرمت‌های فایل دیگر از جمله چند مورد در زیر تبدیل کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-bmp/" name="XML TO BMP" description="تصویر بیت مپ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-emf/" name="XML TO EMF" description="فرمت متافایل پیشرفته" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-gif/" name="XML TO GIF" description="فرمت تبادل گرافیکی" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-html/" name="XML TO HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-jpeg/" name="XML TO JPEG" description="تصویر JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-odp/" name="XML TO ODP" description="فرمت ارائه اسناد باز" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-otp/" name="XML TO OTP" description="فرمت استاندارد OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-pdf/" name="XML TO PDF" description="فرمت سند قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-png/" name="XML TO PNG" description="گرافیک شبکه قابل حمل" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-pot/" name="XML TO POT" description="فایل های قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-potm/" name="XML TO POTM" description="فایل قالب پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-potx/" name="XML TO POTX" description="ارائه الگوی پاورپوینت مایکروسافت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-pps/" name="XML TO PPS" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-ppsm/" name="XML TO PPSM" description="نمایش اسلاید با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-ppsx/" name="XML TO PPSX" description="نمایش اسلاید پاورپوینت" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-ppt/" name="XML TO PPT" description="مایکروسافت پاورپوینت 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-pptm/" name="XML TO PPTM" description="فایل ارائه با قابلیت ماکرو" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-svg/" name="XML TO SVG" description="گرافیک برداری مقیاس پذیر" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-tiff/" name="XML TO TIFF" description="فرمت تصویر برچسب شده" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/xml-to-xps/" name="XML TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

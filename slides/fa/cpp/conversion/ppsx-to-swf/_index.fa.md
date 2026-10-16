---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل PPSX به SWF از طریق برنامه ++C
url: /fa/cpp/conversion/ppsx-to-swf/ 
description: نمونه کد تبدیل C++ برای سند PPSX به فرمت SWF. از کد مثال برای تبدیل دسته ای PPSX به SWF در هر برنامه C++ استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSX را از طریق C++ به SWF تبدیل کنید" h2="تبدیل PPSX به SWF با کارایی بالا با استفاده از کتابخانه ++C بدون نیاز به نصب پاورپوینت مایکروسافت."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="نحوه تبدیل PPSX به SWF با استفاده از ++C" %}}

برای تبدیل PPSX به SWF، از <a href="https://products.aspose.com/slides/fa/cpp">Aspose.Slides for C++</a> API استفاده خواهیم کرد که یک ویژگی غنی و قدرتمند است. و آسان برای استفاده از دستکاری اسناد و API تبدیل برای پلت فرم ++C. می‌توانید آخرین نسخه آن را مستقیماً دانلود کنید، فقط مدیر بسته <a href="https://www.nuget.org/packages/aspose.slides">NuGet</a> را باز کنید، <b>Aspose.Slides.Cpp را جستجو کنید. </b> و نصب کنید. همچنین می توانید از دستور زیر در کنسول Package Manager استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="فرمان" >}}
```cs

PM> Install-Package Aspose.SLIDES.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد منبع تبدیل PPSX به SWF C++" >}}
```cs
// Load the PPSX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppsx");
// Save in SWF format.
prs->Save(u"convertedFile.swf", Aspose::Slides::Export::SaveFormat::Swf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="مراحل تبدیل PPSX به SWF از طریق C++" intro="Aspose.SLIDES API تبدیل فایل PPSX به SWF را در چند خط کد برای توسعه دهندگان آسان می کند." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPSX را با Aspose.Slides برای C++ Presentation Object بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد Save() را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مسیر فایل خروجی را با پسوند فایل (SWF) عبور دهید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل SWF در مسیر مشخص شده ذخیره می شود.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل SWF را در برنامه سازگار باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="سیستم مورد نیاز" intro="Aspose.SLIDES برای C++ در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می کند. لطفا مطمئن شوید که پیش نیازهای زیر را دارید." %}}

- مایکروسافت ویندوز یا یک سیستم عامل سازگار با C++ Runtime Environment برای ویندوز 32 بیت، ویندوز 64 بیت و لینوکس 64 بیت.
- Aspose.Slides برای C++ DLL که در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="برنامه رایگان برای تبدیل PPSX به SWF"
  description="[برنامه رایگان Text To Gif ما را امتحان کنید](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می‌توانید PPSX را به بسیاری از فرمت‌های فایل دیگر از جمله تعداد کمی از آنها در زیر تبدیل کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmap Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Enhanced Metafile Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Graphical Interchange Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="JPEG Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument Presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument Standard Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Portable Document Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Portable Network Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint Template Files" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint Template File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint Template Presentation" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Macro-enabled Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Macro-enabled Presentation File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Open XML presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Scalable Vector Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Tagged Image Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-xml/" name="PPSX TO XML" description="Extensible Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="مشخصات کاغذ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

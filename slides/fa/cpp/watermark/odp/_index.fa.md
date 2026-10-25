---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: افزودن واترمارک به ارائه‌های ODP با C++
url: /fa/cpp/watermark/odp/
description: در C++ واترمارک متنی یا تصویری به ارائه‌های ODP اضافه کنید. از Aspose.Slides for C++ برای قرار دادن واترمارک روی اسلایدها استفاده کنید.
keywords: افزودن واترمارک به ODP، افزودن واترمارک متنی به ODP، افزودن واترمارک تصویری به ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="افزودن واترمارک به ارائه ODP با C++" h2="از Aspose.Slides for C++ برای افزودن واترمارک متنی یا تصویری به فایل‌های ارائه بدون Microsoft PowerPoint استفاده کنید." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="افزودن واترمارک به ارائه ODP از طریق C++" variant="code" %}}

Aspose.Slides for C++ به شما امکان می‌دهد واترمارک متنی یا تصویری به ارائه‌های ODP اضافه کنید. با `AddAutoShape` یک شکل واترمارک به اسلاید اصلی اضافه کنید، با `AddTextFrame` متن اضافه کنید یا شکل را با تصویری که از طریق `File::ReadAllBytes` و `AddImage` بارگذاری می‌شود پر کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک متنی به ODP با C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک تصویری به ارائه ODP با C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه افزودن واترمارک به ODP با C++" intro="برای افزودن واترمارک متنی یا تصویری به فایل‌های ODP این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اسلاید اصلی را از مجموعه `Presentation::get_Masters` انتخاب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با متد `AddAutoShape` یک شکل واترمارک اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با متد `AddTextFrame` متن واترمارک اضافه کنید یا با `AddImage` پرکننده تصویری تنظیم کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل دارای واترمارک را با `SaveFormat::Odp` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="ساخته شده با Aspose.Slides" title="افزودن آنلاین واترمارک به فایل‌های ODP" description="برنامه رایگان Aspose.Slides Watermark با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Watermark" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه واترمارک اضافه می‌کند.
- یک واترمارک متنی یا تصویری به فایل ODP خود اضافه کنید.
- فایل دارای واترمارک را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌کننده واترمارک" subTitle="با C++ می‌توانید به قالب‌های زیر نیز واترمارک اضافه کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

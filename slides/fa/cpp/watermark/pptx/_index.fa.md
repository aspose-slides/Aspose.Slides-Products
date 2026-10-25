---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: افزودن واترمارک به ارائه‌های PPTX با C++
url: /fa/cpp/watermark/pptx/
description: در C++ واترمارک متنی یا تصویری به ارائه‌های PPTX اضافه کنید. از Aspose.Slides for C++ برای قرار دادن واترمارک روی اسلایدها استفاده کنید.
keywords: افزودن واترمارک به PPTX، افزودن واترمارک متنی به PPTX، افزودن واترمارک تصویری به PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="افزودن واترمارک به ارائه PPTX با C++" h2="از Aspose.Slides for C++ برای افزودن واترمارک متنی یا تصویری به فایل‌های ارائه بدون Microsoft PowerPoint استفاده کنید." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="افزودن واترمارک به ارائه PPTX از طریق C++" variant="code" %}}

Aspose.Slides for C++ به شما امکان می‌دهد واترمارک متنی یا تصویری به ارائه‌های PPTX اضافه کنید. با `AddAutoShape` یک شکل واترمارک به اسلاید اصلی اضافه کنید، با `AddTextFrame` متن اضافه کنید یا شکل را با تصویری که از طریق `File::ReadAllBytes` و `AddImage` بارگذاری می‌شود پر کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک متنی به PPTX با C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن واترمارک تصویری به ارائه PPTX با C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه افزودن واترمارک به PPTX با C++" intro="برای افزودن واترمارک متنی یا تصویری به فایل‌های PPTX این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTX را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اسلاید اصلی را از مجموعه `Presentation::get_Masters` انتخاب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با متد `AddAutoShape` یک شکل واترمارک اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با متد `AddTextFrame` متن واترمارک اضافه کنید یا با `AddImage` پرکننده تصویری تنظیم کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل دارای واترمارک را با `SaveFormat::Pptx` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="ساخته شده با Aspose.Slides" title="افزودن آنلاین واترمارک به فایل‌های PPTX" description="برنامه رایگان Aspose.Slides Watermark با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Watermark" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه واترمارک اضافه می‌کند.
- یک واترمارک متنی یا تصویری به فایل PPTX خود اضافه کنید.
- فایل دارای واترمارک را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌کننده واترمارک" subTitle="با C++ می‌توانید به قالب‌های زیر نیز واترمارک اضافه کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PDF را در C++ ویرایش کنید
url: /fa/cpp/editor/pdf/
keywords: ویرایش PDF، PDF، C++ API، C++ Library
description: PDF را در C++ ویرایش کنید. از C++ library API برای ویرایش سند PDF استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PDF را در C++ ویرایش کنید" h2="کتابخانه C++ پرسرعت و کراس پلتفرم برای ویرایش PDF با استفاده از کد C++" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PDF را در C++ ویرایش کنید" variant="code" %}}

با استفاده از [**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/)، می توانید تنها با چند خط کد، یک خط متن جدید به سند PDF اضافه کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد C++ برای ویرایش PDF" >}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PDF را با استفاده از Aspose.Slides ویرایش کنید" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) یک کتابخانه قدرتمند C++ است که برای دستکاری و ویرایش ارائه‌ها، اسناد PDF و فایل‌های دیگر استفاده می‌شود. می توانید یک سند PDF را با افزودن یک خط متن جدید به آن ویرایش کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه ویرایش PDF در C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides را برای C++** نصب کنید. [**نصب**](https://docs.aspose.com/slides/cpp/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک نمونه از کلاس Presentation ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سند PDF را که می خواهید ویرایش کنید بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک خط جدید از متن اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PDF تغییر یافته را ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="ساخته شده با Aspose.Slides" title="ویرایش آنلاین فایل‌های PPTX" description="برنامه رایگان Aspose.Slides Editor با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Editor" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌های شما را پردازش می‌کند.
- فایل‌های PPTX خود را بارگذاری کنید و فوراً ویرایش کنید.
- فایل ویرایش‌شده را ذخیره و دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="فایل های دیگر را ویرایش کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ویرایش کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

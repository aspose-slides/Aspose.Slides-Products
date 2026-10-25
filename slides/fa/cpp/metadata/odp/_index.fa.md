---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: مشاهده یا ویرایش فراداده ODP با C++
url: /fa/cpp/metadata/odp/
description: فراداده ODP را در C++ مشاهده و ویرایش کنید. با Aspose.Slides for C++ ویژگی‌های داخلی و سفارشی ارائه‌ها را به‌روز کنید.
keywords: ویرایش فراداده ODP، مشاهده فراداده ODP، ویرایش ویژگی‌های ODP، مشاهده ویژگی‌های ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ویرایش فراداده ODP با C++" h2="از Aspose.Slides for C++ برای مشاهده و به‌روزرسانی ویژگی‌های داخلی و سفارشی فایل‌های ارائه استفاده کنید." related="FODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تغییر ویژگی‌های ODP با C++" variant="code" %}}

با Aspose.Slides for C++ می‌توانید فراداده فایل‌های ODP را بدون Microsoft PowerPoint بخوانید و به‌روز کنید. از شیء [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) که `Presentation::get_DocumentProperties` در اختیار می‌گذارد برای تغییر ویژگی‌های داخلی مانند `Author` و `Title` یا مدیریت ویژگی‌های سفارشی با `idx_set`، `GetCustomPropertyName` و `RemoveCustomProperty` استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تغییر ویژگی‌های داخلی ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن ویژگی‌های سفارشی به ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه مشاهده یا ویرایش فراداده ODP در C++" intro="برای مشاهده یا ویرایش فراداده ODP این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}شیء `DocumentProperties` را با `get_DocumentProperties` دریافت کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ویژگی‌های داخلی مانند `Author` و `Title` را بخوانید یا به‌روز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ویژگی‌های سفارشی را با `idx_set`، `GetCustomPropertyName` و `RemoveCustomProperty` اضافه کنید، بخوانید یا حذف کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="ساخته شده با Aspose.Slides" title="مشاهده و ویرایش آنلاین فراداده ODP" description="برنامه رایگان Aspose.Slides Metadata با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Metadata" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides ویژگی‌ها را چگونه می‌خواند و می‌نویسد.
- ویژگی‌های داخلی و سفارشی فایل ODP خود را مشاهده و ویرایش کنید.
- فایل به‌روزشده را ذخیره و دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های فراداده پشتیبانی‌شده" subTitle="با C++ می‌توانید فراداده قالب‌های زیر را نیز مدیریت کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

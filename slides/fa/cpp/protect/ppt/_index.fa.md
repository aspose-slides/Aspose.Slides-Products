---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: محافظت از ارائه‌های PPT با C++
url: /fa/cpp/protect/ppt/
description: از ارائه‌های PPT در C++ محافظت کنید. از Aspose.Slides for C++ برای رمزگذاری فایل‌ها و تنظیم محافظت در برابر نوشتن استفاده کنید.
keywords: محافظت در برابر نوشتن PPT، رمزگذاری PPT، قفل کردن ارائه PPT، محافظت از PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="قفل کردن یا محافظت از PPT با رمز عبور در C++" h2="از Aspose.Slides for C++ برای رمزگذاری ارائه‌ها و تنظیم محافظت در برابر نوشتن بدون Microsoft PowerPoint استفاده کنید." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="محافظت از ارائه PPT با C++" variant="code" %}}

Aspose.Slides for C++ به شما امکان می‌دهد ارائه‌های PPT را در برابر باز شدن یا ویرایش محافظت کنید. از شیء `ProtectionManager` در کلاس `Presentation` برای رمزگذاری فایل با `Encrypt` یا محدود کردن ویرایش با `SetWriteProtection` استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="رمزگذاری ارائه PPT با C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تنظیم محافظت در برابر نوشتن برای ارائه PPT با C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه محافظت از PPT با رمز عبور در C++" intro="برای محافظت از ارائه PPT، این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPT را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با شیء `ProtectionManager` از ارائه محافظت کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}برای محافظت با رمز عبور از `Encrypt` و برای محافظت در برابر نوشتن از `SetWriteProtection` استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل محافظت‌شده را با `SaveFormat::Ppt` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="ساخته شده با Aspose.Slides" title="محافظت آنلاین از فایل‌های PPT با رمز عبور" description="برنامه رایگان Aspose.Slides Lock با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Lock" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه از ارائه‌ها محافظت می‌کند.
- برای باز کردن یا ویرایش فایل PPT خود رمز عبور تعیین کنید.
- فایل محافظت‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای محافظت" subTitle="با C++ می‌توانید از فرمت‌های زیر نیز محافظت کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

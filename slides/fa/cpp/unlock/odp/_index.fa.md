---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: باز کردن قفل ارائه‌های ODP با C++
url: /fa/cpp/unlock/odp/
description: قفل ارائه‌های ODP را در C++ باز کنید. از Aspose.Slides for C++ برای حذف رمزگذاری و محافظت در برابر نوشتن از فایل‌های ارائه استفاده کنید.
keywords: حذف محافظت در برابر نوشتن ODP، رمزگشایی ODP، باز کردن قفل ارائه ODP، برداشتن محافظت ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="باز کردن قفل ODP با C++" h2="از Aspose.Slides for C++ برای حذف رمزگذاری و محافظت در برابر نوشتن از فایل‌های ارائه بدون Microsoft PowerPoint استفاده کنید." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حذف محافظت از ارائه ODP با C++" variant="code" %}}

Aspose.Slides for C++ به شما امکان می‌دهد رمزگذاری یا محافظت در برابر نوشتن را از ارائه‌های ODP حذف کنید. برای باز کردن فایل رمزگذاری‌شده از `LoadOptions` استفاده کنید، سپس با شیء `ProtectionManager` در کلاس `Presentation`، `RemoveEncryption` یا `RemoveWriteProtection` را فراخوانی کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف محافظت با رمز عبور از ODP با C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف محافظت در برابر نوشتن از ارائه ODP با C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه حذف رمز عبور از ODP با C++" intro="برای حذف محافظت از ارائه ODP، این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با کلاس `Presentation` و در صورت نیاز به رمز عبور با `LoadOptions` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}برای حذف محافظت از شیء `ProtectionManager` استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}برای فایل‌های رمزگذاری‌شده `RemoveEncryption` و برای فایل‌های محافظت‌شده در برابر نوشتن `RemoveWriteProtection` را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل بازشده را با `SaveFormat::Odp` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="ساخته شده با Aspose.Slides" title="باز کردن قفل فایل‌های ODP به‌صورت آنلاین" description="برنامه رایگان Aspose.Slides Unlock با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Unlock" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه محافظت را حذف می‌کند.
- رمز عبور یا محافظت در برابر نوشتن را از فایل ODP خود حذف کنید.
- فایل بازشده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای باز کردن قفل" subTitle="با C++ می‌توانید محافظت را از فرمت‌های زیر نیز حذف کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

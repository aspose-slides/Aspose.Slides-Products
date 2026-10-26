---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: باز کردن قفل ارائه‌های PPTX با C++
url: /fa/cpp/unlock/pptx/
description: قفل ارائه‌های PPTX را در C++ باز کنید. از Aspose.Slides for C++ برای حذف رمزگذاری و محافظت در برابر نوشتن از فایل‌های ارائه استفاده کنید.
keywords: حذف محافظت در برابر نوشتن PPTX، رمزگشایی PPTX، باز کردن قفل ارائه PPTX، برداشتن محافظت PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="باز کردن قفل PPTX با C++" h2="از Aspose.Slides for C++ برای حذف رمزگذاری و محافظت در برابر نوشتن از فایل‌های ارائه بدون Microsoft PowerPoint استفاده کنید." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حذف محافظت از ارائه PPTX با C++" variant="code" %}}

Aspose.Slides for C++ به شما امکان می‌دهد رمزگذاری یا محافظت در برابر نوشتن را از ارائه‌های PPTX حذف کنید. برای باز کردن فایل رمزگذاری‌شده از `LoadOptions` استفاده کنید، سپس با شیء `ProtectionManager` در کلاس `Presentation`، `RemoveEncryption` یا `RemoveWriteProtection` را فراخوانی کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف محافظت با رمز عبور از PPTX با C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف محافظت در برابر نوشتن از ارائه PPTX با C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه حذف رمز عبور از PPTX با C++" intro="برای حذف محافظت از ارائه PPTX، این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTX را با کلاس `Presentation` و در صورت نیاز به رمز عبور با `LoadOptions` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}برای حذف محافظت از شیء `ProtectionManager` استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}برای فایل‌های رمزگذاری‌شده `RemoveEncryption` و برای فایل‌های محافظت‌شده در برابر نوشتن `RemoveWriteProtection` را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل بازشده را با `SaveFormat::Pptx` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="ساخته شده با Aspose.Slides" title="باز کردن قفل فایل‌های PPTX به‌صورت آنلاین" description="برنامه رایگان Aspose.Slides Unlock با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Unlock" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه محافظت را حذف می‌کند.
- رمز عبور یا محافظت در برابر نوشتن را از فایل PPTX خود حذف کنید.
- فایل بازشده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای باز کردن قفل" subTitle="با C++ می‌توانید محافظت را از فرمت‌های زیر نیز حذف کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

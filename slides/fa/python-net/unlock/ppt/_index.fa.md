---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: باز کردن قفل ارائه‌های PPT با Python
url: /fa/python-net/unlock/ppt/
description: رمزگذاری و محافظت در برابر نوشتن را با Python از ارائه‌های PPT حذف کنید.
keywords: باز کردن قفل PPT، حذف رمز عبور از PPT، حذف رمزگذاری PPT، حذف محافظت در برابر نوشتن از PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="باز کردن قفل ارائه‌های PPT با Python" h2="برنامه‌های Python بسازید که با Aspose.Slides رمزهای باز کردن و تنظیمات محافظت در برابر نوشتن را از ارائه‌های PPT حذف می‌کنند." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حذف رمزگذاری و محافظت در برابر نوشتن از PPT با Python" variant="code" %}}

با [Aspose.Slides for Python via .NET](/slides/fa/python-net/) می‌توانید رمزگذاری‌ای را که برای باز کردن ارائه PPT رمز عبور لازم دارد حذف کنید، یا تنظیم محافظت در برابر نوشتن آن را بردارید. برای باز کردن فایل رمزگذاری‌شده، رمز عبور فعلی را از طریق `LoadOptions` وارد کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف رمزگذاری از ارائه PPT – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف محافظت در برابر نوشتن از ارائه PPT – Python" >}}
```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه حذف محافظت از PPT با Python" intro="برای حذف محافظت از ارائه PPT، این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}برای فایل PPT رمزگذاری‌شده، رمز عبور فعلی را در `LoadOptions` تنظیم کنید و سپس فایل را با `Presentation` باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}برای حذف رمز باز کردن، `ProtectionManager.remove_encryption` را فراخوانی کنید، یا برای برداشتن محافظت در برابر نوشتن، `ProtectionManager.remove_write_protection` را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه حاصل را با `SaveFormat.PPT` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="ساخته شده با Aspose.Slides" title="باز کردن قفل فایل‌های PPT به‌صورت آنلاین" description="برنامه رایگان Aspose.Slides Unlock با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Unlock" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه محافظت را حذف می‌کند.
- رمز عبور یا محافظت در برابر نوشتن را از فایل PPT خود حذف کنید.
- فایل بازشده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای باز کردن قفل" subTitle="از Python برای حذف محافظت از سایر فرمت‌های ارائه پشتیبانی‌شده استفاده کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

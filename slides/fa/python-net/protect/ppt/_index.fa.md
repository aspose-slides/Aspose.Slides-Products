---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: محافظت از فایل‌های ارائه PPT با Python
url: /fa/python-net/protect/ppt/
description: ارائه‌های PPT را رمزگذاری کنید یا با Python محافظت در برابر نوشتن تنظیم کنید.
keywords: محافظت در برابر نوشتن PPT، رمزگذاری PPT با Python، قفل کردن ارائه PPT، محافظت از PPT با Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="محافظت از ارائه‌های PPT با Python" h2="برنامه‌های Python بسازید که با Aspose.Slides ارائه‌ها را رمزگذاری می‌کنند یا محافظت در برابر نوشتن تنظیم می‌کنند." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="محافظت از ارائه PPT با Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/fa/python-net/) دو سازوکار محافظتی متفاوت ارائه می‌دهد. `ProtectionManager.encrypt` را فراخوانی کنید تا ارائه PPT رمزگذاری شود و برای باز کردن آن رمز عبور لازم باشد. همچنین می‌توانید `ProtectionManager.set_write_protection` را فراخوانی کنید تا بدون رمزگذاری فایل، از ویرایش آن جلوگیری شود. کاربر همچنان می‌تواند ارائه محافظت‌شده در برابر نوشتن را باز کند و تغییرات را در فایل دیگری ذخیره کند.

{{< blocks/products/pf/slides-design-update-10-2026/code title="رمزگذاری ارائه PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تنظیم محافظت در برابر نوشتن برای ارائه PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه محافظت از PPT با Python" intro="برای محافظت از فایل PPT، این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPT را با `Presentation` باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از `ProtectionManager.encrypt` برای الزام رمز عبور هنگام باز کردن، یا از `ProtectionManager.set_write_protection` برای جلوگیری از تغییرات استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه محافظت‌شده را با `SaveFormat.PPT` به‌صورت PPT ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="ساخته شده با Aspose.Slides" title="محافظت آنلاین از فایل‌های PPT با رمز عبور" description="برنامه رایگان Aspose.Slides Lock با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Lock" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه از ارائه‌ها محافظت می‌کند.
- برای باز کردن یا ویرایش فایل PPT خود رمز عبور تعیین کنید.
- فایل محافظت‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای محافظت" subTitle="از Python برای محافظت از سایر فرمت‌های ارائه پشتیبانی‌شده استفاده کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

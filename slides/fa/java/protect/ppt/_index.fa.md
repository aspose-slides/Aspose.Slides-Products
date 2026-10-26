---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: محافظت از فایل‌های ارائه PPT با Java
url: /fa/java/protect/ppt/
description: از ارائه‌های PPT در Java محافظت کنید. از Aspose.Slides for Java برای رمزگذاری فایل‌های ارائه و تنظیم محافظت در برابر نوشتن استفاده کنید.
keywords: محافظت در برابر نوشتن PPT، رمزگذاری فایل PPT، قفل کردن ارائه PPT، محافظت از PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="قفل کردن یا محافظت از PPT با رمز عبور در Java" h2="برنامه‌های Java بسازید که با APIهای سمت سرور از فایل‌های ارائه محافظت می‌کنند." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="محافظت از ارائه PPT با Java" variant="code" %}}

با [Aspose.Slides for Java](/slides/fa/java/) می‌توانید با تعیین رمز عبور، ارائه PPT را در برابر باز شدن یا ویرایش محافظت کنید. از شیء `ProtectionManager` در کلاس `Presentation` برای فراخوانی متدهایی مانند `encrypt` و `setWriteProtection` استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="رمزگذاری ارائه PPT با Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تنظیم محافظت در برابر نوشتن برای ارائه PPT با Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه محافظت از PPT با رمز عبور در Java" intro="برای محافظت از ارائه PPT، این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPT را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد `encrypt` یا متد `setWriteProtection` شیء `ProtectionManager` را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل محافظت‌شده را با `SaveFormat.Ppt` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="ساخته شده با Aspose.Slides" title="محافظت آنلاین از فایل‌های PPT با رمز عبور" description="برنامه رایگان Aspose.Slides Lock با [Aspose.Slides for Java](https://products.aspose.com/slides/fa/java/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Lock" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه از ارائه‌ها محافظت می‌کند.
- برای باز کردن یا ویرایش فایل PPT خود رمز عبور تعیین کنید.
- فایل محافظت‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای محافظت" subTitle="با Java می‌توانید از فرمت‌های زیر نیز محافظت کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

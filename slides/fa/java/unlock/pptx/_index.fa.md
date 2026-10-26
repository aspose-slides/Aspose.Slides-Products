---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: باز کردن قفل فایل‌های ارائه PPTX با Java
url: /fa/java/unlock/pptx/
description: رمزهای عبور و محافظت در برابر نوشتن را از ارائه‌های PPTX در Java با Aspose.Slides for Java حذف کنید.
keywords: حذف محافظت در برابر نوشتن PPTX، رمزگشایی PPTX، باز کردن قفل ارائه PPTX، برداشتن محافظت PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="باز کردن قفل PPTX با Java" h2="برنامه‌های Java بسازید که با APIهای سمت سرور رمزهای عبور و محافظت در برابر نوشتن را از فایل‌های ارائه حذف می‌کنند." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حذف محافظت از ارائه PPTX با Java" variant="code" %}}

با [Aspose.Slides for Java](/slides/fa/java/) می‌توانید رمزگذاری یا محافظت در برابر نوشتن را از ارائه PPTX حذف کنید. برای باز کردن ارائه رمزگذاری‌شده از `LoadOptions.setPassword` و برای حذف تنظیمات محافظت از متدهای `removeEncryption` و `removeWriteProtection` در `ProtectionManager` استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف محافظت با رمز عبور از PPTX با Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.pptx", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف محافظت در برابر نوشتن از ارائه PPTX با Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه حذف رمز عبور از PPTX با Java" intro="برای حذف محافظت از ارائه PPTX، این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTX را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اگر ارائه رمزگذاری شده است، از `LoadOptions.setPassword` استفاده کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`removeEncryption` یا `removeWriteProtection` شیء `ProtectionManager` را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه بازشده را با `SaveFormat.Pptx` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="ساخته شده با Aspose.Slides" title="باز کردن قفل فایل‌های PPTX به‌صورت آنلاین" description="برنامه رایگان Aspose.Slides Unlock با [Aspose.Slides for Java](https://products.aspose.com/slides/fa/java/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Unlock" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه محافظت را حذف می‌کند.
- رمز عبور یا محافظت در برابر نوشتن را از فایل PPTX خود حذف کنید.
- فایل بازشده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای باز کردن قفل" subTitle="با Java می‌توانید محافظت را از فرمت‌های زیر نیز حذف کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: پنهان‌سازی اطلاعات در فایل‌های ارائه PPT با استفاده از Java
url: /fa/java/redaction/ppt/
description: متن را در ارائه‌های PPT در Java با Aspose.Slides for Java پیدا و جایگزین کنید.
keywords: پنهان‌سازی اطلاعات PPT، یافتن و جایگزینی متن در PPT، به‌روزرسانی ارائه PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="پنهان‌سازی اطلاعات در PPT با استفاده از Java" h2="برنامه‌های Java بسازید که با APIهای سمت سرور متن را در فایل‌های ارائه پیدا و جایگزین می‌کنند." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="پنهان‌سازی اطلاعات در یک ارائه PPT از طریق Java" variant="code" %}}

با [Aspose.Slides for Java](/slides/fa/java/) می‌توانید متن را در ارائه‌های PPT پیدا و جایگزین کنید. از متد `SlideUtil.findAndReplaceText` برای جستجو در ارائه و جایگزینی متن مطابق با یک مقدار جدید استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="پنهان‌سازی اطلاعات در یک ارائه PPT با استفاده از Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه پنهان‌سازی اطلاعات در PPT از طریق Java" intro="برای پنهان‌سازی اطلاعات در یک ارائه PPT این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPT را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد `SlideUtil.findAndReplaceText` را برای یافتن و جایگزینی متن فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه به‌روزشده را با `SaveFormat.Ppt` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="ساخته شده با Aspose.Slides" title="پنهان‌سازی آنلاین اطلاعات در فایل‌های PPT" description="برنامه رایگان Aspose.Slides Redaction با [Aspose.Slides for Java](https://products.aspose.com/slides/fa/java/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Redaction" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه متن را پیدا و جایگزین می‌کند.
- متن را در فایل PPT خود پیدا و جایگزین کنید، حتی با عبارات باقاعده.
- فایل پردازش‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای پنهان‌سازی اطلاعات" subTitle="با Java می‌توانید اطلاعات را در فرمت‌های زیر نیز پنهان کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 360
title: حذف حاشیه‌نویسی‌های PPTX با Java
url: /fa/java/annotation/pptx/ 
description: نظرها و نویسندگان نظر را با Aspose.Slides for Java از ارائه‌های PPTX در Java حذف کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="حذف نظرها و نویسندگان نظر از PPTX در Java" h2="از Aspose.Slides for Java برای حذف نظرها و نویسندگان نظر از فایل‌های ارائه استفاده کنید." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حذف نظرها از PPTX با Java" variant="code" %}}

Aspose.Slides for Java امکان حذف نظرها و نویسندگان نظر را از ارائه‌های PPTX فراهم می‌کند. فایلی را با کلاس `Presentation` بارگذاری کنید، اشیای `ICommentAuthor` را از `getCommentAuthors` پیمایش کنید، نظرهای آن‌ها را پاک کنید و ارائه به‌روزشده را ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف حاشیه‌نویسی‌ها از PPTX – Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="چگونه نظرها را از PPTX با Java حذف کنیم" intro="برای حذف نظرها و نویسندگان نظر از یک ارائه PPTX این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for Java را نصب کنید. [نصب](https://docs.aspose.com/slides/java/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTX را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اشیای `ICommentAuthor` را از `getCommentAuthors` پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}نظرهای هر نویسنده را با `getComments().clear()` پاک کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مجموعه نویسندگان نظر را خالی کنید و فایل PPTX به‌روزشده را ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="ساخته شده با Aspose.Slides" title="حذف آنلاین نظرهای PPTX" description="برنامه رایگان Aspose.Slides Annotation با [Aspose.Slides for Java](https://products.aspose.com/slides/fa/java/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Annotation" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه نظرها را حذف می‌کند.
- همه نظرها را از فایل PPTX خود حذف کنید.
- فایل پاک‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌شده برای حاشیه‌نویسی" subTitle="با Java می‌توانید حاشیه‌نویسی‌ها را از قالب‌های دیگر نیز حذف کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

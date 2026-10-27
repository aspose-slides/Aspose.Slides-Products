---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: حذف حاشیه‌نویسی‌های ODP با .NET
url: /fa/net/annotation/odp/ 
description: نظرها و نویسندگان نظر را از ارائه‌های ODP در C# حذف کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="حذف نظرها و نویسندگان نظر از ODP در C#" h2="برنامه‌های .NET بسازید که با APIهای سمت سرور، نظرها و نویسندگان را در فایل‌های ارائه مدیریت می‌کنند." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حذف نظرها از ODP با C#" variant="code" %}}

از [Aspose.Slides for .NET](/slides/fa/net/) برای حذف نظرها و نویسندگان نظر از فایل‌های ارائه ODP استفاده کنید. مثال زیر مجموعه `Comments` هر نویسنده و سپس مجموعه `CommentAuthors` ارائه را خالی می‌کند.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف حاشیه‌نویسی‌ها از ODP – C#" >}}
```cs
using var presentation = new Presentation("example.odp");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="چگونه نظرها را از ODP با C# حذف کنیم" intro="برای حذف نظرها و نویسندگان نظر از یک ارائه ODP این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for .NET را نصب کنید. [نصب](https://docs.aspose.com/slides/net/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مجموعه `CommentAuthors` را پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مجموعه `Comments` هر نویسنده نظر را خالی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مجموعه `CommentAuthors` را خالی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه به‌روزشده را با `SaveFormat.Odp` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="ساخته شده با Aspose.Slides" title="حذف آنلاین نظرهای ODP" description="برنامه رایگان Aspose.Slides Annotation با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Annotation" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه نظرها را حذف می‌کند.
- همه نظرها را از فایل ODP خود حذف کنید.
- فایل پاک‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌شده برای حاشیه‌نویسی" subTitle="با C# می‌توانید حاشیه‌نویسی‌ها را از قالب‌های دیگر نیز حذف کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: حذف نظرها از PPTX در Python
url: /fa/python-net/annotation/pptx/ 
description: نظرها و نویسندگان نظر را با Aspose.Slides for Python via .NET از ارائه‌های PPTX در Python حذف کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="حذف نظرها و نویسندگان نظر از PPTX در Python" h2="از Aspose.Slides for Python via .NET برای حذف نظرهای ارائه و نویسندگان مرتبط با آن‌ها استفاده کنید." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حذف نظرها از PPTX با Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/fa/python-net/) دسترسی به نظرها و نویسندگان نظر ذخیره‌شده در یک ارائه PPTX را فراهم می‌کند. فایل را با `Presentation` بارگذاری کنید، مجموعه `comments` هر نویسنده را خالی کنید، `comment_authors` را خالی کنید و نتیجه را در قالب PPTX ذخیره کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف نظرها از PPTX در Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="چگونه نظرها را از PPTX با Python حذف کنیم" intro="برای حذف همه نظرها و نویسندگان نظر از یک ارائه PPTX این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/) را نصب کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPTX را با `Presentation` باز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`comment_authors` را پیمایش کنید و مجموعه `comments` هر نویسنده را خالی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}مجموعه `comment_authors` را خالی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`save` را با `SaveFormat.PPTX` فراخوانی کنید تا ارائه PPTX به‌روزشده نوشته شود.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="ساخته شده با Aspose.Slides" title="حذف آنلاین نظرهای PPTX" description="برنامه رایگان Aspose.Slides Annotation با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Annotation" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه نظرها را حذف می‌کند.
- همه نظرها را از فایل PPTX خود حذف کنید.
- فایل پاک‌شده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌شده برای حاشیه‌نویسی" subTitle="با Python می‌توانید حاشیه‌نویسی‌ها را از قالب‌های دیگر نیز حذف کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

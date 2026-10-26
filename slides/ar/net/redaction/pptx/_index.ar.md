---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تنقيح ملفات عروض PPTX التقديمية باستخدام .NET
url: /ar/net/redaction/pptx/
description: كود مصدري بلغة C# للبحث عن النص واستبداله في عروض PPTX التقديمية.
keywords: تنقيح PPTX، البحث عن النص واستبداله في PPTX، تحديث عرض PPTX التقديمي
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تنقيح ملفات PPTX باستخدام C#" h2="أنشئ تطبيقات .NET تبحث عن النص وتستبدله في العروض التقديمية باستخدام واجهات API من جانب الخادم." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تنقيح عرض PPTX تقديمي باستخدام C#" variant="code" %}}

باستخدام [Aspose.Slides for .NET](/slides/ar/net/)، يمكنك البحث عن النص واستبداله في عرض PPTX تقديمي. استخدم `Presentation.ReplaceText` مع `TextSearchOptions` للتحكم في البحث، ثم احفظ العرض التقديمي المعدَّل.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تنقيح عرض PPTX تقديمي باستخدام C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تنقيح عرض PPTX تقديمي باستخدام C#" intro="اتبع هذه الخطوات لاستبدال النص في عرض PPTX تقديمي." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPTX باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) مع `TextSearchOptions` لاستبدال النص المطلوب.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي المعدَّل باستخدام `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="مبني باستخدام Aspose.Slides" title="تنقيح ملفات PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Redaction المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Redaction" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يبحث Aspose.Slides عن النص ويستبدله قبل أن تكتب الكود.
- ابحث عن النص واستبدله في ملف PPTX، بما في ذلك باستخدام التعبيرات النمطية.
- نزّل الملف المنقَّح.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للتنقيح" subTitle="باستخدام C#، يمكنك أيضًا تنقيح التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

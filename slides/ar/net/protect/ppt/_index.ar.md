---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: حماية ملفات العروض التقديمية PPT باستخدام .NET
url: /ar/net/protect/ppt/
description: كود مصدري بلغة C# لحماية العروض التقديمية PPT بكلمة مرور.
keywords: حماية PPT من الكتابة، تشفير PPT، قفل عرض PPT، حماية PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="قفل ملفات PPT أو حمايتها بكلمة مرور باستخدام C#" h2="أنشئ تطبيقات .NET تشفّر العروض التقديمية وتقيّد تعديلها باستخدام واجهات API من جانب الخادم." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حماية عرض تقديمي PPT باستخدام C#" variant="code" %}}

باستخدام [Aspose.Slides for .NET](/slides/ar/net/)، يمكنك تشفير عرض تقديمي PPT أو تقييد تعديله بكلمة مرور. يتطلب فتح عرض تقديمي مشفّر باستخدام `ProtectionManager.Encrypt` إدخال كلمة المرور. استخدم `ProtectionManager.SetWriteProtection` للسماح بفتح العرض التقديمي مع تقييد التغييرات.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تشفير عرض تقديمي PPT باستخدام C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تعيين الحماية من الكتابة لعرض تقديمي PPT باستخدام C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية حماية عرض تقديمي PPT بكلمة مرور باستخدام C#" intro="اتبع هذه الخطوات لحماية عرض تقديمي PPT بكلمة مرور." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPT باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}شفّر العرض التقديمي باستخدام `ProtectionManager.Encrypt` أو قيّد التغييرات باستخدام `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف المحمي باستخدام `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="مبني باستخدام Aspose.Slides" title="حماية ملفات PPT بكلمة مرور عبر الإنترنت" description="تطبيق Aspose.Slides Lock المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPT الخاصة بك." button="افتح Aspose.Slides Lock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحمي Aspose.Slides العروض التقديمية قبل كتابة الكود.
- عيّن كلمة مرور لفتح ملف PPT أو تحريره.
- نزّل الملف المحمي.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للحماية" subTitle="باستخدام C#، يمكنك أيضًا حماية التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

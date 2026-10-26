---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: حماية ملفات العروض التقديمية ODP باستخدام .NET
url: /ar/net/protect/odp/
description: كود مصدري بلغة C# لحماية العروض التقديمية ODP بكلمة مرور.
keywords: حماية ODP من الكتابة، تشفير ODP، قفل عرض ODP، حماية ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="قفل ملفات ODP أو حمايتها بكلمة مرور باستخدام C#" h2="أنشئ تطبيقات .NET تشفّر العروض التقديمية وتقيّد تعديلها باستخدام واجهات API من جانب الخادم." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حماية عرض تقديمي ODP باستخدام C#" variant="code" %}}

باستخدام [Aspose.Slides for .NET](/slides/ar/net/)، يمكنك تشفير عرض تقديمي ODP أو تقييد تعديله بكلمة مرور. يتطلب فتح عرض تقديمي مشفّر باستخدام `ProtectionManager.Encrypt` إدخال كلمة المرور. استخدم `ProtectionManager.SetWriteProtection` للسماح بفتح العرض التقديمي مع تقييد التغييرات.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تشفير عرض تقديمي ODP باستخدام C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تعيين الحماية من الكتابة لعرض تقديمي ODP باستخدام C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية حماية عرض تقديمي ODP بكلمة مرور باستخدام C#" intro="اتبع هذه الخطوات لحماية عرض تقديمي ODP بكلمة مرور." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف ODP باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}شفّر العرض التقديمي باستخدام `ProtectionManager.Encrypt` أو قيّد التغييرات باستخدام `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف المحمي باستخدام `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="مبني باستخدام Aspose.Slides" title="حماية ملفات ODP بكلمة مرور عبر الإنترنت" description="تطبيق Aspose.Slides Lock المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Lock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحمي Aspose.Slides العروض التقديمية قبل كتابة الكود.
- عيّن كلمة مرور لفتح ملف ODP أو تحريره.
- نزّل الملف المحمي.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للحماية" subTitle="باستخدام C#، يمكنك أيضًا حماية التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

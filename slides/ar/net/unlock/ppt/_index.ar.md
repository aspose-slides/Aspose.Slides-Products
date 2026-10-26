---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: إلغاء قفل ملفات العروض التقديمية PPT باستخدام .NET
url: /ar/net/unlock/ppt/
description: كود مصدري بلغة C# لإزالة الحماية بكلمة مرور من العروض التقديمية PPT.
keywords: إزالة حماية PPT من الكتابة، فك تشفير PPT، إلغاء قفل عرض PPT، إزالة حماية PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إلغاء قفل ملفات PPT باستخدام C#" h2="أنشئ تطبيقات .NET تزيل التشفير والحماية من الكتابة من العروض التقديمية باستخدام واجهات API من جانب الخادم." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إزالة الحماية من عرض تقديمي PPT باستخدام C#" variant="code" %}}

باستخدام [Aspose.Slides for .NET](/slides/ar/net/)، يمكنك إزالة التشفير أو الحماية من الكتابة من عرض تقديمي PPT. لإزالة التشفير، حمّل العرض التقديمي بكلمة المرور الصحيحة واستدعِ `ProtectionManager.RemoveEncryption`. لإزالة الحماية من الكتابة، استدعِ `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="إزالة التشفير من عرض تقديمي PPT باستخدام C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.ppt", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="إزالة الحماية من الكتابة من عرض تقديمي PPT باستخدام C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.ppt");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إزالة الحماية من عرض تقديمي PPT باستخدام C#" intro="اتبع هذه الخطوات لإزالة الحماية من عرض تقديمي PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPT باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}بالنسبة إلى الملف المشفّر، قدّم كلمة المرور عبر `LoadOptions.Password` قبل تحميله.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ `ProtectionManager.RemoveEncryption` أو `ProtectionManager.RemoveWriteProtection` حسب نوع الحماية المطبّقة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي غير المقفل باستخدام `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="مبني باستخدام Aspose.Slides" title="إلغاء قفل ملفات PPT عبر الإنترنت" description="تطبيق Aspose.Slides Unlock المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPT الخاصة بك." button="افتح Aspose.Slides Unlock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يزيل Aspose.Slides الحماية قبل كتابة الكود.
- أزل كلمة المرور أو الحماية من الكتابة من ملف PPT.
- نزّل الملف غير المقفل.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة لإلغاء القفل" subTitle="باستخدام C#، يمكنك أيضًا إزالة الحماية من التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

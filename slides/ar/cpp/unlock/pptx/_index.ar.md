---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: إلغاء قفل العروض التقديمية PPTX باستخدام C++
url: /ar/cpp/unlock/pptx/
description: ألغِ قفل العروض التقديمية PPTX في C++. استخدم Aspose.Slides for C++ لإزالة التشفير والحماية من الكتابة من ملفات العروض التقديمية.
keywords: إزالة حماية PPTX من الكتابة، فك تشفير PPTX، إلغاء قفل عرض PPTX، إزالة حماية PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إلغاء قفل PPTX باستخدام C++" h2="استخدم Aspose.Slides for C++ لإزالة التشفير والحماية من الكتابة من ملفات العروض التقديمية دون Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إزالة الحماية من عرض تقديمي PPTX عبر C++" variant="code" %}}

يتيح لك Aspose.Slides for C++ إزالة التشفير أو الحماية من الكتابة من العروض التقديمية PPTX. استخدم `LoadOptions` لفتح ملف مشفّر، ثم استخدم الكائن `ProtectionManager` من الفئة `Presentation` لاستدعاء `RemoveEncryption` أو `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="إزالة الحماية بكلمة مرور من PPTX باستخدام C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="إزالة الحماية من الكتابة من عرض تقديمي PPTX باستخدام C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إزالة كلمة المرور من PPTX عبر C++" intro="اتبع هذه الخطوات لإزالة الحماية من عرض تقديمي PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPTX باستخدام الفئة `Presentation` و`LoadOptions` عند الحاجة إلى كلمة مرور.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم الكائن `ProtectionManager` لإزالة الحماية.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ `RemoveEncryption` للملفات المشفّرة أو `RemoveWriteProtection` للملفات المحمية من الكتابة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف غير المقفل باستخدام `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="مبني باستخدام Aspose.Slides" title="إلغاء قفل ملفات PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Unlock المجاني مبني باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/ar/cpp/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Unlock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يزيل Aspose.Slides الحماية قبل كتابة الكود.
- أزل كلمة المرور أو الحماية من الكتابة من ملف PPTX.
- نزّل الملف غير المقفل.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة لإلغاء القفل" subTitle="باستخدام C++، يمكنك أيضًا إزالة الحماية من التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

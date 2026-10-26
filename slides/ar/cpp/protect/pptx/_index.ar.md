---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: حماية العروض التقديمية PPTX باستخدام C++
url: /ar/cpp/protect/pptx/
description: احمِ العروض التقديمية PPTX في C++. استخدم Aspose.Slides for C++ لتشفير الملفات وتعيين الحماية من الكتابة.
keywords: حماية PPTX من الكتابة، تشفير PPTX، قفل عرض PPTX، حماية PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="قفل PPTX أو حمايته بكلمة مرور باستخدام C++" h2="استخدم Aspose.Slides for C++ لتشفير العروض التقديمية وتعيين الحماية من الكتابة دون Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حماية عرض تقديمي PPTX عبر C++" variant="code" %}}

يتيح لك Aspose.Slides for C++ حماية العروض التقديمية PPTX من الفتح أو التعديل. استخدم الكائن `ProtectionManager` من الفئة `Presentation` لتشفير ملف باستخدام `Encrypt` أو تقييد التحرير باستخدام `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تشفير عرض تقديمي PPTX باستخدام C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تعيين الحماية من الكتابة لعرض تقديمي PPTX باستخدام C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية حماية PPTX بكلمة مرور عبر C++" intro="اتبع هذه الخطوات لحماية عرض تقديمي PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPTX باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احمِ العرض التقديمي باستخدام الكائن `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم `Encrypt` للحماية بكلمة مرور أو `SetWriteProtection` للحماية من الكتابة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف المحمي باستخدام `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="مبني باستخدام Aspose.Slides" title="حماية ملفات PPTX بكلمة مرور عبر الإنترنت" description="تطبيق Aspose.Slides Lock المجاني مبني باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/ar/cpp/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Lock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحمي Aspose.Slides العروض التقديمية قبل كتابة الكود.
- عيّن كلمة مرور لفتح ملف PPTX أو تحريره.
- نزّل الملف المحمي.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للحماية" subTitle="باستخدام C++، يمكنك أيضًا حماية التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

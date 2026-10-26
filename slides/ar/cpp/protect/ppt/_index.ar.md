---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: حماية العروض التقديمية PPT باستخدام C++
url: /ar/cpp/protect/ppt/
description: احمِ العروض التقديمية PPT في C++. استخدم Aspose.Slides for C++ لتشفير الملفات وتعيين الحماية من الكتابة.
keywords: حماية PPT من الكتابة، تشفير PPT، قفل عرض PPT، حماية PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="قفل PPT أو حمايته بكلمة مرور باستخدام C++" h2="استخدم Aspose.Slides for C++ لتشفير العروض التقديمية وتعيين الحماية من الكتابة دون Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حماية عرض تقديمي PPT عبر C++" variant="code" %}}

يتيح لك Aspose.Slides for C++ حماية العروض التقديمية PPT من الفتح أو التعديل. استخدم الكائن `ProtectionManager` من الفئة `Presentation` لتشفير ملف باستخدام `Encrypt` أو تقييد التحرير باستخدام `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تشفير عرض تقديمي PPT باستخدام C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تعيين الحماية من الكتابة لعرض تقديمي PPT باستخدام C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية حماية PPT بكلمة مرور عبر C++" intro="اتبع هذه الخطوات لحماية عرض تقديمي PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPT باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احمِ العرض التقديمي باستخدام الكائن `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم `Encrypt` للحماية بكلمة مرور أو `SetWriteProtection` للحماية من الكتابة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف المحمي باستخدام `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="مبني باستخدام Aspose.Slides" title="حماية ملفات PPT بكلمة مرور عبر الإنترنت" description="تطبيق Aspose.Slides Lock المجاني مبني باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/ar/cpp/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPT الخاصة بك." button="افتح Aspose.Slides Lock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحمي Aspose.Slides العروض التقديمية قبل كتابة الكود.
- عيّن كلمة مرور لفتح ملف PPT أو تحريره.
- نزّل الملف المحمي.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للحماية" subTitle="باستخدام C++، يمكنك أيضًا حماية التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

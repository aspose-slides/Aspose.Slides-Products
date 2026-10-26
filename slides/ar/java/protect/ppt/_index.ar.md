---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: حماية ملفات العروض التقديمية PPT باستخدام Java
url: /ar/java/protect/ppt/
description: احمِ العروض التقديمية PPT في Java. استخدم Aspose.Slides for Java لتشفير ملفات العروض التقديمية وتعيين الحماية من الكتابة.
keywords: حماية PPT من الكتابة، تشفير ملف PPT، قفل عرض PPT، حماية PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="قفل PPT أو حمايته بكلمة مرور باستخدام Java" h2="أنشئ تطبيقات Java تحمي ملفات العروض التقديمية باستخدام واجهات API من جانب الخادم." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حماية عرض تقديمي PPT عبر Java" variant="code" %}}

باستخدام [Aspose.Slides for Java](/slides/ar/java/)، يمكنك حماية عرض تقديمي PPT من الفتح أو التعديل بتعيين كلمة مرور. استخدم الكائن `ProtectionManager` من الفئة `Presentation` لاستدعاء أساليب مثل `encrypt` و`setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تشفير عرض تقديمي PPT باستخدام Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تعيين الحماية من الكتابة لعرض تقديمي PPT باستخدام Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية حماية PPT بكلمة مرور عبر Java" intro="اتبع هذه الخطوات لحماية عرض تقديمي PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPT باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `encrypt` أو الأسلوب `setWriteProtection` من الكائن `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ الملف المحمي باستخدام `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="مبني باستخدام Aspose.Slides" title="حماية ملفات PPT بكلمة مرور عبر الإنترنت" description="تطبيق Aspose.Slides Lock المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPT الخاصة بك." button="افتح Aspose.Slides Lock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحمي Aspose.Slides العروض التقديمية قبل كتابة الكود.
- عيّن كلمة مرور لفتح ملف PPT أو تحريره.
- نزّل الملف المحمي.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للحماية" subTitle="باستخدام Java، يمكنك أيضًا حماية التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

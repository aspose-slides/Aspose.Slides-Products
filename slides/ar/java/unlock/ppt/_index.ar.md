---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: إلغاء قفل ملفات العروض التقديمية PPT باستخدام Java
url: /ar/java/unlock/ppt/
description: أزل كلمات المرور والحماية من الكتابة من العروض التقديمية PPT في Java باستخدام Aspose.Slides for Java.
keywords: إزالة حماية PPT من الكتابة، فك تشفير PPT، إلغاء قفل عرض PPT، إزالة حماية PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إلغاء قفل PPT باستخدام Java" h2="أنشئ تطبيقات Java تزيل كلمات المرور والحماية من الكتابة من ملفات العروض التقديمية باستخدام واجهات API من جانب الخادم." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إزالة الحماية من عرض تقديمي PPT عبر Java" variant="code" %}}

باستخدام [Aspose.Slides for Java](/slides/ar/java/)، يمكنك إزالة التشفير أو الحماية من الكتابة من عرض تقديمي PPT. استخدم `LoadOptions.setPassword` لفتح عرض تقديمي مشفّر، وأسلوبَي `removeEncryption` و`removeWriteProtection` في `ProtectionManager` لإزالة إعدادات الحماية.

{{< blocks/products/pf/slides-design-update-10-2026/code title="إزالة الحماية بكلمة مرور من PPT باستخدام Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="إزالة الحماية من الكتابة من عرض تقديمي PPT باستخدام Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إزالة كلمة المرور من PPT عبر Java" intro="اتبع هذه الخطوات لإزالة الحماية من عرض تقديمي PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف PPT باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم `LoadOptions.setPassword` عندما يكون العرض التقديمي مشفّرًا.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ `removeEncryption` أو `removeWriteProtection` من الكائن `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي غير المقفل باستخدام `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="مبني باستخدام Aspose.Slides" title="إلغاء قفل ملفات PPT عبر الإنترنت" description="تطبيق Aspose.Slides Unlock المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPT الخاصة بك." button="افتح Aspose.Slides Unlock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يزيل Aspose.Slides الحماية قبل كتابة الكود.
- أزل كلمة المرور أو الحماية من الكتابة من ملف PPT.
- نزّل الملف غير المقفل.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة لإلغاء القفل" subTitle="باستخدام Java، يمكنك أيضًا إزالة الحماية من التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

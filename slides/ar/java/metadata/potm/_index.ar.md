---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: عرض بيانات تعريف ملفات POTM أو تحريرها باستخدام Java
url: /ar/java/metadata/potm/
description: اعرض بيانات تعريف POTM وحرّرها في Java. استخدم Aspose.Slides for Java لتحديث الخصائص المضمنة والمخصصة للعروض التقديمية.
keywords: تحرير بيانات تعريف POTM، عرض بيانات تعريف POTM، تحرير خصائص POTM، عرض خصائص POTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحرير خصائص POTM باستخدام Java" h2="أنشئ تطبيقات Java تعدّل الخصائص المضمنة والمخصصة في ملفات العروض التقديمية باستخدام واجهات برمجية على الخادم." related="FODP,ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تعديل خصائص POTM عبر Java" variant="code" %}}

باستخدام [Aspose.Slides for Java](/slides/ar/java/) يمكن للمطورين الوصول إلى الخصائص المضمنة والمخصصة للعروض التقديمية وتعديلها. استخدم الأسلوب `getDocumentProperties` لكائن `Presentation` للوصول إلى كائن `IDocumentProperties` لملف العرض التقديمي.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تعديل الخصائص المضمنة في POTM – Java" >}}
```java
Presentation presentation = new Presentation("Presentation.potm");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.potm", SaveFormat.Potm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="إضافة خصائص مخصصة إلى POTM – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.potm", SaveFormat.Potm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية عرض بيانات تعريف POTM أو تحريرها في Java" intro="اتبع هذه الخطوات لعرض بيانات تعريف POTM أو تحريرها." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف `POTM` باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `getDocumentProperties` للحصول على كائن `IDocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اقرأ الخصائص المضمنة أو حدّثها، مثل `Author` و`Title` و`Subject` و`Comments`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}صِل إلى الخصائص المخصصة وعدّلها باستخدام `set_Item` و`getCustomPropertyName` و`removeCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="مبني باستخدام Aspose.Slides" title="عرض بيانات تعريف POTM وتحريرها عبر الإنترنت" description="تطبيق Aspose.Slides Metadata المجاني مبني باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات POTM الخاصة بك." button="افتح Aspose.Slides Metadata" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يقرأ Aspose.Slides الخصائص ويكتبها قبل كتابة الكود.
- اعرض الخصائص المضمنة والمخصصة لملف POTM وحرّرها.
- احفظ الملف المحدّث ونزّله.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات بيانات تعريف أخرى مدعومة" subTitle="باستخدام Java يمكنك أيضًا إدارة بيانات تعريف التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

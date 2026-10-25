---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: عرض بيانات تعريف OTP أو تحريرها باستخدام C++
url: /ar/cpp/metadata/otp/
description: اعرض بيانات تعريف OTP وحرّرها في C++. استخدم Aspose.Slides for C++ لتحديث الخصائص المضمنة والمخصصة للعروض التقديمية.
keywords: تحرير بيانات تعريف OTP، عرض بيانات تعريف OTP، تحرير خصائص OTP، عرض خصائص OTP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحرير بيانات تعريف OTP باستخدام C++" h2="استخدم Aspose.Slides for C++ لعرض الخصائص المضمنة والمخصصة في ملفات العروض التقديمية وتحديثها." related="FODP,ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تعديل خصائص OTP عبر C++" variant="code" %}}

يتيح لك Aspose.Slides for C++ قراءة بيانات تعريف ملفات OTP وتحديثها دون Microsoft PowerPoint. استخدم الكائن [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) الذي يوفره `Presentation::get_DocumentProperties` لتغيير الخصائص المضمنة مثل `Author` و`Title`، أو لإدارة الخصائص المخصصة باستخدام `idx_set` و`GetCustomPropertyName` و`RemoveCustomProperty`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تعديل الخصائص المضمنة في OTP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.otp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.otp", SaveFormat::Otp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="إضافة خصائص مخصصة إلى OTP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.otp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.otp", SaveFormat::Otp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية عرض بيانات تعريف OTP أو تحريرها في C++" intro="اتبع هذه الخطوات لعرض بيانات تعريف OTP أو تحريرها." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حمّل ملف OTP باستخدام الفئة `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على كائن `DocumentProperties` باستخدام `get_DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اقرأ الخصائص المضمنة أو حدّثها، مثل `Author` و`Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف الخصائص المخصصة أو اقرأها أو أزلها باستخدام `idx_set` و`GetCustomPropertyName` و`RemoveCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="مبني باستخدام Aspose.Slides" title="عرض بيانات تعريف OTP وتحريرها عبر الإنترنت" description="تطبيق Aspose.Slides Metadata المجاني مبني باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/ar/cpp/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات OTP الخاصة بك." button="افتح Aspose.Slides Metadata" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يقرأ Aspose.Slides الخصائص ويكتبها قبل كتابة الكود.
- اعرض الخصائص المضمنة والمخصصة لملف OTP وحرّرها.
- احفظ الملف المحدّث ونزّله.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات بيانات تعريف أخرى مدعومة" subTitle="باستخدام C++ يمكنك أيضًا إدارة بيانات تعريف التنسيقات التالية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

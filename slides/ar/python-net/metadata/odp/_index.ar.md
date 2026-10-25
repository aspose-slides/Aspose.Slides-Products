---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: عرض بيانات تعريف ODP أو تحريرها باستخدام Python
url: /ar/python-net/metadata/odp/
description: اعرض خصائص بيانات التعريف المضمنة والمخصصة في ملفات ODP وحرّرها باستخدام Python.
keywords: تحرير بيانات تعريف ODP، عرض بيانات تعريف ODP، تحرير خصائص ODP، عرض خصائص ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="عرض بيانات تعريف ODP وتحريرها باستخدام Python" h2="أنشئ تطبيقات Python تقرأ الخصائص المضمنة والمخصصة للعروض التقديمية وتعدّلها باستخدام Aspose.Slides." related="FODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="عرض بيانات تعريف ODP وتعديلها باستخدام Python" variant="code" %}}

يتيح لك [**Aspose.Slides for Python via .NET**](/slides/ar/python-net/) قراءة بيانات التعريف المضمنة وتحديثها، وإضافة خصائص المستند المخصصة أو تحديثها أو إزالتها في عروض ODP التقديمية. صِل إلى كائن [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) عبر `Presentation.document_properties`، وعدّله، ثم احفظ العرض التقديمي بتنسيق ODP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تحديث الخصائص المضمنة في ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="إضافة الخصائص المخصصة في ODP وإزالتها – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحرير بيانات تعريف ODP باستخدام Python" intro="اتبع هذه الخطوات لتحرير بيانات تعريف ملف ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملف ODP باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}صِل إلى كائن `IDocumentProperties` عبر `Presentation.document_properties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}حدّث الخصائص المضمنة أو استخدم `set_custom_property_value` و`remove_custom_property` للخصائص المخصصة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي باستخدام `Presentation.save` و`SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="مبني باستخدام Aspose.Slides" title="عرض بيانات تعريف ODP وتحريرها عبر الإنترنت" description="تطبيق Aspose.Slides Metadata المجاني مبني باستخدام [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ar/python-net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Metadata" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يقرأ Aspose.Slides الخصائص ويكتبها قبل كتابة الكود.
- اعرض الخصائص المضمنة والمخصصة لملف ODP وحرّرها.
- احفظ الملف المحدّث ونزّله.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات بيانات تعريف أخرى مدعومة" subTitle="باستخدام Python يمكنك أيضًا إدارة بيانات تعريف تنسيقات العروض التقديمية الأخرى المدعومة." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

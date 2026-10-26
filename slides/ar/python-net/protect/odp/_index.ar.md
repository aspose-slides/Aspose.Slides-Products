---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: حماية ملفات العروض التقديمية ODP باستخدام Python
url: /ar/python-net/protect/odp/
description: شفّر العروض التقديمية ODP أو عيّن الحماية من الكتابة باستخدام Python.
keywords: حماية ODP من الكتابة، تشفير ODP باستخدام Python، قفل عرض ODP، حماية ODP باستخدام Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="حماية العروض التقديمية ODP باستخدام Python" h2="أنشئ تطبيقات Python تشفّر العروض التقديمية أو تعيّن الحماية من الكتابة باستخدام Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حماية عرض تقديمي ODP باستخدام Python" variant="code" %}}

يوفر [**Aspose.Slides for Python via .NET**](/slides/ar/python-net/) آليتين مختلفتين للحماية. استدعِ `ProtectionManager.encrypt` لتشفير عرض تقديمي ODP واشتراط كلمة مرور لفتحه. أو استدعِ `ProtectionManager.set_write_protection` للحد من التعديل دون تشفير الملف. يظل بإمكان المستخدم فتح عرض تقديمي محمي من الكتابة وحفظ التغييرات في ملف آخر.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تشفير عرض تقديمي ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تعيين الحماية من الكتابة لعرض تقديمي ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية حماية ODP باستخدام Python" intro="اتبع هذه الخطوات لحماية ملف ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملف ODP باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم `ProtectionManager.encrypt` لاشتراط كلمة مرور عند الفتح، أو `ProtectionManager.set_write_protection` للحد من التغييرات.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي المحمي بتنسيق ODP باستخدام `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="مبني باستخدام Aspose.Slides" title="حماية ملفات ODP بكلمة مرور عبر الإنترنت" description="تطبيق Aspose.Slides Lock المجاني مبني باستخدام [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ar/python-net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات ODP الخاصة بك." button="افتح Aspose.Slides Lock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحمي Aspose.Slides العروض التقديمية قبل كتابة الكود.
- عيّن كلمة مرور لفتح ملف ODP أو تحريره.
- نزّل الملف المحمي.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للحماية" subTitle="استخدم Python لحماية تنسيقات العروض التقديمية الأخرى المدعومة." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

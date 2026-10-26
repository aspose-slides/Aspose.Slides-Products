---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: حماية ملفات العروض التقديمية PPT باستخدام Python
url: /ar/python-net/protect/ppt/
description: شفّر العروض التقديمية PPT أو عيّن الحماية من الكتابة باستخدام Python.
keywords: حماية PPT من الكتابة، تشفير PPT باستخدام Python، قفل عرض PPT، حماية PPT باستخدام Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="حماية العروض التقديمية PPT باستخدام Python" h2="أنشئ تطبيقات Python تشفّر العروض التقديمية أو تعيّن الحماية من الكتابة باستخدام Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حماية عرض تقديمي PPT باستخدام Python" variant="code" %}}

يوفر [**Aspose.Slides for Python via .NET**](/slides/ar/python-net/) آليتين مختلفتين للحماية. استدعِ `ProtectionManager.encrypt` لتشفير عرض تقديمي PPT واشتراط كلمة مرور لفتحه. أو استدعِ `ProtectionManager.set_write_protection` للحد من التعديل دون تشفير الملف. يظل بإمكان المستخدم فتح عرض تقديمي محمي من الكتابة وحفظ التغييرات في ملف آخر.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تشفير عرض تقديمي PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="تعيين الحماية من الكتابة لعرض تقديمي PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية حماية PPT باستخدام Python" intro="اتبع هذه الخطوات لحماية ملف PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}افتح ملف PPT باستخدام `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم `ProtectionManager.encrypt` لاشتراط كلمة مرور عند الفتح، أو `ProtectionManager.set_write_protection` للحد من التغييرات.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي المحمي بتنسيق PPT باستخدام `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="مبني باستخدام Aspose.Slides" title="حماية ملفات PPT بكلمة مرور عبر الإنترنت" description="تطبيق Aspose.Slides Lock المجاني مبني باستخدام [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ar/python-net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPT الخاصة بك." button="افتح Aspose.Slides Lock" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف يحمي Aspose.Slides العروض التقديمية قبل كتابة الكود.
- عيّن كلمة مرور لفتح ملف PPT أو تحريره.
- نزّل الملف المحمي.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للحماية" subTitle="استخدم Python لحماية تنسيقات العروض التقديمية الأخرى المدعومة." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

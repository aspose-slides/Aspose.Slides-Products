---
title: تحويل Microsoft PowerPoint Presentation إلى تنسيقات مختلفة باستخدام C ++
url: /ar/cpp/conversion/
description: قم بتحويل شرائح Microsoft PowerPoint إلى ملفات متعددة بما في ذلك تنسيقات HTML و PDF والصور داخل التطبيقات المستندة إلى C ++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> ® </sup> تحويل عرض PowerPoint التقديمي عبر C ++" h2="أمثلة على أكواد C ++ لسيناريوهات التحويل المختلفة لتحويل الشرائح إلى صور و HTML و PDF وتنسيقات أخرى." >}}

{{% blocks/products/pf/feature-page-summary %}}

عملية تحويل تنسيقات Microsoft <sup> ® </sup> PowerPoint بسيطة وسهلة لأتمتة العمليات باستخدام مكتبة C ++ PowerPoint. يمكن للمطورين تحسين التعليمات البرمجية المصدر ذات الصلة ودمجها في تطبيقاتهم. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="التحويل الداخلي لتنسيقات Microsoft PowerPoint" %}}
Interconversion of Microsoft <sup> ® </sup> مستندات PowerPoint بما في ذلك PPT و PPTX برمجيًا هو مجرد رمز مكون من سطرين. قم بتحميل الملف باستخدام [فئة العرض التقديمي](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) واستدعاء [طريقة الحفظ](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وجود ملف الإخراج و SaveFormat.OutputFormats كمعلمات.

{{% blocks/products/pf/feature-page-code h3="كود التحويل C ++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="تحويل ملفات PowerPoint إلى PDF" %}}

يعد تحويل Microsoft <sup> ® </sup> PowerPoint إلى PDF سيناريو شائع بسبب المشاركة الضخمة لمستندات PDF. يمكن للمبرمجين أتمتة ذلك وتعيين إعدادات تحويل PDF ذات الصلة باستخدام [PdfOptions class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). قليل من الإعدادات المحددة مثل مستوى ضغط النص وجودة JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861) ومستوى توافق PDF [الامتثال](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f) ، وتحويل الشرائح المخفية [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose. .

{{% blocks/products/pf/feature-page-code h3="C ++ رمز تحويل PowerPoint إلى PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="حفظ شرائح Microsoft PowerPoint كصور" %}}
عندما تكون هناك حالة لعرض محتوى العرض التقديمي على الويب ، فهناك حاجة لتقديم الملفات بتنسيق HTML أو الصور بتنسيق JPG و TIFF و PNG وما إلى ذلك. عملية تحويل الشرائح كصور بسيطة. احصل على جميع الشرائح باستخدام [get_Slides ()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) وتكرار خلال كل شريحة واحدة تلو الأخرى. أثناء كل تكرار ، استخدم [ISlide-> GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) لصورة الشريحة ثم احفظها في تنسيق الصورة المطلوب. 

{{% blocks/products/pf/feature-page-code h3="C ++ PowerPoint لتحويل الصور" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}
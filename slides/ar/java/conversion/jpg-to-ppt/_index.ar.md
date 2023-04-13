---
title: تحويل JPG إلى PPT في Java
url: /ar/java/conversion/jpg-to-ppt/
keywords: تحويل JPG إلى PPT ، JPG إلى PPT ، PowerPoint ، JPG ، PPT ، Java API ، مكتبة Java
description: تحويل JPG إلى PPT في Java. استخدم Java Library API لتحويل صور JPG إلى PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تحويل JPG إلى PPT في Java" h2="واجهة برمجة تطبيقات Java قوية ومتعددة المنصات لتحويل JPG إلى PPT باستخدام كود Java" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل JPG إلى PPT باستخدام Aspose.Slides" %}}

[** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) هي مكتبة جافا قوية تُستخدم لإنشاء وتحويل ومعالجة عروض PowerPoint التقديمية وملفات PDF ومستندات HTML وغيرها الملفات. عندما تقوم بتحويل JPG إلى PPT ، فأنت تقوم بشكل أساسي بإنشاء عرض PowerPoint تقديمي يحتوي على شرائح بناءً على صور JPG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="تحويل JPG إلى PPT في Java" %}}
باستخدام [** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) ، يمكنك تحويل صورة JPG إلى عرض PowerPoint تقديمي ببضعة سطور من التعليمات البرمجية:

{{% blocks/products/pf/agp/code-block title="كود جافا لتحويل JPG إلى PPT" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="كيفية تحويل JPG إلى PPT في Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
قم بتثبيت ** Aspose.Slides for Java **. راجع [** التثبيت **](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف المكتبة كمرجع في مشروعك.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بإنشاء مثيل لفئة العرض التقديمي.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتحميل صورة JPG التي تريد تحويلها إلى PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ الملف الناتج كعرض تقديمي PPT.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="محول مجاني على الإنترنت" sectionDescription="[كيفية تحويل PPT إلى HTML في Python](https://products.aspose.com/slides/ar/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تحويلات PowerPoint المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل الملفات بتنسيقات أخرى إلى PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
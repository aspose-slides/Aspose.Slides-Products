---
title: حاشیه نویسی PPT را با استفاده از جاوا حذف کنید
weight: 3630
url: /fa/java/annotation/ppt/ 
description: کد نمونه جاوا برای حذف حاشیه نویسی با فرمت PPT در Java Runtime Environment برای برنامه های JSP/JSF و برنامه های دسکتاپ.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="نظرات و نویسندگان نظرات را از PPT در جاوا حذف کنید" h2="برای دستکاری نظرات و نویسندگان در فایل های سند با استفاده از API های سمت سرور، برنامه های جاوا خود را بسازید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="حذف نظرات از PPT از طریق جاوا" %}}
برای حذف حاشیه‌نویسی‌ها از فایل PPT، از API [Aspose.Slides for Java](https://products.aspose.com/slides/fa/java/) استفاده می‌کنیم که یک ویژگی غنی، قدرتمند و آسان برای استفاده است. API دستکاری اسناد برای پلتفرم جاوا.
{{% blocks/products/pf/agp/code-block title="حاشیه نویسی ها را از PPT - Java حذف کنید" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.ppt");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="نحوه حذف نظرات از PPT از طریق جاوا" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای جاوا** نصب کنید. [**نصب**](https://docs.aspose.com/slides/java/installation/) را ببینید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT را با یک نمونه از کلاس Presentation بارگیری کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تکرار روی همه نویسندگان PPT بارگذاری شده
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تمام نظرات یک نویسنده را حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
در پایان تمام نویسندگان را حذف کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های حاشیه نویسی پشتیبانی شده" subTitle="با استفاده از جاوا، می توان به راحتی فرمت های دیگر از جمله حاشیه نویسی کرد." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
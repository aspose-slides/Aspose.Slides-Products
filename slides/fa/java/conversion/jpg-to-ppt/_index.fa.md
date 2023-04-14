---
title: تبدیل JPG به PPT در جاوا
url: /fa/java/conversion/jpg-to-ppt/
keywords: تبدیل JPG به PPT، JPG به PPT، پاورپوینت، JPG، PPT، Java API، کتابخانه جاوا
description: تبدیل JPG به PPT در جاوا. از Java library API برای تبدیل تصاویر JPG به پاورپوینت استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل JPG به PPT در جاوا" h2="بین پلتفرم قدرتمند Java API برای تبدیل JPG به PPT با استفاده از کد جاوا" >}}

{{% blocks/products/pf/feature-page-section h2="با استفاده از Aspose.Slides JPG را به PPT تبدیل کنید" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) یک کتابخانه قدرتمند جاوا است که برای ایجاد، تبدیل و دستکاری ارائه‌های پاورپوینت، فایل‌های PDF، اسناد HTML و موارد دیگر استفاده می‌شود. فایل ها. وقتی JPG را به PPT تبدیل می کنید، اساساً در حال ایجاد یک ارائه پاورپوینت هستید که حاوی اسلایدهایی بر اساس تصاویر JPG است.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="تبدیل JPG به PPT در جاوا" %}}
با استفاده از [**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/)، می توانید تصویر JPG را تنها با چند خط کد به ارائه پاورپوینت تبدیل کنید:

{{% blocks/products/pf/agp/code-block title="کد جاوا برای تبدیل JPG به PPT" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل JPG به PPT در جاوا" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای جاوا** نصب کنید. [**نصب**](https://docs.aspose.com/slides/java/installation/) را ببینید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک نمونه از کلاس Presentation ایجاد کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تصویر JPG را که می خواهید به PPT تبدیل کنید بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل حاصل را به عنوان ارائه PPT ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پاورپوینت پشتیبانی شده" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر به پاورپوینت تبدیل کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل PNG به PPTX در جاوا
url: /fa/java/conversion/png-to-pptx/
keywords: تبدیل PNG به PPTX، PNG به PPTX، پاورپوینت، PNG، PPTX، Java API، کتابخانه جاوا
description: تبدیل PNG به PPTX در جاوا. از Java library API برای تبدیل تصاویر PNG به پاورپوینت استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل PNG به PPTX در جاوا" h2="بین پلتفرم قدرتمند Java API برای تبدیل PNG به PPTX با استفاده از کد جاوا" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تبدیل PNG به PPTX در جاوا" variant="code" %}}

با استفاده از [**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/)، می توانید تنها با چند خط کد، تصویر PNG را به ارائه پاورپوینت تبدیل کنید:

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد جاوا برای تبدیل PNG به PPTX" >}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.pptx", SaveFormat.Pptx);
} finally {
	if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از Aspose.Slides PNG را به PPTX تبدیل کنید" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) یک کتابخانه قدرتمند جاوا است که برای ایجاد، تبدیل و دستکاری ارائه‌های پاورپوینت، فایل‌های PDF، اسناد HTML و موارد دیگر استفاده می‌شود. فایل ها. وقتی PNG را به PPTX تبدیل می کنید، اساساً در حال ایجاد یک ارائه پاورپوینت هستید که حاوی اسلایدهایی بر اساس تصاویر PNG است.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل PNG به PPTX در جاوا" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides را برای جاوا** نصب کنید. [**نصب**](https://docs.aspose.com/slides/java/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک نمونه از کلاس Presentation ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تصویر PNG را که می خواهید به PPTX تبدیل کنید بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل حاصل را به عنوان یک ارائه PPTX ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="مبدل آنلاین رایگان"
  description="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پاورپوینت پشتیبانی شده" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر به پاورپوینت تبدیل کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

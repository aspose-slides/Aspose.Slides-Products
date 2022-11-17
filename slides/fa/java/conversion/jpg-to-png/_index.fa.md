---
title: در جاوا JPG را به PNG تبدیل کنید
url: /fa/java/conversion/jpg-to-png/
keywords: JPG به PNG، تبدیل JPG به PNG، Java API، Java Library، JPG، PNG
description: تبدیل JPG به PNG در جاوا. برای تبدیل فایل‌های JPG به PNG از API کتابخانه جاوا استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="در جاوا JPG را به PNG تبدیل کنید" h2="کتابخانه جاوا پرسرعت و چند پلتفرمی که به توسعه برنامه‌هایی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="در جاوا JPG را به PNG تبدیل کنید" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) یک کتابخانه قدرتمند جاوا برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل JPG به PNG ارائه می‌کند. با استفاده از **Aspose.Slides برای جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های JPG را تنها با چند خط کد جاوا به PNG تبدیل کند.

Aspose.Slides برای جاوا به عنوان یک API مدرن برای پردازش اسناد، فایل‌های JPG را به فرمت‌های فایل PNG صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد JPG را به PNG و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از جاوا، JPG را به PNG تبدیل کنید" %}}
برای تبدیل JPG به PNG، باید Presentation را از فایل JPG ایجاد کنید و آن را به عنوان PNG ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد جاوا برای تبدیل JPG به PNG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل JPG به PNG با استفاده از Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل JPG به PNG در جاوا است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه جاوا خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع JPG را در جاوا باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PNG ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل JPG به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید JPG را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
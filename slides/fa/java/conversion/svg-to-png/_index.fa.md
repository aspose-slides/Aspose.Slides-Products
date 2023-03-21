---
title: در جاوا SVG را به PNG تبدیل کنید
url: /fa/java/conversion/svg-to-png/
keywords: SVG به PNG، تبدیل SVG به PNG، Java API، Java Library، SVG، PNG
description: تبدیل SVG به PNG در جاوا. برای تبدیل فایل‌های SVG به PNG از API کتابخانه جاوا استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="در جاوا SVG را به PNG تبدیل کنید" h2="کتابخانه جاوا پرسرعت و چند پلتفرمی که به توسعه برنامه‌هایی با قابلیت ایجاد، ادغام، بازرسی یا تبدیل فایل‌های ارائه Microsoft PowerPoint و OpenOffice بدون استفاده از هیچ نرم‌افزاری مانند Microsoft یا Open Office، Adobe PDF کمک می‌کند." >}}

{{% blocks/products/pf/feature-page-section h2="در جاوا SVG را به PNG تبدیل کنید" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) یک کتابخانه قدرتمند جاوا برای ایجاد و دستکاری فایل های ارائه است. علاوه بر این، راه‌های انعطاف‌پذیری برای تبدیل SVG به PNG ارائه می‌کند. با استفاده از **Aspose.Slides برای جاوا**، هر برنامه‌نویس یا برنامه‌ای می‌تواند فایل‌های SVG را تنها با چند خط کد جاوا به PNG تبدیل کند.

Aspose.Slides برای جاوا به عنوان یک API مدرن برای پردازش اسناد، فایل‌های SVG را به فرمت‌های فایل PNG صادر می‌کند. کتابخانه پاورپوینت Aspose به شما امکان می دهد SVG را به PNG و بسیاری از فرمت های فایل دیگر تبدیل کنید.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="با استفاده از جاوا، SVG را به PNG تبدیل کنید" %}}
برای تبدیل SVG به PNG، باید Presentation را از فایل SVG ایجاد کنید و آن را به عنوان PNG ذخیره کنید.

{{% blocks/products/pf/agp/code-block title="کد جاوا برای تبدیل SVG به PNG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    String svgContent = new String(Files.readAllBytes(Paths.get("image.svg")));
    ISvgImage svgImage = new SvgImage(svgContent);
    IPPImage ppImage = pres.getImages().addImage(svgImage);
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 
			ppImage.getWidth(), ppImage.getHeight(), ppImage);
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

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل SVG به PNG با استفاده از Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای تبدیل SVG به PNG در جاوا است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) را نصب کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
یک مرجع کتابخانه (وارد کردن کتابخانه) به پروژه جاوا خود اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل های منبع SVG را در جاوا باز کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را به عنوان فایل PNG ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="تبدیل SVG به فرمت های دیگر پشتیبانی شده" subTitle="همچنین می‌توانید SVG را تبدیل کنید و در قالب‌های دیگر ذخیره کنید. تمام فرمت های پشتیبانی شده را در زیر مشاهده کنید" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
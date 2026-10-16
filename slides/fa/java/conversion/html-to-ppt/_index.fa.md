---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تبدیل HTML به PPT در جاوا
url: /fa/java/conversion/html-to-ppt/
keywords: تبدیل HTML به PPT، HTML به PPT، پاورپوینت، HTML، PPT، Java API، کتابخانه جاوا
description: تبدیل HTML به PPT در جاوا. از API کتابخانه جاوا برای تبدیل HTML به پاورپوینت استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تبدیل HTML به PPT در جاوا" h2="بین پلتفرم قدرتمند Java API برای تبدیل HTML به PPT با استفاده از کد جاوا" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تبدیل HTML به PPT در جاوا" variant="code" %}}

با استفاده از [**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/)، می توانید سند HTML را تنها با چند خط کد به ارائه پاورپوینت تبدیل کنید:

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد جاوا برای تبدیل HTML به PPT" >}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    presentation.save("Presentation.ppt", SaveFormat.Ppt);
} catch(IOException e) {
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="HTML را با استفاده از Aspose.Slides به PPT تبدیل کنید" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) یک کتابخانه قدرتمند جاوا است که برای ایجاد، تبدیل و دستکاری ارائه‌های پاورپوینت، فایل‌های PDF، اسناد HTML و موارد دیگر استفاده می‌شود. فایل ها. هنگامی که HTML را به PPT تبدیل می کنید، اساساً محتوای یک سند HTML را به اسلایدهای یک ارائه پاورپوینت منتقل می کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تبدیل HTML به PPT در جاوا" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides را برای جاوا** نصب کنید. [**نصب**](https://docs.aspose.com/slides/java/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک نمونه از کلاس Presentation ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سند HTML را که می خواهید به PPT تبدیل کنید بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل حاصل را به عنوان ارائه PPT ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="مبدل آنلاین رایگان"
  description="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر تبدیل های پاورپوینت پشتیبانی شده" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر به پاورپوینت تبدیل کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/jpg-to-ppt/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/jpg-to-pptx/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

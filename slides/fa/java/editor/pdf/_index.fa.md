---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PDF را در جاوا ویرایش کنید
url: /fa/java/editor/pdf/
keywords: PDF، PDF، Java API، کتابخانه جاوا را ویرایش کنید
description: PDF را در جاوا ویرایش کنید. از API کتابخانه جاوا برای ویرایش سند PDF استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PDF را در جاوا ویرایش کنید" h2="کتابخانه جاوا با سرعت بالا و کراس پلتفرم برای ویرایش PDF با استفاده از کد جاوا" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PDF را در جاوا ویرایش کنید" variant="code" %}}

با استفاده از [**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/)، می توانید تنها با چند خط کد، یک خط متن جدید به سند PDF اضافه کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد جاوا برای ویرایش PDF" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("document.pdf");

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("document.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PDF را با استفاده از Aspose.Slides ویرایش کنید" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) یک کتابخانه قدرتمند جاوا است که برای دستکاری و ویرایش ارائه ها، اسناد PDF و فایل های دیگر استفاده می شود. می توانید یک سند PDF را با افزودن یک خط متن جدید به آن ویرایش کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه ویرایش PDF در جاوا" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides را برای جاوا** نصب کنید. [**نصب**](https://docs.aspose.com/slides/java/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک نمونه از کلاس Presentation ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سند PDF را که می خواهید ویرایش کنید بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک خط جدید از متن اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PDF تغییر یافته را ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="فایل های دیگر را ویرایش کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ویرایش کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
title: تبدیل HTML به PPTX در جاوا
url: /fa/java/conversion/html-to-pptx/
keywords: تبدیل HTML به PPTX، HTML به PPTX، پاورپوینت، HTML، PPTX، Java API، کتابخانه جاوا
description: تبدیل HTML به PPTX در جاوا. از API کتابخانه جاوا برای تبدیل HTML به پاورپوینت استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل HTML به PPTX در جاوا" h2="بین پلتفرم قدرتمند Java API برای تبدیل HTML به PPTX با استفاده از کد جاوا" >}}

{{% blocks/products/pf/feature-page-section h2="HTML را با استفاده از Aspose.Slides به PPTX تبدیل کنید" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/) یک کتابخانه قدرتمند جاوا است که برای ایجاد، تبدیل و دستکاری ارائه‌های پاورپوینت، فایل‌های PDF، اسناد HTML و موارد دیگر استفاده می‌شود. فایل ها. وقتی HTML را به PPTX تبدیل می کنید، اساساً محتوای یک سند HTML را به اسلایدهای یک ارائه پاورپوینت منتقل می کنید.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="تبدیل HTML به PPTX در جاوا" %}}
با استفاده از [**Aspose.Slides for Java**](https://products.aspose.com/slides/fa/java/)، می توانید سند HTML را تنها با چند خط کد به ارائه پاورپوینت تبدیل کنید:

{{% blocks/products/pf/agp/code-block title="کد جاوا برای تبدیل HTML به PPTX" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    presentation.save("Presentation.pptx", SaveFormat.Pptx);
} catch(IOException e) {
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل HTML به PPTX در جاوا" >}}


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
سند HTML را که می خواهید به PPTX تبدیل کنید بارگیری کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
فایل حاصل را به عنوان یک ارائه PPTX ذخیره کنید.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="مبدل آنلاین رایگان" sectionDescription="[نحوه تبدیل PPT به HTML در پایتون](https://products.aspose.com/slides/fa/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پاورپوینت پشتیبانی شده" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر به پاورپوینت تبدیل کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
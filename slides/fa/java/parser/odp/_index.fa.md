---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 5200
title: استخراج متن از اسناد ODP با Java
url: /fa/java/parser/odp/ 
description: با Aspose.Slides for Java متن را از فایل‌های ODP در Java استخراج کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تجزیه فایل‌های ODP در Java" h2="متن و محتوای ارائه را با APIهای سمت سرور Aspose.Slides for Java از اسناد ODP استخراج کنید."
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تجزیه فایل ODP با Java" %}}

از [Aspose.Slides for Java](/slides/fa/java/) برای تجزیه ارائه‌های ODP و استخراج متن از اسلایدها استفاده کنید. برای افزودن کتابخانه به پروژه مبتنی بر Maven، پیکربندی مخزن و وابستگی زیر را در فایل `pom.xml` قرار دهید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="مخزن" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="وابستگی" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="تجزیه فایل‌های ODP – Java" >}}
```java
Presentation presentation = new Presentation("demo.odp");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تجزیه فایل‌های ODP در Java" intro="با Aspose.Slides for Java در چند خط کد متن را از یک ارائه ODP استخراج کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل `ODP` را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد `SlideUtil.getAllTextBoxes` را برای دریافت قاب‌های متن اسلاید اول فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روی هر شیء `ITextFrame`، `IParagraph` و `IPortion` پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متن، اندازه قلم و نام قلم را از هر شیء `IPortion` بخوانید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="پیش‌نیازهای سیستم" intro="Aspose.Slides for Java از پلتفرم‌ها و سیستم‌عامل‌های اصلی پشتیبانی می‌کند. مطمئن شوید محیط شما پیش‌نیازهای زیر را دارد." %}}

- Microsoft Windows یا سیستم‌عامل سازگار با Java Runtime Environment برای برنامه‌های JSP/JSF و برنامه‌های دسکتاپ.
- آخرین نسخه Aspose.Slides for Java از [Maven](https://releases.aspose.com/java/repo/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="ساخته شده با Aspose.Slides" title="استخراج آنلاین متن و تصاویر" description="برنامه رایگان Aspose.Slides Parser با [Aspose.Slides for Java](https://products.aspose.com/slides/fa/java/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Parser" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides فایل‌های شما را چگونه می‌خواند.
- یک فایل ODP بارگذاری کنید و متن و تصاویر آن را دریافت کنید.
- همه را در یک بایگانی ZIP دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

فایل‌هایی با پسوند ODP از قالب OpenDocument Presentation استفاده می‌کنند. فایل ODP اسلایدهایی را ذخیره می‌کند که می‌توانند متن، تصویر، قالب‌بندی، پویانمایی و دیگر محتوای ارائه داشته باشند.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌شده برای تجزیه" subTitle="با Java می‌توانید قالب‌های ارائه دیگر را نیز تجزیه کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/parser/ppt/" name="PPT" description="ارائه PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/parser/pptx/" name="PPTX" description="ارائه PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: جستجوی متن در فایل‌های ارائه PPT با استفاده از Java
url: /fa/java/search/ppt/
description: متن را در ارائه‌های PPT در Java با Aspose.Slides for Java جستجو کنید.
keywords: جستجوی کلمات در PPT، جستجوی متن در PPT، جستجو در متن ارائه PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="جستجوی متن در PPT با استفاده از Java" h2="برنامه‌های Java بسازید که با APIهای سمت سرور متن را در فایل‌های ارائه جستجو می‌کنند." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="جستجوی متن در یک ارائه PPT از طریق Java" variant="code" %}}

با [Aspose.Slides for Java](/slides/fa/java/) می‌توانید متن را در ارائه‌های PPT جستجو کنید. از متد `SlideUtil.getAllTextBoxes` برای جمع‌آوری قاب‌های متنی استفاده کنید و سپس اشیای `ITextFrame`، `IParagraph` و `IPortion` را بررسی کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="جستجوی متن در یک ارائه PPT با استفاده از Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه جستجوی متن در PPT از طریق Java" intro="برای جستجوی متن در یک ارائه PPT این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPT را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد `SlideUtil.getAllTextBoxes` را برای جمع‌آوری قاب‌های متنی هر اسلاید فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اشیای `ITextFrame`، `IParagraph` و `IPortion` را برای یافتن متن مطابق بررسی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="ساخته شده با Aspose.Slides" title="جستجوی آنلاین متن در فایل‌های PPT" description="برنامه رایگان Aspose.Slides Search با [Aspose.Slides for Java](https://products.aspose.com/slides/fa/java/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Search" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه متن را پیدا می‌کند.
- در فایل PPT خود متن ساده یا عبارات باقاعده را جستجو کنید.
- نتایج را به‌صورت فایل متنی دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای جستجو" subTitle="با Java می‌توانید در فرمت‌های زیر نیز متن را جستجو کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

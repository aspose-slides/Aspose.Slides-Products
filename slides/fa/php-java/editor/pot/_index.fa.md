---
lastmod: 2023-02-06
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: POT را در PHP ویرایش کنید
url: /fa/php-java/editor/pot/
keywords: ویرایش POT، ویرایش پاورپوینت، POT، پاورپوینت، PHP API، کتابخانه PHP
description: POT را در PHP ویرایش کنید. از API کتابخانه PHP برای ویرایش فایل‌های POT استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="POT را در PHP ویرایش کنید" h2="کتابخانه PHP پرسرعت و چند پلتفرمی برای ویرایش POT با استفاده از کد PHP" related="FODP,HTML,ODP,OTP,PDF,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="POT را در PHP ویرایش کنید" variant="code" %}}

با استفاده از [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/fa/php-java/)، می توانید تنها با یک خط متنی جدید به سند POT اضافه کنید. چند خط کد

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد PHP برای ویرایش POT" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pot");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.pot", SaveFormat::Pot);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="با استفاده از Aspose.Slides، POT را ویرایش کنید" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/fa/php-java/) یک کتابخانه قدرتمند PHP برای ویرایش سریع و آسان ارائه ها است. طیف گسترده ای از ویژگی ها را در اختیار کاربران قرار می دهد تا به آنها کمک کند اسلایدهایی با ظاهری حرفه ای در کمترین زمان ایجاد کنند. با Aspose، کاربران می توانند متن را ویرایش کنند، تصاویر، انیمیشن ها و انتقال ها را به ارائه خود اضافه کنند و همچنین گزینه های قالب بندی مختلف مانند نوع فونت و انتخاب رنگ را اعمال کنند. علاوه بر این، این کتابخانه هم از فایل‌های پاورپوینت (PPT) و هم از فرمت‌های OpenOffice Presentation (ODP) پشتیبانی می‌کند که اشتراک‌گذاری ارائه‌ها را در پلتفرم‌های مختلف بدون بروز هرگونه مشکل سازگاری آسان‌تر از همیشه می‌کند. با استفاده از قدرت کتابخانه Aspose هنگام ایجاد یا ویرایش ارائه بعدی، مطمئن خواهید بود که اسلایدهای شما هر بار عالی به نظر می رسند!
می توانید یک فایل POT را با افزودن یک خط متن جدید به آن ویرایش کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه ویرایش POT در PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides را برای PHP از طریق جاوا** نصب کنید. [**نصب**](https://docs.aspose.com/slides/php-java/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک نمونه از کلاس Presentation ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه POT را که می خواهید ویرایش کنید بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک خط جدید از متن اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل تغییر یافته را ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="ساخته شده با Aspose.Slides" title="ویرایش آنلاین فایل‌های PPTX" description="برنامه رایگان Aspose.Slides Editor با [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/fa/php-java/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Editor" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌های شما را پردازش می‌کند.
- فایل‌های PPTX خود را بارگذاری کنید و فوراً ویرایش کنید.
- فایل ویرایش‌شده را ذخیره و دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="فایل های دیگر را ویرایش کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ویرایش کنید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/php-java/editor/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
title: تبدیل مایکروسافت پاورپوینت به فرمت های مختلف با استفاده از ++C
url: /fa/cpp/conversion/
description: اسلایدهای مایکروسافت پاورپوینت را به چندین فایل از جمله فرمت های HTML، PDF و تصویر در برنامه های C++ تبدیل کنید.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> تبدیل ارائه پاورپوینت از طریق C++" h2="کدهای مثال C++ برای سناریوهای مختلف تبدیل برای تبدیل اسلایدها به تصاویر، HTML، PDF و فرمت های دیگر." >}}

{{% blocks/products/pf/feature-page-summary %}}

فرآیند تبدیل فرمت‌های Microsoft<sup>®</sup> PowerPoint ساده و آسان برای خودکارسازی فرآیندها با استفاده از کتابخانه C++ PowerPoint است. توسعه دهندگان می توانند کد منبع مربوطه را تقویت کرده و آن را در برنامه های خود ادغام کنند. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="تبدیل بین فرمت های پاورپوینت مایکروسافت" %}}
تبدیل اسناد پاورپوینت مایکروسافت<sup>®</sup> از جمله PPT، PPTX به صورت برنامه نویسی فقط یک کد دو خطی است. فایل را با استفاده از [Presentation class] (https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) بارگیری کنید و با [روش ذخیره] (https://apireference.aspose.com/slides) تماس بگیرید /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) دارای فایل خروجی و SaveFormat.OutputFormats به عنوان پارامتر.

{{% blocks/products/pf/feature-page-code h3="کد تبدیل C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="تبدیل فایل های پاورپوینت به PDF" %}}

تبدیل Microsoft<sup>®</sup> PowerPoint به PDF یک سناریوی رایج به دلیل اشتراک گذاری گسترده اسناد PDF است. برنامه نویسان می توانند آن را خودکار کرده و تنظیمات تبدیل PDF مربوطه را با استفاده از [PdfOptions class] (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options) تنظیم کنند. تعداد کمی از تنظیمات خاص مانند سطح فشرده‌سازی متن، کیفیت JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e31Compliance] level، PDF (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f)، تبدیل اسلایدهای پنهان [ShowHiddenSlides](ShowHiddenSlides.com. /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23)، اسلایدهای انتخاب شده و تولید فایل های قفل شده [Password](https://apireference.aspose.com/slides/cpp/class.class.class. .

{{% blocks/products/pf/feature-page-code h3="کد تبدیل C++ پاورپوینت به PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="اسلایدهای پاورپوینت مایکروسافت را به عنوان تصویر ذخیره کنید" %}}
زمانی که امکان نمایش محتوای ارائه در وب وجود داشته باشد، نیاز به رندر فایل ها به صورت HTML یا تصاویر JPG، TIFF، PNG و غیره وجود دارد. فرآیند تبدیل اسلایدها به صورت تصویر ساده است. همه اسلایدها را با استفاده از [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) دریافت کنید و هر اسلاید را یکی یکی تکرار کنید. در طول هر تکرار از [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) برای تصویر مورد نیاز استفاده کنید و سپس تصویر مورد نیاز را فرمت کنید. 

{{% blocks/products/pf/feature-page-code h3="تبدیل پاورپوینت C++ به تصویر" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}
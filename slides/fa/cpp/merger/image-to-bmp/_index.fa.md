---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ادغام تصویر به BMP در C++
url: /fa/cpp/merger/image-to-bmp/
keywords: تصویر به BMP، ادغام تصویر به BMP، پیوستن تصویر به BMP، ترکیب تصاویر، تصویر، BMP، C++ API، کتابخانه C++
description: ادغام تصویر به BMP در C++. از C++ library API برای ترکیب تصاویر استفاده کنید
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ادغام تصویر به BMP در C++" h2="کتابخانه C++ پرسرعت و کراس پلتفرم برای ادغام تصویر با فایل های BMP با استفاده از کد C++" related="JPG,PNG,HTML,IMAGE,PDF,SVG" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ادغام تصویر به BMP در C++" variant="code" %}}

با استفاده از [**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/)، می توانید تنها با چند خط کد، تصویر را به سرعت با BMP ادغام کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="کد C++ برای ادغام تصویر با BMP" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
        
auto image1 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image1.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 100.0f, 100.0f, image1);
auto image2 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image2.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 200.0f, 100.0f, 100.0f, image2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.bmp", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Bmp());
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ادغام تصویر با BMP با استفاده از Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/fa/cpp/) یک کتابخانه قدرتمند C++ است که برای ایجاد، تبدیل، ادغام و دستکاری ارائه‌ها، فایل‌های PDF، تصاویر و موارد دیگر استفاده می‌شود. فایل ها. هنگامی که تصویر را با BMP ادغام می کنید، به طور موثر تصاویر را برای به دست آوردن یک فایل BMP ترکیب می کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه ادغام تصویر با BMP در C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides را برای C++** نصب کنید. [**نصب**](https://docs.aspose.com/slides/cpp/installation/) را ببینید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}کتابخانه را به عنوان مرجع در پروژه خود اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک نمونه از کلاس Presentation ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تصاویری را که می خواهید به عنوان قاب عکس با هم ادغام کنید بارگیری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل BMP حاصل را ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="ساخته شده با Aspose.Slides" title="ادغام آنلاین تصویر در BMP" description="برنامه رایگان Aspose.Slides Merger با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های تصویر شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Merger" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه فایل‌ها را ادغام می‌کند.
- چند فایل تصویر را بارگذاری کنید و آن‌ها را در یک فایل BMP ترکیب کنید.
- نتیجه ادغام‌شده را به‌صورت یک فایل دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="فایل های دیگر را ادغام کنید" subTitle="همچنین می توانید فایل ها را با فرمت های دیگر ترکیب کنید تا یک فایل واحد بدست آورید" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fa/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

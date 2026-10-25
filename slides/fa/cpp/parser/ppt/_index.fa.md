---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2780
title: استخراج متن از ارائه‌های PPT با C++
url: /fa/cpp/parser/ppt/ 
description: متن را از ارائه‌های PPT در C++ استخراج کنید. از Aspose.Slides for C++ برای تجزیه اسلایدها، قاب‌های متن، پاراگراف‌ها و بخش‌های متن استفاده کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تجزیه ارائه‌های PPT در C++" h2="از Aspose.Slides for C++ برای استخراج متن از اسلایدهای ارائه بدون Microsoft PowerPoint استفاده کنید."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تجزیه فایل PPT با C++" %}}

از Aspose.Slides for C++ برای تجزیه فایل‌های ارائه PPT و استخراج متن از اسلایدها استفاده کنید. API متن اسلایدها را از طریق `SlideUtil::GetAllTextBoxes`، `ITextFrame`، `IParagraph` و `IPortion` در اختیار می‌گذارد، بنابراین می‌توانید محتوای متنی را بدون خودکارسازی Microsoft PowerPoint بخوانید. بسته [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) را از NuGet نصب کنید یا دستور زیر را در Package Manager Console به کار ببرید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="دستور" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="تجزیه فایل‌های PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه تجزیه فایل‌های PPT در C++" intro="با Aspose.Slides for C++ متن را از فایل‌های PPT استخراج کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل PPT را با کلاس `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اشیای `ITextFrame` اسلاید اول را با `SlideUtil::GetAllTextBoxes` دریافت کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روی اشیای `ITextFrame` پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روی اشیای `IParagraph` در هر `ITextFrame` پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}روی اشیای `IPortion` در هر `IParagraph` پیمایش کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متن را با `get_Text` بخوانید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="پیش‌نیازهای سیستم" intro="Aspose.Slides for C++ از پلتفرم‌های اصلی دسکتاپ و سرور پشتیبانی می‌کند. مطمئن شوید پروژه شما پیش‌نیازهای زیر را دارد." %}}

-  Microsoft Windows، Linux، macOS یا سیستم‌عامل سازگار دیگری با محیط اجرای C++ پشتیبانی‌شده.
-  کتابخانه Aspose.Slides for C++ که در پروژه شما ارجاع داده شده است.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="ساخته شده با Aspose.Slides" title="استخراج آنلاین متن و تصاویر" description="برنامه رایگان Aspose.Slides Parser با [Aspose.Slides for C++](https://products.aspose.com/slides/fa/cpp/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Parser" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides فایل‌های شما را چگونه می‌خواند.
- یک فایل PPT بارگذاری کنید و متن و تصاویر آن را دریافت کنید.
- همه را در یک بایگانی ZIP دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

A PPT file is a Microsoft PowerPoint 97-2003 presentation file. It stores slides, text, images, multimedia, and embedded objects in the binary PowerPoint file format used before the Open XML PPTX format.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌شده برای تجزیه" subTitle="با C++ می‌توانید قالب‌های ارائه دیگر را نیز تجزیه کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/parser/odp/" name="ODP" description="ارائه OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/cpp/parser/pptx/" name="PPTX" description="ارائه PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

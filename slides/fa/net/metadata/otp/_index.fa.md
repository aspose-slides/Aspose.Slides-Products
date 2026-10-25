---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: مشاهده یا ویرایش فراداده فایل‌های OTP با .NET
url: /fa/net/metadata/otp/
description: کد منبع C# برای مشاهده یا ویرایش فراداده OTP.
keywords: ویرایش فراداده OTP، مشاهده فراداده OTP، ویرایش ویژگی‌های OTP، مشاهده ویژگی‌های OTP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ویرایش ویژگی‌های OTP با C#" h2="برنامه‌های .NET بسازید که ویژگی‌های داخلی و سفارشی ارائه‌ها را با APIهای سمت سرور می‌خوانند و تغییر می‌دهند." related="FODP,ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تغییر ویژگی‌های OTP با C#" variant="code" %}}

با [Aspose.Slides for .NET](/slides/fa/net/) توسعه‌دهندگان می‌توانند به ویژگی‌های داخلی و سفارشی ارائه‌ها دسترسی داشته باشند و آن‌ها را تغییر دهند. برای خواندن و به‌روزرسانی فراداده OTP از ویژگی [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) شیء `Presentation` استفاده کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="تغییر ویژگی‌های داخلی OTP – C#" >}}
```cs
using var presentation = new Presentation("presentation.otp");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.otp", SaveFormat.Otp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="افزودن ویژگی‌های سفارشی به OTP – C#" >}}
```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.otp", SaveFormat.Otp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه مشاهده یا ویرایش فراداده OTP در C#" intro="برای مشاهده یا ویرایش فراداده OTP این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل OTP را با `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}شیء `DocumentProperties` ارائه را دریافت کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ویژگی‌های داخلی مانند `Author`، `Title` و `Subject` را بخوانید یا به‌روز کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}با `DocumentProperties` به ویژگی‌های سفارشی دسترسی پیدا کنید و آن‌ها را تغییر دهید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="ساخته شده با Aspose.Slides" title="مشاهده و ویرایش آنلاین فراداده OTP" description="برنامه رایگان Aspose.Slides Metadata با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های OTP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Metadata" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides ویژگی‌ها را چگونه می‌خواند و می‌نویسد.
- ویژگی‌های داخلی و سفارشی فایل OTP خود را مشاهده و ویرایش کنید.
- فایل به‌روزشده را ذخیره و دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های فراداده پشتیبانی‌شده" subTitle="با C# می‌توانید فراداده قالب‌های زیر را نیز مدیریت کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

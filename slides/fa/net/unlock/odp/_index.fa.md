---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: باز کردن قفل فایل‌های ارائه ODP با .NET
url: /fa/net/unlock/odp/
description: کد منبع C# برای حذف محافظت با رمز عبور از ارائه‌های ODP.
keywords: حذف محافظت در برابر نوشتن ODP، رمزگشایی ODP، باز کردن قفل ارائه ODP، برداشتن محافظت ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="باز کردن قفل فایل‌های ODP با C#" h2="برنامه‌های .NET بسازید که با APIهای سمت سرور رمزگذاری و محافظت در برابر نوشتن را از ارائه‌ها حذف می‌کنند." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="حذف محافظت از ارائه ODP با C#" variant="code" %}}

با [Aspose.Slides for .NET](/slides/fa/net/) می‌توانید رمزگذاری یا محافظت در برابر نوشتن را از ارائه ODP حذف کنید. برای حذف رمزگذاری، ارائه را با رمز عبور درست بارگذاری کنید و `ProtectionManager.RemoveEncryption` را فراخوانی کنید. برای حذف محافظت در برابر نوشتن، `ProtectionManager.RemoveWriteProtection` را فراخوانی کنید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف رمزگذاری از ارائه ODP با C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="حذف محافظت در برابر نوشتن از ارائه ODP با C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="نحوه حذف محافظت از ارائه ODP با C#" intro="برای حذف محافظت از ارائه ODP، این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}فایل ODP را با `Presentation` بارگذاری کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}برای فایل رمزگذاری‌شده، پیش از بارگذاری رمز عبور را از طریق `LoadOptions.Password` وارد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}بسته به نوع محافظت اعمال‌شده، `ProtectionManager.RemoveEncryption` یا `ProtectionManager.RemoveWriteProtection` را فراخوانی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه بازشده را با `SaveFormat.Odp` ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="ساخته شده با Aspose.Slides" title="باز کردن قفل فایل‌های ODP به‌صورت آنلاین" description="برنامه رایگان Aspose.Slides Unlock با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های ODP شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Unlock" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه محافظت را حذف می‌کند.
- رمز عبور یا محافظت در برابر نوشتن را از فایل ODP خود حذف کنید.
- فایل بازشده را دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر فرمت‌های پشتیبانی‌شده برای باز کردن قفل" subTitle="با C# می‌توانید محافظت را از فرمت‌های زیر نیز حذف کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

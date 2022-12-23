---
title: 在 C# 中編輯 HTML
url: /zh-hant/net/editor/html/
keywords: 編輯 HTML、HTML、C# API、.NET 庫
description: 在 C# 中編輯 HTML。使用 .NET 庫 API 編輯 HTML 文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C# 中編輯 HTML" h2="強大的跨平台 .NET API，用於在 NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上使用 C# 代碼編輯 HTML" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 編輯 HTML" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh-hant/net/) 是一個功能強大的 .NET 庫，用於操作和編輯演示文稿、HTML 文檔和其他文件。您可以通過向其中添加新的文本行來編輯 HTML 文檔。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 C# 中編輯 HTML" %}}
使用 [**Aspose.Slides for .NET**](https://products.aspose.com/slides/zh-hant/net/)，您只需幾行代碼即可向 HTML 文檔添加新的文本行。

{{% blocks/products/pf/agp/code-block title="用於編輯 HTML 的 C# 代碼" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide
    pres.Slides.AddFromHtml("page.html");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("page.html", SaveFormat.Html);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 C# 中編輯 HTML" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安裝 **Aspose.Slides for .NET**。請參閱 [**安裝**](https://docs.aspose.com/slides/net/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加庫作為項目中的引用。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建一個 Presentation 類的實例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載要編輯的 HTML 文檔。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加新的文本行。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存更改後的 HTML 文件。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="編輯其他文件" subTitle="您還可以編輯其他格式的文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: HTML'yi C# ile düzenleyin
url: /tr/net/editor/html/
keywords: HTML, HTML, C# API, .NET Kitaplığını Düzenle
description: HTML'yi C# ile düzenleyin. HTML dosyasını düzenlemek için .NET kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="HTML'yi C# ile düzenleyin" h2="NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında C# kodunu kullanarak HTML'yi düzenlemek için güçlü platformlar arası .NET API'si" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="HTML'yi C# ile düzenleyin" variant="code" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/) kullanarak, yalnızca birkaç satır kodla bir HTML belgesine yeni bir metin satırı ekleyebilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML'yi düzenlemek için C# kodu" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides kullanarak HTML'yi düzenleyin" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/), sunumları, HTML belgelerini ve diğer dosyaları işlemek ve düzenlemek için kullanılan güçlü bir .NET kitaplığıdır. Yeni bir metin satırı ekleyerek bir HTML belgesini düzenleyebilirsiniz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C#'ta HTML nasıl düzenlenir?" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET**'i kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kütüphaneyi projenize referans olarak ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation sınıfının bir örneğini oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Düzenlemek istediğiniz HTML belgesini yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Yeni bir metin satırı ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Değiştirilen HTML dosyasını kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Diğer dosyaları düzenle" subTitle="Diğer formatlardaki dosyaları da düzenleyebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

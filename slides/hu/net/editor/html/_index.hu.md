---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: HTML szerkesztése C#-ban
url: /hu/net/editor/html/
keywords: HTML, HTML, C# API, .NET Library szerkesztése
description: Szerkessze a HTML-t C#-ban. Használja a .NET könyvtár API-t a HTML-fájl szerkesztéséhez
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="HTML szerkesztése C#-ban" h2="Hatékony, többplatformos .NET API a HTML szerkesztéséhez C# kóddal NET Framework, .NET Core, Windows Azure, Mono vagy Xamarin platformokon" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="HTML szerkesztése C#-ban" variant="code" %}}

Az [**Aspose.Slides for .NET**](https://products.aspose.com/slides/hu/net/) használatával mindössze néhány sornyi kóddal új szövegsort adhat hozzá egy HTML-dokumentumhoz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# kód HTML szerkesztéshez" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Szerkessze a HTML-t az Aspose.Slides segítségével" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hu/net/) egy hatékony .NET-könyvtár prezentációk, HTML-dokumentumok és egyéb fájlok kezelésére és szerkesztésére. Egy HTML-dokumentumot szerkeszthet úgy, hogy új szövegsort ad hozzá.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="HTML szerkesztése C#-ban" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az **Aspose.Slides for .NET** alkalmazást. Lásd: [**Telepítés**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adja hozzá a könyvtárat referenciaként a projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy példányt a Prezentáció osztályból.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a szerkeszteni kívánt HTML-dokumentumot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá egy új szövegsort.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse el a módosított HTML-fájlt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Más fájlok szerkesztése" subTitle="Más formátumú fájlokat is szerkeszthet" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Szöveg keresése PPTX bemutatófájlokban .NET segítségével
url: /hu/net/search/pptx/
description: C# forráskód szöveg kereséséhez PPTX bemutatókban.
keywords: Szöveg keresése PPTX fájlban, szöveg megtalálása PPTX fájlban, PPTX bemutató szövegének keresése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Szöveg keresése PPTX fájlokban C# használatával" h2="Készítsen .NET-alkalmazásokat, amelyek kiszolgálóoldali API-kkal keresnek szöveget bemutatókban." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Szöveg keresése PPTX bemutatóban C# használatával" variant="code" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével szöveget kereshet egy PPTX bemutatóban. Kérje le egy dia szövegkereteit a `SlideUtil.GetAllTextBoxes` segítségével, majd keresse meg a kívánt kifejezést a `Text` értékekben.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szöveg keresése PPTX bemutatóban C# használatával" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan kereshet szöveget egy PPTX bemutatóban C# használatával" intro="Az alábbi lépésekkel kereshet szöveget egy PPTX bemutatóban." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX fájlt a `Presentation` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kérje le a kívánt diát a `Presentation.Slides` gyűjteményből, és rendelje hozzá egy változóhoz.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kérje le a dia szövegkereteit a [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/) segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ellenőrizze, hogy az egyes keretek `Text` értéke tartalmazza-e a kívánt kifejezést.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Az Aspose.Slides segítségével készült" title="Szöveg keresése PPTX fájlokban online" description="Az ingyenes Aspose.Slides Search alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Search megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan talál szöveget az Aspose.Slides, mielőtt kódot írna.
- Keressen egyszerű szöveget vagy reguláris kifejezéseket a PPTX fájlban.
- Töltse le a találatokat szövegfájlként.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok kereséshez" subTitle="C# használatával a következő formátumokban is kereshet szöveget." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

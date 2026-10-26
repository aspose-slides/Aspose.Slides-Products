---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Szöveg keresése PPT bemutatófájlokban .NET segítségével
url: /hu/net/search/ppt/
description: C# forráskód szöveg kereséséhez PPT bemutatókban.
keywords: Szöveg keresése PPT fájlban, szöveg megtalálása PPT fájlban, PPT bemutató szövegének keresése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Szöveg keresése PPT fájlokban C# használatával" h2="Készítsen .NET-alkalmazásokat, amelyek kiszolgálóoldali API-kkal keresnek szöveget bemutatókban." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Szöveg keresése PPT bemutatóban C# használatával" variant="code" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével szöveget kereshet egy PPT bemutatóban. Kérje le egy dia szövegkereteit a `SlideUtil.GetAllTextBoxes` segítségével, majd keresse meg a kívánt kifejezést a `Text` értékekben.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szöveg keresése PPT bemutatóban C# használatával" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan kereshet szöveget egy PPT bemutatóban C# használatával" intro="Az alábbi lépésekkel kereshet szöveget egy PPT bemutatóban." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPT fájlt a `Presentation` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kérje le a kívánt diát a `Presentation.Slides` gyűjteményből, és rendelje hozzá egy változóhoz.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kérje le a dia szövegkereteit a [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/) segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ellenőrizze, hogy az egyes keretek `Text` értéke tartalmazza-e a kívánt kifejezést.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Az Aspose.Slides segítségével készült" title="Szöveg keresése PPT fájlokban online" description="Az ingyenes Aspose.Slides Search alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPT fájljaival." button="Aspose.Slides Search megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan talál szöveget az Aspose.Slides, mielőtt kódot írna.
- Keressen egyszerű szöveget vagy reguláris kifejezéseket a PPT fájlban.
- Töltse le a találatokat szövegfájlként.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok kereséshez" subTitle="C# használatával a következő formátumokban is kereshet szöveget." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1480
title: Szöveg kinyerése PPTX fájlokból .NET-tel
url: /hu/net/parser/pptx/ 
description: C#-forráskód szöveg kinyeréséhez PPTX fájlokból .NET-tel.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX fájlok elemzése C#-ban" h2="Szöveg kinyerése és a szövegformázás vizsgálata PPTX fájlokban kiszolgálóoldali .NET API-kkal."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPTX fájl elemzése C#-ban" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével szöveget nyerhet ki PPTX bemutatókból. Telepítse a csomagot a [NuGet](https://www.nuget.org/packages/aspose.slides.net) szolgáltatásból, vagy futtassa a következő parancsot a Csomagkezelő konzolban.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Parancs" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX fájlok elemzése – C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX fájlok elemzése C#-ban lépésről lépésre" intro="Az [Aspose.Slides for .NET](/slides/hu/net/) API-val az alapvető dokumentumelemzéshez néhány sornyi kód elég." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kérje le a szövegkereteket a `SlideUtil.GetAllTextFrames` metódussal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Járja be a szövegkereteket, bekezdéseket és szövegrészeket.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Szükség szerint olvassa ki a `Text`, `FontHeight` és `LatinFont.FontName` tulajdonságot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Rendszerkövetelmények" intro="Szükség van egy támogatott .NET-futtatókörnyezetre és az Aspose.Slides for .NET csomagra mutató hivatkozásra. Használhatja a Visual Studiót vagy más kompatibilis C#-fejlesztőkörnyezetet." %}}

- .NET Framework, .NET, Mono vagy Xamarin-kompatibilis környezet
- C#-fejlesztőkörnyezet, például Visual Studio
- A NuGetről telepített Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Az Aspose.Slides segítségével készült" title="Szöveg és képek kinyerése online" description="Az ingyenes Aspose.Slides Parser alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Parser megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan olvassa az Aspose.Slides a fájljait, mielőtt kódot írna.
- Töltsön fel egy PPTX fájlt, és kapja meg a szövegét és a képeit.
- Töltsön le mindent egyetlen ZIP-archívumban.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

A PPTX-fájlok a Microsoft PowerPointtal létrehozott bemutatók. A bináris PPT formátummal szemben a PPTX az Office Open XML formátumot használja. A bemutató szöveget, képeket, formázást, animációkat és egyéb médiát tartalmazó diákból áll, amelyeket diavetítésként mutatnak be.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott elemzési formátumok" subTitle="C#-ban a következő formátumokat is elemezheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/parser/odp/" name="ODP" description="OpenDocument-bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/parser/ppt/" name="PPT" description="PowerPoint 97–2003-bemutató" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: POTX konvertálása PNG-re C#-on keresztül
weight: 8450
url: /hu/net/conversion/potx-to-png/ 
description: Mintakód a POTX-ből PNG-be C# konvertáláshoz. Használjon API-példakódot a POTX-fájlok kötegelt PNG-vé konvertálásához VB.NET-en, Asp.NET-en vagy bármely .NET-alapú alkalmazáson belül.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="POTX konvertálása PNG-re C#-on keresztül" h2="Exportálja a PowerPoint® POTX fájlokat PNG formátumba .NET Framework, .NET Core, Windows Azure, Mono vagy Xamarin platformokon"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="POTX konvertálása PNG-re C# használatával" %}}

A POTX PNG-re konvertálásához használjuk
 [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net)
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -konverziós API C# platformhoz. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 csomagkezelő, keressen
 Aspose.Diák
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Csomagkezelő konzolparancs" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ez a mintakód a POTX-ből PNG-be való C# konvertálást mutatja" >}}
```cs
using (var presentation = new Presentation("template.potx"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in PNG format
        bitmap.Save(string.Format("Slide_{0}.png", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Png);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Lépések a POTX konvertálásához PNG-be C#-on keresztül" intro="A .NET fejlesztők egyszerűen betölthetik és konvertálhatják a POTX fájlokat PNG formátumba, mindössze néhány sornyi kóddal." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltsön be POTX-fájlt a Presentation osztály egy példányával{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ismételje meg a prezentáció egyes diáit{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy teljes léptékű képet bittérképként minden iterációval{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a Bitmap.Save metódust PNG fájlkiterjesztéssel és ImageFormat.Png paraméterekkel{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="rendszerkövetelmények" intro="A .NET konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer .NET-keretrendszerrel, .NET Core-val, Windows Azure-val, Mono- vagy Xamarin-platformokkal.
- Fejlesztői környezet, mint a Microsoft Visual Studio.
- Aspose.Slides for .NET DLL, amelyre a projektben hivatkozik.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Az Aspose.Slides segítségével készült" title="POTX konvertálása PNG formátumba online" description="Az ingyenes Aspose.Slides Conversion alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját POTX fájljaival." button="Aspose.Slides Conversion megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" upload="Húzza ide vagy töltse fel a fájlt" saveAs="Mentés másként" convert="Konvertálás" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan konvertálja a fájlokat az Aspose.Slides, mielőtt kódot írna.
- Töltsön fel POTX fájlokat, és mentse őket PNG formátumban.
- Töltse le az eredményt, vagy konvertáljon további fájlokat.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="A POTX-et számos más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt ​​fájlformátumba." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-bmp/" name="POTX TO BMP" description="Bittérképes kép" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-emf/" name="POTX TO EMF" description="Továbbfejlesztett metafájl formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-gif/" name="POTX TO GIF" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-html/" name="POTX TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-odp/" name="POTX TO ODP" description="OpenDocument prezentációs formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-otp/" name="POTX TO OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-pdf/" name="POTX TO PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-pot/" name="POTX TO POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-potm/" name="POTX TO POTM" description="Microsoft PowerPoint sablonfájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-pps/" name="POTX TO PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-svg/" name="POTX TO SVG" description="Skálázható vektorgrafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-swf/" name="POTX TO SWF" description="SWF formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Címkézett képformátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/conversion/potx-to-xps/" name="POTX TO XPS" description="XML papírspecifikációk" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

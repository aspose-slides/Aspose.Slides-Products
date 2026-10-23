---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-fájlok szerkesztése .NET-en keresztül
url: /hu/net/editor/odp/ 
description: C#-forráskód az ODP-dokumentum szerkesztéséhez .NET-keretrendszeren, .NET Core-on, Windows Azure-on, Mono- vagy Xamarin-platformokon.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP formátumok szerkesztése C#-ban" h2="Natív és nagy teljesítményű ODP-dokumentumok szerkesztése kiszolgálóoldali Aspose.Slides segítségével .NET API-khoz, olyan szoftverek használata nélkül, mint a Microsoft vagy az Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ODP-fájl szerkesztése C# használatával" %}}

Az ODP-fájl szerkesztéséhez az <a href="https://products.aspose.com/slides/hu/net">Aspose.Slides for .NET</a> API-t használjuk, amely funkciókban gazdag, hatékony. és könnyen használható API C# platformhoz bármely szerkesztő számára. Nyissa meg a <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> csomagkezelőt, keresse meg az <b>Aspose.Slides</b> elemet, és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Parancs" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP fájlok szerkesztése - C#" >}}
```cs
using var presentation = new Presentation("document.odp");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Az ODP-fájlok C#-ban való szerkesztésének lépései" intro="Alapvető dokumentumszerkesztés [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net) Az API-k néhány sornyi kóddal elkészíthetők." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a(z) ODP fájlt egy `Presentation` objektummal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Változókon keresztül érje el a kívánt diát és alakzatot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Frissítse a szöveget a `TextFrame` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a szerkesztett prezentációt a `SaveFormat.Odp` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="rendszerkövetelmények" intro="API-jaink az összes főbb platformon és operációs rendszeren támogatottak. Mielőtt végrehajtaná az alábbi kódot, győződjön meg arról, hogy a következő előfeltételek vannak a rendszeren." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer .NET-keretrendszerrel, .NET Core-val, Windows Azure-val, Mono- vagy Xamarin-platformokkal
- Fejlesztői környezet, mint a Microsoft Visual Studio
- Aspose.Slides for .NET DLL, amelyre a projektben hivatkozik - Telepítse a NuGetből a fenti Letöltés gomb segítségével

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Az Aspose.Slides segítségével készült" title="PPTX fájlok szerkesztése online" description="Az ingyenes Aspose.Slides Editor alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Editor megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan kezeli az Aspose.Slides a fájljait, mielőtt kódot írna.
- Töltse fel PPTX fájljait, és szerkessze őket azonnal.
- Mentse és töltse le a szerkesztett fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

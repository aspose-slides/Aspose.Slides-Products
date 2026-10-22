---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Szerkessze az OTP-fájlokat .NET-en keresztül
url: /hu/net/editor/otp/ 
description: C#-forráskód az OTP-dokumentum szerkesztéséhez .NET-keretrendszeren, .NET Core-on, Windows Azure-on, Mono- vagy Xamarin-platformokon.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="OTP formátumok szerkesztése C#-ban" h2="Natív és nagy teljesítményű OTP-dokumentumszerkesztés a szerveroldali Aspose.Slides segítségével .NET API-khoz, olyan szoftverek használata nélkül, mint a Microsoft vagy az Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,PDF,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="OTP fájl szerkesztése C# használatával" %}}

Az OTP-fájl szerkesztéséhez az <a href="https://products.aspose.com/slides/hu/net">Aspose.Slides for .NET</a> API-t használjuk, amely funkciókban gazdag, hatékony. és könnyen használható API C# platformhoz bármely szerkesztő számára. Nyissa meg a <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> csomagkezelőt, keresse meg az <b>Aspose.Slides</b> elemet, és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Parancs" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP fájlok szerkesztése - C#" >}}
```cs
using var presentation = new Presentation("document.otp");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.otp", SaveFormat.Otp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Az OTP-fájlok C#-ban való szerkesztésének lépései" intro="Alapvető dokumentumszerkesztés [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net) Az API-k néhány sornyi kóddal elkészíthetők." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a(z) OTP fájlt egy `Presentation` objektummal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Változókon keresztül érje el a kívánt diát és alakzatot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Frissítse a szöveget a `TextFrame` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a szerkesztett prezentációt a `SaveFormat.Otp` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="rendszerkövetelmények" intro="API-jaink az összes főbb platformon és operációs rendszeren támogatottak. Mielőtt végrehajtaná az alábbi kódot, győződjön meg arról, hogy a következő előfeltételek vannak a rendszeren." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer .NET-keretrendszerrel, .NET Core-val, Windows Azure-val, Mono- vagy Xamarin-platformokkal
- Fejlesztői környezet, mint a Microsoft Visual Studio
- Aspose.Slides for .NET DLL, amelyre a projektben hivatkozik - Telepítse a NuGetből a fenti Letöltés gomb segítségével

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

Files with .OTP extension represent presentation template files created by applications in OASIS OpenDocument standard format. The contents of such a file include presentation information in the form of slides with text, images, shapes, multimedia content, transition effects and other slide elements. These template files are used for creating new presentations quickly based on the styling information stored in the template itself. OTP files can be created and saved with several different applications such as Impress that comes with OpenOffice suite and Microsoft PowerPoint. The OTP file format is similar to Microsoft PowerPoint template files .POT and .POTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

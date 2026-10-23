---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPS megtekintése C#-ban
keywords: PPS megtekintése, PPS megnyitása, PPS megjelenítő, PPS, PowerPoint, C# API, .NET könyvtár
weight: 7110
url: /hu/net/viewer/pps/ 
description: PPS fájlok megtekintése C#-ban. Az Aspose.Slides for .NET segítségével megnyithatja a bemutatófájlokat, és HTML-ként mentheti őket.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPS megtekintése C#-ban" h2="C# API PPS fájlok megnyitásához és reszponzív HTML-ként való mentéséhez."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPS megtekintése az Aspose.Slides segítségével" %}}

PPS fájlok megtekintéséhez használja az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) API-t, amely egy hatékony, sokoldalú és könnyen használható API C#-hoz. Nyissa meg a [NuGet](https://www.nuget.org/packages/aspose.slides.net) csomagkezelőt, keressen rá az **Aspose.Slides** csomagra, és telepítse. A következő parancsot a Csomagkezelő konzolban is futtathatja.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Csomagkezelő konzol parancs" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Az [**Aspose.Slides for .NET**](/slides/hu/net/) segítségével néhány sornyi kóddal betölthet egy PPS fájlt, és reszponzív HTML-ként mentheti.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-kód PPS megtekintéséhez" >}}
```cs
using var presentation = new Presentation("presentation.pps");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPS megtekintése C#-ban lépésről lépésre" intro="Az Aspose.Slides segítségével a fejlesztők néhány sornyi kóddal megtekinthetik a PPS fájlokat." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az **Aspose.Slides for .NET** könyvtárat. Lásd: [**Telepítés**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adja hozzá a könyvtárat hivatkozásként a projektjéhez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a `PPS` fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy `ResponsiveHtmlController` objektumot a reszponzív HTML-kimenethez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy `HtmlOptions` objektumot, és állítsa be a `HtmlFormatter` tulajdonságot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a PPS fájlt HTML formátumban a `SaveFormat.Html` használatával.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Rendszerkövetelmények" intro="Az Aspose.Slides for .NET minden jelentős operációs rendszert támogat. Győződjön meg arról, hogy teljesülnek az alábbi előfeltételek." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer .NET Framework, .NET Core, Windows Azure, Mono vagy Xamarin környezettel
- Fejlesztői környezet, például Microsoft Visual Studio
- Hivatkozás az Aspose.Slides for .NET könyvtárra a projektben

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Az Aspose.Slides segítségével készült" title="PPS fájlok megtekintése online" description="Az ingyenes Aspose.Slides Viewer alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPS fájljaival." button="Aspose.Slides Viewer megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan jeleníti meg az Aspose.Slides a fájljait, mielőtt kódot írna.
- Töltse fel PPS fájlját, és azonnal tekintse meg a diáit.
- Asztali gépen és mobilon is működik, PowerPoint nélkül.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. The more latest version of this file format is PPSX which is based on Office OpenXML standards. PPS files can still be read by latest versions of Microsoft PowerPoint, but newly created files can only be saved in PPSX file format. When a PPS file is shared with another user and opened, it starts as Powerpoint show unlike PPT file which opens in editable mode.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Más fájlok megtekintése" subTitle="Más formátumú bemutatókat is megnyithat és megtekinthet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/odp/" name="ODP" description="OpenDocument-bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/otp/" name="OTP" description="OpenDocument-bemutatósablon" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/pot/" name="POT" description="PowerPoint 97–2003-sablon" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/potm/" name="POTM" description="Makróbarát PowerPoint-sablon" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/potx/" name="POTX" description="PowerPoint-sablon" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/ppsm/" name="PPSM" description="Makróbarát PowerPoint-diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/ppsx/" name="PPSX" description="PowerPoint-diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/ppt/" name="PPT" description="PowerPoint 97–2003-bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/pptm/" name="PPTM" description="Makróbarát PowerPoint-bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/net/viewer/pptx/" name="PPTX" description="PowerPoint-bemutató" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

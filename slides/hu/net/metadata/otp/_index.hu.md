---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: OTP fájlok metaadatainak megtekintése és szerkesztése .NET-tel
url: /hu/net/metadata/otp/
description: C#-forráskód OTP metaadatok megtekintéséhez és szerkesztéséhez.
keywords: OTP metaadatok szerkesztése, OTP metaadatok megtekintése, OTP tulajdonságok szerkesztése, OTP tulajdonságok megtekintése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="OTP tulajdonságok szerkesztése C#-ban" h2="Készítsen .NET-alkalmazásokat, amelyek kiszolgálóoldali API-kkal olvassák és módosítják a bemutatók beépített és egyéni tulajdonságait." related="FODP,ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="OTP tulajdonságok módosítása C#-ban" variant="code" %}}

Az [Aspose.Slides for .NET](/slides/hu/net/) segítségével a fejlesztők elérhetik és módosíthatják a bemutatók beépített és egyéni tulajdonságait. A OTP metaadatok olvasásához és frissítéséhez használja a `Presentation` objektum [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) tulajdonságát.

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP beépített tulajdonságainak módosítása – C#" >}}
```cs
using var presentation = new Presentation("presentation.otp");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.otp", SaveFormat.Otp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Egyéni tulajdonságok hozzáadása OTP fájlhoz – C#" >}}
```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.otp", SaveFormat.Otp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="OTP metaadatok megtekintése és szerkesztése C#-ban lépésről lépésre" intro="Kövesse az alábbi lépéseket a OTP metaadatok megtekintéséhez vagy szerkesztéséhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a OTP fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kérje le a bemutató `DocumentProperties` objektumát.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Olvassa ki vagy frissítse a beépített tulajdonságokat, például `Author`, `Title` és `Subject`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Érje el és módosítsa az egyéni tulajdonságokat a `DocumentProperties` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Az Aspose.Slides segítségével készült" title="OTP metaadatok megtekintése és szerkesztése online" description="Az ingyenes Aspose.Slides Metadata alkalmazás az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját OTP fájljaival." button="Aspose.Slides Metadata megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan olvassa és írja az Aspose.Slides a tulajdonságokat, mielőtt kódot írna.
- Tekintse meg és szerkessze OTP fájlja beépített és egyéni tulajdonságait.
- Mentse és töltse le a frissített fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott metaadatformátumok" subTitle="C#-ban a következő formátumok metaadatait is kezelheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

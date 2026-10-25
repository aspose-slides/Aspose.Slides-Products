---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPSX fájlok metaadatainak megtekintése és szerkesztése Java nyelven
url: /hu/java/metadata/ppsx/
description: PPSX metaadatok megtekintése és szerkesztése Java nyelven. Az Aspose.Slides for Java segítségével frissítheti a bemutatók beépített és egyéni tulajdonságait.
keywords: PPSX metaadatok szerkesztése, PPSX metaadatok megtekintése, PPSX tulajdonságok szerkesztése, PPSX tulajdonságok megtekintése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSX tulajdonságok szerkesztése Java nyelven" h2="Készítsen Java-alkalmazásokat, amelyek kiszolgálóoldali API-kkal módosítják a bemutatófájlok beépített és egyéni tulajdonságait." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSX tulajdonságok módosítása Java nyelven" variant="code" %}}

Az [Aspose.Slides for Java](/slides/hu/java/) segítségével a fejlesztők elérhetik és módosíthatják a bemutatók beépített és egyéni tulajdonságait. A `Presentation` objektum `getDocumentProperties` metódusával érheti el a bemutatófájl `IDocumentProperties` objektumát.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX beépített tulajdonságainak módosítása – Java" >}}
```java
Presentation presentation = new Presentation("Presentation.ppsx");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.ppsx", SaveFormat.Ppsx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Egyéni tulajdonságok hozzáadása PPSX fájlhoz – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.ppsx", SaveFormat.Ppsx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPSX metaadatok megtekintése és szerkesztése Java nyelven lépésről lépésre" intro="Kövesse az alábbi lépéseket a PPSX metaadatok megtekintéséhez vagy szerkesztéséhez." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a `PPSX` fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `getDocumentProperties` metódust az `IDocumentProperties` objektum lekéréséhez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Olvassa ki vagy frissítse a beépített tulajdonságokat, például `Author`, `Title`, `Subject` és `Comments`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Érje el és módosítsa az egyéni tulajdonságokat a `set_Item`, `getCustomPropertyName` és `removeCustomProperty` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Az Aspose.Slides segítségével készült" title="PPSX metaadatok megtekintése és szerkesztése online" description="Az ingyenes Aspose.Slides Metadata alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPSX fájljaival." button="Aspose.Slides Metadata megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan olvassa és írja az Aspose.Slides a tulajdonságokat, mielőtt kódot írna.
- Tekintse meg és szerkessze PPSX fájlja beépített és egyéni tulajdonságait.
- Mentse és töltse le a frissített fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott metaadatformátumok" subTitle="Java nyelven a következő formátumok metaadatait is kezelheti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-presentatiebestanden zwartlakken met Java
url: /nl/java/redaction/pptx/
description: Zoek en vervang tekst in PPTX-presentaties in Java met Aspose.Slides for Java.
keywords: PPTX zwartlakken, tekst zoeken en vervangen in PPTX, PPTX-presentatie bijwerken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX zwartlakken met Java" h2="Bouw Java-toepassingen die tekst in presentatiebestanden zoeken en vervangen met server-side API's." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Een PPTX-presentatie zwartlakken via Java" variant="code" %}}

Met [Aspose.Slides for Java](/slides/nl/java/) kunt u tekst in PPTX-presentaties zoeken en vervangen. Gebruik de methode `SlideUtil.findAndReplaceText` om de presentatie te doorzoeken en overeenkomende tekst door een nieuwe waarde te vervangen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Een PPTX-presentatie zwartlakken met Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX zwartlakken via Java" intro="Volg deze stappen om een PPTX-presentatie zwart te lakken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPTX-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode `SlideUtil.findAndReplaceText` aan om tekst te zoeken en te vervangen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de bijgewerkte presentatie op met `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Gebouwd met Aspose.Slides" title="PPTX-bestanden online zwartlakken" description="De gratis app Aspose.Slides Redaction is gebouwd met [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Redaction openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides tekst zoekt en vervangt voordat u code schrijft.
- Zoek en vervang tekst in uw PPTX-bestand, ook met reguliere expressies.
- Download het zwartgelakte bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor zwartlakken" subTitle="Met Java kunt u ook de volgende formaten zwartlakken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

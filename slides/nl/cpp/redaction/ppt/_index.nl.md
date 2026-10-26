---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT-presentaties zwartlakken met C++
url: /nl/cpp/redaction/ppt/
description: Lak PPT-presentaties zwart in C++. Gebruik Aspose.Slides for C++ om gevoelige tekst in presentatiebestanden te zoeken en te vervangen.
keywords: PPT zwartlakken, tekst zoeken en vervangen in PPT, PPT-presentatie bijwerken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT zwartlakken met C++" h2="Gebruik Aspose.Slides for C++ om gevoelige tekst in presentatiebestanden te zoeken en te vervangen zonder Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Een PPT-presentatie zwartlakken via C++" variant="code" %}}

Met Aspose.Slides for C++ lakt u PPT-presentaties zwart door gevoelige tekst in dia's te vervangen. Gebruik `SlideUtil::FindAndReplaceText` met een `Presentation`-object om de presentatie te doorzoeken en overeenkomende tekst te vervangen voordat u het bijgewerkte bestand opslaat.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Een PPT-presentatie zwartlakken met C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPT zwartlakken via C++" intro="Volg deze stappen om een PPT-presentatie zwart te lakken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPT-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gebruik de methode [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) om gevoelige tekst te zoeken en te vervangen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het zwartgelakte bestand op met `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Gebouwd met Aspose.Slides" title="PPT-bestanden online zwartlakken" description="De gratis app Aspose.Slides Redaction is gebouwd met [Aspose.Slides for C++](https://products.aspose.com/slides/nl/cpp/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPT-bestanden." button="Aspose.Slides Redaction openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides tekst zoekt en vervangt voordat u code schrijft.
- Zoek en vervang tekst in uw PPT-bestand, ook met reguliere expressies.
- Download het zwartgelakte bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor zwartlakken" subTitle="Met C++ kunt u ook de volgende formaten zwartlakken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

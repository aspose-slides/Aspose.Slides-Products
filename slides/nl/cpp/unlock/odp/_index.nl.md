---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-presentaties ontgrendelen met C++
url: /nl/cpp/unlock/odp/
description: Ontgrendel ODP-presentaties in C++. Gebruik Aspose.Slides for C++ om versleuteling en schrijfbeveiliging van presentatiebestanden te verwijderen.
keywords: Schrijfbeveiliging ODP verwijderen, ODP ontsleutelen, ODP-presentatie ontgrendelen, beveiliging van ODP opheffen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP ontgrendelen met C++" h2="Gebruik Aspose.Slides for C++ om versleuteling en schrijfbeveiliging van presentatiebestanden te verwijderen zonder Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Beveiliging van een ODP-presentatie verwijderen met C++" variant="code" %}}

Met Aspose.Slides for C++ verwijdert u de versleuteling of schrijfbeveiliging van ODP-presentaties. Gebruik `LoadOptions` om een versleuteld bestand te openen en roep vervolgens via het object `ProtectionManager` van de klasse `Presentation` `RemoveEncryption` of `RemoveWriteProtection` aan.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Wachtwoordbeveiliging van ODP verwijderen met C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging van een ODP-presentatie verwijderen met C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een wachtwoord van ODP verwijderen met C++" intro="Volg deze stappen om de beveiliging van een ODP-presentatie te verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het ODP-bestand met de klasse `Presentation` en, als er een wachtwoord nodig is, met `LoadOptions`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gebruik het object `ProtectionManager` om de beveiliging te verwijderen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `RemoveEncryption` aan voor versleutelde bestanden of `RemoveWriteProtection` voor schrijfbeveiligde bestanden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het ontgrendelde bestand op met `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Gebouwd met Aspose.Slides" title="ODP-bestanden online ontgrendelen" description="De gratis app Aspose.Slides Unlock is gebouwd met [Aspose.Slides for C++](https://products.aspose.com/slides/nl/cpp/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Unlock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides beveiliging verwijdert voordat u code schrijft.
- Verwijder het wachtwoord of de schrijfbeveiliging uit uw ODP-bestand.
- Download het ontgrendelde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor ontgrendelen" subTitle="Met C++ kunt u ook de beveiliging van de volgende formaten verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

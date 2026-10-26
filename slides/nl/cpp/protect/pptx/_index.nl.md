---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-presentaties beveiligen met C++
url: /nl/cpp/protect/pptx/
description: Beveilig PPTX-presentaties in C++. Gebruik Aspose.Slides for C++ om bestanden te versleutelen en schrijfbeveiliging in te stellen.
keywords: Schrijfbeveiliging PPTX, PPTX versleutelen, PPTX-presentatie vergrendelen, PPTX beveiligen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX vergrendelen of met een wachtwoord beveiligen met C++" h2="Gebruik Aspose.Slides for C++ om presentaties te versleutelen en schrijfbeveiliging in te stellen zonder Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Een PPTX-presentatie beveiligen met C++" variant="code" %}}

Met Aspose.Slides for C++ beveiligt u PPTX-presentaties tegen openen of wijzigen. Gebruik het object `ProtectionManager` van de klasse `Presentation` om een bestand te versleutelen met `Encrypt` of bewerken te beperken met `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Een PPTX-presentatie versleutelen met C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging instellen voor een PPTX-presentatie met C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX met een wachtwoord beveiligen met C++" intro="Volg deze stappen om een PPTX-presentatie te beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPTX-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Beveilig de presentatie met het object `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gebruik `Encrypt` voor wachtwoordbeveiliging of `SetWriteProtection` voor schrijfbeveiliging.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het beveiligde bestand op met `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Gebouwd met Aspose.Slides" title="PPTX-bestanden online met een wachtwoord beveiligen" description="De gratis app Aspose.Slides Lock is gebouwd met [Aspose.Slides for C++](https://products.aspose.com/slides/nl/cpp/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Lock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides presentaties beveiligt voordat u code schrijft.
- Stel een wachtwoord in om uw PPTX-bestand te openen of te bewerken.
- Download het beveiligde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor beveiliging" subTitle="Met C++ kunt u ook de volgende formaten beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

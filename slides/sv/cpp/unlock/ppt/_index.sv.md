---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lås upp PPT-presentationer med C++
url: /sv/cpp/unlock/ppt/
description: Lås upp PPT-presentationer i C++. Använd Aspose.Slides for C++ för att ta bort kryptering och skrivskydd från presentationsfiler.
keywords: Ta bort skrivskydd PPT, dekryptera PPT, lås upp PPT-presentation, ta bort skydd från PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lås upp PPT med C++" h2="Använd Aspose.Slides for C++ för att ta bort kryptering och skrivskydd från presentationsfiler utan Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ta bort skydd från en PPT-presentation med C++" variant="code" %}}

Med Aspose.Slides for C++ kan du ta bort kryptering eller skrivskydd från PPT-presentationer. Använd `LoadOptions` för att öppna en krypterad fil och använd sedan objektet `ProtectionManager` i klassen `Presentation` för att anropa `RemoveEncryption` eller `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ta bort lösenordsskydd från PPT med C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.ppt", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ta bort skrivskydd från en PPT-presentation med C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.ppt");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så tar du bort ett lösenord från PPT med C++" intro="Följ de här stegen för att ta bort skyddet från en PPT-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPT-filen med klassen `Presentation` och med `LoadOptions` när ett lösenord krävs.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Använd objektet `ProtectionManager` för att ta bort skyddet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `RemoveEncryption` för krypterade filer eller `RemoveWriteProtection` för skrivskyddade filer.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den upplåsta filen med `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Byggd med Aspose.Slides" title="Lås upp PPT-filer online" description="Den kostnadsfria appen Aspose.Slides Unlock är byggd med [Aspose.Slides for C++](https://products.aspose.com/slides/sv/cpp/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Unlock" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides tar bort skydd innan du skriver kod.
- Ta bort lösenordet eller skrivskyddet från din PPT-fil.
- Ladda ned den upplåsta filen.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för upplåsning" subTitle="Med C++ kan du även ta bort skydd från följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

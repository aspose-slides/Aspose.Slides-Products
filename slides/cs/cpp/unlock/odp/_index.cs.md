---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Odemčení prezentací ODP pomocí C++
url: /cs/cpp/unlock/odp/
description: Odemykejte prezentace ODP v C++. Pomocí Aspose.Slides for C++ odeberete ze souborů prezentací šifrování a ochranu proti zápisu.
keywords: Odebrání ochrany proti zápisu ODP, dešifrování ODP, odemčení prezentace ODP, zrušení ochrany ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odemčení ODP pomocí C++" h2="Pomocí Aspose.Slides for C++ odeberete ze souborů prezentací šifrování a ochranu proti zápisu bez aplikace Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Odebrání ochrany z prezentace ODP pomocí C++" variant="code" %}}

Aspose.Slides for C++ umožňuje odebrat z prezentací ODP šifrování nebo ochranu proti zápisu. Pomocí `LoadOptions` otevřete šifrovaný soubor a pak pomocí objektu `ProtectionManager` třídy `Presentation` zavolejte `RemoveEncryption` nebo `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Odebrání ochrany heslem z ODP pomocí C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Odebrání ochrany proti zápisu z prezentace ODP pomocí C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak odebrat heslo z ODP pomocí C++" intro="Postupujte podle těchto kroků a odeberte ochranu z prezentace ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor ODP pomocí třídy `Presentation` a – pokud je vyžadováno heslo – pomocí `LoadOptions`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ochranu odeberte pomocí objektu `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `RemoveEncryption` pro šifrované soubory nebo `RemoveWriteProtection` pro soubory chráněné proti zápisu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte odemčený soubor pomocí `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Vytvořeno pomocí Aspose.Slides" title="Odemčení souborů ODP online" description="Bezplatná aplikace Aspose.Slides Unlock je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Unlock" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides odebírá ochranu, ještě než začnete psát kód.
- Odeberte heslo nebo ochranu proti zápisu ze souboru ODP.
- Stáhněte odemčený soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro odemčení" subTitle="Pomocí C++ můžete odebrat ochranu také z následujících formátů." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

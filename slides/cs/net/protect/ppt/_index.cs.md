---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ochrana souborů prezentací PPT pomocí .NET
url: /cs/net/protect/ppt/
description: Zdrojový kód C# pro ochranu prezentací PPT heslem.
keywords: Ochrana proti zápisu PPT, šifrování PPT, uzamčení prezentace PPT, ochrana PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Uzamčení nebo ochrana souborů PPT heslem pomocí C#" h2="Vytvářejte aplikace .NET, které šifrují prezentace a omezují jejich úpravy pomocí serverových API." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ochrana prezentace PPT pomocí C#" variant="code" %}}

S [Aspose.Slides for .NET](/slides/cs/net/) můžete prezentaci PPT zašifrovat nebo omezit její úpravy heslem. Otevření prezentace zašifrované pomocí `ProtectionManager.Encrypt` vyžaduje heslo. Pomocí `ProtectionManager.SetWriteProtection` povolíte otevření prezentace, ale omezíte změny.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Šifrování prezentace PPT pomocí C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Nastavení ochrany proti zápisu prezentace PPT pomocí C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak chránit prezentaci PPT heslem pomocí C#" intro="Postupujte podle těchto kroků a ochraňte prezentaci PPT heslem." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPT pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zašifrujte prezentaci pomocí `ProtectionManager.Encrypt` nebo omezte změny pomocí `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte chráněný soubor pomocí `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Vytvořeno pomocí Aspose.Slides" title="Ochrana souborů PPT heslem online" description="Bezplatná aplikace Aspose.Slides Lock je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPT." button="Otevřít Aspose.Slides Lock" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides chrání prezentace, ještě než začnete psát kód.
- Nastavte heslo pro otevření nebo úpravy souboru PPT.
- Stáhněte chráněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro ochranu" subTitle="Pomocí C# můžete chránit také následující formáty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

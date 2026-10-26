---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Odemčení souborů prezentací PPT pomocí .NET
url: /cs/net/unlock/ppt/
description: Zdrojový kód C# pro odebrání ochrany heslem z prezentací PPT.
keywords: Odebrání ochrany proti zápisu PPT, dešifrování PPT, odemčení prezentace PPT, zrušení ochrany PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odemčení souborů PPT pomocí C#" h2="Vytvářejte aplikace .NET, které pomocí serverových API odebírají z prezentací šifrování a ochranu proti zápisu." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Odebrání ochrany z prezentace PPT pomocí C#" variant="code" %}}

S [Aspose.Slides for .NET](/slides/cs/net/) můžete z prezentace PPT odebrat šifrování nebo ochranu proti zápisu. Chcete-li odebrat šifrování, načtěte prezentaci se správným heslem a zavolejte `ProtectionManager.RemoveEncryption`. Chcete-li odebrat ochranu proti zápisu, zavolejte `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Odebrání šifrování z prezentace PPT pomocí C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.ppt", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Odebrání ochrany proti zápisu z prezentace PPT pomocí C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.ppt");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak odebrat ochranu z prezentace PPT pomocí C#" intro="Postupujte podle těchto kroků a odeberte ochranu z prezentace PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPT pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}U šifrovaného souboru zadejte před načtením heslo prostřednictvím `LoadOptions.Password`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Podle použité ochrany zavolejte `ProtectionManager.RemoveEncryption` nebo `ProtectionManager.RemoveWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte odemčenou prezentaci pomocí `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Vytvořeno pomocí Aspose.Slides" title="Odemčení souborů PPT online" description="Bezplatná aplikace Aspose.Slides Unlock je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPT." button="Otevřít Aspose.Slides Unlock" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides odebírá ochranu, ještě než začnete psát kód.
- Odeberte heslo nebo ochranu proti zápisu ze souboru PPT.
- Stáhněte odemčený soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro odemčení" subTitle="Pomocí C# můžete odebrat ochranu také z následujících formátů." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

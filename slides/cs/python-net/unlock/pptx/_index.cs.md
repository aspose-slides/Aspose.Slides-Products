---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Odemčení prezentací PPTX pomocí Pythonu
url: /cs/python-net/unlock/pptx/
description: Odeberte šifrování a ochranu proti zápisu z prezentací PPTX pomocí Pythonu.
keywords: odemčení PPTX, odebrání hesla z PPTX, odebrání šifrování PPTX, odebrání ochrany proti zápisu z PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odemčení prezentací PPTX pomocí Pythonu" h2="Vytvářejte aplikace v Pythonu, které pomocí Aspose.Slides odebírají z prezentací PPTX hesla pro otevření a ochranu proti zápisu." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Odebrání šifrování a ochrany proti zápisu z PPTX pomocí Pythonu" variant="code" %}}

S [Aspose.Slides for Python via .NET](/slides/cs/python-net/) můžete odebrat šifrování, kvůli kterému je k otevření prezentace PPTX potřeba heslo, nebo zrušit její ochranu proti zápisu. Chcete-li otevřít šifrovaný soubor, zadejte aktuální heslo prostřednictvím `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Odebrání šifrování z prezentace PPTX – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Odebrání ochrany proti zápisu z prezentace PPTX – Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak odebrat ochranu z PPTX pomocí Pythonu" intro="Postupujte podle těchto kroků a odeberte ochranu z prezentace PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}U šifrovaného souboru PPTX nastavte aktuální heslo v `LoadOptions` a pak soubor otevřete pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `ProtectionManager.remove_encryption`, abyste odebrali heslo pro otevření, nebo `ProtectionManager.remove_write_protection`, abyste zrušili ochranu proti zápisu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte výslednou prezentaci pomocí `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Vytvořeno pomocí Aspose.Slides" title="Odemčení souborů PPTX online" description="Bezplatná aplikace Aspose.Slides Unlock je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Unlock" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides odebírá ochranu, ještě než začnete psát kód.
- Odeberte heslo nebo ochranu proti zápisu ze souboru PPTX.
- Stáhněte odemčený soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro odemčení" subTitle="Pomocí Pythonu můžete odebrat ochranu i z dalších podporovaných formátů prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ochrana souborů prezentací PPTX pomocí Pythonu
url: /cs/python-net/protect/pptx/
description: Šifrujte prezentace PPTX nebo nastavte ochranu proti zápisu pomocí Pythonu.
keywords: ochrana proti zápisu PPTX, šifrování PPTX v Pythonu, uzamčení prezentace PPTX, ochrana PPTX v Pythonu
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ochrana prezentací PPTX pomocí Pythonu" h2="Vytvářejte aplikace v Pythonu, které pomocí Aspose.Slides šifrují prezentace nebo nastavují ochranu proti zápisu." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ochrana prezentace PPTX pomocí Pythonu" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/cs/python-net/) nabízí dva odlišné mechanismy ochrany. Zavolejte `ProtectionManager.encrypt`, abyste prezentaci PPTX zašifrovali a k jejímu otevření bylo nutné heslo. Případně zavolejte `ProtectionManager.set_write_protection`, abyste odradili od úprav bez šifrování souboru. Uživatel může prezentaci chráněnou proti zápisu stále otevřít a uložit změny do jiného souboru.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Šifrování prezentace PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Nastavení ochrany proti zápisu prezentace PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak chránit PPTX pomocí Pythonu" intro="Postupujte podle těchto kroků a ochraňte soubor PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor PPTX pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Použijte `ProtectionManager.encrypt`, aby bylo k otevření nutné heslo, nebo `ProtectionManager.set_write_protection`, abyste odradili od změn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte chráněnou prezentaci jako PPTX pomocí `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Vytvořeno pomocí Aspose.Slides" title="Ochrana souborů PPTX heslem online" description="Bezplatná aplikace Aspose.Slides Lock je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Lock" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides chrání prezentace, ještě než začnete psát kód.
- Nastavte heslo pro otevření nebo úpravy souboru PPTX.
- Stáhněte chráněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro ochranu" subTitle="Pomocí Pythonu můžete chránit i další podporované formáty prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

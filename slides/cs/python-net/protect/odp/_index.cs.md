---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ochrana souborů prezentací ODP pomocí Pythonu
url: /cs/python-net/protect/odp/
description: Šifrujte prezentace ODP nebo nastavte ochranu proti zápisu pomocí Pythonu.
keywords: ochrana proti zápisu ODP, šifrování ODP v Pythonu, uzamčení prezentace ODP, ochrana ODP v Pythonu
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ochrana prezentací ODP pomocí Pythonu" h2="Vytvářejte aplikace v Pythonu, které pomocí Aspose.Slides šifrují prezentace nebo nastavují ochranu proti zápisu." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ochrana prezentace ODP pomocí Pythonu" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/cs/python-net/) nabízí dva odlišné mechanismy ochrany. Zavolejte `ProtectionManager.encrypt`, abyste prezentaci ODP zašifrovali a k jejímu otevření bylo nutné heslo. Případně zavolejte `ProtectionManager.set_write_protection`, abyste odradili od úprav bez šifrování souboru. Uživatel může prezentaci chráněnou proti zápisu stále otevřít a uložit změny do jiného souboru.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Šifrování prezentace ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Nastavení ochrany proti zápisu prezentace ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak chránit ODP pomocí Pythonu" intro="Postupujte podle těchto kroků a ochraňte soubor ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor ODP pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Použijte `ProtectionManager.encrypt`, aby bylo k otevření nutné heslo, nebo `ProtectionManager.set_write_protection`, abyste odradili od změn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte chráněnou prezentaci jako ODP pomocí `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Vytvořeno pomocí Aspose.Slides" title="Ochrana souborů ODP heslem online" description="Bezplatná aplikace Aspose.Slides Lock je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Lock" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides chrání prezentace, ještě než začnete psát kód.
- Nastavte heslo pro otevření nebo úpravy souboru ODP.
- Stáhněte chráněný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro ochranu" subTitle="Pomocí Pythonu můžete chránit i další podporované formáty prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

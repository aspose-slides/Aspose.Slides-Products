---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lås upp ODP-presentationer med Python
url: /sv/python-net/unlock/odp/
description: Ta bort kryptering och skrivskydd från ODP-presentationer med Python.
keywords: lås upp ODP, ta bort lösenord från ODP, ta bort ODP-kryptering, ta bort skrivskydd från ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lås upp ODP-presentationer med Python" h2="Bygg Python-program som tar bort öppningslösenord och skrivskydd från ODP-presentationer med Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ta bort kryptering och skrivskydd från ODP med Python" variant="code" %}}

Med [Aspose.Slides for Python via .NET](/slides/sv/python-net/) kan du ta bort krypteringen som kräver ett lösenord för att öppna en ODP-presentation, eller stänga av dess skrivskydd. Om du vill öppna en krypterad fil anger du det aktuella lösenordet via `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ta bort kryptering från en ODP-presentation – Python" >}}
```python
load_options = slides.LoadOptions()
load_options.password = "current_password"

with slides.Presentation("encrypted-presentation.odp", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("decrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ta bort skrivskydd från en ODP-presentation – Python" >}}
```python
with slides.Presentation("write-protected-presentation.odp") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så tar du bort skydd från ODP med Python" intro="Följ de här stegen för att ta bort skyddet från en ODP-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}För en krypterad ODP-fil anger du det aktuella lösenordet i `LoadOptions` och öppnar sedan filen med `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `ProtectionManager.remove_encryption` för att ta bort öppningslösenordet, eller `ProtectionManager.remove_write_protection` för att stänga av skrivskyddet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den resulterande presentationen med `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Byggd med Aspose.Slides" title="Lås upp ODP-filer online" description="Den kostnadsfria appen Aspose.Slides Unlock är byggd med [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/sv/python-net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna ODP-filer." button="Öppna Aspose.Slides Unlock" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides tar bort skydd innan du skriver kod.
- Ta bort lösenordet eller skrivskyddet från din ODP-fil.
- Ladda ned den upplåsta filen.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för upplåsning" subTitle="Använd Python för att ta bort skydd från andra presentationsformat som stöds." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Skydda ODP-presentationsfiler med Python
url: /sv/python-net/protect/odp/
description: Kryptera ODP-presentationer eller ange skrivskydd med Python.
keywords: ODP-skrivskydd, kryptera ODP med Python, lås ODP-presentation, skydda ODP med Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Skydda ODP-presentationer med Python" h2="Bygg Python-program som krypterar presentationer eller anger skrivskydd med Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Skydda en ODP-presentation med Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/sv/python-net/) erbjuder två olika skyddsmekanismer. Anropa `ProtectionManager.encrypt` för att kryptera en ODP-presentation så att ett lösenord krävs för att öppna den. Du kan också anropa `ProtectionManager.set_write_protection` för att avråda från ändringar utan att kryptera filen. En användare kan fortfarande öppna en skrivskyddad presentation och spara ändringar i en annan fil.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kryptera en ODP-presentation – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ange skrivskydd för en ODP-presentation – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så skyddar du ODP med Python" intro="Följ de här stegen för att skydda en ODP-fil." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna ODP-filen med `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Använd `ProtectionManager.encrypt` för att kräva ett lösenord vid öppning, eller `ProtectionManager.set_write_protection` för att avråda från ändringar.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den skyddade presentationen som ODP med `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Byggd med Aspose.Slides" title="Lösenordsskydda ODP-filer online" description="Den kostnadsfria appen Aspose.Slides Lock är byggd med [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/sv/python-net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna ODP-filer." button="Öppna Aspose.Slides Lock" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides skyddar presentationer innan du skriver kod.
- Ange ett lösenord för att öppna eller redigera din ODP-fil.
- Ladda ned den skyddade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för skydd" subTitle="Använd Python för att skydda andra presentationsformat som stöds." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Skydda ODP-presentationer med C++
url: /sv/cpp/protect/odp/
description: Skydda ODP-presentationer i C++. Använd Aspose.Slides for C++ för att kryptera filer och ange skrivskydd.
keywords: Skrivskydd ODP, kryptera ODP, lås ODP-presentation, skydda ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lås eller lösenordsskydda ODP med C++" h2="Använd Aspose.Slides for C++ för att kryptera presentationer och ange skrivskydd utan Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Skydda en ODP-presentation med C++" variant="code" %}}

Med Aspose.Slides for C++ kan du skydda ODP-presentationer mot att öppnas eller ändras. Använd objektet `ProtectionManager` i klassen `Presentation` för att kryptera en fil med `Encrypt` eller begränsa redigering med `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kryptera en ODP-presentation med C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ange skrivskydd för en ODP-presentation med C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så lösenordsskyddar du ODP med C++" intro="Följ de här stegen för att skydda en ODP-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in ODP-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skydda presentationen med objektet `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Använd `Encrypt` för lösenordsskydd eller `SetWriteProtection` för skrivskydd.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den skyddade filen med `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Byggd med Aspose.Slides" title="Lösenordsskydda ODP-filer online" description="Den kostnadsfria appen Aspose.Slides Lock är byggd med [Aspose.Slides for C++](https://products.aspose.com/slides/sv/cpp/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna ODP-filer." button="Öppna Aspose.Slides Lock" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides skyddar presentationer innan du skriver kod.
- Ange ett lösenord för att öppna eller redigera din ODP-fil.
- Ladda ned den skyddade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för skydd" subTitle="Med C++ kan du även skydda följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

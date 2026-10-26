---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Skydda PPTX-presentationer med C++
url: /sv/cpp/protect/pptx/
description: Skydda PPTX-presentationer i C++. Använd Aspose.Slides for C++ för att kryptera filer och ange skrivskydd.
keywords: Skrivskydd PPTX, kryptera PPTX, lås PPTX-presentation, skydda PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lås eller lösenordsskydda PPTX med C++" h2="Använd Aspose.Slides for C++ för att kryptera presentationer och ange skrivskydd utan Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Skydda en PPTX-presentation med C++" variant="code" %}}

Med Aspose.Slides for C++ kan du skydda PPTX-presentationer mot att öppnas eller ändras. Använd objektet `ProtectionManager` i klassen `Presentation` för att kryptera en fil med `Encrypt` eller begränsa redigering med `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kryptera en PPTX-presentation med C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ange skrivskydd för en PPTX-presentation med C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så lösenordsskyddar du PPTX med C++" intro="Följ de här stegen för att skydda en PPTX-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPTX-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skydda presentationen med objektet `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Använd `Encrypt` för lösenordsskydd eller `SetWriteProtection` för skrivskydd.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den skyddade filen med `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Byggd med Aspose.Slides" title="Lösenordsskydda PPTX-filer online" description="Den kostnadsfria appen Aspose.Slides Lock är byggd med [Aspose.Slides for C++](https://products.aspose.com/slides/sv/cpp/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPTX-filer." button="Öppna Aspose.Slides Lock" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides skyddar presentationer innan du skriver kod.
- Ange ett lösenord för att öppna eller redigera din PPTX-fil.
- Ladda ned den skyddade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för skydd" subTitle="Med C++ kan du även skydda följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

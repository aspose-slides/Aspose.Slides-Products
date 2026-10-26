---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Skydda PPT-presentationsfiler med .NET
url: /sv/net/protect/ppt/
description: C#-källkod för att lösenordsskydda PPT-presentationer.
keywords: PPT-skrivskydd, kryptera PPT, lås PPT-presentation, skydda PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lås eller lösenordsskydda PPT-filer med C#" h2="Bygg .NET-appar som krypterar presentationer och begränsar ändringar med API:er på serversidan." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Skydda en PPT-presentation med C#" variant="code" %}}

Med [Aspose.Slides for .NET](/slides/sv/net/) kan du kryptera en PPT-presentation eller begränsa ändringar i den med ett lösenord. För att öppna en presentation som krypterats med `ProtectionManager.Encrypt` krävs lösenordet. Använd `ProtectionManager.SetWriteProtection` för att tillåta att presentationen öppnas men begränsa ändringar.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kryptera en PPT-presentation med C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ange skrivskydd för en PPT-presentation med C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så lösenordsskyddar du en PPT-presentation med C#" intro="Följ de här stegen för att lösenordsskydda en PPT-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPT-filen med `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kryptera presentationen med `ProtectionManager.Encrypt` eller begränsa ändringar med `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den skyddade filen med `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Byggd med Aspose.Slides" title="Lösenordsskydda PPT-filer online" description="Den kostnadsfria appen Aspose.Slides Lock är byggd med [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Lock" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides skyddar presentationer innan du skriver kod.
- Ange ett lösenord för att öppna eller redigera din PPT-fil.
- Ladda ned den skyddade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för skydd" subTitle="Med C# kan du även skydda följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

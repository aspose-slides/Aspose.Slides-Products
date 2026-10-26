---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Skydda ODP-presentationsfiler med Java
url: /sv/java/protect/odp/
description: Skydda ODP-presentationer i Java. Använd Aspose.Slides for Java för att kryptera presentationsfiler och ange skrivskydd.
keywords: Skrivskydd ODP, kryptera en ODP, lås ODP-presentation, skydda ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lås eller lösenordsskydda ODP med Java" h2="Bygg Java-program som skyddar presentationsfiler med API:er på serversidan." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Skydda en ODP-presentation med Java" variant="code" %}}

Med [Aspose.Slides for Java](/slides/sv/java/) kan du skydda en ODP-presentation mot att öppnas eller ändras genom att ange ett lösenord. Använd objektet `ProtectionManager` i klassen `Presentation` för att anropa metoder som `encrypt` och `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kryptera en ODP-presentation med Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ange skrivskydd för en ODP-presentation med Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så lösenordsskyddar du ODP med Java" intro="Följ de här stegen för att skydda en ODP-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in ODP-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa metoden `encrypt` eller metoden `setWriteProtection` i objektet `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den skyddade filen med `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Byggd med Aspose.Slides" title="Lösenordsskydda ODP-filer online" description="Den kostnadsfria appen Aspose.Slides Lock är byggd med [Aspose.Slides for Java](https://products.aspose.com/slides/sv/java/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna ODP-filer." button="Öppna Aspose.Slides Lock" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides skyddar presentationer innan du skriver kod.
- Ange ett lösenord för att öppna eller redigera din ODP-fil.
- Ladda ned den skyddade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för skydd" subTitle="Med Java kan du även skydda följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

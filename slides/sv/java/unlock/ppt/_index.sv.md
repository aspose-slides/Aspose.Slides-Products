---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lås upp PPT-presentationsfiler med Java
url: /sv/java/unlock/ppt/
description: Ta bort lösenord och skrivskydd från PPT-presentationer i Java med Aspose.Slides for Java.
keywords: Ta bort skrivskydd PPT, dekryptera PPT, lås upp PPT-presentation, ta bort skydd från PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lås upp PPT med Java" h2="Bygg Java-program som tar bort lösenord och skrivskydd från presentationsfiler med API:er på serversidan." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ta bort skydd från en PPT-presentation med Java" variant="code" %}}

Med [Aspose.Slides for Java](/slides/sv/java/) kan du ta bort kryptering eller skrivskydd från en PPT-presentation. Använd `LoadOptions.setPassword` för att öppna en krypterad presentation och `ProtectionManager`-metoderna `removeEncryption` och `removeWriteProtection` för att ta bort skyddsinställningar.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ta bort lösenordsskydd från PPT med Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ta bort skrivskydd från en PPT-presentation med Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så tar du bort ett lösenord från PPT med Java" intro="Följ de här stegen för att ta bort skyddet från en PPT-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPT-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Använd `LoadOptions.setPassword` när presentationen är krypterad.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `removeEncryption` eller `removeWriteProtection` i objektet `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den upplåsta presentationen med `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Byggd med Aspose.Slides" title="Lås upp PPT-filer online" description="Den kostnadsfria appen Aspose.Slides Unlock är byggd med [Aspose.Slides for Java](https://products.aspose.com/slides/sv/java/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Unlock" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides tar bort skydd innan du skriver kod.
- Ta bort lösenordet eller skrivskyddet från din PPT-fil.
- Ladda ned den upplåsta filen.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för upplåsning" subTitle="Med Java kan du även ta bort skydd från följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

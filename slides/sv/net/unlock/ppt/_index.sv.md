---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lås upp PPT-presentationsfiler med .NET
url: /sv/net/unlock/ppt/
description: C#-källkod för att ta bort lösenordsskydd från PPT-presentationer.
keywords: Ta bort PPT-skrivskydd, dekryptera PPT, lås upp PPT-presentation, ta bort skydd från PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lås upp PPT-filer med C#" h2="Bygg .NET-appar som tar bort kryptering och skrivskydd från presentationer med API:er på serversidan." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ta bort skydd från en PPT-presentation med C#" variant="code" %}}

Med [Aspose.Slides for .NET](/slides/sv/net/) kan du ta bort kryptering eller skrivskydd från en PPT-presentation. Om du vill ta bort krypteringen läser du in presentationen med rätt lösenord och anropar `ProtectionManager.RemoveEncryption`. Om du vill ta bort skrivskyddet anropar du `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ta bort kryptering från en PPT-presentation med C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.ppt", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ta bort skrivskydd från en PPT-presentation med C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.ppt");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så tar du bort skydd från en PPT-presentation med C#" intro="Följ de här stegen för att ta bort skyddet från en PPT-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPT-filen med `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}För en krypterad fil anger du lösenordet via `LoadOptions.Password` innan du läser in den.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `ProtectionManager.RemoveEncryption` eller `ProtectionManager.RemoveWriteProtection`, beroende på vilket skydd som används.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den upplåsta presentationen med `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Byggd med Aspose.Slides" title="Lås upp PPT-filer online" description="Den kostnadsfria appen Aspose.Slides Unlock är byggd med [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Unlock" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides tar bort skydd innan du skriver kod.
- Ta bort lösenordet eller skrivskyddet från din PPT-fil.
- Ladda ned den upplåsta filen.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för upplåsning" subTitle="Med C# kan du även ta bort skydd från följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

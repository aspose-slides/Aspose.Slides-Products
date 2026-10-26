---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Maskera PPTX-presentationsfiler med .NET
url: /sv/net/redaction/pptx/
description: C#-källkod för att söka efter och ersätta text i PPTX-presentationer.
keywords: Maskera PPTX, sök och ersätt text i PPTX, uppdatera PPTX-presentation
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Maskera PPTX-filer med C#" h2="Bygg .NET-appar som söker efter och ersätter text i presentationer med API:er på serversidan." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Maskera en PPTX-presentation med C#" variant="code" %}}

Med [Aspose.Slides for .NET](/slides/sv/net/) kan du söka efter och ersätta text i en PPTX-presentation. Använd `Presentation.ReplaceText` med `TextSearchOptions` för att styra sökningen och spara sedan den ändrade presentationen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Maskera en PPTX-presentation med C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så maskerar du en PPTX-presentation med C#" intro="Följ de här stegen för att ersätta text i en PPTX-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPTX-filen med `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Använd [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) med `TextSearchOptions` för att ersätta önskad text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den ändrade presentationen med `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Byggd med Aspose.Slides" title="Maskera PPTX-filer online" description="Den kostnadsfria appen Aspose.Slides Redaction är byggd med [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPTX-filer." button="Öppna Aspose.Slides Redaction" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides söker efter och ersätter text innan du skriver kod.
- Sök efter och ersätt text i din PPTX-fil, även med reguljära uttryck.
- Ladda ned den maskerade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för maskering" subTitle="Med C# kan du även maskera följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

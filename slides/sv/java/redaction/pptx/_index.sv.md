---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Maskera PPTX-presentationsfiler med Java
url: /sv/java/redaction/pptx/
description: Sök efter och ersätt text i PPTX-presentationer i Java med Aspose.Slides for Java.
keywords: maskera PPTX, sök och ersätt text i PPTX, uppdatera PPTX-presentation
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Maskera PPTX med Java" h2="Bygg Java-program som söker efter och ersätter text i presentationsfiler med API:er på serversidan." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Maskera en PPTX-presentation via Java" variant="code" %}}

Med [Aspose.Slides for Java](/slides/sv/java/) kan du söka efter och ersätta text i PPTX-presentationer. Använd metoden `SlideUtil.findAndReplaceText` för att söka igenom presentationen och ersätta matchande text med ett nytt värde.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Maskera en PPTX-presentation med Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så maskerar du PPTX via Java" intro="Följ de här stegen för att maskera en PPTX-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPTX-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa metoden `SlideUtil.findAndReplaceText` för att söka efter och ersätta text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den uppdaterade presentationen med `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Byggd med Aspose.Slides" title="Maskera PPTX-filer online" description="Den kostnadsfria appen Aspose.Slides Redaction är byggd med [Aspose.Slides for Java](https://products.aspose.com/slides/sv/java/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPTX-filer." button="Öppna Aspose.Slides Redaction" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides söker efter och ersätter text innan du skriver kod.
- Sök efter och ersätt text i din PPTX-fil, även med reguljära uttryck.
- Ladda ned den maskerade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för maskering" subTitle="Med Java kan du även maskera följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

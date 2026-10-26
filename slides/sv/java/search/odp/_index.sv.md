---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sök efter text i ODP-presentationsfiler med Java
url: /sv/java/search/odp/
description: Sök efter text i ODP-presentationer i Java med Aspose.Slides for Java.
keywords: sök efter ord i ODP, sök efter text i ODP, sök i ODP-presentationstext
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sök efter text i ODP med Java" h2="Bygg Java-program som söker efter text i presentationsfiler med API:er på serversidan." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sök efter text i en ODP-presentation via Java" variant="code" %}}

Med [Aspose.Slides for Java](/slides/sv/java/) kan du söka efter text i ODP-presentationer. Använd metoden `SlideUtil.getAllTextBoxes` för att samla textramarna och granska sedan objekten `ITextFrame`, `IParagraph` och `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sök efter text i en ODP-presentation med Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så söker du efter text i ODP via Java" intro="Följ de här stegen för att söka efter text i en ODP-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in ODP-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa metoden `SlideUtil.getAllTextBoxes` för att samla textramarna från varje bild.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Granska objekten `ITextFrame`, `IParagraph` och `IPortion` för att hitta matchande text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Byggd med Aspose.Slides" title="Sök efter text i ODP-filer online" description="Den kostnadsfria appen Aspose.Slides Search är byggd med [Aspose.Slides for Java](https://products.aspose.com/slides/sv/java/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna ODP-filer." button="Öppna Aspose.Slides Search" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides hittar text innan du skriver kod.
- Sök efter vanlig text eller reguljära uttryck i din ODP-fil.
- Ladda ned träffarna som en textfil.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för sökning" subTitle="Med Java kan du även söka efter text i följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

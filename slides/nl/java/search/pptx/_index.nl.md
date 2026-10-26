---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tekst zoeken in PPTX-presentatiebestanden met Java
url: /nl/java/search/pptx/
description: Zoek tekst in PPTX-presentaties in Java met Aspose.Slides for Java.
keywords: woorden zoeken in PPTX, tekst zoeken in PPTX, tekst in PPTX-presentatie zoeken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tekst zoeken in PPTX met Java" h2="Bouw Java-toepassingen die tekst in presentatiebestanden zoeken met server-side API's." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tekst zoeken in een PPTX-presentatie via Java" variant="code" %}}

Met [Aspose.Slides for Java](/slides/nl/java/) kunt u tekst zoeken in PPTX-presentaties. Verzamel de tekstkaders met de methode `SlideUtil.getAllTextBoxes` en onderzoek daarna de objecten `ITextFrame`, `IParagraph` en `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tekst zoeken in een PPTX-presentatie met Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tekst zoeken in PPTX via Java" intro="Volg deze stappen om tekst in een PPTX-presentatie te zoeken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPTX-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode `SlideUtil.getAllTextBoxes` aan om de tekstkaders van elke dia te verzamelen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Onderzoek de objecten `ITextFrame`, `IParagraph` en `IPortion` om overeenkomende tekst te vinden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Gebouwd met Aspose.Slides" title="Tekst zoeken in PPTX-bestanden online" description="De gratis app Aspose.Slides Search is gebouwd met [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Search openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides tekst vindt voordat u code schrijft.
- Doorzoek uw PPTX-bestand op gewone tekst of reguliere expressies.
- Download de resultaten als tekstbestand.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor zoeken" subTitle="Met Java kunt u ook tekst zoeken in de volgende formaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

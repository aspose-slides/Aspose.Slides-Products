---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1000
title: Extrahera text från PPTX-dokument med Java
url: /sv/java/parser/pptx/ 
description: Extrahera text från PPTX-filer i Java med Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tolka PPTX-filer i Java" h2="Extrahera text och presentationsinnehåll från PPTX-dokument med API:erna på serversidan i Aspose.Slides for Java."
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tolka en PPTX-fil med Java" %}}

Använd [Aspose.Slides for Java](/slides/sv/java/) för att tolka PPTX-presentationer och extrahera text från bilder. Lägg till biblioteket i ett Maven-projekt med konfigurationen för repository och beroende nedan i filen `pom.xml`.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Repository" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Beroende" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tolka PPTX-filer – Java" >}}
```java
Presentation presentation = new Presentation("demo.pptx");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så tolkar du PPTX-filer i Java" intro="Extrahera text från en PPTX-presentation med Aspose.Slides for Java med några få rader kod." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in `PPTX`-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa metoden `SlideUtil.getAllTextBoxes` för att hämta textramarna från den första bilden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gå igenom varje `ITextFrame`-, `IParagraph`- och `IPortion`-objekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs text, teckenstorlek och teckensnittsnamn från varje `IPortion`-objekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Aspose.Slides for Java stöder de viktigaste plattformarna och operativsystemen. Kontrollera att din miljö uppfyller följande förutsättningar." %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF-program och skrivbordsprogram.
- Den senaste versionen av Aspose.Slides for Java från [Maven](https://releases.aspose.com/java/repo/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Byggd med Aspose.Slides" title="Extrahera text och bilder online" description="Den kostnadsfria appen Aspose.Slides Parser är byggd med [Aspose.Slides for Java](https://products.aspose.com/slides/sv/java/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPTX-filer." button="Öppna Aspose.Slides Parser" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides läser dina filer innan du skriver kod.
- Ladda upp en PPTX-fil och få dess text och bilder.
- Ladda ner allt som ett enda ZIP-arkiv.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Files with the PPTX extension use the Office Open XML presentation format. A PPTX file stores slides that can contain text, images, formatting, animations, and other presentation content.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som kan tolkas" subTitle="Med Java kan du även tolka andra presentationsformat." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/parser/odp/" name="ODP" description="OpenDocument-presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/parser/ppt/" name="PPT" description="PowerPoint 97–2003-presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

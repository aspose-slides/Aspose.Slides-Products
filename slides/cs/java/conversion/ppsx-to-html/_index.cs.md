---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PPSX do HTML pomocí Javy
weight: 1650
url: /cs/java/conversion/ppsx-to-html/ 
description: Ukázka převodního kódu Java pro formát PPSX do souboru HTML. Tento ukázkový kód použijte k exportu prezentací PowerPoint a OpenOffice do HTML v jakékoli webové nebo desktopové Java aplikaci.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PPSX do HTML pomocí Javy" h2="PPSX do HTML Java konverze pro převod jedné nebo více stránek do HTML pomocí On-premise Java knihovny."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak převést PPSX do HTML pomocí Java" %}}

K vykreslení PPSX do HTML použijeme
 [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/)
 API, což je funkčně bohaté, výkonné a snadno použitelné konverzní API pro platformu Java. Jeho nejnovější verzi si můžete stáhnout přímo z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 a nainstalujte jej do svého projektu založeného na Maven přidáním následujících konfigurací do souboru pom.xml.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="úložiště" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Závislost" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Zdrojový kód konverze PPSX do HTML Java" >}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("template.ppsx");
// save the presentation as HTML
presentation.save("output.html", SaveFormat.Html);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroky k převodu PPSX do HTML přes Java" intro="Vývojáři Java mohou snadno převést soubor PPSX do HTML pomocí několika řádků kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPSX s instancí třídy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu Presentation.save a zadejte cestu k výstupnímu souboru a SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor HTML bude uložen do zadané cesty{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Požadavky na systém" intro="Před spuštěním ukázkového kódu konverze Java se ujistěte, že splňujete následující předpoklady." %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
- Získejte nejnovější verzi Aspose.Slides pro Java přímo od Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikace zdarma k převodu PPSX na HTML"
  description="[Vyzkoušejte naši bezplatnou aplikaci pro převod PPT až HTML](https://products.aspose.app/slides/conversion/ppt-to-html)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="PPSX můžete také převést do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="Obrázek JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Formát prezentace OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Standardní formát OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Soubory šablon Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Prezentace s podporou maker" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Soubor prezentace s podporou maker" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Formát otevřené prezentace XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="Formát SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

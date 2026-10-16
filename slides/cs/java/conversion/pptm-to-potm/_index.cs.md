---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PPTM na POTM přes Java
weight: 6120
url: /cs/java/conversion/pptm-to-potm/ 
description: Ukázkový konverzní kód Java pro formát PPTM na soubor POTM. Tento příklad kódu použijte k exportu prezentací PowerPoint a OpenOffice do POTM v rámci jakékoli webové nebo desktopové Java aplikace.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PPTM na POTM přes Java" h2="Konverze PPTM na POTM Java pro převod jedné nebo více stránek na POTM pomocí místní knihovny Java."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak převést PPTM na POTM pomocí Java" %}}

Abychom převedli PPTM do POTM, použijeme
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Zdrojový kód konverze Java z PPTM na POTM" >}}
```cs
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("template.pptm");
// save the presentation as POTM
presentation.save("output.potm", SaveFormat.Potm);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroky k převodu PPTM na POTM přes Java" intro="Vývojáři Java mohou snadno převést soubor PPTM na POTM pomocí několika řádků kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTM s instancí třídy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu Presentation.save a zadejte cestu k výstupnímu souboru a SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor POTM bude uložen do zadané cesty{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Požadavky na systém" intro="Před spuštěním ukázkového kódu konverze Java se ujistěte, že splňujete následující předpoklady." %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
- Získejte nejnovější verzi Aspose.Slides pro Java přímo od Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikace zdarma k převodu PPTM na POTM"
  description="[Vyzkoušejte zdarma Video App](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="PPTM můžete také převést do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-jpeg/" name="PPTM TO JPEG" description="Obrázek JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Formát prezentace OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Standardní formát OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Soubory šablon Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Prezentace s podporou maker" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Formát otevřené prezentace XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Formát SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

---
title: Převést ODP na POTX přes Java
weight: 6340
url: /cs/java/conversion/odp-to-potx/ 
description: Ukázkový konverzní kód Java pro formát ODP na soubor POTX. Tento příklad kódu použijte k exportu prezentací PowerPoint a OpenOffice do POTX v rámci jakékoli webové nebo desktopové Java aplikace.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést ODP na POTX přes Java" h2="Konverze Java ODP na POTX pro převod jedné nebo více stránek na POTX pomocí místní knihovny Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Jak převést ODP na POTX pomocí Java" %}}

 K vykreslení ODP na POTX použijeme
 [Aspose.Slides for Java](https://products.aspose.com/slides/java)
 API, což je funkčně bohaté, výkonné a snadno použitelné konverzní API pro platformu Java. Jeho nejnovější verzi si můžete stáhnout přímo z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 a nainstalujte jej do svého projektu založeného na Maven přidáním následujících konfigurací do souboru pom.xml.

{{% blocks/products/pf/agp/code-block title="úložiště" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Závislost" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod ODP na POTX přes Java" %}}

{{% blocks/products/pf/agp/text %}}

 Vývojáři Java mohou snadno převést soubor ODP na POTX pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor ODP s instancí třídy Presentation
1. Zavolejte metodu Presentation.save a zadejte cestu k výstupnímu souboru a SaveFormat
1. Soubor POTX bude uložen do zadané cesty

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového kódu konverze Java se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
- Získejte nejnovější verzi Aspose.Slides pro Java přímo od Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze ODP na POTX Java" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("template.odp");
// save the presentation as POTX
presentation.save("output.potx", SaveFormat.Potx);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="odp-to-potx"
        sectionTitle="Aplikace zdarma k převodu ODP na POTX" 
        sectionDescription="[Vyzkoušejte zdarma Video App](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Můžete také převést ODP do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-gif/" name="ODP TO GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="Obrázek JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-otp/" name="ODP TO OTP" description="Standardní formát OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-png/" name="ODP TO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pot/" name="ODP TO POT" description="Soubory šablon Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-potm/" name="ODP TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pps/" name="ODP TO PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Prezentace s podporou maker" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Soubor prezentace s podporou maker" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Formát otevřené prezentace XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-svg/" name="ODP TO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-swf/" name="ODP TO SWF" description="Formát SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-xps/" name="ODP TO XPS" description="Specifikace papíru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
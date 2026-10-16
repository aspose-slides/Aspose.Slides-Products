---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti ODP in POTX tramite Java
weight: 6340
url: /it/java/conversion/odp-to-potx/ 
description: Esempio di codice di conversione Java per il formato ODP in file POTX. Utilizzare questo codice di esempio per esportare presentazioni PowerPoint e OpenOffice in POTX all'interno di qualsiasi applicazione basata su Java Web o desktop.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti ODP in POTX tramite Java" h2="Conversione da ODP a POTX Java per convertire pagine singole o multiple in POTX utilizzando la libreria Java in loco."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Come convertire ODP in POTX usando Java" %}}

Per rendere ODP a POTX, useremo
 [Aspose.Slides per Java](https://products.aspose.com/slides/it/java/)
 API che è un'API di conversione ricca di funzionalità, potente e facile da usare per la piattaforma Java. Puoi scaricare la sua ultima versione direttamente da
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 e installalo all'interno del tuo progetto basato su Maven aggiungendo le seguenti configurazioni a pom.xml.

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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dipendenza" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice sorgente di conversione Java da ODP a POTX" >}}
```cs
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("template.odp");
// save the presentation as POTX
presentation.save("output.potx", SaveFormat.Potx);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Passaggi per convertire ODP in POTX tramite Java" intro="Gli sviluppatori Java possono convertire facilmente file ODP in POTX in poche righe di codice." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file ODP con un'istanza della classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiamare il metodo Presentation.save specificando il percorso del file di output e SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Il file POTX verrà salvato nel percorso specificato{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisiti di sistema" intro="Prima di eseguire il codice di esempio di conversione Java, assicurarsi di disporre dei seguenti prerequisiti." %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.
- Ottieni l'ultima versione di Aspose.Slides per Java direttamente da Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="App gratuita da convertire ODP in POTX"
  description="[Prova la nostra app gratuita Video](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire ODP in molti altri formati di file, inclusi alcuni elencati di seguito." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Immagine bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-gif/" name="ODP TO GIF" description="Formato di scambio grafico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="Immagine JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-otp/" name="ODP TO OTP" description="Formato standard OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-png/" name="ODP TO PNG" description="Grafica di rete portatile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-pot/" name="ODP TO POT" description="File modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-potm/" name="ODP TO POTM" description="File modello Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-pps/" name="ODP TO PPS" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Presentazione con attivazione macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="File di presentazione abilitato per le macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Apri il formato di presentazione XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-svg/" name="ODP TO SVG" description="Grafica vettoriale scalabile" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-swf/" name="ODP TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Formato immagine contrassegnato" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/odp-to-xps/" name="ODP TO XPS" description="Specifiche della carta XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}

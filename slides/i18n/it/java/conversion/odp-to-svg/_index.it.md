---
title: Converti ODP in SVG tramite Java
weight: 8550
url: /it/java/conversion/odp-to-svg/ 
description: Esempio di codice di conversione Java per il formato ODP in file SVG. Utilizzare questo codice di esempio per esportare presentazioni PowerPoint e OpenOffice in SVG all'interno di qualsiasi applicazione basata su Java Web o desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti ODP in SVG tramite Java" h2="Conversione da ODP a SVG Java per convertire pagine singole o multiple in SVG utilizzando la libreria Java in loco." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Come convertire ODP in SVG usando Java" %}}

 Per eseguire il rendering di ODP in SVG, utilizzeremo
 [Aspose.Slides per Java](https://products.aspose.com/slides/java)
 API che è un'API di conversione ricca di funzionalità, potente e facile da usare per la piattaforma Java. Puoi scaricare la sua ultima versione direttamente da
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 e installalo all'interno del tuo progetto basato su Maven aggiungendo le seguenti configurazioni a pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dipendenza" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire ODP in SVG tramite Java" %}}

{{% blocks/products/pf/agp/text %}}

 Gli sviluppatori Java possono convertire facilmente i file ODP in SVG in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file ODP con un'istanza della classe Presentation
1. Chiamare il metodo Presentation.save specificando il percorso del file di output e SaveFormat
1. Il file SVG verrà salvato nel percorso specificato

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di esempio di conversione Java, assicurarsi di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.
- Ottieni l'ultima versione di Aspose.Slides per Java direttamente da Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice sorgente di conversione da ODP a Java Java" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a ODP file
Presentation pres = new Presentation("template.odp");
try {
    // Access the first slide
    ISlide sld = pres.getSlides().get_Item(0);

    // Create a memory stream object
    FileOutputStream svgStream = new FileOutputStream("output.svg");

    // Create SVG image of slide and save in memory stream
    sld.writeAsSvg(svgStream);

    svgStream.close();
} catch (IOException e) {
} finally {
    pres.dispose();
}   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="odp-to-svg"
        sectionTitle="App gratuita da convertire ODP in SVG" 
        sectionDescription="[Prova la nostra app gratuita Editor](https://products.aspose.app/slides/editor/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire ODP in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Immagine bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-gif/" name="ODP TO GIF" description="Formato di scambio grafico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="Immagine JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-otp/" name="ODP TO OTP" description="Formato standard OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-png/" name="ODP TO PNG" description="Grafica di rete portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pot/" name="ODP TO POT" description="File modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-potm/" name="ODP TO POTM" description="File modello Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-potx/" name="ODP TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pps/" name="ODP TO PPS" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Presentazione con attivazione macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Presentazione di PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="File di presentazione abilitato per le macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Apri il formato di presentazione XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-swf/" name="ODP TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Formato immagine contrassegnato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-xps/" name="ODP TO XPS" description="Specifiche della carta XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
---
title: Suchen und ersetzen Sie Text in PPT-Dokumenten über Java
weight: 3270
url: /de/java/redaction/ppt/ 
description: Java-Beispielcode zum Schwärzen vertraulicher Informationen in PPT-Dateien in Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Schwärzen Sie PPT-Formate in Java" h2="Natives und leistungsstarkes PPT dokumentiert sensible Schwärzungsinformationen mit serverseitigen Aspose.Slides für Java-APIs, ohne die Verwendung von Software wie Microsoft oder Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="https://www.nuget.org/packages/aspose.slides.java" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="So redigieren Sie eine PPT-Datei mit Java" %}}

 Um die PPT-Datei zu redigieren, verwenden wir
 [Aspose.Folien für Java](https://products.aspose.com/slides/de/java)
 API, die eine funktionsreiche, leistungsstarke und einfach zu verwendende Schwärzungs-API für die Java-Plattform ist. Sie können die neueste Version direkt von herunterladen
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 und installieren Sie es in Ihrem Maven-basierten Projekt, indem Sie der pom.xml die folgenden Konfigurationen hinzufügen.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Abhängigkeit" offSpacer="true" %}}

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


{{< blocks/products/pf/agp/feature-section-col title="Schritte zum Schwärzen von PPT-Dateien in Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Eine grundlegende Dokumentensuche und das Ersetzen von Text in Inhalten, Kommentaren oder Metadaten mit [Aspose.Slides for Java](https://products.aspose.com/slides/de/java) APIs kann mit nur wenigen Codezeilen durchgeführt werden. Suchen und ersetzen Sie Text in PowerPoint und OpenOffice. Bearbeiten Sie Text, Kommentare und Metadaten in der Präsentation über den Regexp-Datenabgleich." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT-Präsentation laden.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Greifen Sie auf die erste Folie zu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterieren Sie über Shapes und setzen Sie einen Verweis auf die gefundene Tabelle.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ändern Sie den Text jedes Platzhalters
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides für Java unterstützt auf allen wichtigen Plattformen und Betriebssystemen. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Runtime Environment für JSP/JSF-Anwendung und Desktop-Anwendungen.
- Holen Sie sich die neueste Version von Aspose.Slides für Java direkt von
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides) .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Schwärzen Sie PPT-Dateien - Java" offSpacer="" %}}

```cs
 //Load PPT file

Presentation pres = new Presentation(dataDir + "sourceFile.ppt");

//Access first slide

ISlide slide = pres.getSlides().get_Item(0);

IShape shape= null;

//Iterate through the shapes and set a reference to the table found

for (int i = 0 ; i < slide.getShapes().size() ; i++){

    shape = slide.getShapes().get_Item(i);

    if (shape.getPlaceholder() != null){

        //Change the text of each placeholder

        ((IAutoShape)shape).getTextFrame().setText("This is Placeholder");

    }

}

//Write the PPT to Disk

pres.save(dataDir + "AsposeReplaceTxt.ppt",SaveFormat.Ppt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Über Aspose.Slides für die Java-API" %}}

 Aspose.Slides API kann zum Lesen, Schreiben, Bearbeiten und Konvertieren von Microsoft PowerPoint-Dokumenten in PDF, XPS, HTML, TIFF, ODP und verschiedene andere Formate verwendet werden. Man kann neue Dateien von Grund auf neu erstellen und diese in den entsprechenden unterstützten Formaten speichern. Aspose.Slides ist eine eigenständige API zum Erstellen, Analysieren oder Bearbeiten von Präsentationen, Folien und Elementen und ist nicht von Software wie Microsoft oder OpenOffice abhängig.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in PPT documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/redaction). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPT files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Schwärzungsdokumente" subTitle="Mit Java kann man problemlos verschiedene Formate redigieren, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/redaction/odp/" name="ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/redaction/pptx/" name="PPTX" description="Offenes XML-Präsentationsformat" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
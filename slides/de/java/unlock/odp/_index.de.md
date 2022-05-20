---
title: ODP-Dokument über Java entsperren
weight: 3650
url: /de/java/unlock/odp/ 
description: Java-Beispielcode zum Entsperren der passwortgeschützten ODP-Datei in der Java-Laufzeitumgebung für JSP/JSF-Anwendung und Desktop-Anwendungen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Entsperren Sie ODP-Dateien über Java" h2="Entfernen Sie den Schutz von PowerPoint-Präsentationen einschließlich ODP-Dateien mithilfe der Java-Bibliothek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="So entfernen Sie die Schutz-ODP-Datei mit Java" %}}

 Um die ODP-Datei zu entsperren, verwenden wir
 [Aspose.Folien für Java](https://products.aspose.com/slides/de/java)
 API, die eine funktionsreiche, leistungsstarke und einfach zu verwendende Schutz-API für die Java-Plattform ist. Sie können die neueste Version direkt von herunterladen
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


{{< blocks/products/pf/agp/feature-section-col title="Schritte zum Entsperren von ODP über Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie gesperrtes ODP mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Überprüfen Sie den Schutz mit der booleschen Eigenschaft isWriteProtected
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Entfernen Sie den Schutz mit der Methode removeWriteProtection()
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im ODP-Format speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides für Java unterstützt auf allen wichtigen Plattformen und Betriebssystemen. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Entsperren Sie ODP-Dateien über C#" offSpacer="" %}}

```cs

// Open the ODP file
Presentation pres = new Presentation("WriteProtectedFile.odp");

// Checking if presentation is write protected
if (pres.getProtectionManager().isWriteProtected())
	// Removing Write protection
	pres.getProtectionManager().removeWriteProtection();

// Saving presentation
pres.save("output.odp", com.aspose.slides.SaveFormat.Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.Slides für die Java-API" %}}

 Aspose.Slides API kann zum Lesen, Schreiben, Bearbeiten und Konvertieren von Microsoft PowerPoint-Dokumenten in PDF, XPS, HTML, TIFF, ODP und verschiedene andere Formate verwendet werden. Man kann neue Dateien von Grund auf neu erstellen und diese in den entsprechenden unterstützten Formaten speichern. Aspose.Slides ist eine eigenständige API zum Erstellen, Analysieren oder Bearbeiten von Präsentationen, Folien und Elementen und ist nicht von Software wie Microsoft oder OpenOffice abhängig.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Unlock ODP" sectionDescription="Check our live demos to [unlock ODP files](https://products.aspose.app/slides/unlock/odp) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload ODP file and hit the \"Unlock\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant ODP file from the link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Entsperrformate" subTitle="Mit Java kann man den Schutz / die Entsperrung verschiedener Formate leicht entfernen, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/unlock/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/unlock/pptx/" name="PPTX" description="Offenes XML-Präsentationsformat" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}